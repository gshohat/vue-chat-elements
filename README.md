# Vue chat elements

![NPM License](https://img.shields.io/npm/l/vue-chat-elements)

**Lightweight** chat components for [Vue](https://vuejs.org/) **< 5k** 😎 <br>

## Usage

`npm i vue-chat-elements`

```
<script setup>
import {ChatItem} from 'vue-chat-elements';
import 'vue-chat-elements/dist/style.css';

const options = {
  avatar: 'https://www.npmjs.com/npm-avatar/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJhdmF0YXJVUkwiOiJodHRwczovL3MuZ3JhdmF0YXIuY29tL2F2YXRhci8xNWY0ZTdjMmRjZDc4OWE3ODgwNGMxMzI1ZDYzNGFjNz9zaXplPTUwJmRlZmF1bHQ9cmV0cm8ifQ.LqE0E5FHjTCs7vIgY8T1XDWgMIT8OVgkos8ZcSMP8oU',
  title: 'Gilad',
  date: new Date(),
  subtitle: 'Hello npm, first message',
};
</script>


<template>
<ChatItem class="message-item" :options="options"></ChatItem>
</template
```


## Contact
Feel free to ping me 💫
<br>
connect@giladshohat.com

[giladshohat.com](https://giladshohat.com)
