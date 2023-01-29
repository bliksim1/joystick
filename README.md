# joystick
An DIY JOYSTICK for flight simulation that allows complete control over centering and tension. 

The joystic can transistion between
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
* It is intended to use easy to source components
* It is intended to use low cost components  
* Documentation is in progress

## future plans

The amount of effort I can put into the project depends on contributions from people like you. 
If you have some spare cash and would like to support future development make a contribution at ko.fi

* make the build easier by converting parts to 3d printable versions
* start a shop where you can buy all the parts in a kit
* improve software
* expand game support
* replace potentiometers with magnetic rotation sensors
* improve aesthetics
* build other cool stuff like pedals, collective etc

## how it works

The joystick is actuated by four large syringes that act as pneumatic actuators. The actuators are controlled by valves and air pumps that vary the pressure in each syringe thereby varying the amount that each syringe pushes on the stick. 

In the pitch axis, one syringe pitches the stick forward and its counterpart pushes the stick back. The airflow between the two syringes can be closed off, which causes the stick to want to return to the point where it was when the valve was closed (centering and biased centering). Alternatively, the air passage between syringes can be left open (no centering). Tension is controlled by varying the pressure in the syringes through the dump valves and air pumps.


## how trim works in airplanes
The position and tension of the stick changes as airflow over the control surfaces increase (ailerons, rudder and elevator).
In basic airplanes the pilot literally feels the airflow pushing against the control surfaces through the controls. 
Trim counteracts these forces and reduces the need for the pilot to constantly push or pull against the controls in order to maintain the desired flight attitude.  
Mentour pilot gives a good explanation here: https://youtu.be/Fp04O0SuPbI?t=117

## how trim works in helicopters
