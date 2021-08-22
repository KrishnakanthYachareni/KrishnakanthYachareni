<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.java.com" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank"> <img src="https://icon-library.com/images/node-js-icon/node-js-icon-19.jpg" alt="nodejs" width="60" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> 
<a href="https://oracleplsql.ru/contents-oracle-plsql.html" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="oraclesql" width="60" height="50"/> </a>


![Krishnakanth's github stats](https://github-readme-stats.vercel.app/api?username=KrishnakanthYachareni&count_private=true&show_icons=true)

<a href="https://krishnakanthyachareni.github.io/personal-website/">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=KrishnakanthYachareni&repo=personal-website" />
</a>
<a href="https://github.com/KrishnakanthYachareni/Gayle-Laakmann-McDowell">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=KrishnakanthYachareni&repo=Gayle-Laakmann-McDowell" />
</a>

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
    blog        : str = "https://krishnakanthyachareni.github.io/personal-website/"


class Stack(metaclass=Meta):
    languages   : Tuple[str, ...] = ("Java", "Python", "Javascript", "Shell")
    databases   : Tuple[str, ...] = ("MySQL", "PostgreSQL", "Oracle", "NoSQL")
    misc        : Tuple[str, ...] = ("Docker", "Kubernet")
    ongoing     : Tuple[str, ...] = ("Spring", "React")


class Social(metaclass=Meta): 
    twitter     : str = "yacharenikrish"
    linkedin    : str = "yacharenikrishnakanth"
````
