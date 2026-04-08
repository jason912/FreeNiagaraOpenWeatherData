# FreeNiagaraOpenWeatherData
Curl open-metro.com to acquire weather data in Niagara station
Already tested in Niagara 4.14, the gline certificate needs to be imported; provided that other gline-prefixed jar packages have been successfully installed, re-importing the certificate is unnecessary. Usage instructions are as follows:
<img width="1185" height="453" alt="image" src="https://github.com/user-attachments/assets/66f76d7a-c655-4be1-a4c6-84e7c6658f72" />
City examples are as follows:
Shanghai
https://api.open-meteo.com/v1/forecast?latitude=31.23&longitude=121.47&current=temperature_2m,relative_humidity_2m,weather_code&daily=weather_code,temperature_2m_max,temperature_2m_min&timezone=Asia%2FShanghai
NewYork
https://api.open-meteo.com/v1/forecast?latitude=40.71&longitude=-74.01&current=temperature_2m,relative_humidity_2m,weather_code&daily=weather_code,temperature_2m_max,temperature_2m_min&timezone=America%2FNew_York
TempC is Celsius and TempF is Fahrenheit.
User trigger to excute the curl command to the URL. 
Should you need to develop more weather functions, such as UV light, IAQ, or weather forecast, just let me know. 
jason.zhang@gline-net.com
