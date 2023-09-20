# This project is underconstruction. 

The project uses panel data which represents mortgage borrowers over 60 periods. The loans may originate before the start of the observation (referred to as the current period throughout) period. The loan observations may  be censored as the loans mature or borrowers refinance. The data set is a randomized selection of mortgage-loan-level data collected from the portfolios underlying U.S. residential mortgage-backed securities (RMBS) securitization portfolios. 

Financial institutions have traditionally developed models to quantify credit risk to limit exposure. Logistic regression, a binary outcome, has seen success traditionally in this context.

Time series analysis, specifically Survival Analyais, creates the possiblity of detirmining - not if something will happen - but when something will happen. Censoring occurs when the loan is under repayment at the moment of data gathering. The origin of all loans (the birth event) is known, but for some loans, a default has not yet occured (the death event). In these cases, it is uknown whether the borrower is good or bad. The customers who have not defaulted yet will be labelled “censored” in the analysis.

Main Objective: Model time to default on mortgages to better identify risk.  
