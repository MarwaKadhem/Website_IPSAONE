---
title: "NOO, a plasma nano-thruster"
date: 2020-05-12T12:14:34+06:00
image: "images/blog/im2.png"
tags: ["Nanotechnologies","Propulsion","Space"]
description: "This is meta description."
draft: false
---

NOO is a nano-thruster based on the Helicon Plasma technology, which refers to the radiofrenquency generation of a plasma and its acceleration through a magnetic nozzle to create thrust. The NOO thruster will allow to counter atmospheric drag on LEO orbits due to residual air molecules while using less propellant.



#### Power requirements

Unlike the ∆V , which mainly influences the amount of fuel loaded on the CubeSat, and is more a constrain on the mission than on the design of the thruster itself, the power available is the most limiting factor for electric propulsion in general, and in particular for a low power system as the one in exam. From literature on RF thruster is possible to find that scaling down the power means decreasing all the performances of the thruster, making of the power requirement the hardest issue to overcome. In fact in studies and researches conducted on RF thursters, the range of power is almost always in the order of hundreds of watts or more. But there are some teams working on low power RF thruster, as Phase-
Four with their RT-F4 thruster, which was tested at power levels down to 40 W. <br>

By interpolation of their measurements on thrust and specific impulse with respect to input power, it has been discovered that their thruster in the range 10-20 W, would deliver a specific impulse ranging from 40 to 60 s, confirming what said previously, and showing that, at the power level available on ARAGOSAT-1, the Isp would be lower than for a cold gas thrusters.


#### Helicon Plasma Thrusters

The Helicon Plasma Thruster is one of the most efficient RF thruster and is characterized by the working principle described in the following. A gas feeding system injects a neutral propellant (xenon usually, but is possible to
use a large variety of propellants) in the discharge chamber. The neutral is ionized inside the discharge chamber using an RF antenna (frequency in the order of some MHz) that produces the EM fields necessary to sustain the plasma.
Permanent magnets generate a quasi-axial magneto-static field (hundreds of Gauss) that has 3 main functions:
- confining the plasma
- allowing for propagation of Helicon waves, having a good plasma generation
- creating a magnetic nozzle effect

This system is also composed of a screen system in order to reduce EMC, a TPS (typically passive, using MLI) and of course a Power Processing Unit. One last word about this kind of RF thruster: the Helicon discharge very efficient
but at the same time is quite hard to achieve it successfully, therefore is important to notice that a considerable number of research team working and publishing about Helicon thruster, probably deal with a simple inductive discharge, less efficient but easier to obtain.

#### Radio Frequency Ion thruster (RIT)

The Radio Frequency Ion thruster uses a high-frequency electromagnetic field to ionize Xenon gas atoms to form a plasma. The positive ions are then accelerated by an electrostatic field, ejected and so they generate thrust. After the ions have been ejected from the thruster, electrons are added from a neutralizer. The plasma is thereby neutralized which prevents the satellite from becoming charged. Acquiring energy from RF waves, electrons are heated and collide with neutral particles. Such collisions lead to excitation and ionization of the last ones. As a result, not only ions appear, but new electrons, leading to a self sustained discharge. During normal operation the first grid of electrodes, under a positive potential of about 1000-1200 V, extracts ions from the plasma. The second grid is under negative voltage about 100-120 V, and accelerates ions while preventing back-stream of electrons from neutralizer area.

#### First prototype: NOO35

The NOO35 thruster was designed to perform the following tasks:
1. Test the operation of a miniaturised helicon propulsion system at CubeSat scale;
2. Characterise the performance of the system;
3. Optimise the size of the tube;
4. Optimise the magnetic field.

Its design was carried out after the study of the CNRS Helicon reactor at the ICARE laboratory, which operates on the same principle as explained in part 1. The thruster is designed as follows: it is a quartz tube with a helical RF antenna in the centre for plasma generation and acceleration. On each side of this antenna are two coils generating a magnetic field that guides the ions through the field lines created. These coils will be replaced by magnets in the flight version of the thruster. Indeed, the coils have the advantage of being able to adapt the magnetic field created but are much more energy consuming for a 3 unit CubeSat. Finally, a gas injection at the rear. All this will be held together by Peek rings and aluminium bars. A faraday cage can be added to the system to limit radiation.

<figure>
  <img src="/images/blog/prop.png/" alt="NOO35 prototype" style="width:90%">
  <figcaption>Fig.1 - NOO35 prototype working principle.</figcaption>
</figure>
