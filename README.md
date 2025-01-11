# Recycling Awareness Project

## Project Overview
This project focuses on promoting recycling awareness and sustainability. The website consists of several key features:
- A visually appealing homepage with an animation of Earth to engage users.
- Sections to highlight the process of recycling: Reduce, Reuse, and Recycle.
- A "News" section that displays the latest news related to recycling efforts.
- A "Detect Trash" feature (planned or implemented) for identifying types of trash for appropriate recycling.
- A "Product Page" showcasing eco-friendly products or related services.

## Features

- **Trash Detection:** Uses TensorFlow.js and the COCO-SSD model to identify recyclable materials.
- **Latest News Section:** Displays curated articles related to sustainability and recycling.
- **User-Friendly Interface:** Built with React for a seamless user experience.
- **Camera Integration:** Employs React Webcam for real-time object detection.
- **Authentication:** Secure user management with React Token Auth.
  
### Homepage
- Animated Earth as the centerpiece.
- Navigation bar with links to various sections (e.g., Home, News, Detect Trash, Product Page).

### Our Process Section
- **Reduce:** Emphasizes reducing waste through sustainable practices and reusable products.
- **Reuse:** Encourages reusing items via donation and upcycling initiatives.
- **Recycle:** Advocates proper recycling by partnering with local recycling facilities.

### News Section
- Latest news articles about recycling, sustainability, and global efforts.
- Positive and constructive narratives around environmental concerns.
- "Read More" button to access full articles.

### Additional Sections (Planned/Implemented)
- **Detect Trash:** A feature to detect trash types and recommend recycling or disposal methods.
- **Product Page:** A catalog of eco-friendly products or services that support recycling goals.

## Tools and Technologies

### Frontend
- **React**: Core library for building the user interface.
- **React Router DOM**: Navigation and routing for single-page applications.
- **React Spinners**: Provides visually appealing loading indicators.
- **React Webcam**: Captures real-time video for trash detection.

### Backend
- **Flask**: Lightweight Python web framework for API and backend services.
- **Proxy**: Configured at `http://127.0.0.1:5000` to connect React with Flask.

### Machine Learning
- **@tensorflow/tfjs**: TensorFlow.js library for running ML models in the browser.
- **@tensorflow-models/coco-ssd**: Pre-trained COCO-SSD model for object detection.


## Installation and Setup
1. Clone this repository.
   ```bash
   git clone [repository-url]
   ```
2. Navigate to the project directory.
   ```bash
   cd recycling-awareness
   ```
3. Install dependencies.
   ```bash
   npm install
   ```
4. Run the project locally.
   ```bash
   npm start
   ```
5. Open `http://localhost:3000` in your browser to view the application.
   
## Screenshots

### Homepage
![Homepage with Earth Animation](/homepage.png)

### Our Process Section
![Our Process: Reduce, Reuse, Recycle](/ourprocess.png)

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch.
   ```bash
   git checkout -b feature-name
   ```
3. Make changes and commit them.
   ```bash
   git commit -m "Add your message here"
   ```
4. Push your changes.
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.
