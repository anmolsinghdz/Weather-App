# Weather App

A **Weather App** that provides real-time weather updates for any city, built with **Spring Boot** for the backend and **Thymeleaf** for the frontend. This app utilizes a third-party API to fetch weather data and displays it in a clean, user-friendly interface.

## Features

- 🌦 **Real-time Weather Updates**: Get current weather details like temperature, humidity, wind speed, and weather conditions for any city.
- 🔎 **Dynamic City Search**: Search for weather updates by entering the city name.
- 🖥 **Clean UI**: Displays weather data in an easy-to-read format using Thymeleaf templates.

## Technologies Used

### Backend: Spring Boot
- **RESTful APIs**: Built using Spring Boot to retrieve weather data from a third-party weather API.
- **Spring MVC**: Manages HTTP requests and responses efficiently.
- **Exception Handling**: Handles errors like invalid city inputs gracefully.
- **Caching**: Optimizes frequent requests and reduces API calls.

### Frontend: Thymeleaf
- **Server-Side Rendering**: Thymeleaf templates dynamically render weather data from the backend.
- **HTML & CSS Integration**: Provides a responsive and visually appealing interface.
- **User-Friendly Forms**: Input city names to fetch weather updates dynamically.

### Other Tools
- **Weather API**: Fetches real-time weather data from a trusted third-party provider.
- **Maven**: Manages project dependencies and build lifecycle.
- **H2 Database**: (Optional) Used for testing or persisting user preferences.

## How to Run the Project

### Prerequisites
1. **Backend**:
   - Java 17 or higher
   - Maven
2. **Frontend**:
   - Embedded with Spring Boot (No additional setup required)

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/anmolsinghdz/Weather-App.git
   cd Weather-App
2. Build and run the Spring Boot application:

   ```bash
   mvn spring-boot:run
Open your browser and navigate to http://localhost:8080 to use the Weather App.

### Endpoints
/ - Home page where users can search for weather updates.
/weather - Displays weather details for the queried city.
/error - Error page for invalid city input or API issues.

### Future Improvements
🌐 Multi-Language Support: Provide weather updates in various languages.
📊 Weather Trends Visualization: Add charts to show weather patterns over time.
📍 Location-based Weather: Automatically fetch weather data based on user location.

### Weather Results
Displays real-time weather details like temperature, humidity, and wind speed.

### Contributing
Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request for review.


### License
This project is licensed under the MIT License.

Enjoy using the Weather App! 🌤 Let me know if you need further assistance.
