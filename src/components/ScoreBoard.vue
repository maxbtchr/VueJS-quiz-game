<!-- eslint-disable prettier/prettier -->
<template>
    <div>
        <section class="score"> Player <span>{{this.winCount}}</span> x <span>{{this.loseCount}}</span> Computer </section>
    </div>
</template>
<!-- eslint-disable prettier/prettier -->

<script>
export default {
    props: ['winCount', 'loseCount']
};
</script>
<!-- eslint-disable prettier/prettier -->
<style lang="scss">
section.score {
    border-bottom: 1px solid black;
    padding: 24px;
    font-size: 18px;
    span {
        padding: 8px;
        font-weight: bold;
        border: 1px solid black;
    }
}


</style>
