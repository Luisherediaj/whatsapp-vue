<template>
<div class="grid-container">

        <div class="item1">
            <img alt="user avatar" src="../assets/user-avatar_opt.jpg" id="userAvatar">
            <p>Luis</p>
        </div>
        <div class="item2">
            <input type="text" placeholder="Buscar o empezar un nuevo chat" class="texto1">
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
            <input type="text" placeholder="Escribe aquí" class="texto2">
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
    display: flex;
    align-items: center;
    justify-content: space-around;
    background-color: rgb(197, 197, 197);
}
.item2 { 
    grid-area: search; 
    display: flex;
    align-items: center;
    background-color: rgb(240, 240, 240);
    padding-left: 0.5rem;
}
.texto1{
    border-radius: 40px;
    width: 18rem;
    height: 1.8rem;
}
.item3 { 
    grid-area: contact1; 
    display: flex;
    align-items: center;
    justify-content: space-around;
    background-color: white;
}
.item4 { 
    grid-area: group; 
    display: flex;
    align-items: center;
    justify-content: space-around;
    background-color: white;
}
.item5 { 
    grid-area: contact2; 
    display: flex;
    align-items: center;
    justify-content: space-around;
    background-color: white;
}
.item6 { 
    grid-area: userconver; 
    display: flex;
    align-items: center;
    justify-content: space-around;
    background-color: rgb(197, 197, 197);
}
.item7 { 
    grid-area: conver; 
    background-image: url(../assets/whatsapp-background.jpg);
}
.item8 { 
    grid-area: writer; 
    display: flex;
    align-items: center;
    background-color: rgb(240, 240, 240);
    padding-left:7rem;
    padding-right: 1rem;
}

.texto2{
    border-radius: 40px;
    width: 45rem;
    height: 5rem;
}

.grid-container {
  display: grid;
  grid-template-areas:
    'user userconver userconver userconver'
    'search conver conver conver'
    'contact1 conver conver conver'
    'group conver conver conver'
    'contact2 writer writer writer';
    grid-template-columns: 20rem 50rem;
  grid-template-rows: 4rem 2.5rem 6rem 6rem 6rem;
  margin-bottom: 10rem;
}

div{
    border: gray 1px solid;
}

</style>