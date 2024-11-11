# WRF-Chem-sulfate

In this repository, we have developed and integrated a new sulfate formation pathway that considers the role of manganese (Mn) catalysis on aerosol surfaces. This pathway has been proven to play a dominant role in the chemical formation of sulfate during haze events in North China. By incorporating this mechanism, we aim to improve the accuracy and predictive capability of WRF-Chem in simulating sulfate aerosol concentrations and their impacts on atmospheric chemistry and climate.


Compilation

 (1) Download WRF-Chem version 4.1.1 at https://github.com/wrf-model/WRF/releases
 (2) Download the three model modules here and move them to the "chem" directory of the WRF-Chem code, replacing the existing model modules.
 (3) Compile the WRF-Chem model as usual


Running WRF-Chem

 To use the improved sulfate mechanism, the chem_opt option in namelist.input must be set to 35.


Citation

 You should include the following reference whenever you use the improved sulfate mechanism for research publications.
 [1] Wang T, Liu M, Liu M, et al. Sulfate Formation Apportionment during Winter Haze Events in North China. Environmental Science & Technology, 2022, 56(12):7771-7778. DOI:10.1021/acs.est.2c02533.
 [2] Wang W, Liu M, Wang T, et al. Sulfate formation is dominated by manganese-catalyzed oxidation of SO2 on aerosol surfaces during haze events. Nature Communications, 2021, 12(1):1993. DOI:10.1038/s41467-021-22091-6.


Contact

 Feel free to contact me: ttwang@pku.edu.cn
