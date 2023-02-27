# Temp-Email

### Objective 

The major usage of this module is to create a temporary mail instantly and access the mailbox inside your mendix application.
  ![image](https://user-images.githubusercontent.com/126104423/221532561-fe6e8d88-3d8a-494d-a406-a0ecdac71039.png)

  
### Dependencies 

•	Studio pro version 9.12.0

•	https://rapidapi.com/calvinloveland335703-0p6BxLYIH8f/api/temp-mail44 

Use the above link to generate key for the API and use the key inside the module to get the response. 

### Configuration

•	Import the module TEMP EMAIL from the mendix marketplace.

•	Call the microflow ACT_GenerateTempEmailAddress to create the temporary email address. 

•	ACT_GetInboxMessages microflow is used to get inbox messages of the Temporary email id.

•	Copy the API key generated created and paste in the Rapid_ApiKey constant.

•	Check the Example page under examples folder on how the API is used.


