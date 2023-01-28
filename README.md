<h1 align="center">Web Scraping with Python Workshop</h1>

<p align="center"><b><i>Created by <a href="https://github.com/ajaygandecha">Ajay Gandecha</a> for Carolina Analytics and Data Science on 1/28/2023.</b></i></p>

 
If you have dabbled even a little bit in the world of data science, you have likely heard of the term *web scraping*. **Web scraping** is the process of using automation to obtain vast amounts of data simply from sources publicly available on the internet.

There are three steps required to successfully scrape a website:

1) **Retreiving the data**

    When you enter a URL into your browser and load a website on your computer, the contents of and the structure of the webpage is downloaded to your computer and displayed by your browser. This data is stored in an *HTML* file. To successfully web scrape a webpage, we must get access to this HTML data so that we can further analyze its contents.
 
2) **Parsing the data**

    How that you have access to a website's HTML data, you now have to make sense of this data. Oftentimes, a big part of this step is figuring out which components of the HTML you need -- and which ones you don't. This is often the hardest and most tedious part of web scraping, but this is where the magic really happens.
    
3) **Using the data**

    Congratulations! Now that you have you data, you can now do something cool with it. You can analyze this data, gain new insights and knowledge, even work on your very own data science app with this data as well (with proper attribution, of course!)
    
In this workshop, you will learn the basics of creating your own web scraping script using the `BeautifulSoup` and `requests` package for the Python programming language. You will learn how to perform all three tasks of web scraping - retreiving the raw source HTML from a webpage, parsing that data to gain valuable data and knowledge, and storing that data to develop new insights or work on your very own data science app. We will also discuss how web scraping has been used in technologies and software commonly used today, as well as the potential ethical implications of the practice.

This workshop is meant to be **introductory** and is open to all skill levels. No prior knowledge of web scraping or any of the Python packages mentioned are required.

## Getting Started

Here are some of the things you must do to get started with this workshop:

### Software Prerequisites

- **This workshop uses the Python programming language.** If you do not already have Python installed on your computer, install the latest version for your operating system [here](https://www.python.org/downloads/).

- This workshop will also use JupyterLab to run Jupyter Notebooks (with Python). Learn how to install JupyterLab [here](https://jupyter.org/install).

- This workshop heavily uses the `beautifulsoup4` package for Python. To install this, create a new cell in your JupyterLab Notebook file and type the following command:
    ```bash
    !pip install beautifulsoup4
    ```

    Running that cell in JupyterLab should install this package for you.
    
- This workshop also heavily uses the `requests` package for Python. This package *should* already be installed when you install JupyterLab, but if it isn't, create a new cell in your JupyterLab Notebook file and type the following command:
    ```bash
    !pip install requests
    ```

    Running that cell in JupyterLab should install this package for you.
    
### Clone this Repository

To download the code of this workshop on your device, you need to clone this repository to your computer.

If you are not familiar with how to use GitHub, using **GitHub Desktop** is an easy way to interact with and manage your repositories. Download GitHub Desktop [here](https://desktop.github.com), and feel free to follow [this](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/cloning-a-repository-from-github-to-github-desktop) tutorial to clone this repo to your computer.

## Slideshow Presentation

[This slideshow]() presentation complements the live demonstration of this workshop.
