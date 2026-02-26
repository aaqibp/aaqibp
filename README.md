```python
class Profile:
    def __init__(self):
        self.name = "aaqib"
        self.role = "computer science student | aspiring full stack & infrastructure engineer"
        self.education = {
            "institution": "university of british columbia",
            "degree": "bachelor of computer science",
            "year": "3rd year"
        }

    def __str__(self):
        return (
            f"name:      {self.name}\n"
            f"role:      {self.role}\n"
            f"school:    {self.education['institution']} — {self.education['degree']} ({self.education['year']})\n"
            f"website:   {self.website}"
        )

aaqib = Profile()
print(aaqib)

```
