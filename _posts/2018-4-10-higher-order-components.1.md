---
layout: post
title: "React con Redux, Localstorage y API externa"
date:   2018-04-09
categories: redux store react localstorage thunk
---

Hoy os dejo un pequeño esquema de lo que sería una aplicación escrita en React con Redux, el LocalStorage del navegador y una API externa. Se incluyen las dependencias principales que afectan a dicha estructura y el ciclo en el proceso de hacer una petición a la API (empezando por el punto 1). Antes de realizarla, eso sí, se puede indicar al *store* de Redux que la petición está en marcha (por ejemplo con *isLoading: true* - punto 2.1, siguiendo con el 5). En este último caso, la interactuación entre la app y redux es más es más rápida. La petición en sí sigue el camino que comienza por el punto 2.2.