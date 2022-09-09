# web-scraping-project
Beautiful Soup is a Python library for pulling data out of HTML and XML files.
By using it I scraped wikipedia !! 

Just be cautious!!!
The simplest ways is to check the robots.txt file of the said website it is usually at the website domain /robots.txt, 
if in the robots.txt file all bots indicated by ‘user-agent: *’ are blocked/disallowed then you’re not allowed to scrape, the next is reading the terms of service of the website.

I found the classes where my particular data was lying in which attribute the data was present first I did it with one movie in particular "Toy Story 3", then i tried to get all disney movies 
from the wikipedia and there info box as well. 
for eg : other necessary details like run time, release date all related properties.

Then solved the problem of scraping in the list I was not getting data in the list format wherever it was required.
After scraping which was a tough process as i did scraping from wikipedia so the data was not in a good format , it required a lot of cleaning removing null values, strip off the long strings
clean up refrences,converting into date-time, converting various data into int datatype like 'run time of movie' and etc
please do check out the code : 
it's very easy to read and understand............
