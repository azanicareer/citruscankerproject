# CitriCare AI: Citrus Canker detection
<p align="center">
  <img src="https://github.com/azanicareer/citruscankerproject/blob/main/logo3.jpg" alt="Logo" width="200">
</p>

Welcome to our AI-powered solution designed to detect and combat citrus canker, a prevalent disease impacting citrus crops globally.

## The Problem

The Florida wine industry generates approximately $7 billion for the Florida economy.

Citrus canker poses a significant threat to citrus trees, leading to blemished leaves, reduced yields, and economic losses for farmers. Traditional detection methods often fall short, requiring time-consuming visual inspections.

### Citrus leaf afflicted by citrus canker
<p align="left">
  <img src="https://github.com/azanicareer/citruscankerproject/blob/main/unhealthyleaf.png" alt="Diseased leaf">
</p>

### Healthy citrus leaf
<p align="left">
  <img src="https://github.com/azanicareer/citruscankerproject/blob/main/Canker%20orange%20data%20deck%20(1).png" alt="Healthy leaf">
</p>

### Canker afflicted orange
<p align="left">
  <img src="https://github.com/azanicareer/citruscankerproject/blob/main/cankerorange.jpg" width=300>
</p>


## Our Solution

Our project uses the AlexNet convolutional neural network to accurately identify healthy citrus leaves from those affected by citrus canker in real-time. By analyzing leaf images, our system provides rapid and precise detection, enabling early intervention and preventive measures.


### Convolutional Layers

- AlexNet's convolutional layers scan the input image in small chunks called filters or kernels.
- Each filter extracts specific features (like edges or textures) by performing element-wise operations and summing up the results with the corresponding part of the input image.

### Feature Maps

- As the filters move across the image, they create feature maps that capture different aspects such as edges, colors, or patterns.
- Each filter generates a feature map, highlighting areas where the filter's specific feature is present.
  <p align="center">
  <img src="https://github.com/azanicareer/citruscankerproject/blob/main/image%20filter.png" alt="feature map" width= "300">
</p>

### Hierarchical Representations

- Feature maps are used to enable the network to understand the input data at multiple levels of abstraction, gradually learning intricate patterns and features.

## Advantages of Early Detection 🍃

* **Improved Crop Health:** Timely identification of citrus canker helps maintain the health of citrus plants, allowing for appropriate and swift action to mitigate the disease's impact. 

* **Cost Efficiency:** Early detection reduces the need for extensive treatments or replacing numerous plants affected by citrus canker, resulting in cost savings for farmers.

* **Consistent Quality:** Identifying and removing diseased leaves ensures that healthy ones are utilized, contributing to the overall quality of the citrus yield.

* **Preventing Spread:** Promptly addressing citrus canker limits its potential spread to nearby plants, safeguarding the health of the entire citrus orchard.

* **Reduced Food Waste:** Early detection prevents the development of unattractive lesions on fruit, ensuring that citrus crops meet supermarket standards and reducing the likelihood of rejection, minimizing food waste.


## Pairing with Drone Technology

To extend our solution's capabilities, we integrate our citrus canker detection software with drone technology for real-time field surveillance. Drones equipped with our AI software conduct aerial surveys, capturing images of citrus groves. When diseased leaves are detected, the software triggers alerts with precise GPS coordinates.

### Key Features

- **AI-Powered Detection:** Utilizes AlexNet for high-accuracy identification of citrus canker.
- **Drone Integration:** Seamless pairing with drones for aerial surveillance.
- **Location-Based Alerts:** Instant alerts with GPS coordinates for targeted action.

## Results 

The graphs below indicate the training accuracy (`acc_train`) and loss over the course of the training runs:

### Accuracy 
<p align="left">
  <img src="https://github.com/azanicareer/citruscankerproject/blob/main/W%26B%20Chart%2012_7_2023%2C%2012_59_56%20PM.png" alt="Accuracy">
</p>

### Loss
<p align="left">
  <img src="https://github.com/azanicareer/citruscankerproject/blob/main/W%26B%20Chart%2012_7_2023%2C%201_02_30%20PM.png" alt="Loss">
</p>

### Run Summary

- **Training Accuracy**: 84.4%
- **Loss**: 0.4695

The high training accuracy suggests that the model has learned to distinguish between diseased and healthy citrus leaves effectively.

## Pose Machine
![pose](posemachine.gif)

By autonomously detecting and localizing affected areas on the plants, the AI system ensures that the application of copper spray is directed precisely at the infected regions, eliminating the need for human operators to directly handle or manually apply the treatment.

This not only enhances safety protocols in agricultural practices but also minimizes the risk of exposure to harmful chemicals for workers in citrus orchards.


## Why Choose Us

- **Innovative Approach:** Pioneering AI for early citrus canker detection.
- **Expertise:** Our team comprises skilled AI engineers with agricultural insights.
- **Impact:** Empowering farmers with advanced technology for sustainable agriculture.

## Contact Us
citricare@gmail.com
