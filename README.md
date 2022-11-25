# Analyze electricity data with C
A program to analyze data of electricity production in C, developed for the course LES10A110 Principles of C-programming of LUT University, Finland.
The program reads a CSV file containing data related to electricity, creates a linked list of the data rows and analyzes the data. The analysis consists of 2 parts:<br>
1. Consumption:<br>
- The total number of measurements per year
- Total consumption of electricity in a year
- Average consumption per hour
- At which hour of the year there was the biggest consumption
- At which hour of the year there wast he least consumption.<br>
The program prints the results on the screen and writes them to a text file named "consumption.txt".<br>
2. Production:<br>
The production of different types of energy is summarized per type and per week. The output is written in a CSV-file named "production.csv".
## Result
consumption.txt
```
Statistics on 8784 measurements:
Consumption totaled 80884331022 kWh, and averaged 9208143.3 kWh.
The highest consumption, 12718885 kWh, occurred on 28.2.2020 8:00.
The lowest consumption, 5620157 kWh, occurred on 20.6.2020 3:00.
```
production.csv
```
Week;Solar power;Wind power;Hydropower;Nuclear power;CHP;Thermal power
Week 1;0.14;198.64;175.81;335.94;341.69;26.07
Week 2;0.22;254.74;277.71;470.43;493.51;38.20
Week 3;0.21;186.10;315.66;470.48;481.33;39.53
Week 4;0.49;227.21;303.99;469.71;474.66;38.49
Week 5;0.30;171.70;286.53;470.37;366.38;32.93
...
```

