<script>
    export let numero; //Exportamos la variable numero para poder llamarla en app.svelte
    let resultado;     //Variable local
    if (numero===0)
        resultado="neutro";
    else
        if (numero%2===0)
            resultado="par";
        else
            resultado="impar";
</script>
<!-- Las Variables las llamamos entre llaves -->
<p>El número {numero} es {resultado} </p>
<style>
    p{
        color: rgb(34, 5, 112);
        font-family: 'segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        font-size: 25px;
    }
</style>