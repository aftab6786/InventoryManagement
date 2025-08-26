# Weather Dashboard

A beautiful, responsive weather application that displays current weather conditions and a 5-day forecast for cities worldwide.

## Features

- **Current Weather Display**: Shows temperature, weather conditions, and feels-like temperature
- **Detailed Weather Information**: Humidity, wind speed, pressure, visibility, and UV index
- **5-Day Forecast**: Extended weather outlook with high/low temperatures and conditions
- **Responsive Design**: Optimized for desktop and mobile devices
- **Search Functionality**: Easy city search with Enter key support
- **Modern UI**: Glassmorphism design with smooth animations and hover effects
- **Real-time Date**: Automatically updates current date and time

## Screenshots

The dashboard features a clean, modern interface with:
- Gradient blue background
- Glassmorphic weather cards
- Interactive forecast items with hover animations
- Responsive grid layout

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Advanced styling with gradients, backdrop filters, and animations
- **JavaScript**: Interactive functionality and data handling
- **Responsive Design**: CSS Grid and Flexbox for optimal viewing on all devices

## Installation

1. Download the `index.html` file
2. Open it in any modern web browser
3. No additional setup or dependencies required!

## Usage

1. **Default View**: The dashboard loads with New York weather data
2. **Search for Cities**: 
   - Enter a city name in the search box
   - Click "Search" button or press Enter
   - View updated weather information
3. **Predefined Cities**: The app includes sample data for:
   - New York
   - London
   - Tokyo
4. **Random Data**: Other cities will display randomized weather data for demonstration

## File Structure

```
weather-dashboard/
└── index.html          # Complete application in a single file
```

## Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Responsive Breakpoints

- **Desktop**: 1200px+ (2-column layout)
- **Tablet**: 768px - 1199px (2-column layout)
- **Mobile**: < 768px (single column layout)

## Sample Data

The application includes pre-configured weather data for demonstration:

### New York
- Temperature: 24°C
- Conditions: Clear sky
- 5-day forecast included

### London  
- Temperature: 18°C
- Conditions: Overcast
- 5-day forecast included

### Tokyo
- Temperature: 28°C
- Conditions: Humid and warm  
- 5-day forecast included

## Customization

### Styling
- Modify CSS variables in the `<style>` section
- Update gradient colors in the `body` selector
- Adjust border radius values for different corner styles

### Weather Data
- Replace the `sampleWeatherData` object with real API data
- Integrate with weather APIs like OpenWeatherMap or WeatherAPI
- Add more cities to the sample data object

### Features to Add
- Geolocation support for automatic location detection
- Temperature unit conversion (Celsius/Fahrenheit)
- Weather maps integration
- Historical weather data
- Weather alerts and notifications

## API Integration

To connect with a real weather API:

1. Sign up for a weather service (e.g., OpenWeatherMap)
2. Replace the `searchWeather()` function to make API calls
3. Update the data structure to match API responses
4. Add error handling for network requests

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test responsiveness and functionality
5. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

## Future Enhancements

- [ ] Real weather API integration
- [ ] Geolocation support
- [ ] Unit conversion toggle
- [ ] Weather maps
- [ ] Offline caching
- [ ] Push notifications
- [ ] Multiple city comparison
- [ ] Weather charts and graphs

## Support

For questions or issues, please open an issue in the repository or contact the development team.

---

**Note**: This is a demonstration application using sample weather data. For production use, integrate with a real weather API service.
