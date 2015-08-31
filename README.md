PIM - course 2014-2015 – Master branch
=================================================

##Image Processing Course from Computer Science Bachelor's degree at University of Barcelona (UB)

###Contributors:
* Igor Dzinka (idzinkdz7@alumnes.ub.edu)
* Vicent Roig (vroigrip8@alumnes.ub.edu)

###### This repository includes every delivered task, each one contained on its dedicated folder (including Ipython notebook with self-contained resources) structured as follows:

###P1. Hybrid Images

We present hybrid images, a technique that produces static images with two interpretations, which change as a function of viewing distance. Hybrid images are based on the multi-scale processing of images by the human visual system and are motivated by masking studies in visual perception. These images can be used to create compelling displays in which the image appears to change as the viewing distance changes.

We show that by taking into account perceptual grouping mechanisms it is possible to build compelling hybrid images with stable percepts at each distance. We show examples in which hybrid images are used to create textures that become visible only when seen up-close, to generate facial expressions whose interpretation changes with viewing distance, and to visualize changes over time within a single picture.

###P2. Russian Empire Images (The three-color principle)

Sergei Mikhailovich Prokudin-Gorskii (1863-1944) [Сергей Михайлович Прокудин-Горский, to his Russian friends] was a man well ahead of his time. Convinced, as early as 1907, that color photography was the wave of the future, he won Tzar's special permission to travel across the vast Russian Empire and take color photographs of everything he saw. His idea was simple: record three exposures of every scene onto a glass plate using a red, a green, and a blue filter.

Never mind that there was no way to print color photographs until much later -- he envisioned special projectors to be installed in "multimedia" classrooms all across Russia where the children would be able to learn about their vast country. Alas, his plans never materialized: he left Russia in 1918, right after the revolution, never to return again. Luckily, his RGB glass plate negatives, capturing the last years of the Russian Empire, survived and were purchased in 1948 by the Library of Congress.

###P3. Seam carving

Effective resizing of images should not only use geometric constraints, but consider the image content as well. We present a simple image operator called seam carving that supports content-aware image resizing for both reduction and expansion.

A seam is an optimal 8-connected path of pixels on a single image from top to bottom, or left to right, where optimality is defined by an image energy function. By repeatedly carving out or inserting seams in one direction we can change the aspect
ratio of an image. By applying these operators in both directions we can retarget the image to a new size. The selection and order of seams protect the content of the image, as defined by the energy function. Seam carving can also be used for image content enhancement and object removal. We support various visual saliency measures for defining the energy of an image, and can also include user input to guide the process. By storing the order of seams in an image we create multi-size images, that are able to continuously change in real time to fit a given size.


###P4. High-dynamic-range imaging

High-dynamic-range imaging (HDRI or HDR) is a set of techniques used in imaging and photography to reproduce a greater dynamic range of luminosity than is possible with standard digital imaging or photographic techniques. The aim is to present the human eye with a similar range of luminance as that which, through the visual system, is familiar in everyday life. The human eye, through adaptation of the iris (and other methods) adjusts constantly to the broad dynamic changes ubiquitous in our environment. The brain continuously interprets this information so that most of us can see in a wide range of light conditions. Most cameras, on the other hand, cannot.

HDR images can represent a greater range of luminance levels than can be achieved using more 'traditional' methods, such as many real-world scenes containing very bright, direct sunlight to extreme shade, or very faint nebulae. This is often achieved by capturing and then combining several different narrower range exposures of the same subject matter.
