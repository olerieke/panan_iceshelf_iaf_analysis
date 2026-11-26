# panan_iceshelf_iaf_analysis
Project for analysing interannual variability of ice shelf melt


Model run that we analyse: 
/g/data/ik11/outputs/access-rom3-panan/MC_4km_jra_iaf+regionalpanan+isf/

More details on the configuration: https://github.com/claireyung/mom6-panAn-iceshelf-tools

The run starts in 1980 from initial conditions that are extrapolated into the cavity. These are being flushed out very quickly, and temperatures and melt rates start off quite high in many places but drop off very quickly. It would therefore make sense to discard the first few years. I have chosen to discard the first five for now but not sure if that's the best choice. 

**Possible project focus / big questions:**
-	Characterise simulated melt variability across all ice shelves (seasonal, interannual).
-	Determine drivers of this variability (temperature, circulation, heat transport across shelf break, DSW formation, winds, sea ice etc).
