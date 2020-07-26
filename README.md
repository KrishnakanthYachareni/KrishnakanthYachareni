<!--
**KrishnakanthYachareni/KrishnakanthYachareni** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
### Coding Profile:
- [HackerRank](https://www.hackerrank.com/yacharenikrish?hr_r=1) | Points: 201668 
- [InterviewBit](https://www.interviewbit.com/profile/yacharenikrish) | Points: 7038
- [Codechef](https://www.codechef.com/users/yacharenikrish) | Rating: 1516
- [Codeforces](https://codeforces.com/profile/yacharenikrish) | Rating: 824
- [Spoj](https://www.spoj.com/users/yacharenikrish/) | Points: 0.3

### Professional Profile:
````python
from dataclasses import dataclass
from typing import Tuple

class Meta(type):
    def __new__(cls, name, bases, attrs):
        new_cls = super().__new__(cls, name, bases, attrs)
        return dataclass(unsafe_hash=True, frozen=True)(new_cls)


class Bio(metaclass=Meta):
    name        : str = "Krishnakanth Yachareni"
    designation : str = "Software Engineer"
    company     : str = "EPAM System Pvt Ltd"
    base        : str = "Hyderabad, India"
    blog        : str = "https://sites.google.com/site/krishnakanthychareni/home"


class Stack(metaclass=Meta):
    languages   : Tuple[str, ...] = ("Java", "Python", "Javascript", "Shell")
    databases   : Tuple[str, ...] = ("MySQL", "PostgreSQL", "Oracle", "NoSQL")
    misc        : Tuple[str, ...] = ("Docker", "Kubernet")
    ongoing     : Tuple[str, ...] = ("Spring", "React")


class Social(metaclass=Meta): 
    twitter     : str = "yacharenikrish"
    linkedin    : str = "yacharenikrishnakanth"
````
