# Solar theme 

![index](/source/images/Solar.png)

A responsive, dark and simple blog theme for [Hexo](http://hexo.io)

I have made some modifications and improvements on the basis of the author's theme.

- based on theme [solar-theme-hexo](https://github.com/tzvetkov75/solar-theme-hexo) by [tzvetkov75](https://github.com/tzvetkov75)
- based on theme [cactus dark](https://github.com/probberechts/cactus-dark.git) by Pieter Robberechts
- using [Full CSS 3D Solar System](http://codepen.io/waynedunkley/pen/YPJWaz) by Wayne Dunkley

## Summary

- [Solar theme](#solar-theme)
  - [Summary](#summary)
  - [General](#general)
  - [Features](#features)
  - [Demo](#demo)
  - [Install](#install)
  - [Configuration](#configuration)
  - [License](#license)

## General

- **Version** : 0.1
- **Compatibility** : Hexo 3 or later

## Features

- responsive theme with 3D animation in header
- clean and structure optimized for blog

## Demo

- Demo at [Solar](https://kpl0111.github.io/blog)
  
## Install

1. In the `root` directory of Hexo:

```shell
git clone git@github.com:kpl0111/solar.git themes/solar
npm install hexo-pagination --save
```

2. Change the `theme` property in the `config.yml` file (hexo config file).

```shell
theme: solar
```

3. Run: `hexo generate` and `hexo server`

## Configuration

You can customize setting in  `_config.yml` in the theme directory `solar`.

- rotation speed
- images of the planets and sun 
- analytics 
- RSS
- social links 
- code highlight

If you want to change some colors use file `css\_variables.styl`

## License
	MIT
