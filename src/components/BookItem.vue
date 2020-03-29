<script>
export default {
    name: 'BookItem',
    props: 'book'
}
</script>

<template>
<li>{{ book.title }}: {{ book.author }}
</template>

<style>
li {
    display: block;
    margin: 0 10px;
}
</style>