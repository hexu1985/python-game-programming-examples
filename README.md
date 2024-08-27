## Python 数学编程 随书示例代码

- [Python游戏编程快速上手](Invent.Your.Own.Computer.Games.With.Python)
- [Python游戏编程入门](More.Python.Programming.For.The.Absolute.Beginner)
- [Python和Pygame游戏开发指南](Making.Games.With.Python.And.Pygame)

### 安装开发测试环境

**conda方式**

```
$ conda create -n game --clone base
$ conda activate game
$ pip install pygame
Collecting pygame
  Downloading pygame-2.6.0-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (12 kB)
Downloading pygame-2.6.0-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (14.0 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 14.0/14.0 MB 762.4 kB/s eta 0:00:00
Installing collected packages: pygame
Successfully installed pygame-2.6.0
$ python
Python 3.12.4 | packaged by Anaconda, Inc. | (main, Jun 18 2024, 15:12:24) [GCC 11.2.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import pygame
pygame 2.6.0 (SDL 2.28.4, Python 3.12.4)
Hello from the pygame community. https://www.pygame.org/contribute.html
>>>
$
```

---

**venv方式**

```
$ python3 -m venv venv_game
$ source venv_game/bin/activate
$ pip install pygame
$ python3
Python 3.12.3 (main, Jul 31 2024, 17:43:48) [GCC 13.2.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import pygame
pygame 2.6.0 (SDL 2.28.4, Python 3.12.3)
Hello from the pygame community. https://www.pygame.org/contribute.html
>>>
$
```
