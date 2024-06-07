# nano-toxicity
Structure of Files
1) Feature Selection is based on SVM-REF model on serum untargeted metabolomic data of free and nano-IRIN. 
   free IRIN: IRIN-TOP30-identify-common 4
	   IRIN_MET_identify-gong4-new
   nano-IRIN: MET-identify-20231221-common2-1
                     LIPIRIN_TOP30% 2_common2_identify-new
                     
1) prediction model construction on serum untargeted metabolomic data of free and nano-IRIN. 
   
free IRIN: IRIN-TOP30-identify-common 4
                IRIN-TOP30-identify-LCA
	IRIN_MET_identify-gong4-new
                IRIN-MET-identify-LCA

   nano-IRIN: MET-identify-20231221-common2-1
                     LIPIRIN_TOP30% 2_R5P_identify-new
                     LIPIRIN_TOP30% 2_HY_identify-new
                     LIPIRIN_TOP30% 2_common2_identify-new
                     MET-identify-20231221-HY-1
                     MET-identify-20231221-P5T-1
                     IRIN_MET_identify-gong4-new 

3) Validaiton of targeted metabolomic data on validation sets  of free, nano-IRIN and tumor bearing mice treated with nano-IRIN:
   
    free IRIN: IRIN-IDE-target-MET&TOP30%-common 4
                    IRIN-target-LCA

    nano-IRIN: LIPIRIN-Target-gong2
                      LIPIRIN-Target-HY
                      LIPIRIN-Target-P5T

    Tumor-nano-IRIN: lip-TUMOR-target-gong2-final
                                 lip-TUMOR-target-HY-final
                                 lip-TUMOR-target-P5T-final	
