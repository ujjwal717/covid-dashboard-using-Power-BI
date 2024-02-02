# covid-dashboard-using-Power-BI
It is a covid-19 dashboard that has various covid related information and is created using Power BI. This dashboard focused on the covid data of Indian citizens.

The dataset has been downloaded from kaggle and I have attached it in this repo as well.
I have also cleaned and pre-processed data a bit as well in Power BI (I used Power BI only as the main focus of the project was to do everything in Power BI).

The Various tiles in the dashboard are :-

1) Card showing total population
2) Card showing total cases
3) Card showing total cured
4) Card showing total deaths
5) Slicer to select different states
6) Pie Chart for states with maximum population
7) Bar chart showing 5 states with maximum death percentage
8) Line chart with different vaccine percentages for dose 1 and dose 2 for different states


**The Dashboard Image is given below :-**

![final screenshot indian covid dashboard](https://github.com/ujjwal717/covid-dashboard-using-Power-BI/assets/93403224/38219317-1dc6-45cd-8557-5f51abc2afa3)



**Explanation of Each Tile :-**

1) **All Cards :-**


   ![cards image](https://github.com/ujjwal717/covid-dashboard-using-Power-BI/assets/93403224/b6e7bf54-ce67-44ee-b2b1-3efacc4669e4)

   **Explanation :-** These are the Cards visuals that basically represent the self explanatory details such as "Total Population", "Total Cases", "Total Cured", "Total Deaths". These Cards 
   support interactive option and we do have slicer in the dashboard and when we change the states from the slicer, then these cards show relevant information of that specific state.

   **Insight :-** The cards convey basic but important information regarding various details that are discussed in the "explanation" part. It gives an easy and efficient way to 
   compare details such as "count of cured patients","count of patients that died", "total population" etc.



2) **States with Maximum Death Percentage :-**


![column chart image](https://github.com/ujjwal717/covid-dashboard-using-Power-BI/assets/93403224/c0dbb407-5a39-4c1d-b4f5-5050ec058c94)


   **Explanation :-** It is the column chart that has states name on the X-Axis and death percentage on the Y-Axis. I used top-n filter to ensure that we have only 5 states to ensure 
     effective data story and readability and usability of dashboard.

   **Insight :-** It shows the top 5 states that had maximum death percentage. It means states where the deaths of patients were most, relative to their population. The data shows states such 
     as "Punjab", "Maharashtra" and "Uttrakhand" etc have high death percentage ranging from 2.46% (maximum in tile) to 1.68% (minimum in tile). 

   




