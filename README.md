![Beautiful-Soup](https://user-images.githubusercontent.com/42691222/150339705-4ae5ac83-8217-4928-8dbd-75f10d5d28f5.jpg)
# Web Scraping with Python

The internet is an absolutely massive source of data — data that we can access using web scraping and Python!

In fact, web scraping is often the only way we can access data. There is a lot of information out there that isn’t available in convenient CSV exports or easy-to-connect API's And websites themselves are often valuable sources of data — consider, for example, the kinds of analysis we could do if we could download every post on a web forum.

To access those sorts of on-page datasets, we’ll have to use web scraping. 

## How Does Web Scraping Work?
When we scrape the web, we write code that sends a request to the server that’s hosting the page we specified. The server will return the source code — HTML, mostly — for the page (or pages) we requested.

So far, we’re essentially doing the same thing a web browser does — sending a server request with a specific URL and asking the server to return the code for that page.

But unlike a web browser, our web scraping code won’t interpret the page’s source code and display the page visually. Instead, we’ll write some custom code that filters through the page’s source code looking for specific elements we’ve specified, and extracting whatever content we’ve instructed it to extract.

For example, if we wanted to get all of the data from inside a table that was displayed on a web page, our code would be written to go through these steps in sequence:

- Request the content (source code) of a specific URL from the server
- Download the content that is returned
- Identify the elements of the page that are part of the table we want
- Extract and (if necessary) reformat those elements into a dataset we can analyze or use in whatever way we require.

Thank you for visiting !!
