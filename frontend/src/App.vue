<script setup lang="ts">
import ChatBox from "./components/ChatBox.vue";
import ChatInput from "./components/ChatInput.vue";
import Conversations from "./components/Conversations.vue";
import Search from "./components/Search.vue";
import UserInfo from "./components/UserInfo.vue";
</script>

<template>
  <div class="container">
    <div id="sidebar-container">
      <Search />
      <Conversations />
    </div>
    <div id="chat-container">
      <UserInfo />
      <ChatBox />
      <ChatInput />
    </div>
  </div>
</template>

<style scoped>
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

#sidebar-container {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  width: 20%;
  height: 80%;
  border-style: dotted;
  border-width: 3px;
  border-color: #ff72f6;
}

#sidebar-container > * {
  border-style: solid;
  border-width: 2px;
  border-color: #ff00ee;
}

#chat-container {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  width: 40%;
  height: 80%;
  border-style: dotted;
  border-width: 3px;
  border-color: #74ff86;
}

#chat-container > * {
  border-style: solid;
  border-width: 2px;
  border-color: #00ff22;
}
</style>
