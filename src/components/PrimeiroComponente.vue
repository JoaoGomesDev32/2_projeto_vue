<template>
    <div>
        <h1>Olá Vue!</h1>
        <p>O meu nome é {{ name }} e trabalho como {{ profissao }}!</p>
        <MultiplosEventos />
    </div>
</template>

<script>
    import MultiplosEventos from './MultiplosEventos.vue'

    export default {
        name: 'PrimeiroComponente',
        components: {
            MultiplosEventos
        },
        data() {
            return {
                name: 'João',
                profissao: 'Programador'
            }
        }
    }
</script>