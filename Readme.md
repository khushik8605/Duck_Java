This project demonstrates the Strategy Pattern by modeling the behavior of various ducks. Each duck exhibits different flying and swimming behaviors using interfaces and separate implementation classes.


File	Purpose
Duck.java	: Abstract base class for all ducks.
MallardDuck.java :	Implements Duck with specific behavior.
RedheadDuck.java :	Implements Duck with specific behavior.
RubberDuck.java : Implements Duck with specific behavior.
DecoyDuck.java : Implements Duck with specific behavior.
FlyBehavior.java :	Interface for flying behavior.
SwimBehavior.java :	Interface for swimming behavior.
Fly.java :	Implements FlyBehavior for flying ducks.
NotFly.java :	Implements FlyBehavior for non-flying ducks.
Swim.java :	Implements SwimBehavior for swimming ducks.
Float.java :	Implements SwimBehavior for floating ducks.
Drown.java :	Implements SwimBehavior for drowning ducks.
Main.java	: Executes the duck behavior simulation.
