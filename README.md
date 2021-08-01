# ATLAS_opendata_internship
Repository to store all the progress in making a jupyter notebook to find DM using ML (and data cuts) for my internship at the University of Sussex

Files:

First_notebook(OBSOLETE)
  This notebook was used to explore and understand the data for the first time. Contains: code opening a file (MM800sig) and writing to a pandas dataframe, code making plots of the pt of the leptons and of the missing Et before any cuts
First notebook created

First_attempt_at_cuts(OBSOLETE)
  This notebook was the first to implement the cuts from the 13 TeV note (and one from the13 TeV paper). There are also plots and a couple Yield tables. This was done on the MM800 signal MC file, so the yield tables and plots may be of use
Second notebook created
  
Cuts_on_ZZ(OBSOLETE)
  copy of First_attempt_at_cuts(OBSOLETE), but this time using the ZZ BG MC file (llvv). Yield tables and plots may be of use
Third notebook created

cut_on_initial
  This notebook was used to perform cuts on the initial MC to try and make an oredered cut flow for each file - not needed now. There were also some (not needed) s/b calculations. Then all the cuts from the 13 TeV paper were performed sequentially performed to find the total weight of each file before/after each cut. then cut flows were made in the same order, but with the 4 cuts for students to do left for the end
Fourth notebook created

writing_to_csv
  this performs the chosen pre-cuts on the MC and puts the remaining MC into a csv for further use
Fifth notebook created

Draft_final_nb
  This notebook contains content and ideas for content for the final notebook for children. There are only ideas for the introduction, but shoud flow well into code implementing cut-based analysis
