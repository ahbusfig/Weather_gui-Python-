# **Weather Application using CustomTkinter**

## **Description**
This Python application provides a modern and interactive graphical user interface (GUI) built with **CustomTkinter**. It allows users to retrieve real-time weather information by entering a city name. The app integrates with the OpenWeatherMap API to display:

- Temperature
- Weather description
- Humidity
- Wind speed

The app uses a `.env` file to securely manage the OpenWeatherMap API key.

## **Features**
- Clean and responsive GUI design using CustomTkinter.
- Real-time weather data retrieval via OpenWeatherMap API.
- Secure storage of the API key using a `.env` file.
- Error handling for invalid city names or connection issues.
- Cross-platform compatibility (Windows, macOS, Linux).

## **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file in the project root and add your OpenWeatherMap API key:
   ```env
   API_KEY=your_api_key_here
   ```

4. Run the application:
   ```bash
   python app.py
   ```

## **Usage**
1. Launch the application.
2. Enter the name of a city and click the **Search** button to retrieve weather data.

## **Project Structure**
- `app.py`: Main application file containing the GUI and weather logic.
- `.env`: File for securely storing environment variables (e.g., API key).
- `requirements.txt`: List of dependencies for easy installation.

## **License**
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it.

## **Contributing**
Contributions are welcome! Feel free to open issues or submit pull requests to enhance the application.

## **Acknowledgments**
- [CustomTkinter](https://github.com/TomSchimansky/CustomTkinter) for the modern GUI design.
- [OpenWeatherMap](https://openweathermap.org/) for providing weather data.
- [python-dotenv](https://github.com/theskumar/python-dotenv) for managing environment variables.

