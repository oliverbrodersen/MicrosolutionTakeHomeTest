# MicrosolutionTakeHomeTest

## Introduction
This is a solution designed to challenge a potential developer candidate with simple features that touches many relevent technologies that are othen used in Microsolutions applications.

# The task
Create a new page from where you can search emojies from an API, see your search history and favorite specific emojis.
- The page should be available from the nav menu
- Use the [emojihub API](https://github.com/cheatsnake/emojihub)
- The user should be able to search for emojies in the Groups and Catagories documented in the APIs documentation
- The user should be able to see their API search history from the page 
- The user should be able favorite specific emojies from the search result and also see these favorites
- The search history and favorites should be saved in seperate tables using Entity Framework

## Notes
### Version control
Clone the project using Visual Studio and create a new Branch for your code. You can create as many commits you want during development.

When you are done, create a pull request into main. If you have any tasks you know you did not finish please describe the problems you encountered in the pull request message. 

### Development
We do not have any specific requirement regarding how your code should look. Instead we want to see how you would go about implementing these features in a maintainable, readable and efficient way using best practices in regards to the technologies you are using.

### Database
The database is SQLLite database which should also be included in your final pullrequest.

You will need to use Entity Framework to query, add and update records in your database. The DBContext is provided and setup in the DataContext class in the Database folder. 

