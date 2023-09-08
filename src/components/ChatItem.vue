<script setup>

const props = defineProps(['options']);

const propDate = props.options.date;
const formattedDate = formatDate(propDate);

function formatDate(date) {
  let month = date.getUTCMonth() + 1;
  let day = date.getUTCDate();
  let year = date.getUTCFullYear();
  return `${day}/${month}/${year}`;
}

</script>

<template>
  <div class="message-item">
    <div class="avatar-container">
      <img class="avatar"
          :src="props.options.avatar"
          alt="avatar"
      />
    </div>
    <div class="text-message">
      <div class="upper-row">
        <span class="title">{{props.options.title}}</span>
        <span class="time">{{formattedDate}}</span>
      </div>
      <div class="subtitle">{{props.options.subtitle}}</div>
    </div>
  </div>

</template>


<style scoped>
.message-item {
  display: flex;
  padding: 1rem;
  gap: 1rem;
}

.avatar-container {
  flex: 1;
}

.avatar {
  border-radius: 50%;
  padding: 0.2rem;
}

.text-message {
  flex: 4;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
}

.upper-row {
  display: flex;
  justify-content: space-between;
}

.title {
  text-overflow: ellipsis;
  white-space: nowrap;
  overflow: hidden;
  flex: 3;
  font-weight: bold;
  font-size: 1.2rem;
  color: #ffffffe8;
}

.time {
  flex: 1;
}

.subtitle {
  text-overflow: ellipsis;
  white-space: nowrap;
  overflow: hidden;
}
</style>
