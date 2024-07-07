# Awesome Computer Graphics Resources [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome computer graphics resources. Inspired by awesome-... stuff.

## Basic Raster Graphics Algorithms for Drawing 2D Primitives

### Line Drawing
*Scan Converting Lines*

* [Line Drawing Algorithm - Wikipedia](https://en.wikipedia.org/wiki/Line_drawing_algorithm)
* [How to draw ugly lines really fast](https://cohost.org/tomforsyth/post/648716-how-to-draw-ugly-lin) - Beyond textbook Bresenham
* [Xiaolin Wu's line algorithm](https://en.wikipedia.org/wiki/Xiaolin_Wu%27s_line_algorithm) - Xiaolin Wu's line algorithm was presented in the article "An Efficient Antialiasing Technique" in the July 1991 issue of Computer Graphics
* [Bresenham](https://github.com/w8r/bresenham-zingl) - Bresenham rasterisation functions by Alois Zingl

### Conic Section and Ellipse
*Scan Converting Ellipses*

* [Fast Parametric Ellipse Algorithm](https://arxiv.org/abs/2009.03434) - A Fast Parametric Ellipse Algorithm, Jerry R. Van Aken
* [conic-draw](https://github.com/jvanaken1/conic-draw) - Pitteways algorithm for drawing conic curves, Jerry R. Van Aken
* [Ellipse Projection](https://static.laszlokorte.de/quad/) - A unit circle inscribed in the unit square projects to an ellipse inscribed in the quadrilateral.

### Béziers
*Rational Bézier, Cubic Bézier curves, Rational cubic Bézier*

* [Pomax Bezier](https://pomax.github.io/bezierinfo/) - A free, online book for when you really need to know how to do Bézier things.
* [From Bézier to Bernstein](http://www.ams.org/publicoutreach/feature-column/fcarc-bezier) - From Bézier to polynomials defined by Bernstein.
* [Parallel curves of cubic Béziers](https://raphlinus.github.io/curves/2022/09/09/parallel-beziers.html)
* [An Interactive Introduction](https://www.jezzamon.com/fourier/) - An Interactive Introduction to Fourier Transforms
* [Bezier Curves on Hacker News](https://news.ycombinator.com/item?id=30100427) - Discussion about alternatives to Bezier curves.


### Antialiasing

* [Anti-aliasing Wikipedia](https://en.wikipedia.org/wiki/Spatial_anti-aliasing) - Spatial anti-aliasing EN
* [Antialiasing Wikipedia DE](https://de.wikipedia.org/wiki/Antialiasing_(Computergrafik)) - Antialiasing DE

### 2D Libraries

* [Blend2d](https://github.com/blend2d/blend2d) Blend2D is a high performance 2D vector graphics engine written in C++ and released under the Zlib license.
* [Skia](https://skia.org/) Skia is an open source 2D graphics library which provides common APIs that work across a variety of hardware and software platforms.
* [Anti-Grain Geometry AGG](https://agg.sourceforge.net) High Fidelity 2D Graphics
* [libart](https://levien.com/libart/) Libart is a library for high-performance 2D graphics. It is currently being used as the antialiased rendering engine for the Gnome Canvas.
* [geometry-central.net](https://github.com/nmwsharp/geometry-central) Applied 3D geometry in C++, with a focus on surface meshes.
* [FastUIDraw](https://github.com/intel/fastuidraw) FastUIDraw is a library that provides a higher performance Canvas interface. It is designed so that it always draws using a GPU.

## Image Manipulation and Storage

### JPEG and JPEG XL
*JPEG is a commonly used method of lossy compression for digital images*

* [JPEG XL](https://jpeg.org/jpegxl/) - The JPEG XL Image Coding System (ISO/IEC 18181) 
* [JPEG XL image format reference implementation](https://gitlab.com/wg1/jpeg-xl) - JPEG XL image format reference implementation.
* [JPEGLI](https://github.com/libjxl/libjxl/tree/main/lib/jpegli) - Improved JPEG encoder and decoder implementation
* [NanoJPEG](https://keyj.emphy.de/nanojpeg/) - NanoJPEG: a compact JPEG decoder.

### PNG 
*PNG is a raster-graphics file format that supports lossless data compression.*

* [libpng](http://libpng.org/pub/png/) - libpng website
* [OptiPNG](http://www.olegkikin.com/png_optimizers/) - Comparison of lossless PNG compression tools 

### Digital Halftoning

* [Dithering Eleven Algorithms](https://tannerhelland.com/2012/12/28/dithering-eleven-algorithms-source-code.html) - Eleven Algorithms and Source Code
* [Chrilly's MonaLena](https://github.com/DonChr/MonaLena) - Classical Dithering Algorithms, C Library.
* [Otsu's method](https://en.wikipedia.org/wiki/Otsu%27s_method) - Automatic image thresholding, Otsu's method
* [Halftoning and Dithering](https://photo.stackexchange.com/questions/5779/what-is-the-difference-between-halftoning-and-dithering) - Halftoning and Dithering.
* [Modern-Digital-Halftoning](https://www.routledge.com/Modern-Digital-Halftoning/Lau-Arce/p/book/9781420047530) - Modern Digital Halftoning By Daniel L. Lau, Gonzalo R. Arce
* [Blue- and Green-NoiseHalftoning Models](https://www.researchgate.net/publication/3321489_Blue_and_green_noise_halftoning_models) - Blue- and Green-NoiseHalftoning Models
* [Druckraster](https://de.wikipedia.org/wiki/Druckraster) - Druckraster/Halftone
* [Links on the art and algorithm of dithering](https://dbohdan.com/wiki/dithering) - Links on the art and algorithm of dithering
* [Ditherpunk](https://surma.dev/things/ditherpunk/) - Ditherpunk  The article I wish I had about monochrome image dithering 
* [Dithering for quantization and sampling in video games](https://bartwronski.com/2016/10/30/dithering-in-games-mini-series/) - Blog post series about various uses of dithering for quantization and sampling.
* [a dither](http://pippin.gimp.org/a_dither/) - a dither algorithm; small, spatially stable, based on magic numbers and arithmetic
* [Dithering in computer graphics](http://extremelearning.com.au/unreasonable-effectiveness-of-quasirandom-sequences/#dither) - Dithering in computer graphics
* [Dither Machine](https://lunarlabs.itch.io/dither-machine) - Dither Machine

### Image Processing

* [Image Processing On Line](http://www.ipol.im/) - IPOL is a research journal of image processing and image analysis
* [Diffusion based image generative models](https://chitwansaharia.github.io/) - Diffusion based image generative models 
* [Image Super-Resolution via Iterative Refinement](https://iterative-refinement.github.io/) - Image Super-Resolution via Iterative Refinement
* [Image Unshredding](https://github.com/robinhouston/image-unshredding) - Image unshredding.
* [Perfectly Secure Steganography](https://arxiv.org/abs/2210.14889) - Perfectly Secure Steganography Using Minimum Entropy Coupling
* [ThumbHash](https://evanw.github.io/thumbhash/) A very compact representation of an image placeholder.
* [Introduction To Fourier Transforms](https://www.cs.unm.edu/~brayer/vision/fourier.html) - Introduction To Fourier Transforms For Image Processing
* [Mipmaps](https://en.wikipedia.org/wiki/Mipmap) - Mipmap; pre-calculated, optimized sequences of images
* [OpenCV](https://opencv.org/) Open Source Computer Vision Library
* [SOD](https://sod.pixlab.io/articles/modern-image-processing-algorithms-implementation.html) An Embedded Computer Vision & Machine Learning Library
* [Perlin noise](https://en.wikipedia.org/wiki/Perlin_noise#cite_note-Perlin:1985:IS:325165.325247-2) - Perlin noise

## 3D computer graphics

### Raytracing

* [Tiny Taytracer](https://github.com/ssloy/tinyraytracer) - Tiny Raytracer 

### OpenGL

* [Awsome OpenGL](https://github.com/eug/awesome-opengl) A curated list of awesome OpenGL libraries, debuggers and resources.
* [Learn OpenGL](https://learnopengl.com/) - Online book for learning OpenGL
* [WEBGL Water](http://madebyevan.com/webgl-water/) - WebGL Water Demo

## Miscellaneous

### Graphics Gems

* [Graphics Gems](http://www.realtimerendering.com/resources/GraphicsGems/) - Official on-line repo for the code from the Graphics Gems.
* [Graphics Gems Github](https://github.com/erich666/GraphicsGems) - Official on-line repo for the code from the Graphics Gems.

### Digital Libraries, Journals and Online Courses

* [Scratch A Pixel](https://www.scratchapixel.com/) - Foundations of 3D Rendering.
* [Computer Graphics Techniques](http://jcgt.org/) - The Journal of Computer Graphics Techniques peer-reviewed, open access, and free to all.
* [Grafica Obscura](http://graficaobscura.com/) - A compilation of technical notes, pictures and essays.
* [ACM](https://www.acm.org/) - ACM Digital Library has opened more than 117,500 articles published between 1951 and the end of 2000, during the first 50 years of its publishing program.
* [Physical Based Rendering Course](https://blog.selfshadow.com/publications/) Physical Based Rendering

### Mathematics for Computer Graphics

* [Computer Graphics & Vison Lab, Tsing Hua University](https://cgv.cs.nthu.edu.tw/publications) - Publications
* [cantorsparadise](https://www.cantorsparadise.com/) - https://www.cantorsparadise.com/
* [euler-math-toolbox](http://euler-math-toolbox.de/) - http://euler-math-toolbox.de/
* [walkingrandomly](https://walkingrandomly.com/) - https://walkingrandomly.com/
* [mathpuzzle links](https://www.mathpuzzle.com/Links.html) - https://www.mathpuzzle.com/Links.html
* [Brian Hayes](http://bit-player.org/) - Brian Hayes, American scientist, columnist and author. 
* [Brian Hayes, American Scientist](https://www.americanscientist.org/author/brian_hayes) - Brian Hayes, American Scientist.
* [Hyperbolic Geometry](http://roguetemple.com/z/hyper/dev.php) - Hyperbolic Geometry

### Books

* [Digital Image Processing](https://sde.uoc.ac.in/sites/default/files/sde_videos/Digital%20Image%20Processing%203rd%20ed.%20-%20R.%20Gonzalez,%20R.%20Woods-ilovepdf-compressed.pdf) - Rafael C. Gonzalez, Richard E. Woods - Digital Image Processing
* [Computer Graphics: Principles and Practice](https://cgpp.net/about.xml) - Computer Graphics: Principles and Practice, 3rd Edition
* [Digital Halftoning](https://mitpress.mit.edu/9780262526470/digital-halftoning/) - Digital Halftoning by Robert Ulichney 
* [Compressed Image File Formats](https://books.google.at/books/about/Compressed_Image_File_Formats.html?id=_nJLvY757dQC&redir_esc=y) Compressed Image File Formats (JPEG, PNG, GIF, XBM, BMP) by John Miano 

### Blogs

* [Michael Fogleman](https://www.michaelfogleman.com/projects/) - Michael Fogleman
* [Alex Tardif](http://alextardif.com/LearningGraphics.html) - Alex Tardif
