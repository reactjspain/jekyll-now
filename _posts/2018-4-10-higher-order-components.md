---
layout: post
title: "Higher-Order Components"
date:   2018-04-10
categories: react hoc higher order components share code
---

Después de descubrir y ver esta gran [charla](https://youtu.be/BcVAq3YFiuc) de [Michael Jackson](https://github.com/mjackson) sobre las ventajas e inconvenientes de utilizar los Higher-Order Components (HOC) de React, os comparto más abajo el código de prueba que he realizado y un breve resumen de lo que más me ha ayudado sobre la primera parte del vídeo. Ésta se centra en explicar lo que es un HOC, además de mostrar las ventajas de los mismos frente a los deprecated *mixins*.

El objetivo principal de todo esto: ***evitar repetir código*** y poder ***compartirlo*** de manera sencilla.

Este tipo de conferencias sí que merecen la pena. Bien explicado, al grano y sin olor a postureo.

![Higher-Order Components](../images/higher-order-components.png)

Es necesario decir que publicaré otro artículo sobre la segunda parte del mismo. En él se mostrarán las desventajas de los HOC y la solución definitiva frente a ellas: las ***Render Props***.

Vamos!

## Referencias

* [Never Write Another HoC](https://youtu.be/BcVAq3YFiuc)
* [Use a render prop!](https://cdb.reacttraining.com/use-a-render-prop-50de598f11ce)