# README for Tocca Coding challenge
## Directions
Develop an API that accesses a Firebase real-time database to extract and return groups of 50 records from the document user_profile
user_profile structure is the following:
User_profile: {

  $user_id: { misc. profile information }

}


The API must be designed in such a way that it returns the profiles in a JSON object that contains no more than 50 profiles at one time. Many requests to this API can be performed to download all the profiles in the database 


Technologies to be used: Javascript, Firebase function and or any other tools from the FIrebase or GCloud environments. Preferred framework: Express - if proposing to use a different one or not to use this one, please provide the reason why.
