# Book Explorer - ShinyApp

This is the final project of the Network Analytics Course. 
We have developed an application on ShinyApp called Book Explorer for book passionate people who wants to find books that could match their preferences. 
Check the application here https://mariabaglieri.shinyapps.io/na_project_group_17/ . 

Do you want to find the next book to read? Do you want to know which are the most famous books based on our users' experience? Or probably you simply want some inspiration based on an author/publisher you already know. With this app, we will try to provide you with useful information and analyses regarding all the books we know and the network of users who read and rated those books.

The app is divided into four main pages. The Statistics page shows the key features and descriptive statistics of our dataset. Check here which are the main characteristics of our books and readers.

The Overall Plot page allows you to see several different visualizations of our huge book-reader network. You can filter the plot based on a Genre you usually prefer, an Author you appreciate, or a Publisher you like. Based on the filter, the plot will show all the books (vertices) and the users who read those books (edges). The width of the edge is proportioned to the number of readers.

Following the navigation bar, on the fourth page we created an elaborate analysis that could be useful for you to understand which books our users will probably read, based on their past experience. Based on books with common readers, we are trying in this page to predict some future links among books. The probability that a user will read the displayed books is based on the analysis of common neighbors (see setup.R file for more explanation of the logic behind this page). The highest the probability, the fewer the books that will appear. e.g. If User X already read Book A, Book B, and Book C, which book he will probably read next. On this page, you have to search for a specific book, so that you can see which books are strictly linked to your selection.

The last page is probably for the ones who want just to know which are the most appreciated books based on Average Rating. Here you can always choose your filters and check for some of the most central books in our dataset.
