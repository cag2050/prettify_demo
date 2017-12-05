<template>
<div>
    <pre class='prettyprint lang-sql linenums'>
        select * from user
        select * from user11111
        select * from user
        select * from user2222
        select * from user
        select * from user
        select * from user33
        select * from user
        select * from user
        select * from user
        select * from user
        select * from user
        select * from user
        where uid = 1;
    </pre>
</div>
</template>

<script>
let PR = window.PR

export default {
    name: '',
    data () {
        return {
        }
    },
    created () {
        console.log(PR)
    }
}
</script>

<style>

</style>
