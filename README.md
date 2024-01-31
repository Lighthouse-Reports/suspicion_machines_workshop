# Suspicion Machine Workshop 


You can find the notebook that matches the districts to their corresponding CBS data in notebooks/merge_feature_cbs.ipynb 

The resulting Excel sheet can be found in the 02_intermediate folder 

For now, it only looks at 'wijks' and matches them to all their CBS data. It also calculates the share in the real world vs their share in the training data (last few columns). 

A few things to note: 
- Quite a few rows in the synthetic data (±3000) have no district with a 1. I don't remember if this was also the case in the real data. 
