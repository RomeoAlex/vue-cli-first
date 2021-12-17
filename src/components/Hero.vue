<template>
    <div class="Jumbotron">
        <button>
            Applicazione CLIVUE
        </button>
    </div>
  
</template>

<script>
// oggetto
export default {
  name: "Hero",

};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
*{
    margin: 0;
    padding:0;
    box-sizing: border-box;
}
.Jumbotron{
    background-image: url(../assets/aliens-fireteam-elite-1276397-1280x0-min.jpeg);
    background-repeat: no-repeat;
    background-size: cover;
    width:100%;
    height: 1000px;
}

</style>