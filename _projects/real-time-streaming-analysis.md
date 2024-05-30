---
layout: post
title:       Real-time video stream analysis
image:
  path:    /assets/img/real-time-streaming-analysis.png
---
Image generated with ChatGPT to give a basic idea of what the project looked like. A user was able to add video streams and observe real-time analytics about the videos.
{:.figcaption}
### Project overview

One of the most interesting projects I've worked on was this **real-time video streaming analysis service**. This website allowed users to input one or more video stream URLs, such as from <a target="_blank" href="https://www.cameraftp.com/cameraftp/publish/publishedcameras.aspx">IP cameras</a>. Users could then select various computer vision models to analyze the streams in real-time and gather analytics over a long period of time.  
It was designed with multiple use cases in mind, including security applications, such as detecting unauthorized entry into restricted areas, or verifying equipment status.  

### Key features

- **Scalable stream analysis**: Designed and developed an architecture capable of handling an unlimited number of streams for processing, ensuring scalability and robustness.
- **Customizable machine learning models**: Implemented a system that supports the selection of various machine learning and computer vision models, enabling real-time analysis of streams.
- **Analytics platform**: Deployed an analytics platform that allows the creation of custom dashboards for long-term analytics of video streams, providing valuable insights and visualizations.

### Development and execution

The project was developed by a team of three using the SCRUM methodology, occasionally with assistance from additional contributors.

It involved tasks such as:

- **Planning the whole architecture** to ensure easy scalability (multiple streams, models and users)
- **Integrating various machine learning models** and computer vision algorithms, including object detection, image classification, landmark detection, and image segmentation
- **Synchronizing video frames**
- **Developing the website**
- **Storing information in a database**
- **Creating dashboards to view real-time statistics** from the collected data
- **Containerizing multiple services, creating deployment pipelines, and setting up CI/CD processes**

And also technologies such as **Python**, **Redis**, **ELK stack**, **tensorflow**, **pytorch**, among others.

### Conclusion

Overall, I really enjoyed working on this project. From tackling hard technical challenges, such as synchronizing video frames between various machine learning models, to experiencing great teamwork and using cutting-edge technologies, I ended up learning a lot.