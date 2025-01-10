```python
import os

class IlyesDjerfaf:

    def __init__(self):
        self.name = "Ilyes DJERFAF"
        self.location = "Paris"
        self.education = "MSc Data Science Student @ University Paris-Saclay"
        self.occupation = "Apprentice Data Scientist @ Safran Aircraft Engines"
        self.current_projects = ["Behavioral Segmentation for Intelligent Email Crafting"]

    @staticmethod
    def connect():
        return {
            "LinkedIn": "https://www.linkedin.com/in/ilyesdjerfaf",
            "Mail": f"{os.getenv('firstname')}.{os.getenv('lastname')}@etu-upsaclay.fr"
        }


if __name__ == "__main__":
    print("Contact me:")
    for platform, url in IlyesDjerfaf.connect().items():
        print(f"{platform}: {url}")
```
