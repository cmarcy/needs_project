Steps to run the project:

1. run either plantfile1-gdx-file-creator or plantfile1-gdx-file-creator-noretire
creates the plant data formatted correctly needed for the gdx files, outputs/needs_final.csv
	a. plantfile1-gdx-file-creator uses ReEDS age-based assumptions
	b. plantfile1-gdx-file-creator set 2100 as the retirement age for non-announced retirements

2. run plantfile2-xlsx-file-creator 
creates adds VOM/FOM data and formats files for the ReEDS CAV plantfile, outputs/needs_final2.csv

3. save a copy of outputs/needs_final2.csv in gdx_generator and follow skhanal instructions in gdx_generator
note: I have very little to the skhanal setup that was provided to me by NREL