```python
import os

class IlyesDjerfaf:

    def __init__(self):
        self.name = "Ilyes DJERFAF"
        self.location = "Paris"
        self.education = "Data Science Student @ University Paris-Saclay"
        self.occupation = "Apprentice Data Scientist @ Safran Aircraft Engines"
        self.current_focus = "LLMs"
        self.current_projects = ["Code Generation enhanced by Behavior Driven Development"]

    @staticmethod
    def connect():
        return {
            "LinkedIn": "https://www.linkedin.com/in/ilyesdjerfaf",
            "Mail": f"{os.getenv('firstname')}.{os.getenv('lastname')}@universite-paris-saclay.fr"
        }


if __name__ == "__main__":
    print("Contact me:")
    for platform, url in IlyesDjerfaf.connect().items():
        print(f"{platform}: {url}")
```
