## Basics on computer vision: how it came up and conceptualization

### Pictures contain information
> **Distribution**
> > Consider DDM and its applications through adding noises
> >
> > Consider the unlikeliness of 'continuity'

> **Pixels**
> > Contains information:
> > > Color
> > >
> > > Distance
> > >
> > > Brightness

### Some ‘secrets’ about human vision systems

- Copying human vision system?
  - How?
    - How human vision systems function:
      - Input? 
        - Pictures & **Videos**
        - Within a frame, but the boundary of the frame could change
          - OR to perceive this as a fixed frame with different visual information
      - Some encoding maybe?
      - Segmentation, classification
        - I am guessing this is how 'self-supervised' is achieved
  - Hardware?
    - O(10**11) neurons -- whatever they are
    - O(10**8) transistors for a CPU
    - Parallel, slow & serial, fast
  - Vision Illusion?
    - Should we be solving this or imitating this? How do we define the success of a vision system?
      - Maybe avoiding this misfunction will lead to the collapses of other functions



- Specific Applications(or to call it sub-fields)
  - Object Classification
    - Like teaching a baby to recognize stuff
    - Pretty Straightforward, supervised, (and pretty boring haha)
  - Object Detection
    - To my understanding it is segmentation and classification
  - Body-pose tracking
  - Face Detection
  - Advanced Image Search
    - Text based?
    - This is quite interesting, multimodal
  - Self-driving cars
    - This is very interesting
    - I always think this should be described as mimicing the behavior of a community
    - More than just vision
      - LIDAR(controls light and ranging though I am not pretty sure what that means)
      - Planning
      - Mapping
      - Other cars' behavior
  - VR, AR
  - Vision Based Interaction, Robotics
  - Medical
    - Very important
  - Novel view synthesis
    - Question: what is Sparsely-sampled
      - a signal processing technique
      - known as compressive sampling, compressive sensing also
      - The summarized methodology is to find solutions to underdetermined linear systems
        - I am not really sure what this means so I will probably revisit this later
  - Mobile Apps
    - Of course

###### Information Retrieval <-- I put it here just because I don't really know how the theory of this works

- Task Overview
  - Image Classification
  - Image Segmentation
  - Object Detection
  - Instance Segmentation

- The most interesting(According Yann LeCun)  ***VIDEO DATA***
  - Video Classification
  - Multimodal Video Understanding


- Some concepts preview:
  - Input --> Convolution --> Images Maps --> Subsampling --> Fully Connected(Now mostly gotten rid of) --> Output
  - RNN, attention
  - Self-supervised Learning
    - Pipeline picture in my head -->  distance function --> how does the scalar value make a difference?
    - The scalar should be 0 or what? Dependent on different tasks? Does not make much sense intuitively
  - Generative Modeling 
    - Of course again
  - 3D Modeling



