## Cholesterol Analysis Project ##

- Computational Biology method overview


## Reserach Question
- How did total cholesterol levels evolve by country from 1980 to 2018, how does this correlate with modern statin utilization, and does a mechanistic pharmacokinetic model reproduce the individual-level drug effect that underlies population-level declines?

## Part 1 
- Data Cleaning with Pandas/NumPy (merges, groupby, joins, etc).

- EDA shallow analysis with ydataprofiling

- EDA deeper analysis with seaborn/matplotlib + Pandas/numpy

## Part 2 

- Machine learning: How accurately can we predict total cholesterol level (1980-2018) given current day statin usage data (available online),
and other subfactors?

- Sci-Kit Learn (GradientBoost Regression model with Kfold cross validtation + Feature importance graph)

## Part 3 
- Simulation of Statin/PCSK9 usage adapted from Research Paper (Modeled using Ordinary DIfferential Equations, numerical values taken directly from paper)

- Simulation help/code done with Opus 4.7 assistance


## Datasets

- NCD Risk factor Collaboration Dataset (standarized by country): https://www.ncdrisc.org/data-downloads-cholesterol.html 

- Our world in Data (Statin usage by country from 2019-2020):  https://ourworldindata.org/grapher/utilization-of-statins#reuse-this-work


## By Bhargav Ashok

##### Note: Country codes are notated by iso3 


## Sources 
## Sources used for the project

- Claude Opus 4.7 for ODE reproduction fixes, understanding research papers from a data science perspective, syntax issues and general project scaffolding workflows

- DATASETS: https://www.ncdrisc.org/data-downloads-cholesterol.html , https://ourworldindata.org/grapher/utilization-of-statins#reuse-this-work

- https://www.heart.org/en/health-topics/cholesterol/hdl-good-ldl-bad-cholesterol-and-triglycerides

- https://my.clevelandclinic.org/health/drugs/22550-pcsk9-inhibitors

- https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GroupKFold.html

- Inspiration for this project: A whole-body mathematical model of
cholesterol metabolism and transport
Peter Emil Carstensen ∗,∗∗ Jacob Bendsen ∗,∗∗
Laura Hjort Blicher ∗,∗∗ Kim Kristensen ∗∗
John Bagterp Jørgensen ∗
∗Technical University of Denmark, Department of Applied
Mathematics and Computer Science, DK-2800 Kgs. Lyngby, Denmark∗∗Novo Nordisk A/S, DK-2880 Bagsværd, Denmark


- Paper used for ODEs and Values with corrected adaptation by Opus: Modeling and Simulation to Support Phase 2 Dose Selection for RG7652, a Fully
Human Monoclonal Antibody Against Proprotein Convertase Subtilisin/Kexin
Type 9
Nageshwar R. Budha,1 Maya Leabman,2 Jin Y. Jin,1 D. Russell Wada,3 Amos Baruch,2 Kun Peng,2
Whittemore G. Tingley,4 and John D. Davis5,6,7
Received 23 October 2014; accepted 17 February 2015; published online 31 March 2015

- Additional papers found online: 

 - - Erratum to “Mathematical modelling of hepatic lipid metabolism,
Mathematical Biosciences 262 (2015) 167–181”Adrian C. Pratt a,b, Jonathan A.D. Wattis b,∗, Andrew M. Salter aa Division of Nutritional Sciences, School of Biosciences, University of Nottingham, Sutton Bonington Campus, Loughborough, Leicestershire LE12 5RD, UKb Centre for Mathematical Medicine and Biology, School of Mathematical Sciences, University of Nottingham, University Park, Nottingham NG7 2RD, UK

- - A Mechanistic Systems Pharmacology Model for 
Prediction of LDL Cholesterol Lowering by PCSK9 
Antagonism in Human Dyslipidemic Populations
K Gadkar1, N Budha1, A Baruch1, JD Davis1, P Fielder1 and S Ramanujan1
