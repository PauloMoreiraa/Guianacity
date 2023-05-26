<template>
    <div class="teste">
        <div class="efeito"></div>
            <div class="efeito-2">
                <h1>Guaianases</h1>
                <h2>Bairro da Zona Leste de São Paulo</h2>
            </div>
    </div>  
    
</template>

<script>
    export default{
        name: 'Main'
    }
</script>

<style lang="scss" scoped>
    .teste{
        width: 100%;
        height: 70vh;
        background-image: url('https://gujsp.com.br/wp-content/uploads/2019/05/Centro-Guaianases-1024x683.jpg');
        background-size: 400px;
        background-position: top;
        padding-top: 10vh;



        
        .efeito{
            width: 50%;
            height: 100vh;
            position: absolute;
            background-color: #ffff;
            transform: rotate(10deg);
            margin-top: -150px;
            margin-left: -100px;
           
        }
            .efeito-2{
                display: flex;
                flex-direction: column;
                align-items: flex-start;
                justify-content: center;
                width: 40%;
                height: 100%;
                padding-left: 10%;
            }
            
            
            h1{
                font-size: 5em;
                color: #333;
                z-index: 1;
            }
            h2{
                color: #aaaaaa;
                letter-spacing: 1px;
                z-index: 1;
            }
            

      
    }
</style>