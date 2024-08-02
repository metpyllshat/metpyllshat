## Hi there 👋

<!--
**metpyllshat/metpyllshat** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
```python
class SoftwareEngineer:

    def init(self):
        self.name = "Матвей Шаталов"
        self.language_spoken = ["ru_RU", "en_US"]
        self.experience_years = 5
        self.skills = ["Python", "Java", "Git"]
        self.github_profile = "https://github.com/yourusername"

    def say_hi(self):
        print("Привет, я " + self.name + "!")

    def display_skills(self):
        print("Мои навыки:")
        for skill in self.skills:
            print("- " + skill)

    def update_experience(self, years):
        self.experience_years += years
        print("Опыт работы обновлен. Теперь у меня " + str(self.experience_years) + " лет опыта.")

    def print_github_profile(self):
        print("Мой профиль GitHub: " + self.github_profile)


me = SoftwareEngineer()
me.say_hi()
me.display_skills()
me.update_experience(1)
me.print_github_profile()
```
