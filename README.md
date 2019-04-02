## Boris Bike
A program that will emulate all the docking stations, bikes, and infrastructure (repair staff, and so on) required to make their dream a reality.

Objects | Messages
-------- | -------
Person |
Bike | bike_condition?
Docking Station | release_bike

### Domain Model
Bike --> working? --> true/false
├── if true --> DockingStation --> release_bike --> a Bike
└── if false --> Bike (start)
