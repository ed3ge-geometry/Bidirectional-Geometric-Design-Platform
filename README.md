# Bidirectional-Geometric-Design-Platform
The curved surfaces in various fields of engineering including civil and architectural engineering, mechanical engineering, and industrial design are required to satisfy various specifications and restrictions, as well as to enhance the beauty of their appearance. In the conventional (forward) design scheme, the designers first model the shapes using parametric representation such as NURBS. Then, the structural analysis is carried out by discretizing the models into a triangular or quadrilateral mesh, and the model is further converted to manufacturable shapes. On the other hand, in the inverse design scheme, the necessary structural performance and the restrictions for manufacturability are first defined. Then, the shapes of the products are determined to satisfy the predefined conditions through, for example, an optimization approach. Furthermore, it is important that the forward and inverse design process is restricted to specific classes of surfaces, such as piecewise developable surfaces, to automatically satisfy manufacturability requirements. Using the same mesh in the processes of design, analysis, and manufacturing is also important. 
We developed a bidirectional circulative design platform based on the novel geometry of discrete surfaces; mainly piecewise developable surfaces, to realize a computationally efficient and seamless cycle of the forward and inverse design scheme.
This platform was developed as a part of JST CREST, Evolving Design and Discrete Differential Geometry: towards Mathematics Aided Geometric Design (ED3GE). The platform includes the following tools. Note that the tools of structural analysis are not included because they are widely available.
- Basic tools of discrete differential geometry.
- Surface approximation using rigid origami
- Curved-folding origami design of piecewise developable surfaces
- Non-uniform constant mean curvature (CMC) surface
- Piecewise developable surface (PDS) without explicit meshes
- Inverse design of PDS shell using structural optimization and machine learning
- Shape design of shells for specified stress distribution

To install the tool, you first need to create the "ED3GE_Tools" folder in your Grasshopper UserObjects folder. Then, place the ghuser files and unzipped folders in the "ED3GE_Tools" folder. The "ED3GE_Tools" tab will appear on your Grasshopper window.
