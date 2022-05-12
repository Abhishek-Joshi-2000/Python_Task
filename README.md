# Python_Task
Create a small python program that will use the Google Books Api  e.g. https://www.googleapis.com/books/v1/volumes?q=user+story+mapping and get the isbn number than use this isbn to do a search on the Barnes and Noble site and display the books found on that site.

First I have used Requests package to send HTTP requests to given uniform resource locator of Google Books Api and get responses. I received response 200, which implies that my request was fulfilled. I also saved the result as a python dictionary in json format. Then, using the provided API, I pulled only the isbn values for each book. I had isbn values in two different formats for each book, which I saved in two different lists.

Following that, I installed the Selenium package as well as Chromedriver. Then, using webscraping, I located search box on https://www.google.com/, entered a random isbn number that I had already collected, and clicked the search button using the click() method.

