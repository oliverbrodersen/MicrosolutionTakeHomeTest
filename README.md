# MicrosolutionTakeHomeTest

## Introduction
This is a solution designed to challenge a potential developer candidate with simple features that touches many relevant technologies that are often used in Microsolutions applications. The task definition is intentionally technically vague because we want to see how you will go about solving it. 

# The task
Create a new page from where you can search emojies from an API, see your search history and favorite specific emojis.
- The page should be available from the nav menu
- Use the [emojihub API](https://github.com/cheatsnake/emojihub)
- The user should be able to search for emojies in the Groups and Catagories documented in the APIs documentation
- The user should be able to see their API search history from the page (including what was searched, what was returned and timestamp)
- The user should be able favorite specific emojies from the search result and also see these favorites
- The search history and favorites should be saved in seperate tables using Entity Framework
These are the minimum requirements, you are allowed to add additional features if you would like

## Notes
### Version control
Clone the project using Visual Studio.
When you are done, take your repo folder, ZIP it, and send I to the email that send you this challenge. 

### Development
We do not have any specific requirement regarding how your code should look. Instead we want to see how you would go about implementing these features in a maintainable, readable and efficient way using best practices in regards to the technologies you are using.

### Database
The database is SQLLite database which should also be included in your final pullrequest.

You will need to use Entity Framework to query, add and update records in your database. The DBContext is provided and setup in the DataContext class in the Database folder. 

