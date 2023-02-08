# Articles website with webscraper
Blackpaper - PHP, MySQL, jQuery website with articles supplied from webscraper

This project has been created to put learned PHP and mySQL skills into practice.
PHP and MySQL article website part is completed, webscrapper that will supply this app with data is still under construction.

## PHP & MySQL part:
    1.Created a database to store articles information.
    2.Connected the PHP script to the database for retrieving and updating article information.
    3.Implemented the combination of PHP and HTML to display a formatted list of articles.
    4.Added pages to show, edit, and add articles.
    5.Validated the ID passed in the query string to ensure that it's a valid article.
    6.Refactored the code into separate files to improve organization and maintainability.
    7.Used an .htaccess file to deny access to the includes folder, improving security.
    8.Validated the form input using HTML5 form validation to ensure data integrity.
    9.Inserted article information into the database using PHP.
    10.Implement measures to prevent SQL injection attacks and Cross-site scripting (XSS).
    11.Validated submitted article's title, content, and date to ensure that the data entered is valid.
    12.Allowed for editing and deleting articles in the database from PHP.

## jQuery webscraper part:
    1.Built a function to scrape website data using jQuery and AJAX
    2.Created a loop to scrape data from multiple pages of the website
  To do:
    1.Parse the scraped data to extract relevant information such as article titles, dates and content
    2.Store the extracted information in a JSON object
    3.Send the JSON data to the PHP script using AJAX
    4.Validat the received data on the PHP side to ensure its integrity
    5.Inserted the validated data into the MySQL database
    6.Use jQuery to display the scraped data in an attractive and user-friendly format on the website
    7.Implement error handling to catch any errors that may occur during the scraping process
    8.Optimize the performance of the web scraper by using techniques such as lazy loading and caching.
