```python
class Vivaan(Person):

    def __init__(self) -> None:
        self.age = 16
        self.pronouns = ("he", "him")  
        self.nationality = "Indian"
        self.citizenship = "American"

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
                "Decent": ["Python", "Java", "Javascript"],
                "Learning": ["C", "C++", "C#"]
            }
        }

    @property
    def contact(self) -> dict[str, list[str]]:
        return {
            "Email": ["vivaansinghvi8@gmail.com", "singhvi.vivaan@gmail.com"]
        }

    @property
    def favorite_projects(self, key: str) -> dict[str, tuple(str)]: 
        return {
            "MandelPlot": (
                "Creates beautiful, interactive graphs of the Mandelbrot Set", 
                "https://vivaansinghvi07.github.io/mandelplot"
            ),
            "Pynterface": (
                "Useful tools for terminal input-output",
                "https://github.com/vivaansinghvi07/pynterface"
            ),
            "KenKen Solver": (
                "My first image processing project, which solves a KenKen puzzle",
                "https://github.com/vivaansinghvi07/kenken-solver"
            ),
            "Statistics Website": (
                "Website catered towards AP Statistics, with all units except for the last one",
                "https://vivaans-statistics-site.000webhostapp.com/index.php"
            ),
            "Stock Predictor": (
                "My attempt at creating a simple machine learning model to predict stock activity",
                "https://github.com/vivaansinghvi07/stock-predictor"
            ),
            "Rocket League Custom Quickchats": (
                "Macros for custom chats in my favorite game Rocket League",
                "https://github.com/vivaansinghvi07/rocket-league-custom-quickchats"
            )
            ...
        }
```
