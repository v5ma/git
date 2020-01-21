Nvidia News for 2019
  In one year there are now 50 more developers on Nvidia GPUs, 50 percent more Cuda downloads, there are now 140 super computers powered by Nvidia, that's a 50% growth in the Top500 Supercomputers. that includes the #1 super computer in the world the ORNL Summit, the #1 in Europe - Swiss CSCS Piz Daint, the #1 in Japan, AIST ABCI, and 22 of the Top 25 most Energy Efficient.
  
  There are now 600 Cuda applications
  15 of the top 15 most popular applications are now powered by Cuda
  
  CryoSPARC
    Cryo the reconstruction of particles from cryo electron beam microscopy
    CryoSPARC is the state-of-the-art platform used globally for obtaining 3D structural information from single particle cryo-EM data.

The cryoSPARC platform enables automated, high quality and high-throughput structure discovery of proteins, viruses and molecular complexes for research and drug discovery.
    
  CryoSPARC is an integrated platform that combines state-of-the-art algorithmic advances with high performance numerical implementations and well designed software to power high-throughput single particle cryo-EM workflows.
    https://cryosparc.com/
    
  
  Fun3D
    FUN3D is a Computational Fluid Dynamics (CFD) suite of tools actively developed at NASA that benefits Aeronautics, Space Technology, and Exploration by modeling fluid flow.
    https://fun3d.larc.nasa.gov/
  
  Gromacs
    Chemistry - Molecular dynamics
    GROMACS is a versatile package to perform molecular dynamics, i.e. simulate the Newtonian equations of motion for systems with hundreds to millions of particles.

It is primarily designed for biochemical molecules like proteins, lipids and nucleic acids that have a lot of complicated bonded interactions, but since GROMACS is extremely fast at calculating the nonbonded interactions (that usually dominate simulations) many groups are also using it for research on non-biological systems, e.g. polymers.
   http://www.gromacs.org

  
  Microvolution
    Microscopy - An inverse convolution method to enhance imagery
    Nearly instantaneous 3D deconvolution—up to 200 times faster.
    https://www.microvolution.com/
    
  Parabricks
   GPU Accelerated Genomics Analysis
    
  https://www.parabricks.com/
  
  WRF
    Weather - the worlds most popular weather simulator
    The Weather Research and Forecasting (WRF) Model is a next-generation mesoscale numerical weather prediction system designed for both atmospheric research and operational forecasting applications. It features two dynamical cores, a data assimilation system, and a software architecture supporting parallel computation and system extensibility. The model serves a wide range of meteorological applications across scales from tens of meters to thousands of kilometers. The effort to develop WRF began in the latter part of the 1990's and was a collaborative partnership of the National Center for Atmospheric Research (NCAR), the National Oceanic and Atmospheric Administration (represented by the National Centers for Environmental Prediction (NCEP) and the (then) Forecast Systems Laboratory (FSL)), the (then) Air Force Weather Agency (AFWA), the Naval Research Laboratory, the University of Oklahoma, and the Federal Aviation Administration (FAA).
    https://www.mmm.ucar.edu/weather-research-and-forecasting-model
    
Using exactly the same GPU and exactly the same infrastructure Cuda applications 
    
  such as Amber,
    
   Chroma
    
   Lammps
    
   Milc
    
   Namd
    
   Quantum Expresso
    
   SF3D
    
   continue to improve in performance, up 25 times in 2018, and up 40 times in 2019.
   
   This year Nvidia announces Cuda-X which GPU-Accelerated Computing Libraries
   
   Cuda Acceleration Libraries
    
   Cude runs on top of all of Nvidia's GPU's
    
   It runs on top of the graphics GPU called RTX
   The deep learning system called DGX
   The hyper scale system called HGX
   and the autonomous machine embedded systems called AGX
    
   On top of Cuda Nvidia builds domain specific acceleration libraries
    
  Rtx Computer Graphics
  
  HPC High performance computing
  
  AI Artificial Intelligence
  
  DR Automomous Driving
  
  IS Isaac Robotics
  
  CL for Clara Medical Imaging
  
  ME Metropolis for Smart Cities
  
  All of these are now part of Cuda X and on top of it is NGC, the Nvidia GPU cloud. Whenever it is possible to containerize these libraries, they are added to the GPU cloud.


Three chapters of Nvidia's talk"
Computer Graphics is the driving force of Nvidia's company, it is the simulation of virtual reality, one of the most challenging computation problems in all of the industry, after 25 years of pursuing real time virtual reality we have not achieved it, not even close, but we are getting closer and closer to it every single day.

Last week

Nvidia Keynote start at 15:46 to 20:39

The Nvidia GTC Keynote and the Unity GDC Keynote showed the exact same video.
It featured Microsoft's DXR or Direct X with Ray Tracing API.

It was a video of Real Time Ray Tracing, with Unity, running on Nvidia's RTX graphics cards.

On the left side was a real video and on the right side was a virtual reality simulation built in Unity, with real time ray tracing, or Nvidia RTX technology

It was virtually impossible for the audience to tell which side was real and which side was not real.

The Unity Real Time Raytracing RTX demo (shown at GTC & GDC during both the Nvidia and Unity keynotes respectively) will be available for everyone to play with April 4th. You will need to download Unity and you will need an RTX capable graphics card such as the RTX 2060 or higher.


Nvidia Turing RTX architecture:
Turing's architecture is notable because it split the floating point and integer execution so that they could be done concurrently. In the past GPU's were used for shading, but in the future the plan is to use GPU's for real time raytracing, by doing both concurrently complex dominant shading operations could be done at the same time as demanding ray tracking operations

Nvidia also brings a new technology called variable rate shading, depending on what part of the screen it is the amount of shading does not have to be nearly as precise.

Using variable rate shading we can reduce the amount of shading necessary. The mesh shaders allows advanced level of detail adjustments to render massive amounts of stuff in the virtual environment.

Nvidia is still heavily investing in DLSS which is the technology that will allow an Nvidia GPU to do less work to render a picture, and have AI infer the rest of the picture. DLSS is about super resolution.

Microsoft Windows DXR or Direct X with Ray Tracing is now available.

Unreal Engine 4.2.2 will incorporate DXR and lastly Vulkan RT 

27:10 - 28:52
RTX Demo A developer called Nexon shows what UE4.2.2 is capable of.

Quake RTX Demo

"and of course this is not Quake without the BFG"

"Pixar artists already rely on Nvidia Ray tracing, and RTX more than doubles the performance they will see. We're excited to use RTX on our upcoming films." - Steve May, CTO, Pixar

On CPU a typical movie studio shot, with ray tracing computer graphics, lasting a few seconds, would take 25 CPU nodes (Dual Skylake) or 1 RTX server node (4x RTX 8000), on CPU the total render time would be 38 hours, on RTX 6 hours. The cost of power over 5 years on CPU 70k, and the total cost on CPU is 250k, while the cost of power over 5 years on RTX is 10k, with the total cost being 30k.

Which means that if you are Pixar you could get 7 RTX Servers for less than the total cost of using CPU's to render your films, and each RTX server would process that scene 6 times faster. 6 times faster times 7 RTX Servers (6 x 7 = 42) compared to one CPU farm costing 250k.

Nvidia Omniverse article at 45:30 minutes into the keynoteunit