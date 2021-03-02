<template>
<div class="grid-container">

        <div class="item1">
            <img alt="user avatar" src="../assets/user-avatar_opt.jpg" id="userAvatar">
            <p>Luis</p>
        </div>
        <div class="item2">
            <input type="text" placeholder="Buscar o empezar un nuevo chat">
        </div>
        <div class="item3">
            <img alt="user avatar" src="../assets/user-avatar_opt.jpg" id="userAvatar">
            <p>Fulanito</p>
        </div>
        <div class="item4">
            <img alt="user avatar" src="../assets/user-avatar_opt.jpg" id="userAvatar">
            <p>P1_Coders</p>
        </div>
        <div class="item5">
            <img alt="user avatar" src="../assets/user-avatar_opt.jpg" id="userAvatar">
            <p>Menganito</p>
        </div>
        <div class="item6">
            <img alt="user avatar" src="../assets/user-avatar_opt.jpg" id="userAvatar">
            <h3>Fulanito</h3>
        </div>
        <div class="item7">
            <p>Hola</p>
            <p>No quiero saber de ti</p>
        </div>
        <div class="item8">
            <input type="text" placeholder="Escribe aquí">
        </div>

</div>

  
</template>

<script>
export default {
    name: "Home"
}
</script>

<style scoped>

.item1 { 
    grid-area: user; 
    align-content:center;
    border: black;
    
}
.item2 { grid-area: search; }
.item3 { grid-area: contact1; }
.item4 { grid-area: group; }
.item5 { grid-area: contact2; }
.item6 { grid-area: userconver; }
.item7 { grid-area: conver; }
.item8 { grid-area: writer; }

.grid-container {
  display: grid;
  grid-template-areas:
    'user user userconver userconver userconver userconver'
    'search search conver conver conver conver'
    'contact1 contact1 conver conver conver conver'
    'group group conver conver conver conver'
    'contact2 contact2 writer writer writer writer';
  grid-gap: 10px;
  padding: 10px;
}


</style>