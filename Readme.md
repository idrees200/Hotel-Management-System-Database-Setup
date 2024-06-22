# Hotel Management System Database Setup

This project involves setting up a hotel management system database with tables for hotels, rooms, guests, and bookings. The SQL script includes table creation, data insertion, and various queries to manage and retrieve data.

## Database Structure

### Tables

1. **Hotel**
   - Attributes: `hotelno`, `hotelname`, `city`
   - Stores hotel information.

2. **Room**
   - Attributes: `roomno`, `hotelno`, `type`, `price`
   - Tracks room details for each hotel.

3. **Guest**
   - Attributes: `guestno`, `guestname`, `guestaddress`
   - Stores guest information.

4. **Booking**
   - Attributes: `hotelno`, `guestno`, `datefrom`, `dateto`, `roomno`
   - Records booking details.

## Key Operations

1. **Data Insertion**
   - Populating tables with initial data for hotels, rooms, guests, and bookings.

2. **Table Alterations**
   - Adding primary keys and foreign key constraints.
   - Modifying table structures to establish relationships.

3. **Data Manipulation**
   - Inserting, updating, and deleting records to manage the database.

4. **Queries**
   - Retrieving specific records based on conditions.
   - Performing joins and filtering data based on criteria.

## Sample Queries

- Retrieve all hotels in London, ordered by hotel name in descending order.
- Retrieve hotels with names matching specific patterns.
- Retrieve bookings where the end date is not specified.
- Extract first names from guest names.
- Retrieve guest information based on address and name patterns.
- Retrieve room numbers and booking dates for specific years.
- Retrieve specific room details based on type and price range.
- Order rooms by price in descending order and retrieve the top result.
- Concatenate and format hotel information.
- Join room and hotel tables to retrieve room and hotel names based on room types.

## How to Use

1. **Create Database and Tables**
   - Run the provided SQL script to create the `hotelsys` database and its tables.

2. **Insert Initial Data**
   - Insert sample data into the tables as shown in the script.

3. **Modify and Query Data**
   - Perform data modifications and queries to interact with the database.

This setup provides a foundation for managing hotel-related data with a structured and relational approach. The script ensures the integrity and consistency of the data through various constraints and relationships.
