# Web Scraping with Selenium and undetected-chromedriver

## Overview

This project demonstrates how to scrape web data (such as titles and author names) from PubMed or similar sites using Selenium and undetected-chromedriver. The script collects article titles and author names, navigating through multiple pages, and saves the extracted data into a CSV file.

By using undetected-chromedriver, the script bypasses anti-bot mechanisms that might prevent scraping through traditional methods.

## Features

Automated browser interaction using Selenium
Bypasses website bot detection with undetected-chromedriver
* Scrapes article titles and authors from PubMed
* Stores the scraped data in a CSV file for later use
* Supports pagination for scraping across multiple pages

## Requirements

Make sure you have the following before running the project:

* Python 3.x
* Google Chrome browser (Ensure that Chrome is installed and up-to-date. The version should match the ChromeDriver version)
* ChromeDriver (The driver to control the Chrome browser)
* Required Python libraries listed in requirements.txt

## Setting Up ChromeDriver

* Download ChromeDriver from [here][https://developer.chrome.com/docs/chromedriver/downloads]. Choose the version that matches your installed Chrome browser version.
* Once downloaded, either:
*- Add ChromeDriver to your system’s PATH, or
*- Provide its path in the script
