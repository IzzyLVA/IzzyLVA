## Greetings :3

```python
import Energy_Drink
    class PenTester:
        def __init__(self):
            self.name = "Izzy"
            self.role = "Student"
            self.location = "U.S"
            self.major = "Cybersecurity"
            self.interests = ["Cybersecurity", "Automotive", "Computer Science"]
            self.currently_learning = ["Hacking :3", "Coding"]
            self.energy_drink = None

        def broke(self):
            if self.energy_drink is None:
                self.energy_drink = "Rockstar"
                print("Out of money☹ ")

me = PenTester()
me.broke()
