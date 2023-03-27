# API_Automation
This repository contains an API automation test demo designed to teach how to automate testing of an API using Python and the pytest framework. The demo includes a sample API and test script that can be used as a reference for writing API tests.

Prerequisites
1) Install Postman in your device
2) Install node in your device

Installation
Clone this repository to your local machine:

bash
git clone https://github.com/yourusername/API_Automation.git
Open postman
Import the json file
You should see the API collection in postman after importing it
Import the environment variable which is also a JSON file
Run the login request first for testing using the login data there
If that doesnt work for some reason run the registration request where you will only need to change the email address and phone number in the payload for it to work
You can set it up to your own client's, project or company's work
Make sure the test is automatable by using the environment variables
Export it once done with making it automatable
Export your Environment too in the same place
Install Newman by using the command
"node install -g newman"
Go to your Collection location in our Local system using CMD
Run Newman in CMD or terminal
Newman run <CollectionName> -e  <EnvironmentName>
where collectionName is the JSON collection you exported and EnvironmentName is the JSON environment you exported
After you are sure the run is similar to the one in postman then you can create your report with the command below
Newman run <CollectionName> -e  <EnvironmentName> -reporter=cli,htmlextra
