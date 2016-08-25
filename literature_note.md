
## extended depth of field ##
6. Eyal Ben-Eliezer,[An optimal binary amplitude-phase mask for hybrid
imaging systems that exhibit high resolution and
extended depth of field](https://www.osapublishing.org/DirectPDFAccess/8CB56C81-E73B-B8D2-1B93CCDA54DD1B04_175057/oe-16-25-20540.pdf?da=1&id=175057&seq=0&mobile=no)

given a method to optimazate the mask for extend DOF

you can also find a optimizaion method from[Pupil coding masks for imaging polychromatic
scenes with high resolution and extended depth
of field ](https://www.osapublishing.org/DirectPDFAccess/8C9A88EF-AEE4-89C0-C34A01907A102310_203692/oe-18-15-15569.pdf?da=1&id=203692&seq=0&mobile=no)

5. Eyal Ben-Eliezer,[All-optical extended depth of field
imaging system](http://iopscience.iop.org/article/10.1088/1464-4258/5/5/359/pdf)

using mutilplexed Fresnel lenses to extend the depth of field. it is very like focus swap, the aperture is seperate to a lot of different focus fresnel lens

4. Chenguang Ma, [High-rank Coded Aperture Projection for Extended Depth of Field](http://web.media.mit.edu/~gordonw/research/HR3DProjector_ICCP2013.pdf)

  proposed a projected light field, and use a mattix to calicarate it, two mask
  
  "every pixel of the image is an accumulation of light rays from different directions and we can view the projected
imagery as an integration of the emitted light field. In other words, the projection screen works as a geometrydependent
2D down-projection of the 4D light field, which can be further expressed as matrix multiplication."

3. Shree Nayar, [Diffusion Coded Photography for Extended Depth of Field](http://www1.cs.columbia.edu/CAVE/publications/pdfs/Cossairt_SIGGRAPH10.pdf)

   the diffusion mask can be looked as a phase mask, it pu on the pupil of lens. generate blur of orginal psf.
   It is very similar with the design of achromatic lens by alen, we need to accoding the psf to generate a psf with smallest depth varience and maxmium MTF
   
   "To implement the diffuser defined in Equation 14, we follow the procedure in [Sales 2003], which simply implements a diffuser
surface as a sequence of quadratic elements whose diameter and sag is drawn from a random distribution. The scatter function is designed to be roughly Gaussian with 0.5mm variance (corresponding to w = 1mm in Equation 16) as shown in Figure 11(c). To create
a radially symmetric diffuser, we create a 1D random profile and then apply a polar transformation to create the final 2D surface (see
Figures 11(a) and 11(b)). The maximum height of the surface is 3µm. The diffuser was fabricated using a laser machining technology
which has a minimum spot size of about 10µm. To ensure that each quadratic element was fabricated with high accuracy, the minimum diameter of a single element was chosen to be 200µm, resulting in a diffuser with 42 different annular sections. T"

2. Shree Nayar, [Spectral Focal Sweep: Extended Depth of Field from Chromatic Aberrations](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5585101)
   
    use the chromatic of lens to sweep the focus of the lens. at different object distance, use this new lens, one can get a 
    psf not depend on the object distance. this lens is limited on the widespectral application


1. Albertina Castro, [Asymmetric phase masks for extended depth of field] (https://www.osapublishing.org/view_article.cfm?gotourl=https%3A%2F%2Fwww%2Eosapublishing%2Eorg%2FDirectPDFAccess%2F90FAEEF8-BC3A-E0E5-C37E378BD255CF61_80180%2Fao-43-17-3474%2Epdf%3Fda%3D1%26id%3D80180%26seq%3D0%26mobile%3Dno&org=King%20Abdullah%20University%20of%20Science%20and%20Technology%20)
   
   in this paper, the author present a family of asymmetric phase mask (p=exp(i2piasgn(u)(u/d)n))Q(u))for extends the depth of field. for the asymmetric
   phase masks of the order n=4,5,6, all the image suffer from low visibility. It seems that the absence of zeros values within the passband of
   the mtf is acheieved at the expense of "democratically" distributing low visibility among the images along the depth of field.
