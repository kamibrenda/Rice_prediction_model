# Rice Variety Prediction Project

## Project Overview

This project is dedicated to predicting the category of rice varieties, specifically the distinction between "Kecimen" and "Bresni," utilizing a decision tree model. The dataset used in this project consists of 900 observations (rows) and 8 characteristics (columns).

### Characteristics of Interest

1. **Area**: This attribute represents the count of pixels enclosed within the boundaries of a rice grain.
2. **Perimeter**: It gauges the outline of the rice grain by calculating the distance between its boundaries and the surrounding pixels.
3. **MajorAxisLength**: This feature signifies the length of the major axis of a rice grain, which is the longest line that can be drawn on it.
4. **MinorAxisLength**: It denotes the length of the minor axis of a rice grain, which is the shortest line that can be drawn on it.
5. **Eccentricity**: This characteristic provides a measurement of the ellipticity of the rice grains, sharing the same moments.
6. **ConvexArea**: It represents the number of pixels within the smallest convex hull encasing the rice grain.
7. **Extent**: This attribute computes the ratio of the area covered by the rice grain to the total number of pixels within the bounding box.

### Dependent Attribute

- **Class**: This attribute signifies the type of rice grain, which could be either "Kecimen" or "Bresni."

## Project Goals

The fundamental goals of this project include:

1. The development of a Python script employing a decision tree algorithm to predict the "Class" attribute, containing the dependent variables.
2. The implementation of a machine learning model capable of effectively distinguishing between "Kecimen" and "Bresni" rice varieties based on the provided characteristics.

Please don't hesitate to delve into the project repository to discover more details and the execution of the decision tree model.
