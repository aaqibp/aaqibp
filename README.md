```python
class Profile:
    def __init__(self):
        self.name = "aaqib"
        self.role = "computer science student | aspiring cloud & infra engineer"
        self.education = {
            "institution": "university of british columbia",
            "degree": "bachelor of computer science",
            "year": "ongoing"
        }
        self.interests = [
            "building",
            "basketball",
            "tech",
        ]
        self.website = "aaqibp.me"

    def __repr__(self):
        return f"<Profile: {self.name}, Role: {self.role}>"

aaqib = Profile()
print(aaqib)
```
