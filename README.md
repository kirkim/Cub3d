# Cub3d

2021.04 ~ 2021.07

Cub3d is my favorite project in 42Seoul.

## Goal

Make virtual 3D environment using raycasting like <a href="https://fr.wikipedia.org/wiki/Wolfenstein_3D" target="blank">Wolfenstein 3D</a>

<img src="https://kirkim.github.io/assets/storage/cub3d/cub3d2.gif" alt="playing cub3d">

## How to run

```shell
git clone git@github.com:kirkim/Cub3d.git
cd Cub3d
```

you can make two kinds of cub3d `basic` & `bonus`

- basic

```shell
make
```

```shell
./cub3d ./map/test.cub
```

- bonus

```shell
make bonus
```

```shell
./cub3d ./map/test_bonus.cub
```

## raycasting controls

- `w, a, s, d`: move key.
- `←, ↑, →, ↓`: eyesight move key.
- `1`: open door key.
- `2`: close door key.
- `3`: turn on mouse mode.
- `4`: turn off mouse mode.
