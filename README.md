```python
class Vivaan(Person):
    def __init__(self) -> None:
        self.age = 16
        self.pronouns = ("he", "him")  
        self.nationality = "Indian"
        self.citizenship = "American"

    @property 
    def hobbies(self) -> list[str]:
        return ["programming", "working out", "biking", "gaming", "drumming"]

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

    def projects(self, key: str) -> dict[str, str] | str: 
        if key == "Websites":
            return {
                "MandelPlot":               "https://vivaansinghvi07.github.io/mandelplot/",
                "AP Statistics Website":    "https://vivaans-statistics-site.000webhostapp.com/index.php",
                "Connect Four":             "https://vivaansinghvi07.github.io/connect-four/",
                "Get Javascript":           "https://vivaansinghvi07.github.io/get-javascript/",
                "Aim Lab":                  "https://vivaansinghvi07.github.io/aim-trainer/",
                "Wordle Cheater":           "https://vivaansinghvi07.github.io/wordle-cheater/"
            }
        elif key == "Packages":
            return {
                "UniSci":                   "https://pypi.org/project/unisci/",
                "Pynterface":               "https://pypi.org/project/pynterface/"
            }
        elif key == "Math":
            return { 
                "Rotation":                 "https://github.com/vivaansinghvi07/rotation",
                "Fractal Graphs":           "https://github.com/vivaansinghvi07/fractal-points",
                "Mandelbrot GIFs":          "https://github.com/vivaansinghvi07/mandelbrot-gifs",
                "Misiurewicz Points":       "https://github.com/vivaansinghvi07/misiurewicz-points",
                "Riemann Sums":             "https://github.com/vivaansinghvi07/riemann-sums"
            }
        elif key == "Machine Learning":
            return {
                "Cancer Prediction":        "https://github.com/vivaansinghvi07/cancer-prediction"
                "Stock Prediction":         "https://github.com/vivaansinghvi07/stock-predictor",
                "AI Text Detection":        "https://github.com/vivaansinghvi07/ai-text-detection"
            }
        elif key == "Research and Data Analytics":
            return {
                "GMO Scientific Consensus": "https://github.com/vivaansinghvi07/gmo-scientific-consensus",
                "Income on SAT Scores":     "https://github.com/vivaansinghvi07/income-vs-sat-scores"
            }
        elif key == "Algorithms":
            return {
                "Encryption":               "https://github.com/vivaansinghvi07/encryption",
                "Sudoku Solver":            "https://github.com/vivaansinghvi07/sudoku-solver",
                "Reaction Balancer":        "https://github.com/vivaansinghvi07/chemical-equation-balancer",
                "Tic Tac Toe Bot":          "https://github.com/vivaansinghvi07/tic-tac-toe",
                "Checkers Bot":             "https://github.com/vivaansinghvi07/checkers-bot",
            }
        elif key == "Terminal Games":
            return {
                "Typing Test":              "https://github.com/vivaansinghvi07/typing-test",
                "Wordle":                   "https://github.com/vivaansinghvi07/wordle",
                "Minesweeper":              "https://github.com/vivaansinghvi07/minesweeper",
                "Tower of Hanoi":           "https://github.com/vivaansinghvi07/tower-of-hanoi",
                "Chess":                    "https://github.com/vivaansinghvi07/chess",
                "Tower of Hanoi v2":        "https://github.com/vivaansinghvi07/tower-of-hanoi-v2",
                "Hangman":                  "https://github.com/vivaansinghvi07/hangman"
            }
        else: 
            return "Other projects not listed here!"

```