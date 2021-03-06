# vue scrollup menu

> Directive using vue js to show the menu when the user scrolls up and hide when scrolling down using pure javascript

## Example

![ezgif com-crop](https://user-images.githubusercontent.com/23389358/51559769-f6a63d80-1e69-11e9-8769-c2960bfc9f2b.gif)

### Online demo

https://wemboava.github.io/vue-scrollup-menu

## Getting Started

### install
``` npm i vue-scrollup-menu ```

### Use

```vue
<template>
    <header v-vue-scrollup-menu class="header"></header>    
</template>
```

### Import directive

```vue
<script>
    import vueScrollupMenu from 'vue-scrollup-menu'

    export default {
        name: 'Header',

        directives: {
            vueScrollupMenu
        },
    }
</script>
```

##### Or use directive globally

```javascript
import Vue from 'vue'
import vueScrollupMenu from 'vue-scrollup-menu'

Vue.directive('vue-scrollup-menu', vueScrollupMenu)
```

