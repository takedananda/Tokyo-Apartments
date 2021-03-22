# Tokyo-Apartments

The aim of this project was to analyze the pricing of apartments in Tokyo. The reason why I chose to do a project on this is because my parents are living in Tokyo, and the insights I gain through this project will be useful for me in case I ever need to find an apartment to rent to go take care of them.

Rather than using a prexisting dataset, I collected the data myself by web scraping. To gather the data, I used the Selenium library on Python to web scrape the data from apartments.gaijinpot.com, which is an apartment listing website catered towards expats. Then, I went through the entire ETL process by cleaning the data using Pandas and then loaded it to a PostgreSQL database.

After the data was been cleaned, I performed exploratory data analysis on Tableau to figure out which types of information explain apartment pricing. Finally, I constructed a dashboard to condense relevant information into one visualization. The dashboard can be found here: https://public.tableau.com/profile/kenji.takeda#!/vizhome/TokyoApartments/TokyoApartmentDataDashboard

