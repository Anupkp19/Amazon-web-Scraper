

Amazon Web Scraper
This Amazon Web Scraper allows you to track prices and automatically sends email notifications whenever there is a significant price drop. It is implemented using MongoDB, TypeScript, Bright Data, and cron jobs.

Getting Started
Follow these steps to run the project:

Sign up for Bright Data at https://brightdata.com and set up the web unlocker.

Create a .env file and add the following parameters:

makefile
Copy code
BRIGHT_DATA_PASSWORD=your_bright_data_password
BRIGHT_DATA_USERNAME=your_bright_data_username
MONGODB_URI=your_mongodb_uri
EMAIL_PASSWORD=your_email_password
Install the project dependencies:

MONGODB
1.For creating a mongodb url singup in mongodb and Launch a cluster and Click on connect to connect with Node.js then paste the url there.
bash
Copy code
npm install
Start the development server:

bash
Copy code
npm run dev
Usage
Wait for the website to fully load.

Go to Amazon and paste the product link into the provided interface.

The scraper will automatically add the item to the database.

You will be able to see the following information:

Current price
Highest price


EXAMPLE
<img width="1428" alt="Screenshot 2023-10-06 at 9 23 00 AM" src="https://github.com/Anupkp19/Amazon-web-Scraper/assets/93922233/835eed45-39c4-4c42-807f-bb4de9acae69">


