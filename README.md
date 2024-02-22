Particle swam optimization is a computational method that tries to find the minimum (or the maximum) of a function developed by James Kennedy, Russel Eberhart and Yuhui Shi. In opposition to other computational methods, Pso doesn't require the derivative of the function to exist.

This is a toy project made in my spare time, it can calculate the Pso on a certain amount of iterations on a 2 variables function f(x,y), and for each iteration it creates a plot with both the function and the particles and then churns out a gif with the animation of the particles. as you'll see, despite starting in different places throughout the space, they eventually start moving towards the same direction and eventually converge. Thus, the name Particle swarm optimization

There are certain parameters which are given and shouldn't be changed too much - alfa, beta and epsilon1 and 2 -. As of today, the discussion of which values are better is still an ongoing dispute in the fields of mathematics. However, there are also certain values that i suggest changing to see how they affect the animation, namely the random seed, the X initial particle distribution and the initial velocity of each particle, so don't be afraid to experiment and break things when you mess too much with this values.

As one of my teachers said the first day of the course "introduction to artificial intelligence", after taking the photo of a sign in the Sydney Botanic Garden: "Please walk on the grass, we also invite you to smell the roses, hug the trees, talk to the birds and picnic on the lawns". I invite you doing the same here

You will need ffmpeg to render the animation, or any other renderer, such as Imagemagick or Pillow

This implementation was based on Xin-She Yang's Nature-Inspired Optimization Algorithms pseudocode, although minor variations are present. Another resource i found valuable was [this article](https://machinelearningmastery.com/a-gentle-introduction-to-particle-swarm-optimization/)



