## Input files

Follow the links to download the binary files of initial temperature, salinity and tracer 
concentration, bathymetry files, and spatially variable vertical diffusivity required 
to run the model or download the [zip file](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/input_files.zip) to get them all (2.4 GB when unzipped). 

### Bathymetry 

* [bathy_smooth_616x360_NonUni_BarkleyLikeQuadExt.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/bathymetry/bathy_smooth_616x360_NonUni_BarkleyLikeQuadExt.bin) - `bathyFile` in data file. Canyon bathymetry. 
* [bathy_smooth_616x360_NonUni_NoCanyonQuad.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/bathymetry/bathy_smooth_616x360_NonUni_NoCanyonQuad.bin) - `bathyFile` in data file for no-canyon cases.
* [delx_616x360_NonUni_BarkleyLikeQuadExt.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/bathymetry/delx_616x360_NonUni_BarkleyLikeQuadExt.bin)- `delXfile` in data. X-spacing for the canyon cases.
* [delx_616x360_NonUni_NoCanyonQuad.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/bathymetry/delx_616x360_NonUni_NoCanyonQuad.bin)- `delXfile` in data. X-spacing for the no-canyon cases.
* [dely_616x360_NonUni_BarkleyLikeQuadExt.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/bathymetry/dely_616x360_NonUni_BarkleyLikeQuadExt.bin)- `delYfile` in data. Y-spacing for the canyon cases.
* [dely_616x360_NonUni_NoCanyonQuad.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/bathymetry/dely_616x360_NonUni_NoCanyonQuad.bin)- `delYfile` in data. Y-spacing for the no-canyon cases.  

### Stratification
        
* [Linsal_N5p5_90zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/stratification/Linsal_N5p5_90zlev_616x360.bin) - `hydrogSaltFile` in data. Base case salinity.
* [Lintmp_N5p5_90zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/stratification/Lintmp_N5p5_90zlev_616x360.bin) - `hydrogThetaFile` in data. Base case temperature.
* [Lintmp_N4p5_90zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/stratification/Lintmp_N4p5_90zlev_616x360.bin) - Salinity for lower_N run.
* [Lintmp_N4p5_90zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/stratification/Lintmp_N4p5_90zlev_616x360.bin) - Temperature for lower_N run. 
* [Linsal_N006_90zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/stratification/Linsal_N006_90zlev_616x360.bin) - Salinity for higher_N runs.
* [Lintmp_N006_90zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/stratification/Lintmp_N006_90zlev_616x360.bin) - Temperature for higher_N runs.
* [Linsal_N7p4_90zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/stratification/Linsal_N7p4_90zlev_616x360.bin) - Salinity for highest_N runs.
* [Lintmp_N7p4_90zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/stratification/Lintmp_N7p4_90zlev_616x360.bin) - Temperature for highest_N runs.
  
### Tracer Profile

* [Linnit90zlev_616x360.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/stratification/Linnit90zlev_616x360.bin) - `PTRACERS_initialFile(num)` in data.ptracers. Linear tracer profile for all runs.

### Vertical diffusivity

`diffKrFile` in data file only for runs in 3DVISC.

* [KrDiff1E_7_1E_3_90zlev_616x360_Quad.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/diffusivity/KrDiff1E_7_1E_3_90zlev_616x360_Quad.bin) - Run highestKc_lowKbg
* [KrDiff1E_7_1E_4_90zlev_616x360_Quad.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/diffusivity/KrDiff1E_7_1E_4_90zlev_616x360_Quad.bin) - higherKc_lowKbg
* [KrDiff1E_5_1E_4_90zlev_616x360_Quad.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/diffusivity/KrDiff1E_5_1E_4_90zlev_616x360_Quad.bin) - Run higher_Kc
* [KrDiff1E_5_1E_3_90zlev_616x360_Quad.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/diffusivity/KrDiff1E_5_1E_3_90zlev_616x360_Quad.bin) - Run high_Kc
* [KrDiff1E_5_5E_3_90zlev_616x360_Quad.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/diffusivity/KrDiff1E_5_5E_3_90zlev_616x360_Quad.bin) - Run high2_Kc.
* [KrDiff1E_5_1E_2_90zlev_616x360_Quad.bin](https://www.eoas.ubc.ca/~kramosmu/tracer_upwelling_paper/input_files/diffusivity/KrDiff1E_5_1E_2_90zlev_616x360_Quad.bin) - Run highest_Kc.
