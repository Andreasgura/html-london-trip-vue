<template>
    <main>
        <div class="container">
            <div id="jumbotron">
            <img src="../img/pexels-bill-emrich-230794-0.jpg" alt="London">
            <img src="../img/pexels-bill-emrich-230794-1.jpg" alt="London">
            <img src="../img/pexels-bill-emrich-230794-2.jpg" alt="London">
        </div>
        <h2>Le mie spese</h2>
            <table>
                <thead>
                    <tr>
                        <th>Numero</th>
                        <th>Descrizione</th>
                        <th>Costo</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>1</td>
                        <td>Biglietto aereo</td>
                        <td>120€</td>
                    </tr>
                    <tr>
                        <td>1</td>
                        <td>Biglietto aereo</td>
                        <td>120€</td>
                    </tr>
                    <tr>
                        <td>1</td>
                        <td>Biglietto aereo</td>
                        <td>120€</td>
                    </tr>
                </tbody>
                <tfoot>
                    <tr>
                        <td colspan="2">Totale</td>
                        <td>360€</td>
                    </tr>
                </tfoot>
            </table>
       
        </div>
        
    </main>
</template>

<script>
    export default {
        name: "MainComponent"
    }
</script>

<style lang="scss" scoped>

</style>