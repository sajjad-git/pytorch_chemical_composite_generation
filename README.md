# microstructure_generation

This repo showcases my attempts at generating inorganic chemical composite images.

The aim of this project is to understand the hidden characteristics of chemical composites structures and create different versions of them. Additionally, the project seeks to blend these structures together to form new ones that possess specific physical and chemical properties desired by the researchers.

To see our best model, see latent_diffusion_model.

A bit about this microstructure generation
Composite materials consist of various components that are combined to form a novel
material possessing specific characteristics. The use of composite materials is on the rise in
contemporary engineering and design because of the ability to customize microstructures to
achieve particular material properties. However, the development of composite materials is a
time-intensive and expensive process. In the last few years, materials modeling and machine
learning have contributed to speeding up materials development. However, some of these
frameworks do not ensure the manufacturability of their generated materials. To enhance the
likelihood of creating materials that can be manufactured, one approach is to make minor
adjustments to existing microstructures that can result in better chemical and physical properties.
In order to improve the physical and chemical properties of materials, it is necessary to examine
the composition and structure of the material to determine which attributes in the microstructures
will lead to different properties. However, analyzing these microstructures is time-consuming
and computationally expensive due to their complexity. Instead, we can simplify the
microstructure to reduce its complexity, analyze the simplified version, select the simplified
microstructure that possesses the desired properties, and then reconstruct the original version
from the simplified one. Our team used deep learning models to simplify the representation of
complex microstructure data. These models can analyze microstructure images and learn how to
represent them in a simpler manner while retaining their important characteristics. Additionally,
these models can also reconstruct the original microstructure from the simplified representation.
We were able to reduce the complexity of microstructure images by more than 99%, while still
producing high-quality representations that were very similar to the original data. Our proposed
solution has the capability to compress 2-dimensional microstructure images to 0.16% of their
original size, while still producing high-quality microstructure samples that are statistically
similar to the original microstructures.