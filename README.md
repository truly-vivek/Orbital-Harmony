# Orbital Harmony

Orbital Harmony is a simple and visually captivating simulation of the Earth and Moon orbiting the Sun. Built using HTML5 Canvas and JavaScript, this project demonstrates the beauty of celestial mechanics in a responsive and interactive way.

![Orbital Harmony Screenshot](https://repository-images.githubusercontent.com/942161005/cad36074-67e2-4340-a15b-fb3cac3a9f80)  
*(Replace this with an actual screenshot of your project)*

## Live Demo

Check out the live demo of the project here:  
[Orbital Harmony Live Demo](https://orbitalharmony.web.app/)

## Features

- **Responsive Design**: The simulation adjusts to the size of your browser window.
- **Realistic Animation**: Smooth animation of the Earth orbiting the Sun and the Moon orbiting the Earth.
- **Interactive Background**: A starry background adds depth and realism to the simulation.

## How It Works

The project uses HTML5 Canvas to render the Sun, Earth, and Moon. The positions of the Earth and Moon are calculated using trigonometric functions (`Math.cos` and `Math.sin`) to simulate their orbits. The animation is powered by `requestAnimationFrame`, ensuring smooth and efficient rendering.

### Key Components

- **Sun**: A stationary yellow circle at the center of the canvas.
- **Earth**: A blue circle orbiting the Sun.
- **Moon**: A gray circle orbiting the Earth.
- **Stars**: Randomly placed white dots to create a starry background.

## Code Overview

The core logic of the project is in the `<script>` tag of the HTML file. Here's a breakdown:

1. **Canvas Setup**: The canvas is dynamically resized to fit the browser window.
2. **Celestial Bodies**: The Sun, Earth, and Moon are drawn using the `arc` method.
3. **Animation**: The `animate` function updates the positions of the Earth and Moon and redraws the scene for each frame.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/orbital-harmony.git

2. Navigate to the project directory:
   ```bash
   cd orbital-harmony

3. Open the index.html file in your browser:
   ```bash
   open index.html

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**

## Contributing

Contributions are welcome! If you'd like to improve this project, please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeatureName
3. Commit your changes:
   ```bash
   git commit -m 'Add some feature'
4. Push to the branch:
   ```bash
   git push origin feature/YourFeatureName
## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

Enjoy the beauty of celestial motion with Orbital Harmony! 🌍🌕☀️
