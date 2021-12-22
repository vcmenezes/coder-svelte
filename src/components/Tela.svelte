<script lang="ts">
    export let valor: string;
</script>

<div class="tela">
    <span>{valor}</span>
</div>

<style>
    .tela {
        display: flex;
        background-color: aliceblue;
        flex: 1;
        justify-content: flex-end;
        align-items: center;
        padding: 0px 5px;
        overflow: hidden;
        font-size: 1.7rem;
        margin: 2px 1px;
        border-top-right-radius: 5px;
        border-top-left-radius: 5px;
    }
</style>
