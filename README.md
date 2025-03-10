
a
# :man_technologist: Hello! I am Jones Franco!

```python

from dataclasses import dataclass
from typing import Tuple


class Meta(type):
    def __new__(cls, name, bases, attrs):
        new_cls = super().__new__(cls, name, bases, attrs)
        return dataclass(unsafe_hash=True, frozen=True)(new_cls)


class Bio(metaclass=Meta):
    name        : str = "Franco Nicolas Jones"
    designation : str = "Full Stack Developer"
    company     : str = "coming soon"
    base        : str = "Dresden, Germany"
    blog        : str = "https://francoj.pythonanywhere.com/"


class Stack(metaclass=Meta):
    languages          : Tuple[str, ...] = ("Python", "C++", "JavaScript")
    version_management : Tuple[str, ...] = ("Git", "GitHub")
    databases          : Tuple[str, ...] = ("Visual Fox", "Sql", "MongoDB")
    misc               : Tuple[str, ...] = ("Django", "Flask", "React", "Vue")
    ongoing            : Tuple[str, ...] = ("AWS", "Unity")


class Social(metaclass=Meta):
    linkedin    : str = "https://www.linkedin.com/in/franco-nicolas-jones-266a62162"
    twitter     : str = "nicobscrew"
```


## 🙋‍♂️ Social
  [![My Portfolio](https://img.shields.io/badge/My%20Portfolio-4285F4?style=for-the-badge&logo=GoogleChrome&logoColor=white)](https://francojones.netlify.app/)&nbsp;
  [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/franco-nicolas-jones-266a62162)&nbsp;
  [![Instagram](https://img.shields.io/badge/Zero9BSC-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://instagram.com/nico_bscrew)&nbsp;
  [![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white)](https://www.facebook.com/nico.jones.330)&nbsp;
  [![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:franconicolasjones@gmail.com)&nbsp;
  [![Twitter](https://img.shields.io/badge/Zero9BSC-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)](https://twitter.com/nicobscrew)&nbsp;
  [![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/542804239246)&nbsp;
  [![Telegram](https://img.shields.io/badge/Telegram-%230088FF.svg?style=for-the-badge&logo=Telegram&logoColor=white)](https://t.me/franco_nicolas_jones)&nbsp;
  
  [![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://cafecito.app/nicobs)


# 📈 Github Statistic 
<div align="center">
  <a href="https://github.com/Zero9BSC">
    <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=Zero9BSC&show_icons=true&theme=algolia&include_all_commits=true&count_private=true&hide_border=true"/>
    <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=Zero9BSC&layout=compact&langs_count=8&theme=algolia&hide_border=true"/>
  </a>
</div>

<img width="100%" src="https://github-readme-streak-stats.herokuapp.com?user=Zero9BSC&theme=algolia&date_format=M%20j%5B%2C%20Y%5D&hide_border=true">

![Zero9BSC GitHub activity graph](https://activity-graph.herokuapp.com/graph?username=Zero9BSC&hide_border=true&bg_color=050F2C&color=0194DD&line=0194DD&point=2DDD97)

[![trophy](https://github-profile-trophy.vercel.app/?username=Zero9BSC&theme=algolia&no-frame=true&margin-w=10&column=8)](https://github.com/ryo-ma/github-profile-trophy)


<img align="right" alt="GIF" height="170px" src="https://media.giphy.com/media/J5B1Y8QZnzXXbLQIBu/giphy.gif" />

### Spotify Playing 🎧

[![Spotify](https://spotify-now-playing.satyu.vercel.app/api/spotify-playing)](https://open.spotify.com/artist/3zw9kN0i8eKIDbGhEiIIwo)


##### Fun fact: I once solved the world's oldest question with a single line of JavaScript
<!-- wi*quL3fcV -->

```javascript
// Which came first: the chicken or the egg?
console.log(['🥚', '🐣', '🐥', '🐔'].sort())

>>> [ '🐔', '🐣', '🐥', '🥚' ]
```
