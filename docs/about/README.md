# pygame-web.github.io
CDN root used by [pygbag](https://pypi.org/project/pygbag/)

[Github repo](https://github.com/pygame-web/archives)

This software does not track usage at all, even for statistics purpose so if you like it : please do not forget to [star](https://github.com/pygame-web/pygbag/stargazers) it !

___

# [Pygbag packager WIKI](https://pygame-web.github.io/wiki/pygbag/)

#### IMPORTANT: Please do not use .WAV audio format when packaging, pygbag 0.1.5+ will not work.
sfx sound patch need ogg format ( if linux+ffmpeg conversion is automatic, on windows you can use audacity ).

Adapt your code this way if you still want wav format on desktop :
```py
if sys.platform == "emscripten":
    snd = pygame.mixer.Sound("sound.ogg")
else:
    snd = pygame.mixer.Sound("sound.wav") # or .WAV
```
___

## [Coding for WASM](https://pygame-web.github.io/wiki/python-wasm/)

## [Coding with pygbag](https://pygame-web.github.io/wiki/pygbag-code/)

## [Enter Debug mode](https://pygame-web.github.io/wiki/pygbag-debug/)

## [pygame-script](https://pygame-web.github.io/wiki/pygame-script/) (wip!)

### Demos on github pages :

(for testing, may not always work since they use daily/weekly devel version)

##### heavy cpu load not for low-end devices:

[Perfect Rain](https://pmp-p.github.io/pygame-perfect-rain-wasm/)

[Alien Dimension](https://pmp-p.github.io/pygame-alien-dimension-wasm/)

##### Light cpu load :

[Breakout](https://pmp-p.github.io/pygame-breakout-wasm/index.html)

[PyChess](https://pmp-p.github.io/pygame-pychess-wasm/index.html)

[Penguins Can't Fly !](https://pmp-p.github.io/pygame-PenguinsCantFly-wasm/)

### view code from above games and others on github

[[view the code]](https://github.com/pmp-p?tab=repositories&q=pygame-.-wasm&sort=name)

Please ! use the tag [pygame-wasm](https://github.com/topics/pygame-wasm) for your projects hosted on Github
and also add a favicon.png icon 32x32 next to your game main.py, so it is picked up by default.


### Demos on itch.io:

( expected to be stable )

[games on itch.io](https://itch.io/c/2563651/pygame-wasm)


### Early demos ( may not fully work as intended ):

[pygame tech demo PyCon DE & PyData Berlin 2022](https://pmp-p.github.io/pygame-wasm/)

[Galaxy Attack](https://pmp-p.github.io/pygame-galaxy-attack-wasm/)


___

## Technology:

[devlog](https://github.com/pygame/pygame/issues/718)

[Python Wasm explained by core dev Christian Heimes (youtube video)](https://www.youtube.com/watch?v=oa2LllRZUlU)


## current status

[explore current issues](https://github.com/pygame-web/pygbag/issues)

[PyPI stats](https://pepy.tech/project/pygbag)

[pyodide/pyscript](https://github.com/pyodide/pyodide/issues/289#issuecomment-1121021861)


### Thanks for supporting pygame and pygbag. Without support now, there won't be pygame or pygbag later.

[Hello from the pygame community.](https://www.pygame.org/contribute.html)


#### Work in Progress, PR welcomed,  propose links to games or tutorials, please contribute !!!


[edit this page](https://github.com/pygame-web/pygame-web.github.io/edit/main/README.md)

