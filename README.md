# FriendFinder


### Premise
This application was built to demonstrate the use of URL route handling within the express server.  It simulates the function of a "matching" application where the user completes a short survey and is paired with a compatible selection from a predefined collection of options.  


### Features
Key fatures of this application include:
* Handling a default route "/" and a survery route "/survey"
* Basic field completion checking to disallow empty responses
* Processing of basic POST operations to retrieve supplied values
* A comparison function to determine best match
* A link to expose JSON formated API data
* First application deployed to Heroku hosting service


## Requirements
The application require the usage of the `express` server package libraries. 


## Usage
1. Access [the application](https://lit-beyond-24073.herokuapp.com/) on Heroku  
2. You will be presented with with a welcome page where you can elect to:
    * Take the survey
    * Display the API Friends List, or 
    * Access my GitHub Repo
3. Accessing the survey you will be required to provide somthing for all prompts
4. Upon completion, click the "Submit" button.
5. You will be presented your match or and error prompt.


## Considerations
* The application has a small number of available seed matches.  The seed matches have diverse responses to demonstrate the features of the matching routine.  Varying your responses to the prompt will result in new matches.  
* The images displayed with the matches are random photos which simulate the display of stored profile pictures for these individuals.    

