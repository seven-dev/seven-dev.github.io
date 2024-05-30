---
layout: post
title:       Real-time people tracking heatmap for Retail
image:
  path:    /assets/img/retail-heatmap.webp
---
Image generated with ChatGPT to give a basic idea of what the project looked like. It would draw a heatmap in real-time of the places where customers would stop the most inside a certain space.
{:.figcaption}

### Project overview

The objective of this project was to track customer movement and identify high-traffic areas in retail environments, such as supermarkets. It generated a real-time heatmap displaying areas where customers frequently stopped, using color-coded indicators.

### Key features

- **Customer position detection**: Identified and tracked individual customers within the store using an object detection model, which were then converted to coordinates within the space.
- **Real-time heatmap generation**: Displayed high-traffic areas in specific colors, and updated them dynamically to reflect real-time data.

### Development and execution

The project was developed mostly by myself with occasional input from my team. It involved:

- **Analyzing IP camera's footage in real-time**: Captured live video feed from an IP camera placed in a room using OpenCV, ensuring real-time processing.
- **Integrating and fine-tuning an object detection model**: Integrated a TensorFlow object detection model to accurately identify customers and their positions in the room. Gathered and labeled a dataset using camera's footage and fine-tuned the model to enhance its accuracy and reliability.
- **Generating a heatmap**: Utilized OpenCV for image processing tasks, including converting the detected coordinates to a bird's eye view and created a dynamic heatmap by accumulating positional data over time.
- **Containerizing the application**: Packaged the entire application using Docker to ensure consistent and simplified deployment across different environments.

Tecnologies used included **Python**, **C++**, **OpenCV**, **Tensorflow**, **Docker** and others.

### Conclusion

This project was an exciting experience, demonstrating interactive and accurate real-time results. The real-time heatmap provided valuable insights into customer movement and high-traffic areas within the retail space. Through this project, I significantly improved my skills in image and video processing, as well as my understanding of real-time data analysis and application deployment.
