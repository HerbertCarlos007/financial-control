<script>
export default {
    name: 'Form'
}
</script>

<template>
    <div class="container">
        <div class="container-form">
            <div class="content">
                <div class="lef-section">
                    <div class="content-inputs">
                        <label>Descrição</label>
                        <input class="input" type="text">
                    </div>

                    <div class="content-inputs">
                        <label>Valor</label>
                        <input class="input" type="text">
                    </div>
                </div>

                <div class="right-section">
                    <div class="radio-group">
                        <div class="content-radio-group">
                            <input type="radio" />
                            <label>Entrada</label>

                            <input type="radio" />
                            <label>Saida</label>
                        </div>
                    </div>
                    
                   <button class="button-add">ADICIONAR</button>
                </div>
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

.container-form {
    width: 52%;
    height: 70px;
    background-color: #FFF;
    margin-top: 20px;
    border-radius: 8px;
}

.content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 5px 15px;
}

.lef-section {
    display: flex;
    gap: 20px;
}

.content-inputs {
    display: flex;
    flex-direction: column;
}

.input {
    outline: none;
    border-radius: 5px;
    padding: 5px 10px;
    font-size: 15px;
    border: 1px solid #CCC;
    width: 150px ;
}

.right-section {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 60px;
}

.content-radio-group {
    display: flex;
    flex-direction: row;
    gap: 10px;
}

.button-add {
    width: 80px;
    height: 45px;
    background-color: teal;
    color: #FFF;
    border-radius: 8px;
}
</style>