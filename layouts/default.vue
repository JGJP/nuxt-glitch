<template lang="pug">

.layout

    header
        h1 header
        nuxt-link(to="/") home page
        nuxt-link(to="/about/") about page

    nuxt

    footer
        h1 footer

</template>

<style>

/*.page-leave-active {
    transition: opacity .1s ease-out, transform .1s ease-out;
}
.page-enter-active {
    transition: opacity .3s ease-out, transform .3s ease-out;
}

.page-leave-active {
    opacity: 0;
    transform: translateY(.3em);
}

.page-enter {
    opacity: 0;
    transform: translateY(.5em);
}*/

header {
    background: blue;
    height: 10em;
    color: white;
}

header a {
    padding: 1em;
}

main {
    background: yellow;
    height: 20em;
}

footer {
    background: red;
    height: 10em;
    color: white;
}

</style>
