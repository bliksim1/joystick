# Bliksim joystick - UH-1H Huey helicopter edition
An DIY JOYSTICK for flight simulation that allows complete control over centering and tension. 

The joystick can seamlessly transistion between:
* centering (returns to center)
* off-center bias (returns to somewhere other than center)
* no centering (stays where you leave it - more or less - WIP)

as well as varying the pressure required to move the stick. 

It can be controlled by physical buttons or by a UDP data stream coming from a computer.
The joystick action is smooth because it uses pneumatic actuators instead of electrical motors. 

## status

* The project is at prototype stage (works for me, but ugly)
* It is open source (GPLv3)
* It is intended to be easy to build with fairly basic tools  
* It is intended to use easily sourced, low cost components
* [Documentation](https://github.com/bliksim1/joystick/wiki) is in progress

If you would like to build a prototype version you can find [instructions in the wiki](https://github.com/bliksim1/joystick/wiki/Build)

## initial version

I specifically wanted something that works for the UH-1H Huey helicopter in Digital Combat Simulator (DCS), so my first version uses the [B8 grip](https://www.thingiverse.com/thing:2235488/files) and a stick extension with a 90 degree bend.
The grip and stick extension are designed to be changed out for different aircraft. The B8 grip is correct for the Huey and coming F4 Phantom, but it's possible to add other combinations like the Mustang or the Hornet.

## future plans

The amount of effort I can put into the project depends on contributions from people like you. 
If you have some spare cash and would like to support future development please make a contribution at ko.fi
Depending on how much community support there is I would like to:

* make the build easier by converting parts to 3D printable versions
* start a shop where you can buy all the parts in a kit
* improve software
* expand game support
* create more fixed wing variations 
* replace potentiometers with magnetic rotation sensors
* improve aesthetics
* build other cool stuff like pedals, collective etc

## how it works

The joystick is actuated by four large syringes that act as pneumatic actuators. The actuators are controlled by valves and air pumps that vary the pressure in each syringe thereby varying the amount that each syringe pushes on the stick. 

In the pitch axis, one syringe pitches the stick forward and its counterpart pushes the stick back. The airflow between the two syringes can be closed off, which causes the stick to want to return to the point where it was when the valve was closed (centering and biased centering). Alternatively, the air passage between syringes can be left open (no centering). Tension is controlled by varying the pressure in the syringes through the dump valves and air pumps.

for more details see the [videos in the wiki](https://github.com/bliksim1/joystick/wiki#videos)


