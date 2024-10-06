```python
class AboutMe:
    def __init__(self):
        self.name = "Gabrielle"
        self.profession = "Data Science Student"
        self.skills = {
            "languages": ["Python"],
            "areas_of_interest": ["Data Science", "AI", "Trend Research", "Behavior Analysis"]
        }

        self.goals = ["Collaborate on open-source projects", "Find an internship"]

    def hobbies(self):
        return ["Music (drummer)", "Watching movies and TV shows", "Reading (fiction and comics)"]

    def future_plans(self):
        return "Expand skills in data science and AI, and contribute to impactful projects."

    def __str__(self):
        return f"My name is {self.name}, and I'm a {self.profession}. I am currently working on: {self.current_projects}. My goals are: {', '.join(self.goals)}."

if __name__ == "__main__":
    me = AboutMe()
    print(me)
    print(f"My hobbies include: {', '.join(me.hobbies())}")
    print(f"Skills: {me.skills['languages']}")
    print(f"Areas of Interest: {', '.join(me.skills['areas_of_interest'])}")
    print(f"Future plans: {me.future_plans()}")
