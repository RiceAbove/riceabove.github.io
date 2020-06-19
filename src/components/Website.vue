<template>
    <div class="shell">
        <p>$ ssh gicocarlo.me</p>
        <p class="name">
            Hi! I’m Gico Carlo Evangelista! 
        </p>
        <p>
            I'm a 4th year Computer Science undergraduate studying at UC Santa Cruz.
            I love tech, and creating cool projects that I can share
            with everyone! I'm also really into food, video games, and streetwear.
        </p>
        <p>
            I have experience in full stack web development, and am currently working
            towards self teaching myself mobile development, IoT's, and much more! If
            you would like to see my work, or to just get to know me more, please
            check out the links below!
        </p>
        <p>
            Last updated: 6/18/2020
        </p>
        <p>
            $ ls
        </p>
        <p>
            <a href="Resume.pdf">Resume </a>
            <a href="">Projects </a>
            <a href="https://github.com/RiceAbove" target="_blank">GitHub </a> 
            <a href="https://www.linkedin.com/in/gico/" target="_blank">LinkedIn </a>
            <a href="https://twitter.com/RiceAbove" target="_blank">Twitter </a>
            <a href="https://www.youtube.com/user/xXMeLikeRiceXx" target="_blank">YouTube </a>
            <a href="mailto:evangelistagico@pm.me">Email </a>
        </p>
        <p>$</p>
    </div>
</template>

<script>
export default {
    name: "Website"
}
</script>

<style scoped>
    p {
        padding-bottom: 2%;
    }

    a {
        color: white;
    }

    .shell{
        font-size: 125%;
    }

    .blink{
        white-space: nowrap;
        overflow: hidden;
    }

    .name {
        text-align: center;
    }
</style>