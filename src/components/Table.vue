<script>
import '@fortawesome/fontawesome-free/css/all.css'
import '@fortawesome/fontawesome-free/js/all.js'

export default {
    name: 'Table',
}
</script>

<template>
    <div class="container">
        <div class="content">
            <div class="columns">
                <span class="columns-name">Descrição</span>
                <span class="columns-name">Valor</span>
                <span class="columns-name">Tipo</span>
                
            </div>
            <div class="line"></div>

            <div class="Rows">
                <span class="rows-name">Salário</span>
                <span class="rows-name">1500</span>
                <i class="fas fa-arrow-up  rows-name" style="color: #44ff00;"></i>
                <i class="fa-solid fa-trash icon-trash"></i>
            </div>
            
            <div class="Rows">
                <span class="rows-name">Alimentação</span>
                <span class="rows-name">300</span>
                <i class="fas fa-arrow-down rows-name" style="color: #e60a0a;"></i>
                <i class="fa-solid fa-trash icon-trash"></i>
            </div>
            
        </div>
    </div>
</template>

<style scoped>
.container {
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.content {
    width: 52%;
    background-color: #FFF;
    margin-top: 20px;
}

.columns {
    width: 80%;
    display: flex;
    justify-content: space-between;
    margin: 15px 20px;
    align-items: center;
}


.line {
    width: 95%;
    height: 1px;
    background-color: #CCC;
    margin-left: 20px;
}

.Rows {
    width: 80%;
    display: flex;
    justify-content: space-between;
    margin: 15px 20px;
    align-items: center;
}

.columns-name {
    width: 20px;
}

.rows-name {
    width: 20px;
}

.icon-trash {
    position: absolute;
    right: 27%;
}
</style>