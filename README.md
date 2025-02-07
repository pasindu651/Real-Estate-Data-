# Real Estate Data Analyzer + Scraper
A streamlit app built with Python that scrapes real estate data of a given location and graphs the data using a linear regression model. 

## Demo
![](https://github.com/pasindu651/Real-Estate-Data-Analyzer/blob/master/demo_gif_speed.gif
)

## Tools Used
🚩Streamlit was used for the front-end.<br />
🚩Selenium was used to handle dynamic web elements and passed to a Beautiful Soup object.<br />
🚩Beautiful soup was used to scrape listing information from Selenium HTML.<br />
🚩Pandas was used for data analysis and manipulation.<br />
🚩Plotly, in combination with Streamlit was used for graphing and interactive data visualization.<br />
🚩Sklearn was used for linear regression and data testing and training.<br />
<img alt="Diagram of process" width="730" src="https://i.ibb.co/z6TssC2/web-scraping-about.png">

## Prerequisites
```$ pip install requirements.txt```<br>
To run locally:
```$ streamlit run 1_🏘️Home.py```

<figure>
<img src="https://i.ibb.co/WPsPm4R/newplot-2.png" alt="Sample output graph" style="width:730">
  <figcaption align = "center"><b>Scatter plot output for <b>area vs price</b> of <b>land</b> in <b>Toronto, Ontario</b>.</figcaption>
</figure>

<figure>
<img src="https://i.ibb.co/z5pxfQh/newplot.png" alt="Sample output linear regression" style="width:730">
  <figcaption align = "center">Linear regression output for <b>houses</b> in <b>Toronto, Ontario</b>.</figcaption>
</figure>





