---
layout: post
title:       Real-time video stream analysis
image:
  path:    /assets/img/stream-a.png
---
Image generated with ChatGPT to give a basic idea of what the project looked like. A user was able to add video streams and observe real-time analytics about the videos.
{:.figcaption}
## Project overview

One of the most interesting projects I've worked on was this real-time video streaming analysis service. This website allowed users to input one or more video stream URLs, such as from <a target="_blank" href="https://www.cameraftp.com/cameraftp/publish/publishedcameras.aspx">IP cameras</a>. Users could then select various computer vision models to analyze the streams in real-time and gather analytics over a long period time.  
It was designed with multiple use cases in mind, including security applications, such as detecting unauthorized entry into restricted areas, or verifying various equipment.  
It was developed by just 3 people using the SCRUM methodology, sometimes with a little help of others.

It involved tasks such as:

- **Planning the whole architecture** to ensure easy scalability (multiple streams, models and users)
- **Integrating various machine learning models** and computer vision algorithms, including object detection, image classification, landmark detection, and image segmentation
- **Synchronizing video frames**
- **Developing the website**
- **Storing information in a database**
- **Creating dashboards to view real-time statistics** from the collected data
- **Containerizing multiple services, creating deployment pipelines, and setting up CI/CD processes**

And also technologies such as **Python**, **Redis**, **ELK stack**, **tensorflow**, **pytorch**, among others.

Overall, I really enjoyed working on this project. From tackling hard technical challenges, such as synchronizing video frames between various machine learning models, to experiencing great teamwork and using cutting-edge technologies, I ended up learning a lot.