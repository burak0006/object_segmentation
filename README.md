# Object Segmentation

## Object segmentation using HSV Color space

HSV color space segmentation is a technique used in image processing and computer vision to separate objects or regions within an image based on their color. The HSV color space represents colors using three components: Hue, Saturation, and Value.

- Hue: This component represents the color type (e.g., red, green, blue, etc.) and is typically measured in degrees ranging from 0° to 360°, where each degree corresponds to a specific color.
- Saturation: This component measures the intensity or purity of the color, with values ranging from 0 (completely desaturated, grayscale) to 1 (fully saturated, pure color).
- Value: This component represents the brightness of the color, with values ranging from 0 (black) to 1 (maximum brightness).

## HSV Color Space Segmentation 

In this exercise, the objective is to develop an algorithm that can accurately segment an object, specifically an apple, from the rest of the frame using color filters. To achieve this, I first defined an objective function that represents appropriate segmentation in out-of-sample frames. Next, I optimized the objective function to ensure that it performs well on these out-of-sample frames. The algorithm relies on the color filtering technique for segmentation and not use any deep learning models or pre-built computer vision functions, but rather a simple but effective method using HSV color space. The bounding boxes of the object in the first three frames will be provided to guide the development of the algorithm, while the remaining frames will be considered out-of-sample for testing purposes. Please note that I could not provide dataset but will do as soon as I can

## Preparation
### Library
- OpenCV 2
- numpy
- pandas

Execute following commands to install libraries:
```sh
pip install python-magic
sudo apt-get install libmagic1
```

## Results

<img src="https://github.com/burak0006/objectsegmentation/blob/c87600b668c2ed503a625d231e356356436300c0/results/im1.png?raw=true" width = "400" height = "300"/> <img src="https://github.com/burak0006/objectsegmentation/blob/c87600b668c2ed503a625d231e356356436300c0/results/im2.png?raw=true" width = "400" height = "300"/>
