                         COVID-19 VACCINATION ANALYIS  

PROBLEM STATEMENT : 

This project aims to comprehensively analyze Covid-19 vaccine data, specifically concentrating on vaccine effectiveness, distribution patterns, and adverse reactions. The primary objective is to generate actionable insights to assist policymakers and healthcare entities in enhancing their vaccination deployment strategies.
 
CONTRIBUTERS:

1.DINESH BABU P K

2.MOHAMED ARSATH T

3.JEYAKMUAR N K

4.YASHWANTH  J A

5.PRITHIVIRAJ  S D

INTRODUCTION:

This project involves the analysis of COVID-19 vaccination data using Python and various data analysis libraries. The analysis is performed on two datasets: one containing information about vaccine manufacturers, and the other containing country-level vaccination data.
              
Data Sources
The project utilizes two primary data sources:
- [country_vaccinations_by_manufacturer.csv](data/country_vaccinations_by_manufacturer.csv): Data on vaccine manufacturers.
- [country_vaccinations.csv](data/country_vaccinations.csv): Country-level vaccination data.




Columns in `country_vaccinations.csv :

- `location`: The location or country where vaccinations are recorded.
- `date`: The date on which vaccination data was reported.
- `vaccine`: The type of vaccine administered.
- `total_vaccinations`: The total number of vaccinations administered on the specified date.

 Requirements

To run the analysis script, ensure that you have the following Python libraries installed:
- NumPy
- Pandas
- Seaborn
- Matplotlib
- Plotly
- Plotly Express

Running the Code in Google Colab

To run the code in Google Colab, follow these steps:

1. Open Google Colab in your web browser.
2. Click on "File" > "New Notebook" to create a new Colab notebook.
3. Copy and paste the code from `vaccine_data_analysis.py` into the Colab notebook.
4. Upload the dataset files `country_vaccinations_by_manufacturer.csv` and `country_vaccinations.csv` to your Google Drive.
5. Mount your Google Drive in the Colab notebook using the following code:

```python
from google.colab import drive
drive.mount('/content/drive')



Analysed: 
. Visualization of Data
![image](https://github.com/prithivirajSD/Naanmuthalvanproject/assets/118063853/b5948549-0897-4ed8-8118-1a0730a050a4)

Top countries in vaccinations Utilization
![image](https://github.com/prithivirajSD/Naanmuthalvanproject/assets/118063853/3f0b69b0-31a1-4518-9e70-3452a3c7ec82)


Fully Vaccinated Count
![image](https://github.com/prithivirajSD/Naanmuthalvanproject/assets/118063853/cd927c79-abf9-4ef1-8892-b32bdac3cc37)


Most commonly used vaccines in the World
![image](https://github.com/prithivirajSD/Naanmuthalvanproject/assets/118063853/45dc8c8e-5e19-4704-b31a-1a802bd5223c)


Daily vaccinations per million top countries
![image](https://github.com/prithivirajSD/Naanmuthalvanproject/assets/118063853/df0698df-2f26-400e-9ec7-be0324194c97)


Country wise daily vaccination per million
![image](https://github.com/prithivirajSD/Naanmuthalvanproject/assets/118063853/d8fcb4b1-0a99-4e59-a018-2460b448295d)

