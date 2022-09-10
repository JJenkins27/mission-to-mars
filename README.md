# Mission to Mars

Using Python, Jupyter Notebook, Pandas, Splinter, BeautifulSoup, ChromeDriverManager, Flask, MongoDB and HTML to analyze web scrape several URLs to combine information about Mars.

## Overview of Project

An analysis of information collected through HTML web scraping to find key news and other information about Mars. The information is combined with several sources to create a Mission to Mars webpage.

### Purpose

A junior data scientist, Robin enjoys freelance astronomy work. Her dream is to land a position at NASA and is very interested in the Mission to Mars. However, the information about Mars is spread across many data sources. Robin would like to combine several key sources into one web page. The combined web page would scrape new information or news items about Mars upon the click of a button.

## Results

The completed Flask webpage features the following items:
- The latest Mars news, including the title of the article and a teaser description
- A featured Mars image
- Facts about Mars and a comparison to Earth
- Stylized pictures and names of the 4 hemispheres of Mars 

When the webpage needs to be updated, there is an easy to use button in the header picture titled "Scrape New Data". If there are any updates to any news items, pictures, or facts, the information will be updated in MongoDB and displayed on the webpage.

![full web page](https://user-images.githubusercontent.com/108373151/189461904-52ac9cba-a51c-415f-b498-33ac451cab9f.png)

Consideration has also been made for mobile devices. Below is a sample of the webpage viewed as if the user had a iPhone 12 Pro. 

![sample mobile device](https://user-images.githubusercontent.com/108373151/189461908-ecb3e4b9-6fc7-4a99-b170-2be6434911e0.png)