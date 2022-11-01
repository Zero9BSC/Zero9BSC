




```python

from dataclasses import dataclass
from typing import Tuple


class Meta(type):
    def __new__(cls, name, bases, attrs):
        new_cls = super().__new__(cls, name, bases, attrs)
        return dataclass(unsafe_hash=True, frozen=True)(new_cls)


class Bio(metaclass=Meta):
    name        : str = "Jones Franco Nicolas"
    designation : str = "Developer"
    company     : str = "coming soon"
    base        : str = "Gaiman, Argentina"
    blog        : str = "coming soon"


class Stack(metaclass=Meta):
    languages   : Tuple[str, ...] = ("Python", "C++", "JavaScript")
    databases   : Tuple[str, ...] = ("coming soon")
    misc        : Tuple[str, ...] = ("coming soon")
    ongoing     : Tuple[str, ...] = ("Django")


class Social(metaclass=Meta):
    linkedin    : str = "https://www.linkedin.com/in/franco-nicolas-jones-266a62162"
    twitter     : str = "nicobscrew"
```







# 📈 Github Statistic 
<div align="center">
  <a href="https://github.com/Zero9BSC">
    <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=Zero9BSC&show_icons=true&theme=algolia&include_all_commits=true&count_private=true&hide_border=true"/>
    <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=reskimulud&layout=compact&langs_count=8&theme=algolia&hide_border=true"/>
  </a>
</div>

<img width="100%" src="https://github-readme-streak-stats.herokuapp.com?user=Zero9BSC&theme=algolia&date_format=M%20j%5B%2C%20Y%5D&hide_border=true">

![Zero9BSC GitHub activity graph](https://activity-graph.herokuapp.com/graph?username=Zero9BSC&hide_border=true&bg_color=050F2C&color=0194DD&line=0194DD&point=2DDD97)

[![trophy](https://github-profile-trophy.vercel.app/?username=Zero9BSC&theme=algolia&no-frame=true&margin-w=10&column=8)](https://github.com/ryo-ma/github-profile-trophy)




