<script>
    let name = "dude"; // Modified to use 'dude' as per your new snippet
    let src = "/image.gif"; // Path to your GIF image
    let count = 0;
    $: doubled = count * 2;
    function increment() {
        count += 1;
    }
</script>

<h1>Hello {name.toUpperCase()}!</h1>
<img {src} alt="{name} dances." />

<p>{@html name}</p>

<button>
    Clicked {count}
    {count === 1 ? "time" : "times"}
</button>
<p>{count} doubled is {doubled}</p>

<style>
    /* Write your CSS here */

    p {
        color: blue;
        font-family: "Futura";
        font-size: 2em;
    }
</style>
