# What is Game Physics
Game Physics is some rules running in the digital world that pretend to be real physics do. In computer graphics, at lest four field are introduced in now days, which is Rendering, Simulation, Geometry, Animation.
Generally, Physics is in the field of simulation. A Computer Game is a simple simulation scene. But this parts are not devided - means that when coming with real problems, you need to do this all.

# When Should I Use Physics
In game physics, the main part is game rather than physics. This means the sense of <b>control</b> is more important than <b>accuracy</b> in real engineering. 
Mostly, game physics contains:
1. RigidBodyDynamics
2. DummyBodyDynamics
3. CharacterController
4. RagDollDyanamics
5. ClothSimulation
6. WaterSimulation
7. DeformableSimulation
8. SkeletonDyanmics
9. Vehicle
10. InverseKinematics
11. ParticleSystem
12. ClimateSystem
...

You may have seen this in other part before. Like particle system, which is always introduced in a rendering system. 
Actually, the range of Rendering and Physics will be blurry, sodo the Geometry and Simulation. Physics emphasize real world <b>rules</b>, but Rendering emphasize the <b>visual effect</b>. so when it comes to particle simulation, it may be a physics and a rendering problem.

Mostly, game physics talking about classical machanics. So when you want your game world simulate like a real macroscopic world did, you need some classical game physics.

Now days, Graphic Phyics Engineer are doing their jobs mostly in Cloth、Water and Deformable Simulations.The power of GPU makes the massive rigidbody dynamics posible. So it also maybe a era of massive rigid dynamics simulation.

But there are many other non-classical game physics engineers doing there job.
Like:
* https://spaceengine.org/ Space Engine
* https://robertsspaceindustries.com/starmap space citizen
* https://www.nomanssky.com/ no mans sky
...
but for now, we are in earth. We need do as a earthman do.

# More Informations
We made a list for some notably game physics paper and talks:
Click to jump:
* [BasicsOfPhysics](./BasicPhyics/main.md)
* [RigidBody](./RigidBody/main.md)
* [SceneQuery](./SceneQuery/main.md)
* [Clothing](./Cloth/main.md)
* [Deformable](./Deformable/main.md)
* [Fluid](./Fluid/main.md)
* [IK](./IK/main.md)
* [Particle](./Particle/main.md)

It is highly recommanded that newbie should read<b>BasicsOfPhyisics</b>、<b>RigidBody</b> and <b>SceneQuery</b> first, which will make your path eaiser.
# Books List
Here are some useful book for you when learning basic physics.
* <div align="center">《Foundations of Physically Based Modeling and Animation》</div>
  <div align="center"><img src = "../Pictures/Books/fopbmaa.jpg") </div>