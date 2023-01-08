<script setup lang="ts">

defineProps<{}>()

</script>

<template>
  <div class="container">
    <div class="profile-picture">
        <img src="https://via.placeholder.com/40/000000/808080?Text=ProfilePicture" />
    </div>
    <div class="description">
        <div class="title">TITLE</div>
        <div class="detailList">
            <div class="detail">
                <div class="title">TITLE 11</div>
                <div class="description">DETAIL 12</div>
            </div>
        </div>
    </div>
  </div>
</template>

<style scoped>
.container {
    display: flex;
    justify-content: space-around;
    align-items: center;
    gap: 1em;
    padding: 1em;
}

.profile-picture {
    display: flex;
    width: 25%;
}

.description {
    display: flex;
    flex-direction: column;
    width: 75%;
    gap: 1em;
}

.detailList {
    display: flex;
}

</style>
