
Algorithm 
Start the program.
Step 2: Declare three two-dimensional arra
aqi[5][7] – stores Air Quality Index.
Step 3: Initialize dataReady = 0.
Step 4: Display the menu with seven options:
Input / Update Data
Display Data
Zone-wise Averages
Detect Risk Days
Green Index and Ranking
Recommendations
Exit
Step 5: Read the user's choice.
Step 6: If the user selects Input Data:
Read temperature, humidity and AQI for five zones over seven days.
Validate each reading.
Re-enter invalid values.
Set dataReady = 1.
Step 7: If the user selects Display Data, display all three matrices.
Step 8: If the user selects Zone-wise Averages, calculate and display the average temperature, humidity and AQI for each zone.
Step 9: If the user selects Detect Risk Days:
Check AQI greater than 150.
Check temperature greater than 35°C.
Check humidity greater than 80%.
Count each risky day only once.
Display the risky day numbers.
Step 10: If the user selects Green Index and Ranking:
Calculate AQI Score.
Calculate Temperature Score.
Calculate Humidity Score.
Calculate Green Index.
Rank all five zones from highest to lowest.
Display equal ranks for tied scores.
Step 11: If the user selects Recommendations, display suitable environmental improvements for each zone.
Step 12: If the user selects Exit, terminate the program.
Step 13: Stop.