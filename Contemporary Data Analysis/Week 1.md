# Introduction
the field and the data

## Overview of the field

### Definitions
- Battle for multiple definitions, "data science", "data analytics" "business analytics" "statistics", etc
- Methods used For
	- Data Analytics
		- Data Querying
		- Data Wrangling
		- Statistical Modeling
		- Data Analysis
		- Data Visualization
	- Data Science
		- Data sourcing
		- Data cleaning
		- Data modelling
		- Results evaluation
		- Results testing and deployment
- Circles
	- Programming
	- Machine Learning
	- Data Processing
	- Data Science
	- Mathematics & Statistics
	- Statistical Research
	- Domain Expertise
- Skills
	- Data Science Skills, Data Analytics Skills
	- Data Science, ML, Data Engineering
	- Data Mining, Data Analytics, Data Analysis, Data Science

???

#### Dave Holtz, data scientist at Airbnb
A Data Scientist is a Data Analyst who lives in San Francisco?

Some companies/fields/programs anyone is a data scientist, regardless of what they do!

#### Everyone has their own definitions

##### S. Kakati
Data science, also known as data-driven science, is an interdisciplinary field about scientific methods, processes, and systems to extract knowledge or insights from data in various forms, either structured or unstructured, similar to data mining

##### J.L Heilbron
Data science is a systematic enterprise that builds and organizes knowledge in the form of testable explanations and predictions

##### J. Leek
The key word in data science is not "data" it is "science". Data science is only useful when the data are used to answer a question. That is the science part of the equation

#### History of the term
- The term data science -> 1974
- Danish computer user Peter Naur urged for a potentially different name for engineering science
- Data Science was originally used interchangeably with Computer Science
- When Harvard BR called it the Sexist Job of the 21st Century, the term became a buzzword
- Now it is often applied to business analytics, or even an arbitrary use of data
- CF Jeff Wu, 1997, Statistics = Data Science
	- data collection, data modelling and analysis and decision making
	- In his conclusion, he initiated the modern, non computer science, usage of the term, "data science" and advocated that statistics be renamed data science and statisticians - data scientists
- William S. Cleveland, 2001, Data Science : An Action Plan to Expand the Technical Field of Statistics
	- William is credited with conception of data science, as a separate discipline, extending the field of statistics to incorporate advances in computing with data

#### William established 6 technical areas which he believed to encompass the field of data science
1. multidisciplinary investigations
2. models and methods for data
3. computing with data
4. pedagogy
5. tool evaluation
6. and theory

- 1,000s of years ago we used abacus
- 500s years ago, we used mechanical calculating machines (Wilhelm Schickard, 1623)
- 100s of years ago, we used Dalton's adding-listing machine (1902)
- Today we use computers. But we are still trying to do the same thing, generate meaning out of data.

### Contents
- Foundational course for graduate education in data analytics
	- review course, state-of-the-art interdisciplinary data analysis methods
	- introduce problem formulation at the intersection of mathematics and social science
	- gateway to advanced graduate studies (phd) in different fields

#### Master's program "Network Analytics for Business"
- Core : 6 general lectures & 6 specific topics reviewed in details
- Specialization : 6 overview lectures of the classical "path to insights" methods
- From descriptive to prescriptive analytics
- For practicing analysts, discussion and examples focus on applications in business and management

#### Course Structure
- Value vs Difficulty
	- What happened? (Descriptive Analytics)
		- **Information** -> Hindsight
	- Why did it happen? (Inferential Analytics)
		- Decision-making -> Insight
	- What will happen? (Predictive Analytics)
		- Optimization -> **Foresight**
	- How can we make it happen? (Prescriptive Analytics)

##### Data Issues
Applied missing data analysis
Advanced measurement methods

##### Descriptive Analytics

##### Inferential Analytics

##### Predictive Analytics
Instrumental Variables
Spatial data analysis
Time-series analysis
Causality extended : RDD

##### Prescriptive Analytics

## The field map

### Other maps includes
- Map
	- Statistics
	- Data
	- Characterization
	- Visualization
	- Hypothesis
	- Predictions
	- Probability
	- Distributions
- Chart
	- Questions -> Data -> Analysis -> Action -> Questions
- Flow
	- Reality -> Raw data collected -> data processed (clean dataset) -> exploratory data analysis -> analytics and modelling -> reports | data products | decisions -> reality

	- Data Sources (DB,flat,Text) -> Data Preparation -> Data for Analysis -> Data Analytic Techniques (D, Pred, Pres) ->Analysis Results (Summaries, Viz, Modesl, Candidate Solutions)

![image](/.attachments/abbf6db8a554af9973e66bb42b439390f7836301.png)

# Role of data
## Data economy
- Cira 18,000 BC : first evidence of tally stick
- Cira 5,000 BC : more advanced record-keeping by people settled along large rivers
- Circa 2,400 BC : Abacus, Babylon
- 300 BC - 48 AD : Alexandria Library, largest collection of data in the world (at that time)
- Cira 100-200 AD : The Antikythera Mechanism, the earliest discovered mechanical computer
- 1663 : first recorded experiment in statistics carried out by John Graunt
- 1865 : The first time the term "business intelligence" is used by Richard Millar Devens
- 1922 : Works of Ronald Fisher defined the field of statistics
- 1926 : Tesla predicts wireless technology in his interview to the Colliers magazine
- 1928 : Fritz Pfleumer invents a method of storing information magnetically on tape
- 1962 : First steps towards speech recognition
- 1970 : Relational database framework developed by Edgar F Codd
- 1989 : use of the "big data" term, possibly, for the first time
- 1991 : The birth of internet as we know it today
- 2011 - 2020, volume of data in the world has increased from 1.8 to 59 zettabytes, 90% of all available data we have today was generated in the last two year
- In 2025, it is expected to reach 175 ZB

### What is Data Economy?
- A global digital ecosystem in which data is gathered, organized and exchanged by a network of vendors for the purpose of deriving value from the accumulated info.
- A branch of economics, where data are the goods. Related discipline is called "data economics"
- Mallow's "The Zeroth Problem"
	- A major breakthrough ("an epochal event") for the field of statistics
		- In 1922 Fisher decoupled the theory of statistics from its applications
	- Why major and important?
		- "A rich complex of concepts can be defined: tests, estimates, prior and posterior distributions, likelihood, sufficiency, efficiency, admissibility, invariance... We can study approximations and asymptotics. We can develop a theory of experimental design. We can develop general procedures such as the bootstrap."
	- Objective of statistics = reduction of data
	- Fisher's problems that arise from reduction of data
		- Problems of Specification
		- Problems of Estimation
		- Problems of Distribution
	- Most work in Data Analysis
		- Classical (Neyman/Pearson) and Bayesian methodology
		- Robustness studies
	- Most studies in statistics concern
		- Problem of Estimation
		- Problem of Distribution
	- Today research focus
		- Data scientists focus on "specification, estimation and distribution" of fisher's specification
		- New algorithms, methods, approaches all fall within these approaches
		- "But there are problems that logically precede Fisher's namely deciding what the relevant population is, what the relevant data are, and just how these relate to the purpose of the statistical study" - C. Mallow, 1998
		- DATA should not be missing from "data science"

## What are data?

- Data are facts. In any shape, form and format
- Information is data processed to be meaningful to the person who receive it
- Knowledge is a combination of information, experience and insight that may benefit the individual or the organization

### Definitions (no one single agreeable definition)
- Forbes approach (13 different types)
	1. Big data
	2. Structured, unstructured, semistructured
	3. Time-stamped
	4. Machine
	5. Spatiotemporal
	6. Open data
	7. Dark data
	8. Real-time data
	9. Genomics
	10. Operational
	11. High-dimensional
	12. Unverified outdated
	13. Translytic

Network data ???

![image](/.attachments/8363507108b14ebfb6a686ccfc1ab46c359d01f0.png)

### Data = Foundation
- Decision (changes, movement)
	- Purpose
- Wisdom (integrated, actionable)
	- Insight
- Knowledge (contextual, synthesized)
	- Meaning
- Information (organized, structured)
	- Context
- Data (raw, unstructured)

#### Data to Wisdom path is not always linear...

- Wisdom
	- Understanding the fundamental principle of relations
- Knowledge
	- Patterns in data, meaning
- Information
	- Structured, relations between data
- Data
	- Items, events, no relations

## Data Types & Classifications

### Basic types of measurement
- Fundamental
	- direct measurements of selected attributes, for example, mass and volume in physics
- Derived
	- measurements computed from already measured (known) qualities. For example, density is the ration between mass and volume

#### Measurement needs scale
- Measuring, assign a value to a property using some predetermined transformation laws
- Scales can be different (eg: mass, temperature)
- Measurement scales measuring the same property are equivalent
- For usual scales, the replacement scales can be obtained from each other using the admissible transformations

#### 5 Scale types
All data can fit into 5 scales
1. Nominal
2. Ordinal
3. Interval
4. Ratio
5. Absolute

![image](/.attachments/85a1ad3fd503151b457008d66b2683f0a998f31e.png)

#### High level classification

- Quantitative
	- numbers and all the things they can measure objectively
		- Continuous, divisible to finer and finer levels (eg: ranking)
		- Discrete, count that can't be divided further (eg: number of children)
- Qualitative
	- characteristics and descriptors that can't be easily measured, but can be observed subjectively 
		- Binomial, Items assigned to two mutually exclusive categories (0/1,T/F) (eg: binary)
		- Nominal, items assigned to individual items to named categories that do not have an implicit or natural value or rank (eg: flag, colors)
		- Ordinal, items assigned to categories that do have some king of implicit of natural order (eg: average, good, bad)

##### More classifications
Organizing data and management
- Converting data to computer readable formats
	- Integer
	- Floating point number
	- Character
	- String
	- Boolean
- Time
	- Time-series
	- Cross-sectional
- Domain
	- Public
	- Internal only
	- Confidential
	- Restricted
- Organizational data management
	- Paper-based classification
	- Automated classification
	- User-driven classification

## Data Sources

### Where do data come from?

- **Primary** data are collected directly from the source
	- **Primary** data are specific to the needs of the researcher at the moment of data collection
		- Reliable
		- Authentic
		- Objective
	- It is accurate compared to secondary data
		- Not subjected to personal
		- The authenticity can be trusted
	- Primary data are collected directly from the source
		- The searcher owns the data and can
			- make it available publicly
			- patent it
			- sell it
		- Primary data are usually up to date
			- Data are collected in real-time
			- Not from the old sources
		- The researcher has full control over the data. Can choose
			- Design
			- Method
			- Data analysis techniques
		- Primary data are very expensive compared to secondary data
		- Time-consuming
		- May not be feasible to collect due to
			- complexity
			- required commitment
- **Secondary** data, collected in the past by someone else
	- More easily accessible
	- Available on different platforms
	- Very affordable
	- Low time required for collection
	- Make longitudinal studies more feasible
	- Helps generating new insights into available primary data
	- Secondary data may not be authentic and reliable
	- Many data may not be relevant
	- May include unknown personal bias of original researcher
	- Secondary data sources may be outdated

![image](/.attachments/ade9d79bac96e3a20c2097b7b0e404bea426fe6c.png)

### Source Credibility

- Data credibility is important
- There are many helpful guides on determining the credibility of the source (hint: do not start with the internet)
- Credibility of the source should supersede all other data requirements

# Modeling

## What is a model?

Webster's dictionary, 14 different meanings.
- a usually miniature representation of something
- a system of postulates, data, and inferences presented as a mathematical description of an entity or state of affairs
- an example for imitation or emulation
- a description or analogy used to help visualize something (such as an atom) that cannot be directly observed

### 3 models types used in analytics
- Iconic models - physical replicas or real objects
- Analog models - physical in form, but do not physically resemble the object being modeled
- Mathematical models - represent real world problems through a system of mathematical equations

Models are informative representations

"All models are wrong, but some are useful"
George E. P. Box.

## Why model?
- Epstein, 2008, 16 reasons to model
	1. To explain something
	2. To guide data collection
	3. To illuminate core dynamics
	4. To suggest dynamical analogies
	5. To discover new questions
	6. To promote scientific mind
	7. To find outcome boundaries
	8. To illuminate core uncertainties
	9. To offer crisis options in real-time
	10. To show tradeoffs
	11. To challenge robustness of theories
	12. To expose incorrect beliefs
	13. To train practitioners
	14. To discipline the policy dialogue
	15. To educate the general public
	16. To reveal simple vs complex

- Characteristics of a Good Model
	- Parsimony
	- Tractability
	- Conceptual insightfulness
	- Generalizability
	- Falsifiability
	- Empirical consistency and
	- Predictive precision

**Parsimony**, stinginess, model simplicity

**Tractability**, a model that can be solved
	- analytical tractability (a solution to a theoretical model)
	- empirical tractability (estimating/calibrating a model)
	- computational tractability (finding numerical solutions)

**Generalizability**, the performance and adaptability of a model when applied to a new conditions while maintaining the same basic set of explanatory variables, same variables give similar results on a different data

**Falsifiability**, Scientific models must have the potential to be refuted or falsified. This means that it must be possible to do a real-world test that could show the model is incorrect 

## Analysis for decision-making

### Decision Theory

- Decision theory is a theory about decision
	- The subject is not very unified
	- There are many different ways to theorize about decisions
	- There are many different research traditions
	- The emphasis is on the less (mathematically) technical aspect of decision-making
	- Human activities involve decisions
	- Decision theory focuses on only some aspects of human activity
	- We choose among options in a non-random way
	- Hence, decision theory is concerned with **goal-directed behavior in the presence of options**

- Historical development
	- Mostly since the middle of 20th century
- Contribution from several disciplines
	- Economics
	- Statistics
	- Operational Research
	- Social Sciences
- Multidisciplinary field
	- Large overlap
	- Variety of analytical methods

- Normative Decision Theories
	- how decisions should be made
- Descriptive Decision Theories
	- how decisions are made

#### Mathematical Models that Aid Decision-Making
- General components of a decision-making model
	- Objective function
		- A mathematical expression that describes the problem's objective, such as maximizing profit or minimizing cost
	- Constraints
		- A set of restrictions or limitations, such as production capacities
	- Uncontrollable inputs
		- Environmental factors that are not under the control of the decision maker
	- Decision variables
		- Inputs, decision alternatives specified by the decision maker, such as the number of units of product to produce

#### Modelling reality requires using probability

- Deterministic model
	- all uncontrollable inputs to the model are known and cannot vary
- Stochastic (or probabilistic) model
	- some uncontrollable inputs are uncertain and subject to variation (these are often more difficult to analyze)

#### Good models are data intensive !
- Data preparation is not trivial
	- Substantial time requirements
	- Possibility of data collection errors
- A model with 50 decision variables and 25 constraints could have over 1300 data elements
	- Large dataset may be required

#### Range of solutions
- Optional solution : the best output
- Infeasible solution : a solution that does not satisfy all constraints
- Possible solution : a solution that satisfies all constraints and is feasible

- Special solution procedures have been developed for specific mathematical models
	- Small models/problems can be solved by hand
	- Most practical applications require programming or special software

#### Model Testing & Validation

- Goodness of fit/accuracy of a model are usually assessed after solutions are generated
- Use "small test" problems for known or expected solutions to validate new models
	- If solutions are as expected on a "small test" problem, the model on the full-scale problem
- Corrective actions for inaccurate models
	- Collection of more accurate input data
	- Modification of the model

![image](/.attachments/447d2b24b1d134aced733f6981c2687c20cb0ed6.png)

### Types of Analysis

![image](/.attachments/1db426cf98653740a97dbc8f75b4e65555d215bd.png)

