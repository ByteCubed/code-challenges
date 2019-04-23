# Data Engineering Code Challenge

## Introduction

Imagine that you work in the technology department of used car dealership chain and you've been tasked to develop a solution
that enables other developers to get access to a messy dataset. The information in the dataset will be used for two main tasks:
 
1. Generating reports regarding monthly purchases of vehicles by store
2. Fetching information about specific vehicles, as well as vehicles coming from specific stores 

Your goal is to design a solution that allows other users to programmatically access the information contained in the
dataset in an easy way.   

#### Skills assessment

The purpose of this code challenge is to assess:

* Your ability to work with messy data
* Your understanding of SQL databases, including but not limited to: schema design, query patterns, and normalization
* Your knowledge of API design and general software engineering skills

## Actual Task

Create a RESTful API to interact with the dataset. Make sure to include the following functionality:

* Standard CRUD operations on a particular data point
* Ability to fetch aggregate data on a dimension of your choice. Ideas are: number of vehicles purchased per store, 
* Filtering based on price and store location
average purchase price per store, sorted list of most commonly sold makes/brands, etc. 
* Must use a SQL-based database, we recommend SQLite to minimize development overhead

A few notes:
* Focus on how you'd design a schema that enables evolution over time with minimal overhead
* Keep performance considerations in mind when designing indexes, and make sure to document the trade-offs that your decisions will entail


#### Helpful tips

As you work, consider how you might productionize your solution to work in a cloud environment. We work a lot with Docker, 
so bonus point if you decide to include it in the submission. 

Keep note of any challenges or blockers you encounter as you work and be ready to discuss your development work flow, 
including things you tried and lessons you've learned as you completed the code challenge. 

Finally, be creative and have fun! :smiley:

## Deliverables

#### What deliverables do I submit?

Please submit the following deliverables to complete this code challenge: 

* A `README.md` file containing the following items:
    * Thorough instructions on how to run your solution. This could be things like how to install dependencies, 
    a single docker command, or whatever else is needed to be able to interact with your solution
    * An explanation of the components of the solution. At a minimum, it should briefly document how the API is structured and
    what methods each endpoint allows. If there are any ETL steps that you designed prior to loading the data into the database,
    make sure to include that as well
* The actual submission code, with all that's needed to run it


#### How do I submit my deliverables?

Please archive all of your deliverables into a single compressed file and save the file using the file naming convention shown below. Please substitute your first name for *FIRST_NAME*, last name for *LAST_NAME*, and the year (*YY*), month (*MM*), and date (*DD*) when you submitted your code challenge.

*FIRST_NAME-LAST_NAME-YYMMDD-data-engineering-code-challenge*

#### When do I submit my deliverables?

Please submit your solution within 1 week (7 days) of receiving the code challenge. If you require more time, drop us a line at [DataScienceU@u.group](DataScienceU@u.group). Let us know why you need more time, and how much more time you'll need to complete the challenge.

#### Where do I submit my deliverables?

Please send your completed code challenge to [DataScienceU@u.group](DataScienceU@u.group).

## Data

The [data](data/data_engineering_dataset.csv) you will use for this code challenge is a historical snapshot of vehicles that have been sold by a used car dealership across multiple stores. 

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
| EngineLiters    | Engine displacement in Liters                      |
| FuelType        | Fuel type of vehicle                               |
| Transmission    | Transmission type of vehicle                       |
| SaleLoc         | ID number of dealership that sold vehicle          |
| PurchVal        | Purchase price of vehicle                          |


## Questions

Please send all questions about the code challenge to [DataScienceU@u.group](DataScienceU@u.group).
