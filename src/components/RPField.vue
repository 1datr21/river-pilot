<template>
    <table>
        <tr v-for="r in rows" :key="r" height="20">
            <td v-for="c in cols" :key="c" width="20"></td>

        </tr>
    </table>
</template>

<script>


const F_ORIENTATION = {Vertical : 1, Horizontal : 2};

class Fishka {
    
}


export default ({
    setup() {
        
    },
    data() {
        return {
            Fishkas : [],
            rows: 10,
            cols: 10
        };
    }
})
</script>

<style scoped>
</style>
