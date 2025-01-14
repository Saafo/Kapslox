# Kapslox

Implementation of `Capslox` default configurations on `Karabiner`, only tested well on macOS.

# Introduction

This repository contains Implementation of Capslox default configurations on Karabiner and my other karabiner configurations, which includes:

## Kapslox.json

Import URL:

```
karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/Saafo/Kapslox/main/Kapslox.json
```

This configuration implemented default configurations that `Capslox` provides, which empowers your `CAPS LOCKS` key, and includes:

* `Caps + e / s / d / f` as `arrow up / left / down /right`
* `Caps + a / f` as `cmd + left / right` (move the cursor to the beginning or ending of the line)
* `Caps + w / r` as `delete / fn + delete` (delete the char before or after the cursor)
* `Caps + q / t` as `cmd + delete / cmd + fn + delete` ( delete all of chars before or after the cursor)
* `Caps + i / j / k / l` as `shift + arrow up / left / down / right` (select chars up / left / down / right)

This implementation differs from others by using `fn` as the hyper key instead of common `cmd + opt + shift + control`, which is inspired by this [article](https://joey.blue/2021/04/08/Karabiner-Elements-%E4%B9%8B-%E4%BB%8B%E7%BB%8D%E5%92%8C%E4%BD%BF%E7%94%A8%EF%BC%88part-1%EF%BC%89/).

One of the main good point of using `fn` as hyper key is that you can passthough `opt` or `shift` or `cmd` when using `Caps`, e.g. you can use `Caps + opt + e` as `opt + arrow up`, or `Caps + cmd + d` as `cmd + arrow down`. Besides, you can press `Caps` with `f1-f12` directly because pressing `Caps` means pressing `fn`.

## DarkMode.json

Import URL:

```
karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/Saafo/Kapslox/main/DarkMode.json
```

This configuration allows you to simply press `F6` to toggle Dark Mode. I chose `F6` because there is a moon on it.

## NumberPad.json

Import URL:

```
karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/Saafo/Kapslox/main/NumberPad.json
```

This configuration allows you to using number pad inside the alphabet area of you keyboard, here's how to use:

1. Press and hold Spacebar
2. Press:

&ensp; w e r &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;7 8 9

a s d f &ensp; equals to &ensp; . 4 5 6

z x c v &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;0 1 2 3

This configuration works well with `Kapslox`.

## NumberKeyPad.json

Import URL:

```
karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/Saafo/Kapslox/main/NumberKeyPad.json
```

This configuration allows you to using number pad inside the alphabet area of you keyboard, here's how to use:

1. Press and hold Spacebar
2. Press:

&ensp; w e r &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;7 8 9

a s d f &ensp; equals to &ensp; . 4 5 6

z x c v &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp; &ensp;0 1 2 3

This configuration works well with `Kapslox`. It differs from `NumberPad.json` by using `keypad_n` instread of `n`.

## LaunchApps.json

Import URL

```
karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/Saafo/Kapslox/main/LaunchApps.json
```

This configuration allows you to Launch Apps quickly using ``Caps + ` / 1 / 2 / 3`` or etc. to launch different apps. You can customize it easily.
