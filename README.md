# Real-Time Body Segmentation Computer Vision

This project is a **Real-Time Body Segmentation** application using **TensorFlow.js** and **BodyPix**. It processes live webcam footage and segments body parts in real-time, visualizing them with colored masks. The project uses **React** for the front-end and **Bootstrap** for styling.


## Features
- **Real-Time Segmentation**: Segments body parts (e.g., arms, legs, torso) in real-time using your webcam.
- **Easy-to-Use UI**: Clean and intuitive UI created with **Bootstrap** and custom styles.
- **Web-Based**: Runs entirely in the browser using **TensorFlow.js**, no need for local installations.

## Table of Contents
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Screenshots](#screenshots)
- [UI/UX Design](#uiux-design)
- [Contributing](#contributing)
- [License](#license)

## Demo

**Live Demo**: [Click here to view the live demo](https://drive.google.com/file/d/1fiF84TYt5BSwg_6VPGitpvrlhG06icxf/view?usp=sharing)

## Installation

To get started with this project, follow the steps below.

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Pahinithi/Real-Time-Body-Segmentation-with-Computer-Vision
   ```

2. **Navigate to the project folder**:
   ```bash
   cd real-time-body-segmentation
   ```

3. **Install the necessary dependencies**:
   ```bash
   yarn install
   ```
   or 
   ```bash
   npm install
   ```

4. **Run the development server**:
   ```bash
   yarn start
   ```
   or
   ```bash
   npm start
   ```

The app will start on `http://localhost:3000` by default.

## Usage

1. **Open the Application**: After starting the app, open it in your browser.
2. **Webcam Access**: Ensure your camera permissions are enabled.
3. **Body Segmentation**: The app will process your live video feed, applying segmentation in real-time.
4. **Results**: Different body parts will be highlighted with colored masks.

## Project Structure

```
real-time-body-segmentation/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── demo-image.png
│   ├── manifest.json
│   └── robots.txt
├── src/
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── ...
├── package.json
└── yarn.lock
```

- **public/**: Contains static assets like `index.html` and images.
- **src/**: Contains the main React components and JavaScript logic for the app.
- **App.js**: The main component which handles the webcam and BodyPix integration.
- **App.css**: Contains custom styles.

## Technologies Used

- **React**: The front-end JavaScript framework for building the UI.
- **TensorFlow.js**: A library for running TensorFlow models in the browser.
- **BodyPix**: The TensorFlow.js model used for body segmentation.
- **Webcam.js**: A package used for capturing video from the user's webcam.
- **Bootstrap 4.5**: For styling and layout.
- **HTML/CSS**: To structure and style the application.

## Screenshots

Here are some screenshots of the real-time body segmentation in action:

<img width="1728" alt="Screenshot 2024-09-15 at 12 31 18" src="https://github.com/user-attachments/assets/46f53e3e-e918-46f6-a90a-53feb5f9d60c"> <br> <br>


<img width="1728" alt="CV04" src="https://github.com/user-attachments/assets/9139fdd7-99b2-4448-ac5f-d95e5b054203">


## UI/UX Design

The user interface was designed with simplicity and clarity in mind. The background is styled using a gradient to create a clean, visually appealing layout. The navigation bar provides easy access to key sections like **Home**, **About**, and **Contact**.

- **Bootstrap Integration**: A responsive navbar with a collapsible menu for mobile screens.
- **Custom Background**: A linear gradient background (`#c3d8f7`, `#f7cdd0`, `#fce8e8`) provides a light and modern feel.
- **Footer**: A simple fixed footer at the bottom of the page displaying the project title and developer information.



## Contributing

Contributions are welcome! Please follow the standard GitHub flow:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push to the branch.
5. Create a new pull request.

## License

This project is licensed under the MIT License. 

## Contact

For any questions or support, please contact:

- **Name**: Pahirathan Nithilan
- **Email**: [nithilan32@gmail.com](mailto:nithilan32@gmail.com)
- **GitHub**: [Pahinithi](https://github.com/Pahinithi)


