# Example 3D Website

This is a creative website showcasing example projects, work history, and a touch of personality. It utilizes Three.js to create a 3D scene with a background, torus, moon, and an avatar. Scrolling the webpage animates the camera position and rotates some elements.

## Running the Project

### Prerequisites

- Node.js installed on your system

### Download and Setup

1. Download the entire project folder containing `index.html`, `main.js`, and `style.css`.
2. Alternatively, you can copy and paste the code for each file into separate files on your computer.

### Commands to Run the Project

```bash
# Clone the repository
git clone https://github.com/your-username/your-repository.git

# Navigate to the project folder
cd your-repository

# Install dependencies
npm install

# Run the project
npx vite

```

### Explanation of Files

- `index.html`: This is the main HTML file that defines the website structure and loads the `main.js` script. It also includes the styles from `style.css`.
- `main.js`: This JavaScript file contains the Three.js code that creates the 3D scene, animations, and handles user interaction (scrolling).
- `style.css`: This CSS file defines the styles for the website's text, layout, and canvas element.

### Additional Notes

- This project uses external resources like textures for the space background, moon, Hamza avatar, and a custom font. Make sure these image files (`space.jpg`, `moon.jpg`, `normal.jpg`, `hamza.png` - rename the avatar image file) are in the same folder as your HTML file.
- You can customize the textures and content of the website to make it your own.
- For further exploration, refer to the Three.js documentation [here](https://threejs.org/) to learn more about creating 3D graphics in the browser.
