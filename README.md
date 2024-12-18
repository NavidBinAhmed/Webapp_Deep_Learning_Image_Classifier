# CNN-based deep learning image classifier AI webapp
The **Deep Learning Image Classifier AI Webapp** is a web application that uses a deep learning model to classify images into various categories. This project leverages a ResNet50 neural network, pre-trained on the ImageNet dataset, to accurately identify and classify images. The system recognises the object in an image uploaded by the user.

![Illustration](https://path_to_illustration_image) <!-- Replace with an illustration related to your project -->


![Project Logo](https://path_to_your_logo_image) <!-- to be replaced with the actual path to the project logo -->

copyright @navidbinahmed 2023

## Table of Contents
- [Project Overview](#project-overview)
- [Tools and Tech Used](#tools-and-tech-used)
- [Features](#features)
- [Steps for Implementation](#steps-for-implementation)
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)
- [How to Contribute](#How-to-contribute)
- [License](#license)
- [Contact](#contact)


## Tools and Tech Used

### Key Tools
[![](https://skillicons.dev/icons?i=python,pytorch,docker&theme=dark)](https://skillicons.dev)
1. Jupyter Notebook & Anaconda
2. VS Code
3. Docker/WSL 2
4. GitHub/Git CLI
5. Python v3.9
6. Flask
7. HTML/CSS

### Key Technologies
- **TensorFlow**: For deep learning model creation and training.
- **Keras**: High-level neural networks API.


## Features
- **Image Upload**: Users can upload images for classification.
- **Real-time Predictions**: Get instant predictions on uploaded images.
- **Visual Feedback**: Display of the classified category along with confidence scores.
- **User-Friendly Interface**: Simple and intuitive UI.

## Steps for Implementation
1. Created a new conda environment (imageclassifier)
2. Downloaded dataset
3. Model Building
    i.   Preprocessing data
    ii.  EDA/ feature engineering
    iii. Model building
    iv.  Saved model as a .h5 file
4. Customized app building using Flask
5. Install Docker Desktop with supporting tools (WSL 2)
6. Pushed the repo to Git CLI (and Docker)
    i. Configuaration commands:
   
       ```
       git config --global user.name (Navid Bin Ahmed)
       ```
       ```
       git config --global user.email (******)
       ```
   
    ii. used commands:
   
         ```
         git add <file name>
         
         git add . (adds all files)
         ```
         ```
         git commit -m "message"
         ```
         ```
         git push origin <branch name> master or main
         ```
         ```
         git status
         ```

## Installation
To get a local copy up and running, follow these simple steps.

### Prerequisites
- Python 3.x
- Virtual environment (recommended)

### Installation Steps
1. **Clone the Repository**
    ```bash
    git clone https://github.com/NavidBinAhmed/Webapp_Deep_Learning_Image_Classifier.git
    cd Webapp_Deep_Learning_Image_Classifier
    ```

2. **Create and Activate a Virtual Environment**
    ```bash
    python -m venv venv
    source venv/bin/activate # On Windows use `venv\Scripts\activate`
    ```

3. **Install Required Packages**
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Application**
    ```bash
    python app.py
    ```

## Usage
1. Navigate to `http://127.0.0.1:5000/` in your web browser.
2. Upload an image using the provided interface.
3. Click the "Predict" button to get the classification result.
4. The application will display the predicted category along with the confidence score.

## Demo 
### Link
Check out the live demo of the application [here](http://your-demo-url.com). <!-- Replace with the actual URL of your live demo -->

### Expected Output
1. image 1
    ![image](https://user-images.githubusercontent.com/45857107/208315378-f96cb20c-5026-4c5b-aaa6-a3c7c5731b0b.png)
    
2. Image 2
    ![image](https://user-images.githubusercontent.com/45857107/208315404-2d1ec7d8-4e16-4430-83dc-979749970527.png)

   Application in action (to be updated):
   
![Demo GIF](https://path_to_demo_gif) <!-- Replace with a GIF showing the application in action -->

## How to Contribute
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
- **Email**: navid_bin_ahmed@yahoo.com
