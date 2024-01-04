# Hyperspectral Imaging

In this project we analyze satelite images of Pavia University and attempt to classify pixels as a combination of distinct materials. Two approaches are used:

- **Spectral Unmixing** where we reduce the problem to a constrained linear regression problem, where the results follow the properties of a pdf (probability density function). Following this paradigm, we can assign a probability value for each distinct material on each pixel.
- **Pixel Classification** where we use traditional ML classifiers to classify individual pixels.

We analyze the results of the two approaches, their benefits and drawbacks, and conclude with ways with which they can be combined for the Hyperspectral Imaging task. Includes relevant documentation and references to existing academic literature. 
