```python
class Vivaan(Person):

    def __init__(self) -> None:
        super().__init__(age=16, pronouns=('he', 'him'), nationality="Indian", citizenship="American")

    @property
    def website(self) -> str:
        return "https://vivaansinghvi07.github.io"

    @property 
    def hobbies(self) -> list[str]:
        return ["Programming", "Working Out", "Biking", "Gaming", "Drumming"]

    @property
    def languages(self) -> dict[str, dict[str, list[str]]]:
        return {
            "Real Life": {
                "Fluent": ["English", "Hindi"],
                "Learning": ["German"]
            },
            "Programming": { 
                "Decent": ["Python", "JavaScript"],
                "Amateur": ["C", "C++", "C#", "Shell", "Java", "TypeScript"]
            }
        }

    @property
    def contact(self) -> dict[str, list[str]]:
        return {
            "Email": ["singhvi.vivaan@gmail.com", "vsinghvi@umich.edu"]
        }
```
