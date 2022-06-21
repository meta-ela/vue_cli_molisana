<template>
    <div>
        <!--  creare una cartella img in public  -->
        <!-- senza slash quindi img/la_molisana-logo.png diventa un percorso relativo -->
        <!-- usare sempre slash quindi /img/la_molisana..ecc -->
        <img src="/img/la-molisana-logo.png" alt="logo la molisana">
    </div>
</template>

<script>
export default {
    // buona norma aggiungere chiave name: "stesso nome del file"
    name: "TheHeader",
}
</script>

<style>

</style>