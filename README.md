## Burger



A simple application using Express, Node, Handlebars, and MySQL. 

Upon loading the page, a get request is made to retrieve the database and present the data. All burgers are initiated with a false boolean representing whether or not they've been devoured. All burgers that have been devoured will be moved to the devoured div, where the rest will have a button with them allowing for them to be devoured. The button will make an update request, changing the value of the devoured bool and refreshing the page. Submissions to the form will make a post request, adding the new burger to the database.