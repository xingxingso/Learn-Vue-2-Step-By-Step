[TOC]

# [Learn Vue 2: Step By Step](https://laracasts.com/series/learn-vue-2-step-by-step)

> Vue is easily one of the most exciting additions to the front-end world in many years. With its intuitive API, and the fact that it can be applied to any type of application, it's no wonder why folks have gravitated to it as much as they have.

> If you'd like to jump on board, let me show you, step by step, exactly what you need to know. It's the best way to learn Vue!

## Episodes

### 01. [Basic Data Binding](https://laracasts.com/series/learn-vue-2-step-by-step/episodes/1)

> Let's begin with a review of basic data binding in Vue. You'll get your first glimpse into the framework's wonderful, and automatic, reactivity.

#### Note

```html
<body>
    <div id="root">
        <input type="text" id="input" v-model="message">
        <p>the content if the input is {{message}}</p>
    </div>

    <script src="https://unpkg.com/vue@2.6.8/dist/vue.js"></script>

    <script>
        // let data = {
        //     message: 'Hello World'
        // }

        // document.querySelector('#input').value = data.message;

        new Vue({
            el: "#root",
            // data: data
            data: {
                message: 'Hello World'
            }
        });
    </script>
</body>
```

#### Reference

- [Installation — Vue.js](https://vuejs.org/v2/guide/installation.html)

## References Collection

- [Vue.js](https://vuejs.org/)

### Type

- [title](url)

## Examples

### Type
