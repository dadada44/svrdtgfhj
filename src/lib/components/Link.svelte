<script>
    let {href, color, children} = $props(); // Deklarujeme atributy, které zadávame při volání komponenty
    // $props() - je reaktivní funkce, která zajišťuje funkce atributu (tím že něco do nich napíšu, se hned projeví)
</script>

<a href="{href}" class="button {color}">
    {@render children()} <!-- Vypisuje content mezi element -->
</a>

<style>
    .button{
        width: 50px;
        background-color: red;
    }

    .ghost{
        color: white;
    }

    .green{
        color: green;
    }
</style>