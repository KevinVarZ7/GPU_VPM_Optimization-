# GPU_VPM_Optimization
GPU optimized Variational Projection Method (VPM) for seismic wave propagation in irregular media. 
VPM is based on weak Galërkin formulation of the elastic equation. A depth dependent family functions are proposed with horizontal smooth variation. While integrating by parts, the weak 
formulation of the problem is obtained, resulting in a coupled partial differential equations
system that represents a variational projection towards the surficial horizontal plane at each node.
CUDA (Computing Unified Device Architecture) optimization is applied in the time solution of the method. It can be applied to irregular 3D geological models in few minutes. 
