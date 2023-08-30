<script>
export default {
    name: 'Resume',
}
</script>

<template>
    <div class="container">
        <div class="content">
            <div class="card-resume">Entradas</div>
            <div class="card-resume">Saidas</div>
            <div class="card-resume">Total</div>
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
    width: 60%;
    display: flex;
    justify-content: space-around;
    gap: 20px;
}

.card-resume {
    width: 40%;
    height: 120px;
    background-color: #FFF;
    margin-top: -50px;
    border-radius: 8px;
}
</style>