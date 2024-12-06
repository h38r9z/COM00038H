java c
COM00038H
BEng, BSc, MEng and MMath Degree Examinations 2023–24
Computer Science
Computer Vision  Graphics

Figure 1: CIE xy diagram
1 (30 marks) Light, colour and surface reflectance
(i) [8 marks] Consider a monochromatic LED that emits a power (radiant flux) of 3W.
(a) [5 marks] Given that the light source emits N = 1019 photons per second, determine the wavelength (in nm) of the light produced by the LED.
(b) [3 marks] What would be the luminous flux of a monochromatic light source that emits the same number of photons, but at a wavelength of 555 nm?
(ii) [8 marks] A graphics card represents colors in the sRGB color space using 8 bits per channel.
(a) [3 marks] Consider a triangle in a scene, uniformly coloured with the RGB values of (155, 108, 60). Determine the CIE xy coordinates of this color, briefly explaining the steps you have used to compute the values. Then, plot the colour on the provided CIE xy diagram (Figure 1), and label the corresponding point with “T”.
(b) [5 marks] Given the CIE xyY coordinates (x = 0.3892, y = 0.5135, Y = 0.9500), determine the corresponding colour in the sRGB representation on the graphics card.
(iii) [14 marks] Consider a flat, glossy surface illuminated by a point light source. This source is located at a distance of r = 2m from a specific point on the surface. The surface’s reflectance is modeled using a Phong BRDF specular lobe (non-energy conserving), complemented by a Lambertian diffuse lobe.
Calculate the colour observed by a viewer at the point on the surface, given the following conditions:
• The diffuse albedo (ρd) of the material is (0.2941, 0.1176, 0.1961).
• The specular reflection constant (ks) is (0.2500, 0.2500, 0.2500), and the Phong exponent (m) is 16.
• The intensity of the light source is Li = (0.5, 1, 0.5).
• The direction of the light (vi) is defined by the angles (θi = 4/π, ϕi = 0).
• The direction of the viewer (vr) is defined by the angles (θr = 6/π, ϕr = π).
• All provided RGB values are in linear space, in the range [0 − 1].
Write down intermediate steps and results to 4 decimal places.

Figure 2: Visualisation of a cube using two images.
2 (25 marks)
Multi-view Geometry
(i) [12 marks] Consider a pair of images viewing a cube from two different directions, with their defining planes parallel to two adjacent faces of the cube, as shown in Figure2. Assume that the centers of projection for the two images are COP1 and COP2, respectively. COP1, COP2 and an observed point O are located on the plane defined by z and x axes.
(a) [4 marks] What regions of the cube are simultaneously visible in both images? Identify the parts of the cube that can be seen in both image 1 and image 2.
(b) [8 marks] Write the transformation matrix from the coordinate system of the camera in Image 2 to the coordinate system of the camera in Image 1 in homogeneous coordinates. Consider the coordinate system as indicated in the figure, with the centre of the coordinate system located in COP1, where the plane of the observed point O, COP1 and COP2 is parallel with XZ plane, and assume that the distance between COP1 and COP2 is d and that the vector joining COP1 and COP2 is parallel to X axis.
(ii) [13 marks] Consider two images taken while moving along a corridor as shown in Figure3.
(a) [4 marks] Describe the geometrical relationship between the image planes 代 写COM00038H Computer Vision & Graphics  2023–24C/C++
代做程序编程语言of Image 1 and Image 2. How can Image 1 be approximately transformed to match the perspective of Image 2?
(b) [4 marks] Consider Image 1 and Image 2 from above. Chose four points in each of these images and draw approximately the epipolar lines and epipolar points for each of these images.
(c) [5 marks] Consider that Image 1 and Image 2 are part of a longer sequence of several

Figure 3: Two images taken while moving along a corridor.
images taken along the corridor in a similar way to those images. Describe a simple algorithm that can be used to model the movement of the person with the camera taking these pictures.

Figure 4: Diagram showing the transparent slabs with varying indices of refraction used in Question 3.
3 (20 marks) Ray tracing
(i) [15 marks]
A ray of light strikes three transparent slabs (Figure4), the first one made of sapphire (Index Of Refraction 1.77), the second of diamond (IOR 2.42), and the third one made of quartz (IOR 1.54). The region above the sapphire slab is air, while below the quartz slab is water (IOR 1.33). Each layer has infinite surface area, but their thicknesses are d, d, and 2d respectively (d = 1). Assume the incident angle on the sapphire surface is θi = 6/π, the plane of incidence is the X − Y plane, and that the ray hits the surface of the sapphire at the coordinates (xs, ys) = (3, 5).
Perform. all the calculations required to trace the path of the refracted ray through each medium and interface, and compute the coordinates of the point where the ray hits the surface of the water.
(ii) [5 marks] Assume that, instead of being water, the bottom layer is an ideal mirror. Determine the coordinates at which the ray would exit the surface of the sapphire. Also, specify the angle it makes with respect to the surface normal. Illustrate the resulting ray on the provided figure.
4 (25 marks)
3-D scene reconstruction
(i) [12 marks] Consider taking a set of images acquired from all around a central object.
(a) [4 marks] How many images do you need to represent most points from the surface of a sphere? Answer the same question when considering a cube.
(b) [4 marks] What should be location and orientation of the viewing planes for the images for capturing the central object either a sphere or a cube, considered at (a) for capturing the entire surface of the object? Draw the objects and the viewing planes of the images in relation to the object.
(c) [4 marks] Consider that both the sphere and the cube from (a) have patterns on their entire surfaces. Consider the images from (a) for reconstructing the surfaces of each of the two objects, sphere and cube. Which regions from the surface of each object, sphere or cube, are most distorted or have some missing details in the projections?
(ii) [8 marks] Consider shape-from-silhouettes as well as space carving as methods to represent a 3D scene from multiple images. Provide two disadvantages for using shape-from-silhouettes and another two for using space carving when comparing these methods with each other for 3D scene reconstruction. By disadvantage we understand lack in the precision of reconstruction.
(iii) [5 marks] Consider a feature detector, such as Harris corner detector or SIFT, applied on a depth map image. What would represent the features detected by such an operator in a depth map?





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
