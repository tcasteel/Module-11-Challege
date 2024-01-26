# Module-11-Challege

Within this code, there are two parts that both do web scraping.

In the first part, it goes over a website that does news for Mars.
It can grab the header and the preview for the articles on the website.
It grabs the information by using BeautifulSoup and following where the information falls within the HTML file.
It can do that by being able to read the entire site's text element portions.

In the second part, the code can scrape a different site with a table for Mars Weather.
As the site is mainly just a table, it grabs all the elements within, from the headers to the data itself.
After grabbing all of the information/data in the table it gets turned into a Pandas DataFrame making it usable for plots.
From converting it over to a Pandas DF the data values are all set to object
After taking a look into the data, it gets converted over the following formats that make each be able to work for plotting them.
Then the amount of months that there are on Mars compared to Earth months.
Then the amount of Martian days that are within the data frame.
Afterwards the average low temperature by month gets calculated and gets plotted in a bar graph.
Then in a similar vein, the average LOW temp by month gets plotted and assembled.
The average pressure is up to bat now for its turn.
Not only does the average per month get calculated but it also gets graphed by Bar Graph.
Last but not least the min temp over time gets graphed in a plot graph to show the min temp over the total days that we have data on.

Then the data gets saved on a CSV.
The browser then gets closed.
