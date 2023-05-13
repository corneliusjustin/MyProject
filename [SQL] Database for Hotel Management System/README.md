# Hotel Management System Database

This project was developed as the final project for the "Database for Data Science" class, with a team of 5 members. The goal of this project is to create and develop a database for a 3-star hotel in Jakarta, Indonesia. 

## Background

A hotel is a building with rooms that are rented out for temporary lodging and/or dining purposes. Hotels are profit-oriented businesses, and processing and storing data in a systematic and computerized way can make it easier to control and monitor room availability, room reservations, transactions, complete administrative processes, and even gain insights into how long visitors typically stay at the hotel. By storing data systematically and in a database, decision-making based on data and visualization of data become more accessible. 

Manual data collection for room reservations, transactions, and other administrative processes can be time-consuming and difficult to access. Therefore, this database was developed to simplify data archiving. By processing data systematically and computerizing it, hotel management can make informed decisions and promotions to increase room bookings and customer satisfaction.

## Objectives

The objectives of this project are to:
- Facilitate the hotel in processing data quickly and accurately.
- Make it easy for employees to record, search, and access reservation, transaction, and administrative data.
- Provide better and faster service to hotel customers because the process is managed by the system.

## Methodology

We conducted research by using dummy data created by ourselves. In this research, we used 5 stages to create the Hotel Management System database:
1. Research Technique (Literature Method)
Using the literature method, we searched for information related to databases from journals, books, and other sources on the internet. Our goal was to deepen our understanding of the application of SQL so that we could present an analysis of the relationships in the database.

2. Data Collection and Analysis
Before creating the dummy data, we searched for information on the system's requirements and collected appropriate data to be inputted into the database.

3. Conceptual Level Database Design
The conceptual level database design aims to see user needs, limitations, and relationships between data. In this stage, we usually create an ER Diagram. The ERD is expected to provide a clear relationship between the inputted data. We will also select the primary key and foreign key.

4. Logical Level Database Design
The logical level database design maps the previous stage's design into a database model that will be used. We will use a table description model that is modified from the previously created ER Diagram. We will create a table that describes which data is a primary key and foreign key, the data type, and the data length.

5. Physical Level Database Design
In this stage, we will implement the design from the previous stages to obtain a functional database. We will use an SQL program to create the required tables and input the dummy data. After implementation, we will analyze a problem scenario and draw conclusions from the created database.

## ER Diagram Description

The hotel has various facilities, including rooms, restaurants, and conference rooms. Each room has a different type, size, and price. Each guest has a unique guest ID and can stay for several days. Each guest can book one or more rooms, and each room can be booked by one or more guests. The database also stores information about restaurant reservations and conference room bookings.

## Conclusion
Based on the work that has been done and realized before, there are several conclusions that can be drawn regarding the database for storing information about hotel management data. The main purpose of creating this database is to facilitate data collection, and with the created database, it can ease the process for employees to search for various customer data or facilitate the data collection process. The interconnection between each data also allows for better and faster service to hotel customers because of the streamlined processes within the system. Overall, the database proves to be a useful tool in managing hotel operations efficiently.