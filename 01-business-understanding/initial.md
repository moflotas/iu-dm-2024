# Business Understanding

## Determine business objectives

### Background

> Record the information that is known about the organization's business situation at the beginning of the project.

Company under domain name [aqar.fm](https://sa.aqar.fm/) is a real estate company that provides a platform for real estate agents to advertise their properties for sale or rent. The company is based in Saudi Arabia and has a website and mobile application.

### Business objectives

> Describe the customer's primary objective, from a business perspective. In addition to the primary business objective, there are typically other related business questions that the customer would like to address. For example, the primary business goal might be to keep current customers by predicting when they are prone to move to a competitor. Examples of related business questions are "How does the primary channel (e.g., ATM, visit branch, internet) a bank customer uses affect whether they stay or go?" or "Will lower ATM fees significantly reduce the number of high-value customers who leave?"

The primary business objective is to predict the price of a property based on its features to automate the process of pricing properties for sale or rent. The related business questions are:

- What are the most important features that affect the price of a property?
- How does the location of a property affect its price?
- How does the size of a property affect its price?
- etc.

### Business success criteria

> Describe the criteria for a successful or useful outcome to the project from the business point of view. This might be quite specific and able to be measured objectively, such as reduction of customer churn to a certain level or general and subjective such as "give useful insights into the relationships." In the latter case it should be indicated who makes the subjective judgment.

The criteria for a successful outcome to the project from the business point of view is to have a model that can predict the price of a property with a high accuracy. The accuracy of the model will be measured by the mean absolute error (MAE) and the root mean squared error (RMSE).

## Assess situation

### Inventory of resources

> List the resources available to the project, including: personnel (business experts, data experts, technical support, data mining personnel), data (fixed extracts, access to live warehoused or operational data), computing resources (hardware platforms) and software (data miningtools, other relevant software).

Since we provide offline analytics without the help of the company, the only available resources are

- My computing resources (Laptop with GPU, Google Colab)
- [Dataset](https://www.kaggle.com/datasets/mohdph/saudi-arabia-real-estate-dataset)
- [Website](https://sa.aqar.fm/)

### Requirements, assumptions and constraints

> List all requirements of the project including schedule of completion, comprehensibility and quality of results and security as well as legal issues.As part of this output, make sure that you are allowed to use the data. List the assumptions made by the project.
> These may be assumptions about the data that can be checked during data mining, but may also include non-checkable assumptions about the business upon which the project rests. It is particularly important to list the latter if they form conditions on the validity of the results.
> List the constraints on the project. These may be constraints on the availability of resources, but may also include technological constraints such as the size of data that it is practical to use for modeling.

The requirements of the project are:

- The project should be completed by the end of the course.
- The results should be understandable by the company.
- The results should be of high quality.

The assumptions made by the project are:

- The dataset is representative of the company's data.
- The dataset is clean and does not contain any errors.

The constraints on the project are:

- The dataset is huge and might be hard to process

### Risks and contingencies

> List the risks or events that might occur to delay the project or cause it to fail. List the corresponding contingency plans; what action will be taken if the risks happen.

The event that might occur to delay the project or cause it to fail is crisis in the country with consequences on the real estate market causing the prices to change drastically. The contingency plan is to use the latest data available.

### Terminology

> Compile a glossary of terminology relevant to the project. This may include two components:
(1) A glossary of relevant business terminology, which forms part of the business understanding available to the project. Constructing this glossary is a useful "knowledge elicitation" and education exercise.
> (2) A glossary of data mining terminology, illustrated with examples relevant to the business problem in question.

So far there is no terminology relevant to the project.

### Costs and benefits

> Construct a cost-benefit analysis for the project, which compares the costs of the project with the potential benefit to the business if it is successful. The comparison should be as specific as possible, for example using monetary measures in a commercial situation.

The cost of the project is the time spent on it and the benefit is the time saved by the company.

## Determine data mining goals

### Data mining goals

> Describe the intended outputs of the project that enables the achievement of the business objectives.

The data mining goals are:

- Predict the price of a property based on its features.
- Identify the most important features that affect the price of a property.

### Data mining success criteria

> Define the criteria for a successful outcome to the project in technical terms, for example a certain level of predictive accuracy or a propensity to purchase profile with a given degree of "lift." As with business success criteria, it may be necessary to describe these in subjective terms, in which case the person or persons making the subjective judgment should be identified.

The criteria for a successful outcome to the project in technical terms is to have a model that can predict the price of a property with a high accuracy. The accuracy of the model will be measured by the mean absolute error (MAE) and the root mean squared error (RMSE).

## Produce project plan

### Project plan

> List the stages to be executed in the project, together with duration, resources required, inputs, outputs and dependencies. Where possible make explicit the large-scale iterations in the data mining process, for example repetitions of the modeling and evaluation phases. As part of the project plan, it is also important to analyze dependencies between time schedule and risks. Mark results of these analyses explicitly in the project plan, ideally with actions and recommendations if the risks appear.
> Note: the project plan contains detailed plans for each phase. For example, decide at this point which evaluation strategy will be used in the evaluation phase. The project plan is a dynamic document in the sense that at the end of each phase a review of progress and achievements is necessary and an update of the project plan accordingly is recommended. Specific review points for these reviews are part of the project plan, too.

The project plan is divided into six phases:

- Business understanding (2 weeks)
- Data understanding (2 weeks)
- Data preparation (2 weeks)
- Modeling (2 weeks)
- Evaluation (2 weeks)
- Deployment (2 weeks)

### Initial assessment of tools and techniques

> At the end of the first phase, the project also performs an initial assessment of tools and techniques. Here, you select a data mining tool that supports various methods for different stages of the process, for example. It is important to assess tools and techniques early in the process since the selection of tools and techniques possibly influences the entire project.

The tools and techniques used in the project are:

- Python and it's libraries (Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn, etc.) for data analysis and visualization
- Google Colab and it's GPU support for faster model training
- Git and Github for version control
