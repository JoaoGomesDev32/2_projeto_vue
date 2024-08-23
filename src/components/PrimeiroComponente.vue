<template>
    <div>
        <h1>Olá Vue!</h1>
        <p>O meu nome é {{ name }} e trabalho como {{ profissao }}!</p>
        <MultiplosEventos />
        <Reutilizacao />
    </div>
</template>

<script>
    import MultiplosEventos from './MultiplosEventos.vue'
    import Reutilizacao from './Reutilizacao.vue';

    export default {
        name: 'PrimeiroComponente',
        components: {
            MultiplosEventos,
            Reutilizacao
        },
        data() {
            return {
                name: 'João',
                profissao: 'Programador'
            }
        }
    }
</script>