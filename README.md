**WeatherApp**

WeatherApp is an Android application that retrieves and displays the current weather details based on the user's location.
It fetches the weather data from the OpenWeatherMap API and displays information such as temperature, humidity, weather description, and address.

**Features**

  Fetches current weather details based on user's location. <br>
  Displays weather information including temperature, humidity, and description. <br>
  Shows the user's current address. <br>
  Updates the weather information in real-time. <br>
  Displays the current time. <br>
  Additional features: 
  
      Search History: Keeps track of recently searched cities for easy access to weather information. 
      
      Unit Conversion: Provides options to switch between Celsius and Fahrenheit temperature units. 
      
      Error Handling: Alerts the user with informative messages in case of network errors or invalid city names. 

  ![image](https://github.com/ymnaasik/Weather_App/assets/160098895/b9d592fd-5df9-45ae-b0f4-13ec0ae82414)
  ![image](https://github.com/ymnaasik/Weather_App/assets/160098895/d6c1c1a3-60ce-4c9f-91dc-ac7f3670405b)
  ![image](https://github.com/ymnaasik/Weather_App/assets/160098895/0d79c1ca-1613-4cb7-9730-6ef91622db06)
  ![image](https://github.com/ymnaasik/Weather_App/assets/160098895/cbc10409-fee0-4537-8d20-a10a368bc61f)

  
**Setup Instructions**
**Prerequisites**
  Android Studio installed on your machine.
  An OpenWeatherMap API key. You can get one by signing up at OpenWeatherMap.
  
Steps

  1. Clone the repository:
     
    git clone https://github.com/your-username/WeatherApp.git
    cd WeatherApp
2. Open the project in Android Studio:
   
      Open Android Studio.
      Click on File > Open.
      Navigate to the cloned repository and select the WeatherApp project.

3. Add your OpenWeatherMap API key:

    Open MainActivity.java.
    Replace the placeholder API key with your actual OpenWeatherMap API key
   
      String apiKey = "YOUR_API_KEY"; // Replace "YOUR_API_KEY" with your actual OpenWeatherMap API key

4. Run the app:

    Connect your Android device or start an emulator.
    Click on the Run button in Android Studio.
    The app should start on your device/emulator.
