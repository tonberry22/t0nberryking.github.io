---
title: "Yolo v8 Guitar Detection Demo"
excerpt: "Training a Yolo v8 model to detect guitars via transfer learning on Google Colaboratory"
header:
  image: /assets/images/YOLO/sample_validation.jpg
  teaser: /assets/images/YOLO/sample_validation.jpg
gallery:
  - url: /assets/images/YOLO/test1.jpg
    image_path: /assets/images/YOLO/test1.jpg
    alt: "teaser image 1"
  - url: /assets/images/YOLO/test2.jpg
    image_path: /assets/images/YOLO/test2.jpg
    alt: "teaser image 2"
  - url: /assets/images/YOLO/test3.jpg
    image_path: /assets/images/YOLO/test3.jpg
    alt: "teaser image 3"
order: 1
---

You only look once (YOLO) is a state-of-the-art, real-time object detection system. From the maker's own words, "YOLOv8 is designed to be fast, accurate, and easy to use, making it an excellent choice for a wide range of object detection and tracking, instance segmentation, image classification and pose estimation tasks."

Released in January 2023, it claims to be faster and more accurate than the already widely-used YOLOv5. Let's try it out using a custom dataset (I like guitars but you can choose your own!) and leveraging the powerful and most importantly free GPUs of Google Colaboratory.

{% include gallery caption="Sample outputs of the model" %}

<a href="https://github.com/tonberry22/Yolo-v8-Guitar-Detection-Demo-Colab" target="_blank">Click here to see the github repository and run it yourself!</a>