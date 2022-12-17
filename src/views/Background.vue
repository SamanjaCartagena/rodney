
    <template>
      <div class="container">
        <div class="videos">
        <the-videos></the-videos>
        </div>
      </div>
    </template>
    
    <script>
        import TheVideos from '../components/TheVideos.vue'
    export default {
        components:{
            TheVideos
        }
    
    }
    </script>
    
    <style scoped>
    .container{
        background-image: url(../assets/resurrection.jpg);
        background-repeat: no-repeat;
        background-size:100%;
        height:900px;
        width:100%;
    }
    body{
        padding:0;
        margin:0;
    }
   .videos{
    position: relative;
    top:700px;
   }
    </style>