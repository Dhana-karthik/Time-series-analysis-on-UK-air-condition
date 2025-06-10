# Time series analysis on UK air condition
## Summary:
Worked on predicting the future wave of air pollution of PM 2.5 from real-world datasets from UK government air pollution datasets. I took a dataset of Birmingham from 2022-2023 of PM 2.5. Plotted the initial graph and after that using **simple exponential smoothing** predicted the pattern for the upcoming year and compared it with the actual values.

## Methodology: 
Time series methods follow the assumption that a forecast is a linear sum of all past observations or delays. Exponential smoothing gives more weight to the most recent observations and reduces exponentially as the distance from the observations rises, with the premise that the future will be similar to the recent past. The word "exponential smoothing" refers to the fact that each demand observation is assigned an exponentially diminishing weight.

=> This technique captures the general pattern and can be expanded to include trends and seasonal variations, allowing for precise time series forecasts using past data.
<br> => This method gives a bit of erroneous long-term forecasts.
<br> => It works well with the technique of smoothing when the parameters of the time series change gradually over time.

# Results:

![Screenshot 2025-06-10 103828](https://github.com/user-attachments/assets/255661fc-5681-4140-b2c5-1da8873a5661)

# Appendix:

![Screenshot 2025-06-10 103921](https://github.com/user-attachments/assets/2c11c812-8546-4535-ab44-3b90f43afdab)
![Screenshot 2025-06-10 103941](https://github.com/user-attachments/assets/31bf33cd-bc80-42ed-aa0d-88f4820002a8)
