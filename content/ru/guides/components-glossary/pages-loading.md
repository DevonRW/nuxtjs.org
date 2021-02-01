---
title: 'Свойство loading'
description: Свойство `loading` дает вам возможность отключить прогресс-бар используемый по умолчанию на определенной странице.
menu: Свойство Property
category: components-glossary
---

> Свойство `loading` дает вам возможность отключить прогресс-бар используемый по умолчанию на определенной странице.

- **Тип:** `Boolean` (по умолчанию: `true`)

По умолчанию Nuxt.js использует свой собственный компонент для показа прогресс-бара при переходе между роутами.

Вы можете отключить или настроить его глобально используя [конфигурацию загрузки](/docs/2.x/configuration-glossary/configuration-loading). Также вы можете отключить кастомную загрузку для определенных страниц задав `loading:false` в коде страницы:

```html
<template>
  <h1>My page</h1>
</template>

<script>
  export default {
    loading: false
  }
</script>
```