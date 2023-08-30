<script>
import '@fortawesome/fontawesome-free/css/all.css'
import '@fortawesome/fontawesome-free/js/all.js'

export default {
    name: 'Resume',
}
</script>

<template>
    <div class="container">
        <div class="content">
            <div class="card-resume">
                <div class="card-resume-title">
                    <span>Entradas</span>
                    <div class='icon'>
                        <i class="fas fa-arrow-up"></i>
                    </div>
                </div>
                <div class="card-resume-values">
                    <span>R$ 1000</span>
                </div>
            </div>

            <div class="card-resume">
                <div class="card-resume-title">
                    <span>Entradas</span>
                    <div class='icon'>
                        <i class="fas fa-arrow-down"></i>
                    </div>
                </div>
                <div class="card-resume-values">
                    <span>R$ 1000</span>
                </div>
            </div>

            <div class="card-resume">
                <div class="card-resume-title">
                    <span>Entradas</span>
                    <div class='icon'>
                        <i class="fa-solid fa-dollar-sign"></i>
                    </div>
                </div>
                <div class="card-resume-values">
                    <span>R$ 1000</span>
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

.content {
    width: 52%;
    display: flex;
    justify-content: space-around;
    gap: 20px;
}

.card-resume {
    width: 50%;
    height: 120px;
    background-color: #FFF;
    margin-top: -50px;
    border-radius: 8px;
}

.card-resume-title {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    height: 60%;
}

.card-resume-values {
    display: flex;
    justify-content: center;
    align-items: center;
}

.icon {
    width: 20px;
    border: 1px solid black;
    border-radius: 20px;
    padding: 2px;
    text-align: center;
}
</style>