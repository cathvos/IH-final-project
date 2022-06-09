# Ironhack Final Project - 
by [Roger Serret](https://github.com/rogerserret) & [Cath Vos](https://github.com/cathvos), June 2022
<br/><br/>

## Cocktail/Mocktail flavor trends

![Classification Case Study](https://github.com/cathvos/IH-final-project/blob/main/Presentation/image%20readme.jpeg?raw=true)

## Project Brief
**Scenario:**

Bacardi, the company:
- Sell +200 brands
- Present in +150 countries worldwide
- Main product categories: sparkling wine, rum, vodka, gin, vermouth, cognac, whisky, bourbon, tequila, cachaça, liqueurs
- Sustainability as a key branding element:
  - Positive environmental impact (environmental-friendly production)
  - Reduce alcohol-related harm (low/non-alcohol drinks) 
  - Be inclusive (none-sexist ads)
  - Responsible sourcing partnerships (“local” partners)

Bacardi had several project requests:
- Forecast sales (KPI: Volume, 3 next years, detail expected accuracy)
- Suggest next spirit hit (By Country, Age Range, Wealth Range…)
- Suggest next preferred flavor for customers (By Country, Age Range, Wealth Range…)

They provided us with 3 internal data sets to use and we were free to use whatever external data source we wanted. When using external data sources,  they asked us to explain:
- Which External data you have used (in the model)
- Explain Why you selected that data
- Explain How you mixed it

We decided to focus on the flavor and next spirit hit part of their request and connect it to one of bacardi´s sustainability goals: Reduce alcohol-related harm (low/non-alcohol drinks). As this was our focus, we did not use any of Barcadi´s provided data, but created our own data set that met our needs.

**Problem:**

Can we suggest the next preferred flavor for low/non alcohol drinks?<br/><br/>

**Challenge:**

Create a data set of minimal 1000 cocktail recipes with a timestamp to find out what are the preferred flavors across seasons and years.


## Data

Leveraging on cocktail recipe [data](https://github.com/cathvos/IH-final-project/tree/main/Data) we scraped from the web, retrieved through API´s from social media (Instagram and Pinterest) and found on Kaggle, we put together a Data frame in Python with almost 2000 recipes. The original Data frame was very simple and only contained 3 columns, Date, Ingredients, and Source Tag. The Ingredients column contains the full recipe(post) text, so we created a function in Python to extract the information on the ingredients mentioned in each of the recipe (post) texts. Our approach here was to create a function that would search through the text and create a Boolean value if the ingredient on our list was found in the text or not. This resulted in a huge Data frame of 72 columns. Once the Data frame was complete, we used Tableau's data visualisation tools to analyse the data. <br/> <br/>

## Process & Tools

**Process**

- **Github:** set up our Github repo to collaborate on.<br/>
- **Trello:** set up our Trello board to help us plan.<br/>
- **Python:** web scraping, process API retrieved data, EDA, assessment of dataframe, data cleaning and wrangling<br/>
- **Tableau:** data analysis, creating visualizations<br/>

**Deliverables**

 - **Data:** csv´s created with Python - [Link to Data folder](https://github.com/cathvos/IH-final-project/tree/main/Data)
 - **Notebooks:** Jupyter Notebook - [Link to Notebooks folder](https://github.com/cathvos/IH-final-project/tree/main/Notebooks)

**Visualizations**

 - **Plots & Charts:** Tabeau worksheet - [Link to Tableau](https://public.tableau.com/app/profile/roger.serret.aracil/viz/Final_project-Ironhack/TOPHerbsComplementstrendline)
 - **Presentation:** PowerPoint - [Link to Presentation folder](https://github.com/cathvos/IH-final-project/tree/main/Presentation)<br/>


## Key Take Aways

### 1.  

**Thank you for reading!** <br/>
If you have any questions, please reach out to us.<br/><br/>
Roger Serret & Cath Vos
