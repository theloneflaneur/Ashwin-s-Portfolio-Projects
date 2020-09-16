Welcome to Covid - 19 analysis and prediction ! Link to this project on portfolio blog : https://mlwithashwin.wordpress.com/2020/09/16/covid-19-data-analysis-and-prediction-project/

This project uses John Hopkins's daily covid data ( https://github.com/CSSEGISandData/COVID-19 ) . For the purposes of the project, only the data till 12th July.

Data is provided for daily confirmed cases, active cases , recorveries and covid-19 related fatalities for 188 countries. On exploration of the data files, I found that only three
files were of immense importance to the project as other two files were related to USA specifically. 

My objectives were as follows  : 
 1. Explore the data 
 2. Analyse the data to derive insights into covid 19 confirmed cases, active cases, recoveries and fatalities. 
 3. Once the analysis done for the global data, I must write a function that analyzes the same for any specific country mentioned in our data. 
 4. All the visualizations should be easy to understand and convey the very specific objectives I have accomplished. 
 5. Predict the rise in Confirmed cases and recoveries for the global data. 
 
 How I have set out to accomplish these 5 objectives  :
  1. I have explored the data, convereted the date from string to datetime type. 
  2. I used plotly to analyze and present the daily rise in the covid 19 cases , recoveries, active cases and fatalities. 
  3. Plotly was my choice for country level analysis as well as it gives accurate and interactive information to the user. 
  4. Plotly and Matplotlib was my preferred visualization libraries for this project. Simple line plots and pie charts with matplotlib gives a simplified but rich insight into the 
     analysis and interactive graphs help in gaining a lot of information out of a simple graph. 
  5. I used Support vector regression for the predictions. It seemed like an obvious choice since we have a data that is continuous across months and very much dependent on the 
     previous data values. I used a simple matplotlib and plotly graph to project the rise of cases and recoveries. I have done the preedictions till 30th of August 2020. 

Future updates : The project will be updated later. I am currently working on deploying this project using Flask. 
