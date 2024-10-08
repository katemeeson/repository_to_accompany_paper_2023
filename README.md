# repository_to_accompany_paper_2023
'Constraint-based modelling predicts metabolic signatures of low and high-grade serous ovarian cancer', NPJ Systems Biology and Applications, 2024. Meeson and Schwartz.
Link to accepted publication corresponding to this code https://lnkd.in/epkMwiTP.
Repository to accompany paper (Meeson and Schwartz), accepted 2024. Includes models, and working notebook for model simulations. 

###   Constraint-based modelling performed on the 'Human-GEM-annotated.xml' 2020 version of the Human1 genome-scale model, developed by Robinson et al, 2020 (PMID: 32209698) [(https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7331181/)]

###   Transcriptomics data was used to constrain generic GEM to six cell line-specific ovarian cancer models (CCLE, DepMap Public 22Q2, 'CCLE_expression.csv') [(https://depmap.org/portal/download/all/)]

###   Six cell line-specific models were constrained: three high-grade (CAOV3, COV318, OAW28), and three low-grade (59M, HEYA8, OV56)

###   Constraint-based modeling used FBA and own integration code to create reaction constraint dictionaries, which were integrated using COBRApy and MEWpy
