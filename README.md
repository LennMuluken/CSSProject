This is a github project which investigates bias in reporting on Israels war on gaza in three english speaking newspapers: The New York Times, BBC, and the Guardian.
It analyzes a total of 1624 headlines. 



MediaAnalysis.ipnyb is the notebook that contains code on how we filtered the dataset, ran GPT-4 prompts and created the figures that we implemented in our paper.


sufferingcomplete_df is our final dataset which contains NYT, BBC and Guardian headlines that entail keywords related to suffering in the context of Israel-Palestine since October 7 2023. It has additional columns that contain output from GPT-4 on who the perpetrator of suffering is, who the described victim is, and whether the headline is written in active or passive language


merged_df contains the dataset of NYT, Guardian and BBC headlines relating to Israel-Palestine. It has not yet been filtered for keywords related to suffering (injury, death)


The Appendices doc contains two elements:Appendix A and Appendix B. 
Appendix A contains the wordbank that the dataset of headlines was filtered for, Appendix B contains the prompts for GPT-4 to determine who is suffering, who is the perpetrator and whether the headline is written in active or passive language.

The reliability excel sheets entail the manually annotated headlines. One excel sheet contains the manual annotations on whose suffering is described and the other contains manual annotations of perpetrator and voice.
