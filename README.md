

# I make things, I break things, and then I solve things. That's pretty much me in a nutshell.

```python
class Riza:
    def __init__(self):
        self.name = "Riza"
        self.age = 14
        self.interests = ["coding", "gaming", "learning", "football"]
        self.skills = ["Python", "JavaScript", "C++", "C#"]

    def __str__(self):
        return f"👋 Hey, I'm {self.name}!\n\n🎉 I'm {self.age} years old and passionate about {', '.join(self.interests)}.\n\n💻 My skills include {', '.join(self.skills)}.\n\nLet's connect and build something amazing together!"

# Instantiate Riza
riza = Riza()

# Output Riza's information
print(riza)
```
