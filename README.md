# IMDB-Project-EN
A quick rundown of its process

This personal project, still ongoing to this day, is based on building, via web-scraping, a list of movies I might be interested to watch. In order to get that list, we'll be sraping data from Subscene (subscene.com), which is a website hosting a variety of subtitles. The logic behind it is : if a subtitle is available for download, then the file (movie/episode) that the subtitle is for is also available.
This way, using filters on language and upload date, I can highlight newly available movies.

![Scraping_Subscene](https://i.imgur.com/TOPVKaf.png)

Using scraping tools, we put together a list of movies. Each entry will have additionnal information (rating, duration, genre) added from another source : its IMDB web-page.

![Scraping_IMDB](https://i.imgur.com/07KsSaU.png)

The final table will contain both links to IMDB and Subscene.
Using a tool call SendGrid, we'll be able to send this list via email  (in HTML format), to which we'll join an Excel Spreadsheet containing the archive of all previous web-scraping processes.

![Resultat](https://i.imgur.com/sdyoVho.png)
