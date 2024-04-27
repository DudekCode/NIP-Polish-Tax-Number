# NIP-Polish-Tax-Number

## Project Overview

NIP ("Numer Identyfikacji Podatkowej") is the Polish Taxpayer Identification Number, a unique identifier assigned to businesses and individuals for tax purposes in Poland. 

This web scraping project aims to automate the collection of data about Polish companies from the [http://bnip.pl/](http://bnip.pl/) website.

## Project Details

This repository contains a Python script that utilizes web scraping techniques to retrieve data from the [http://bnip.pl/](http://bnip.pl/) website. The script scrapes information such as company name, tax identification number, link and address. The collected data can be stored in various formats: CSV or Excel.

## Getting Started

To get started with this project, follow these steps:

1. Copy repository
2. Install require libraries:

```bash
pip install pandas requests beautifulsoup4
```

3. Select which page (or pages) you want to scrape.

![image](https://github.com/DudekCode/NIP-Polish-Tax-Number/assets/111693910/a265c8d4-38ae-4200-ab30-49398d911646)


   
5. Write the selected page or pages in the control panel section.
```bash
# Example scrape page 'X':
pages = ['X']
```
6. Run the code


## Output example

Dataframe from page 'X'. 

![image](https://github.com/DudekCode/NIP-Polish-Tax-Number/assets/111693910/e489f3b8-d50f-413f-ab64-fab60d3391c7)
