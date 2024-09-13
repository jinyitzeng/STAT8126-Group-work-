# STAT8126-Group-work-

Link to the Article: https://www.sciencedirect.com/science/article/pii/S2352340919306985?via%3Dihub#sec1

Link to the Data: https://www.kaggle.com/datasets/manvendrarajsingh/obesitydataset-raw-and-data-sinthetic?resource=download

# For the Age group
Age_Group = 
SWITCH(
    TRUE(),
    obe[Age] < 20, "Youth",
    obe[Age] >= 20 && obe[Age] < 30, "Young Adult",
    obe[Age] >= 30 && obe[Age] < 40, "Middle Age",
    obe[Age] >= 40 && obe[Age] < 50, "Older Adults",
    obe[Age] >= 50, "Senior"
)
