<script>
    let username = ""
    let password = ""
</script>

<div class=" bg-stone-600 "> 
    <input placeholder="type Username here" type="text" bind:value={username}>
    <input placeholder="type Password here" type="text" bind:value={password}>
    {#if (username === "EW" && password === "GROSS")}
        <a href="./main">Go To Main Page</a>
    {/if}
</div>