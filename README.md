# FreeNiagaraOpenWeatherData 🆓

[![Niagara 4.14+](https://img.shields.io/badge/Niagara-4.14%2B-blue)](https://www.tridium.com)
[![Free to use](https://img.shields.io/badge/Free_to_use-brightgreen)](LICENSE)
[![License: MIT](https://img.shields.io/badge/License-MIT-green)](LICENSE)

> **🆓 Free weather data for your Niagara Station — pull live forecasts and current conditions from Open-Meteo.**

---

## What Is It?

A free Niagara 4 module that fetches real-time weather data from [Open-Meteo](https://open-meteo.com/) (a free, no-API-key-required weather service) and writes it directly into Niagara points.

### Data Available

- Current temperature, humidity, wind speed
- Weather condition code (sunny, cloudy, rain, etc.)
- 7-day forecast data
- Configurable city/location

---

## Quick Start

```bash
# 1. Install gline.pem certificate (or skip if other gline modules already installed)

# 2. Add glineCurlWeather-rt.jar to your modules/ directory

# 3. Restart station

# 4. Configure your city coordinates (latitude/longitude)

# 5. Enable → weather data flows into your station points
```

The module uses the `gline`-prefix certificate. If you've already installed other gline jar packages, re-importing the certificate is not necessary.

---

## Features

| Feature | Support |
|---------|:-------:|
| Free to use | ✅ |
| No API key required | ✅ Open-Meteo API |
| Current conditions | ✅ Temperature, humidity, wind |
| 7-day forecast | ✅ |
| Configurable location | ✅ Any lat/lon |

---

## Pricing

**🆓 Free** — no license, no API key, no hidden costs.

---

## Commercial Contact

Need weather data from a different source? Custom data feeds? We build it.

- **Email**: [jason.zhang@gline-net.com](mailto:jason.zhang@gline-net.com)
- **WhatsApp**: [+86 138 0199 0968](https://wa.me/8613801909968)

**Shanghai Gline Net Co., Ltd.** — Your Partner in Smarter Automation
Already tested in Niagara 4.14, the gline certificate needs to be imported; provided that other gline-prefixed jar packages have been successfully installed, re-importing the certificate is unnecessary. Usage instructions are as follows:
<img width="1185" height="453" alt="image" src="https://github.com/user-attachments/assets/66f76d7a-c655-4be1-a4c6-84e7c6658f72" />
City examples are as follows:
Shanghai
https://api.open-meteo.com/v1/forecast?latitude=31.23&longitude=121.47&current=temperature_2m,relative_humidity_2m,weather_code&daily=weather_code,temperature_2m_max,temperature_2m_min&timezone=Asia%2FShanghai
NewYork
https://api.open-meteo.com/v1/forecast?latitude=40.71&longitude=-74.01&current=temperature_2m,relative_humidity_2m,weather_code&daily=weather_code,temperature_2m_max,temperature_2m_min&timezone=America%2FNew_York
TempC is Celsius and TempF is Fahrenheit.
User trigger to excute the curl command to the URL. 
Here is another sample:
Singapore 
https://api.open-meteo.com/v1/forecast?latitude=1.29&longitude=103.85&current=temperature_2m,relative_humidity_2m,weather_code&daily=weather_code,temperature_2m_max,temperature_2m_min&timezone=Asia%2FSingapore
<img width="1284" height="375" alt="image" src="https://github.com/user-attachments/assets/7061154d-596c-4f84-b74a-df3f4d4cd03a" />

Should you need to develop more weather functions, such as UV light, IAQ, or weather forecast, just let me know. 
jason.zhang@gline-net.com
