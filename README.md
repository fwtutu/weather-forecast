# 天氣預報應用程式

這是一個使用 Python 和 Flask 構建的簡單天氣預報應用程式。它使用 OpenWeatherMap API 來獲取並顯示指定城市的天氣數據。

## 功能

- 獲取任何城市的當前天氣信息
- 顯示溫度、天氣描述、濕度和風速

## 系統需求

- Python 3.x
- Flask
- requests

## 安裝

1. 下載該專案：

    ```bash
    git clone https://github.com/yourusername/weather_forecast.git
    cd weather_forecast
    ```

2. 安裝所需的依賴項：

    ```bash
    pip install -r requirements.txt
    ```


## 使用方法


1. 通過註冊 [OpenWeatherMap](https://openweathermap.org/) 來獲取你的 OpenWeatherMap API 金鑰。

2. 修改config.test為config文件， 將 `YOUR_API_KEY` 替換為你的 API 金鑰。

3. 運行 Flask 應用程式：

    ```bash
    python app.py
    ```

4. 打開你的瀏覽器，並前往 `http://127.0.0.1:5000/`。

5. 輸入一個城市的名稱，然後點擊 "Get Weather" 按鈕，即可查看該城市的當前天氣信息。


![WeatherForecast](https://github.com/fwtutu/line-notify/assets/171393477/310b190f-ce01-4c24-b962-d983644ac752)
