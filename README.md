# Weather-APP-Python
My first weather application created using python
**COMPANY** : CODETECH IT SOLUTIONS
**NAME** : KISHORE JOHN
**DOMAIN** : PYTHON PROGRAMMING
**BATCH DURATION** : JANUARY 5th, 2025 to FEBRUARY 5th, 2025
**MENTOR NAME** : NEELA SANTHOSH KUMAR
# DESCRIPTION OF THE TASK : 
This Weather Application project is corely powered by **openweathermap API**. But the problem with this particular API is that , it was not able to directly take city names as an input. Though this feauture exists for US cities it is not available for Indian cities. But openweather API provides an option where we can give **latitude and longitude** as its input to get the weather details at that location. Considerig this option I have also used a **Geocoding API** which returns the latitude and longitude of the city given as an input whose extracted **JSON Results** are further given as an input to **openweathermap API**. Finally the results of openweather API which is in **JSON format** are extracted and visualized in terms of grap plotting using **matplotlib**.But in ordr to plot the data in terms of matplotlib , I found out that it require an array of weather data as well as the timings . To solve it I have used a set of modules such as **datetime** and **numpy** to handle the numerical plotting of the matplotlib. Also after using the **datetime** module I found that, it is functioning based on US standard time. In order to convert it into **IST** , I have used the module , **timezone** from **pytz**. You can clearly see the implementation in my code which I have attached to the repository.
# OUTPUT OF THE TASK : 
![Image](https://github.com/user-attachments/assets/761fe7e3-8dfb-44e2-8d58-8c66b543c121)
![Image](https://github.com/user-attachments/assets/53269e71-f482-44ee-9452-3e8f1c94ae8d)
![Image](https://github.com/user-attachments/assets/afbb2f5c-53d1-4da7-b904-70a9d2dfb326)
