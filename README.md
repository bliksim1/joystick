# joystick
An DIY joystick for flight simulation that allows complete control over centering and tension. 
The joystick can transistion between no centering, centering or off-center bias as well as varying the pressure needed to move the stick. 
It can be controlled by physical buttons or by a UDP data stream coming from a computer.
The joystick action is smooth because it uses pneumatic actuators instead of electrical motors. 

## why
Just like in the glider I like to fly, I wanted a joysick that has could have no centering while sitting on the ground and basically just flop to wherever it is pushed. Once I'm in the air it should require more pressure to move and should push backward, requiring trim.

## how trim works in airplanes
The position and tension of the stick changes as airflow over the control surfaces increase (ailerons, rudder and elevator).
In basic airplanes the pilot literally feels the airflow pushing against the control surfaces through the controls. 
Trim counteracts these forces and reduces the need for the pilot to constantly push or pull against the controls in order to maintain the desired flight attitude.  
Mentour pilot gives a good explanation here: https://youtu.be/Fp04O0SuPbI?t=117

## how trim works in helicopters
