<template>
    <footer>
        <ul>
            <li>Federica</li>
            <li>Elisa</li>
            <li>ANdrea</li>
            <li>Adriana</li>
            <li>Francesca</li>
        </ul>
        <ul>
            <li v-for="(todo, index) in listToDo" :key="index">{{todo.where + todo.when + todo.what}}</li>
        </ul>
    </footer>
</template>
<script>
export default {
    name: 'FooterComponent',
    data() {
        return {
            listToDo: [
                {
                    where: London,
                    when: April,
                    what: drink
                },
                {
                    where: London,
                    when: April,
                    what: drink
                },
                {
                    where: London,
                    when: April,
                    what: drink
                }
            ]
        }
    }
}
</script>
<style lang="scss" scoped></style>
