## Notes

# The Psychophysical Correspondence
There is no simple functional description for the perceived color of all lights under all viewing conditions, but ......
A helpful constraint:
Consider only physical spectra with normal distributions 

# Physiology of Color Vision
We have 3 kinds of cones that allow us to see color

Metamers - Two different spectral energy distributions that look the same to a person

# RBG cube
- Easy for devices
- But not perceptual
– Where do the grays live?
– Where is hue and saturation?

# For Assignment 1
Take the cropped green channel.
Iterate through crops of red and blue channel (Trying to find the upper left)
- Get the row and column of both R and G and compare them
- How to compare them? A few ways.
1. Sum of squared differences
2. Convert crops to a vector, then compute the sum of squared differences between the vector
3. Get the normalized cross correlation
4. Find gradients with each cropped image and compare the edges

# Image Filtering
Compute function of local neighborhood at each position
- Really Important!
– Enhance images
• Denoise, resize, increase contrast, etc.
– Extract information from images
• Texture, edges, distinctive points, etc.
– Detect patterns
• Template matching
