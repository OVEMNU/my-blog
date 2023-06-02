---
sidebar_position: 1
---

# Instrucciones

Docusaurus crea una página **para cada publicación de blog.**

## Crear tu primer blog post

Crea un archivo en `blog/2021-02-28-hola-mundo.md`:

```md title="blog/2021-02-28-hola-mundo.md"
---
slug: hola
title: Hola Mundo
authors:
  - name: Juan Penas
    title: Co-editor de Tirando Codigo
    url: https://github.com/JuanPenas
    image_url: https://github.com/JoelMarcey.png
  - name: Sébastien Lorber
    title: Docusaurus maintainer
    url: https://sebastienlorber.com
    image_url: https://github.com/slorber.png
tags: [greetings]
---

Felicidades, ya hiciste tu primer blog post!
```

## Notas Importantes

:::info

Recuerda que el titulo de tu articulo utilizado en `title` es el titulo que se vera reflejado en el arbol de navegacion:

```md title="hola-mundo-post.md"
---
title: Hola Mundo
---
```

:::

:::caution Info

No olvides agregar tus datos en el archivo `blog/authors.yml` esto se requiere para hacer la relacion de autor en tu articulo.

```authors.yml"
---
juan:
  name: Juan Penas
  title: Editor de Tirando Codigo
  url: https://juanpenas.com
  image_url: https://github.com/juan.png
---
```
:::

## Inicia tu sitio

Ejecuta el server de desarrollo:

```bash
cd my-website
npm run start
```

El comando `cd` cambia el directorio con el que está trabajando. Para trabajar con su sitio de Docusaurus recién creado, deberá navegar por la terminal allí.

El comando `npm run start` command construye su sitio web localmente y lo sirve a través de un servidor de desarrollo, listo para que lo vea en http://localhost:3000/.

Abre `docs/intro.md` (esta página) y editar algunas líneas: el sitio **recarga automaticamente** y muestra tus cambios.
