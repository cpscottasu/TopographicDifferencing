# Topographic Differencing 

Topographic differencing reveals surface change from a variety of tectonic, geomorphic, and anthropogenic processes including earthquakes, volcanic eruptions, river erosion, landslides, sand dune migration, and urban development. Differencing techniques have grown in popularity over the past decade as the number of multi-temporal topographic datasets have increased.  

Vertical differencing is the subtraction of gridded elevation data (a.k.a. raster or digital elevation models (DEMs)) that span an event of interest. Early application of this method focused on rivers, although the technique has since been applied to a broader case set. 3D differencing is calculated with a windowed implementation of the Iterative Closest Point (ICP) algorithm. This approach works best with the landscape shifts laterally, for example in a surface rupturing earthquake. 

Here, we have compilied the set of resources produced by OpenTopography about topographic differencing. The material includes several video tutoials, blog posts with multiple differencing examples, links to GitHub code respositories, material presented at workshops, and an undergraduate differencing exercise. 

![Sand Dune Migration in New Mexico](https://cloud.sdsc.edu:443/v1/AUTH_opentopography/www/images%2Fsand_dunes_NM.gif)

## Tutorials: 
These YouTube tutorials walk users through how to perform on-demand topographic differencing on OpenTopography.Currently, OpenTopography has over 45 dataset pairs with vertical and 3D differencing enabled. 

[Vertical differencing Tutorial](https://youtu.be/BlDx66AQ3G0)

[3D differencing Tutorial](https://youtu.be/OoIasU4yMeQ)

## Blog Posts: 
These blog posts show several examples of vertical and 3D topographic differencing. The 3D differencing blog also includes a technical overview of how the Iterative Closest Point (ICP) algorithm is applied to geologic processes. 

[Vertical differencing](https://opentopography.org/blog/topographic-differencing-showcase)

[3D differencing](https://opentopography.org/blog/demand-3d-topographic-differencing)

## Differencing Workshop: 
[Workshop link](https://opentopography.org/blog/topographic-differencing-showcase): 2018 EarthCube Research Coordination Network Workshop - Advancing the Analysis of High Resolution Topography (A2 HRT). This includes several lectures on topographic differencing and tutorial material on several topographic differencing methods. 

## Matlab ICP differencing code and with example dataset from the 2016 M7 Kumamoto, Japan, Earthquake:
[Matlab ICP differencing](https://github.com/cpscottasu/ICP_Topo_Diff_Matlab)

## GitHub Code Repositories of Differencing Code:

[Vertical differencing](https://github.com/OpenTopography/Vertical_Differencing)

[3D differencing C++](https://github.com/OpenTopography/libicp)

[3D Differencing Python & Matlab](https://github.com/OpenTopography/3D_Differencing)


## Undergraduate topographic differening exercise:

[Link to exercise](https://github.com/cpscottasu/ICP_Topo_Diff_Matlab)

Funding Acknowledgment: OpenTopography is supported by the National Science Foundation under Award Numbers 1833703, 1833643 & 1833632
