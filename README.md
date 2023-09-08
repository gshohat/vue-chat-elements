# Vue chat elements

![NPM License](https://img.shields.io/npm/l/vue-chat-elements)

**Lightweight** chat components for [Vue](https://vuejs.org/) **< 10k** 😎 <br>

![chat-item](https://github-production-user-asset-6210df.s3.amazonaws.com/91323932/266632052-68a9f5cf-3bf0-42ed-90ca-aa226d6da935.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20230908%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230908T135922Z&X-Amz-Expires=300&X-Amz-Signature=3acc13f864c0ed2521d545e135ff7b9fac3977a198ed31254a525b2dbb4fdab8&X-Amz-SignedHeaders=host&actor_id=91323932&key_id=0&repo_id=685670567)

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
