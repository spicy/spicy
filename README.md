<!-- <p align="center">
    <img alt="" src=https://img.shields.io/github/stars/spicy?style=for-the-badge&?affiliations=OWNER%2CCOLLABORATOR />
    <img alt="" src=https://komarev.com/ghpvc/?username=spicy&style=for-the-badge />
</p> -->

```python
from typing import NamedTuple, List, Dict

class ContactInfo(NamedTuple):
    email: str
    discord: str

class CodingInfo(NamedTuple):
    specialities: List[str]
    environments: List[str]
    databases: List[str]
    orms: List[str]
    languages: Dict[str, List[str]]

class Attributes:
    
    @staticmethod
    def get_contact_info() -> ContactInfo:
        """
        Returns contact details.
        """
        email = "danieltcurrey@gmail.com"
        discord = "spicy#7453"
        return ContactInfo(email, discord)

    @staticmethod
    def get_coding_info() -> CodingInfo:
        """
        Returns coding details including languages, tools, and specialities.
        """
        languages = {
            'expert': ['c#', 'c++', 'python', 'yaml'],
            'intermediate': ['powershell', 'c', 'typescript', 'java', 'js'],
            'learning': ['asm', 'go']
        }
        specialities = ['unity', 'azure devops', 'fullstack', 'CI/CD']
        environments = ['vs ide', 'vscode', 'pycharm']
        databases = ['MS SQL Server', 'MySQL', 'SQLite', 'Oracle']
        orms = ['EF']

        return CodingInfo(specialities, environments, databases, orms, languages)
```
## Projects
- **Detection** *(Lead Developer - C#, Unity)* - An immersive virtual reality first person shooter where you need to scan your environment.
- **Strafe Analyzer** *(Sole Developer -C++, C#, PHP)* - Real-time statistical overlay for improving video game speedrunning movement.
- **FirstBulletAccuracy** *(Sole Developer - C++, ImGUI)* - Window overlay for real time FPS gameplay monitoring and tips.

<h2 align="center">Skills</h2>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=cs,cpp,python,js,css,html,vscode,c" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/spicy">
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=spicy&show_icons=true&theme=tokyonight&count_private=true" alt="Spicy's GitHub Stats" />
    <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=spicy&theme=tokyonight&layout=compact" 
      alt="Spicy's GitHub Top Languages" />
  </a>
</p>

[youtube]: https://www.youtube.com/channel/UC-22kxkKtKnBZugyPFwl9bw
