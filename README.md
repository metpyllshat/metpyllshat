## ZDAROVA 👋

```python
class Developer:

    def init(self):
        self.name = "Матюха"
        self.language_spoken = ["ru_RU", "en_US"]
        self.experience_years = 5
        self.skills = ["Python", "Java", "Git","HTML","CSS","MySQL","TensorFlow","Django","FastAPI"]
        self.github_profile = "https://github.com/metpyllshat"

    def say_hi(self):
        print(f"Привет, меня зовут {self.name}!")

    def display_skills(self):
        print("Мои навыки:")
        for skill in self.skills:
            print("- " + skill)


    def print_github_profile(self):
        print("Мой профиль GitHub: " + self.github_profile)


me = SoftwareEngineer()
me.say_hi()
me.display_skills()
me.print_github_profile()
```
