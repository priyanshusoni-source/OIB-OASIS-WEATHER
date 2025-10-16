Task 4: Climara – Your Personal Weather App

Climara is a Python-based terminal weather application that provides real-time weather information for any city. It can automatically detect your current location based on your IP if no city is entered. The app displays temperature, humidity, and weather conditions and runs in a continuous loop until the user types “exit.” The application securely hides the API key using environment variables.

How it Works:

When you run Climara, it first displays a welcome message. It then prompts the user to enter a city name. If no city is provided, Weatheria attempts to detect the current location automatically. Using the OpenWeatherMap API, the app fetches the latest weather data for the city and displays the temperature, humidity, and weather condition. The program continues running in a loop, allowing you to check multiple cities, until you type “exit” to quit. The API key is stored in a .env file or system environment variable to keep it secure.

To use Climara:

Clone the repository.
1.Create a .env file in the project root and store your API key as: api_key = (Your API Key)

2.Install the required Python packages: requests and python-dotenv.

3.Run the program and enter a city name or leave blank to use your current location. Type “exit” to quit.
