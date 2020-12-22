<!--DE HER SIDER SKAL SGU DA IKKE VÆRE VIEWS!!1 DE SKAL DA INJECTES! -->


<template>
  <div class="hello">
    <h1 class="helloh1">Hvor får?</h1>
    <p class=hellop1>
    Et lille spil hvor det gælder om at klikke på alle fårene inden tiden løber ud.
    </p>

    

    <p class=hellop2>Kendte fejl i version 1: Musikken og lydeffekter er lidt ujævne og sporadiske. Der er kun en bane. :(</p>
    <p class=hellop3>Værktøjer:HTML, CSS, JavaScript</p>
    

    <a class="helloa" href="https://wheresheepgamevers1.netlify.app/"><button class="hitMe">Prøv det!</button></a>
   
  </div>

  
</template>

<script>
export default {
  name: 'Wheresheep',
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.hello {
display: grid;
grid-template-columns: 1fr 1fr 1fr 1fr 1fr ;
font-size: 2em;

}

.helloh1{
grid-column:1/6;
grid-row:1/3;
}

.hellop1{
grid-column:1/6;
grid-row:3/4;
}

.hellop2{
grid-column:1/6;
grid-row:4/5;
justify-self: center;
}

.hellop3{
grid-column:1/6;
grid-row:5/6;
justify-self: center;
}

.helloa{
grid-column:1/6;
grid-row:6/8;
justify-self: center;
}


h3 {
  margin: 40px 0 0;
}


.button {

border: solid red 2px;
}

.hitMe{

margin: 0.5em;
    padding: 0.5em;
    background: #decf2b;
    width: 150px;
    height: 150px;
    border: 2px solid #1661a7;
    border-radius: 20%;
    color: #0c3963;
    font-family: "Quicksand", sans-serif;
    font-size: 1em;
    font-weight: 700;
    letter-spacing: 0.02em;
    line-height: 1;
    text-decoration: none;
    text-transform: uppercase;
    cursor: pointer;
    transition: 0.3s;
    outline: none;

}

 
</style>
