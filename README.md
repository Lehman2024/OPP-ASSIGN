# OPP-ASSIGN
OPP
# Base class
class Vehicle:
    def move(self):
        print("This vehicle moves... somehow.")

# Subclasses with different implementations
class Car(Vehicle):
    def move(self):
        print("Driving on the road 🚗")

class Plane(Vehicle):
    def move(self):
        print("Flying through the sky ✈️")

class Boat(Vehicle):
    def move(self):
        print("Sailing on water 🚢")

# Polymorphic behavior
vehicles = [Car(), Plane(), Boat()]

for v in vehicles:
    v.move()
