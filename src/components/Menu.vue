<template>
    
    <header>
        <nav>
            <h1>Meu Bairro</h1>
            <ul>
                <li><a href="#">Início</a></li>
                <li><a href="#">Mapa</a></li>
                <li><a href="#">Economia</a></li>
                <li><a href="#"></a></li>
            </ul>
        </nav>
    </header>
</template>

<script>
    export default{
        name: 'Menu'
    }
</script>

<style lang="scss" scoped>
    header{
        width: 100%;
        height: 10vh;
        background-color: #fff;
        padding: 0 10%;
        position: fixed;
        z-index: 99;
        box-shadow: 0px 5px 5px #0000002c;

        nav{
            display: flex;
            justify-content: flex-start;
            align-content: center;
            background-color: transparent;
            width: 100%;
            height: 100%;

            h1{
                display: flex;
                align-items: center;
                padding-right: 30px;
            }

            ul{
                display: flex;
                align-items: center;
                justify-content: center;
                background-color: transparent;
                list-style: none;
              

                li{
                    font-size: 1.2em;
                    padding: 10px;
                    background-color: transparent;

                    a{
                        text-decoration: none;
                        color: #9c9c9c;

                        &::after{
                            content: '';
                            width: 00px;
                            height: 5px;
                            background-color: #444;
                            position: absolute;
                            margin-top: 10px;
                            display: flex;
                            margin-left: 4px;
                            transition: .2s ease-in;
                        }
                        
                        &:hover{
                            color: #444;
                            transition: .2s ease-in;

                            &::after{
                                content: '';
                                width: 30px;
                                height: 5px;
                                background-color: #444;
                                position: absolute;
                                margin-top: 10px;
                                display: flex;
                                margin-left: 4px;
                                transition: .2s ease-in;
                            }
                        }
                        
                    }

                }
            }
        }
    }
</style>