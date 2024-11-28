# FakerDataSeeder

**FakerDataSeeder** is a Django-based tool that uses the `Faker` library to easily generate realistic test data for your database, ideal for development, testing, and prototyping.

## Features
- Seamlessly integrates with Django models.
- Customizable data generation for various fields (names, emails, phone numbers, etc.).
- Allows quick population of your database with realistic data.

## Installation

1. Install the package using pip:

   ```bash
   pip install faker
   
2. Open Django Shell from terminal:
 
   ```bash
   python manage.py shell

3. Import the seeding function:

   ```bash
   from home.seed_db import *
   
4. Call the function to generate data:

   ```bash
   dbSeeder(records=50)  

5. Call dbSeeder2 to populate additional data:

   ```bash
   dbSeeder2(records=50) 

Generates 50 and if we dont enter records like dbSeeder() then it is set to 10 by default
