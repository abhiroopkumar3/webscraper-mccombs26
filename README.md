# Web Scraping Project

[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/) [![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)](https://www.python.org/) [![Selenium](https://img.shields.io/badge/Selenium-Automation-brightgreen?logo=selenium)](https://www.selenium.dev/) [![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  

This branch contains a series of Jupyter Notebooks demonstrating various web scraping techniques using Python, focusing on different challenges encountered in modern web applications. The primary tool used is **Selenium**, which is a powerful library for automating web browsers.

---

## 📑 Table of Contents
- [Project Overview](#project-overview)
- [01 - Basic Web Scraping Demo](#01---basic-web-scraping-demo)
- [02 - Handling 'Load More' Buttons](#02---handling-load-more-buttons)
- [03 - Scraping Infinite Scroll Pages](#03---scraping-infinite-scroll-pages)

---

## 🚀 Project Overview

The notebooks in this repository are designed to teach fundamental and advanced web scraping concepts. The code is written to be executed in a **Google Colab** environment, with pre-configured dependencies for Chrome and ChromeDriver to work with Selenium.

---

## 🕸️ 01 - Basic Web Scraping Demo

This notebook, **01 - WebScraping_Demo.ipynb**, introduces the basics of using Selenium to scrape a static website. It covers the following key concepts:

- **Environment Setup**: Installing Selenium and setting up a headless Chrome browser in a Colab environment.  
- **Element Location**: Using XPath and CSS selectors to find specific elements on a web page.  
- **Data Extraction**: Pulling text content, attributes, and other data from identified elements.  
- **Handling Pagination**: Demonstrates how to navigate through pages with numbered pagination.  

---

## 🔘 02 - Handling 'Load More' Buttons

The **02 - LoadNext_Demo.ipynb** notebook tackles a common web scraping challenge: sites that load more content via a **"Load More"** button. Key activities include:

- **Button Identification**: Locating the "Load More" button using its class or text.  
- **Programmatic Clicking**: Using Selenium to click the button repeatedly to load new content.  
- **Data Collection**: Extracting and appending new data to a list as it becomes available.  
- **Data Structuring**: Creating a Pandas DataFrame from the scraped movie data and saving it to a CSV file.  

---

## 📜 03 - Scraping Infinite Scroll Pages

This notebook, **03 - InfiniteScroll_Demo.ipynb**, addresses the most dynamic of web scraping scenarios: infinite scroll. This technique is often used on social media sites and image galleries. The notebook demonstrates how to:

- **Automated Scrolling**: Programmatically scroll down the page to trigger the loading of new content.  
- **Dynamic Content Handling**: Waiting for new content to load before continuing the scraping process.  
- **Looping Mechanism**: Implementing a loop to continue scrolling and scraping until a condition is met (e.g., reaching the bottom of the page or a specified number of items).  
- **Practical Example**: The notebook uses a **Pinterest page** to showcase how to scrape images from an infinite-scrolling feed.  
