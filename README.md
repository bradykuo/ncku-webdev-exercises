# Web Development Final Assignment Collection

An interactive web application featuring health calculators and mini-games implemented with HTML, JavaScript, and jQuery UI.<br>
<br>
（成大工資系｜網頁程式開發｜期末作業）

## Project Components

### BMI Calculator
- Interactive BMI calculation with projected weight analysis
- Features:
  - Real-time BMI calculation
  - Weight projection table (±5kg)
  - Clickable results for detailed analysis
- Files:
  ```
  Final/
  ├── BMI.html           # BMI calculator implementation
  ```

### Drink Water Calculator
- Water intake recommendation system
- Features:
  - Calculates daily water intake based on height and weight
  - Tracks current water consumption
  - Provides hourly drinking recommendations
- Files:
  ```
  Final/
  ├── DrinkWater.html    # Water intake calculator
  ```

### Finger Exercise Game
- Interactive clicking challenge game
- Features:
  - Customizable click target goals
  - Progress tracking
  - Reward video upon completion
  - Adjustable difficulty settings
- Files:
  ```
  Final/
  ├── FingerExercise.html # Click challenge game
  ```

### Interactive Ball Animation
- Canvas-based physics animation
- Features:
  - Dynamic ball generation
  - Gravity and collision physics
  - Mouse interaction effects
  - Continuous animation
- Files:
  ```
  Final/
  ├── game.html          # Interactive animation
  ```

### Main Interface
- jQuery UI tabbed interface
- Features:
  - Responsive layout
  - Seamless navigation
  - Integrated components
- Files:
  ```
  Final/
  ├── FinalBase.html     # Main application framework
  ```

## Technical Requirements

### Development Environment
- Modern web browser (Chrome/Firefox recommended)
- Local web server for testing
- Text editor for code editing

### Required Libraries
- jQuery 1.10.2
- jQuery UI 1.11.4
- jQuery UI CSS theme (blitzer)

## Implementation Notes

### BMI Calculator
- Dynamic table generation
- Input validation
- Real-time calculations
- Responsive design

### Drink Water Calculator
- Formula: (height + weight) * 10
- Input validation
- Remaining intake calculation
- Clear result presentation

### Finger Exercise Game
- Event listener implementation
- Counter mechanism
- Dynamic content update
- YouTube video integration

### Ball Animation
- Canvas API usage
- Physics calculations
- Mouse tracking
- Dynamic rendering

## Directory Structure
```
Final/
├── BMI.html
├── DrinkWater.html
├── FingerExercise.html
├── FinalBase.html
├── game.html
└── README.md
```

## Features
- Responsive design
- Cross-browser compatibility
- Interactive user interface
- Real-time calculations
- Engaging animations
- Integrated health tools

## Setup Instructions
1. Ensure all files are in the same directory
2. Open FinalBase.html in a modern web browser
3. Navigate through tabs to access different components
4. Each component can also be accessed individually

## Browser Compatibility
- Chrome (recommended)
- Firefox
- Edge
- Safari

## Notes
- Internet connection required for jQuery and UI resources
- YouTube connectivity needed for game reward video
- Local storage not implemented - data resets on page refresh

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is available for academic and educational purposes.
