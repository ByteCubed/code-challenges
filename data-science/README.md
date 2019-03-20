# Data Science Code Challenge

## Introduction

Imagine that a used car dealership chain has asked us to help them modernize their infrastructure, improve their business processes, and increase their profitability. The car dealership has provided us with an anonymized sample of used car data. For this code challenge, your goal is to investigate these data and come up with at least one data science service that we could offer to the dealership.

#### Skills assessment

The purpose of this code challenge is to assess:

* Your ability to translate business problems into data science questions.
* Your use of the Python data science stack to work with and manipulate data.
* Your application of data science tools and methods to provide solutions to business problems.
* Your ability to communicate your work to different audiences.

## Task

Your task is to come up with at least one data science service or offering to pitch to the client. 

For example, your data science solution might improve business operations, increase profitability, or reduce the time it takes to sell a vehicle.

To complete this task you should:

1. Use a [Python](https://www.python.org) and a [Jupyter](https://jupyter.org/) notebook for your analysis and presentation. 
2. Load the anonymized sample of [used car data](data/used_cars.csv) into a [Pandas](https://pandas.pydata.org/) dataframe and perform any necessary pre-processing steps.
3. Conduct an exploratory data analysis and look for interesting patterns and stories. Be sure to support your findings with plots, figures, and graphics using [Matplotlib](https://matplotlib.org/), [Seaborn](https://seaborn.pydata.org/), or another data visualization package of your choice.
4. Identify a business problem that where data science may offer a solution. Implement data science methods and/or build a prototype to solve this business problem.   
5. Create a short slide deck that communicates your findings and service or offering to the client.

#### Helpful tips

As you work, consider how you might productionize your data science solution or offering if the used car dealership contracted us to perform this work. Keep in mind that you do not need to actually productionize your work for this code challenge, but be prepared to talk about how you might implement your data science service or offering.

Keep note of any challenges or blockers you encounter as you work and be ready to discuss your development work flow, including things you tried and lessons you've learned as you completed the code challenge. 

Finally, be creative and have fun! :smiley:

## Deliverables

#### What deliverables do I submit?

Please submit the following deliverables to complete this code challenge: 
 
1. A well-documented [Jupyter](https://jupyter.org/) notebook.

   This notebook should include your [Python](https://www.python.org) code for pre-processing, manipulating, and exploring the data provided for this challenge. Use [Pandas](https://pandas.pydata.org/) for this task. Please also include your code for developing any machine learning models, figures and graphics, if applicable.  

2. Documentation that sufficiently describes your development workflow.

   This documentation should include the requirements and libraries you used to create your data science service or offering. Using your documentation, we should be able to execute the code in your [Jupyter](https://jupyter.org/) notebook and reproduce your output.

3. A short slide deck that communicates your work to the client.

   Your slide deck may be delivered in Microsoft PowerPoint, Google Slides, or other software of your choice. This presentation should clearly define your data science question and how it relates to the business problem you identified. The slide deck should also showcase your service or offering and answer your data science question. 
   
   *Please limit your presentation to no more than 5 slides.*

#### How do I submit my deliverables?

Please archive all of your deliverables into a single compressed file and save the file using the file naming convention shown below. Please substitute your first name for *FIRST_NAME*, last name for *LAST_NAME*, and the year (*YY*), month (*MM*), and date (*DD*) when you submitted your code challenge.

*FIRST_NAME-LAST_NAME-YYMMDD-data-science-code-challenge*

#### When do I submit my deliverables?

Please submit your solution within 1 week (7 days) of receiving the code challenge. If you require more time, drop us a line at [DataScienceU@u.group](DataScienceU@u.group). Let us know why you need more time, and how much more time you'll need to complete the challenge.

#### Where do I submit my deliverables?

Please send your completed code challenge to [DataScienceU@u.group](DataScienceU@u.group).

## Data

The [data](data/used_cars.csv) you will use for this code challenge is a historical snapshot of vehicles that have been sold by a used car dealership across multiple stores. 

### Data dictionary 

| Column Title    | Column Description                                 |
| --------------- | -------------------------------------------------- |
| VIN             | Vehicle Identification Number (Unique vehicle ID)  | 
| CarYear         | Model year of vehicle                              | 
| Color           | Color of vehicle                                   |
| VehBody         | Body type                                          |
| EngineType      | Engine size in cylinders                           |
| Make            | Model name                                         |
| Miles           | Odometer reading at time of inventory              |
| SaleType        | (R) for resale, (N) for new vehicle                |
| Odometer        | Accuracy of odometer reading                       |
| Brand           | Vehicle make                                       |
| VehType         | Passenger, Truck, or Motorcycle                    |
| LocationNum     | ID number of store that acquired vehicle           |
| CarType         | Vehicle segment type                               |
| IsDomestic      | 0 = Foreign make, 1 = American make                |
| EngineLiters    | Engine displacement in Liters                      |
| Country         | Country of manufacture                             |
| FuelType        | Fuel type of vehicle                               |
| SeatingCapacity | Seating capacity of vehicle                        |
| Transmission    | Transmission type of vehicle                       |
| Status          | Status of vehicle                                  |
| SaleLoc         | ID number of dealership that sold vehicle          |
| ZIP             | Zip code of dealership that sold vehicle           |
| SellVal         | Final sale price of vehicle                        |
| PurchVal        | Purchase price of vehicle                          |
| ServiceVal      | Cost to service the vehicle (on-site repairs)      |
| ReconVal        | Cost to recondition the vehicle (off site repairs) | 
| LotTime         | Days vehicle spent on lot before sale              |

## Questions

Please send all questions about the code challenge to [DataScienceU@u.group](DataScienceU@u.group).