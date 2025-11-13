# Releasing Carneiro

```shell
cldfbench download cldfbench_carneiro4.py
```

```shell
cldfbench makecldf cldfbench_carneiro4.py --with-cldfreadme --glottolog-version v5.2
pytest
```

```shell
cldfbench cldfviz.map cldf --pacific-centered --format png --width 20 --output map.png --with-ocean --no-legend
```

```shell
cldferd --format compact.svg cldf > erd.svg
```

```shell
cldfbench readme cldfbench_carneiro4.py
cldfbench zenodo --communities dplace cldfbench_carneiro4.py
dplace check cldfbench_carneiro4.py
```

```shell
git status
git tag
```

```shell
dplace release cldfbench_carneiro4.py vX.Y
```
