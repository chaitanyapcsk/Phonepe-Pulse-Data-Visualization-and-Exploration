# Phonepe Pulse Data Visualization and Exploration
This is a Python code that creates a real-time phonepaydata visualization and exploration dashboard using Streamlit, Pandas, Numpy, and Plotly Express.

The code first imports the necessary libraries, including Streamlit, Pandas, Numpy, Plotly Express, and time.

It then loads a CSV file from a GitHub repository into a Pandas dataframe. The CSV file contains data related to PhonePe transactions, including the job title of the person performing the transaction, their age, marital status, and account balance.

The user can select a specific job title from a dropdown menu, which filters the dataframe to only show transactions performed by people with that job title.

The code then enters a loop that runs for 200 iterations. In each iteration, the code creates new columns in the dataframe that contain modified versions of the age and balance columns. The modified values are generated by multiplying the original values by a random number between 1 and 4.

The code also calculates three key performance indicators (KPIs) based on the modified data. These KPIs are the average age, the count of married people, and the average account balance. The values of these KPIs are updated in real-time.

The dashboard displays the updated KPIs in three metric cards using the metric() function from Streamlit. It also displays two charts using Plotly Express - a density heatmap and a histogram - that show the distribution of age and marital status in the filtered dataframe. Additionally, the dashboard displays a detailed data view of the filtered dataframe using the dataframe() function from Streamlit.

Finally, the time.sleep(1) statement introduces a delay of 1 second between iterations of the loop, which gives the dashboard time to update and refresh.

The result of this project will be a live geo visualization dashboard that displays information and insights from the Phonepe pulse Github repository in an interactive and visually appealing manner.

The dashboard will have at least 10 different dropdown options for users to select different facts and figures to display. 
The data will be stored in a MySQL database for efficient retrieval and the dashboard will be dynamically updated to reflect the latest data.

Users will be able to access the dashboard from a web browser and easily navigate the different visualizations and facts and figures displayed. The dashboard will
provide valuable insights and information about the data in the Phonepe pulse Github repository, making it a valuable tool for data analysis and decision-making.

Overall, the result of this project will be a comprehensive and user-friendly solution for extracting, transforming, and visualizing data from the Phonepe pulse Github repository.
