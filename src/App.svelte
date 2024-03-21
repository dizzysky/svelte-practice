<script>
    let name = "dude"; // Modified to use 'dude' as per your new snippet
    let src = "/image.gif"; // Path to your GIF image
</script>

<h1>Hello {name.toUpperCase()}!</h1>
<img {src} alt="{name} dances." />

<p>{@html name}</p>

<style>
    /* Write your CSS here */

    p {
        color: blue;
        font-family: "Futura";
        font-size: 2em;
    }
</style>
