This is a weather app built using the Django framework in Python. The app displays the current weather conditions and temperature of a user-specified city. 

## Installation

1. Clone the repository to your local machine.
2. Install the required packages by running the following command in your terminal:

   ```
   pip install -r requirements.txt
   ```

3. Set up a free account at [OpenWeatherMap](https://openweathermap.org/) to obtain an API key.
4. In the `weatherapp` directory, create a file named `secrets.py`.
5. In `secrets.py`, add the following line of code with your OpenWeatherMap API key:

   ```
   API_KEY = 'your_api_key_here'
   ```

   Save the file.
6. Run the app by running the following command in your terminal:

   ```
   python manage.py runserver
   ```

7. Navigate to `localhost:8000` in your web browser to use the app.

## Usage

1. Enter a city name in the search bar and click the 'Get Weather' button.
2. The app will display the current weather conditions and temperature of the specified city.
3. To search for a different city, simply enter a new city name and click the 'Get Weather' button again.

## Credits

This app was built using the Django web framework in Python. The app also uses the [OpenWeatherMap API](https://openweathermap.org/) to obtain weather data for user-specified cities. 

## License

This project is licensed under the terms of the MIT license. and basic html.
