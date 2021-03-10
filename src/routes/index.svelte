<script>
    import Header from "$components/Header.svelte"
    import Nav from "$components/Nav.svelte"
    import Footer from '$components/Footer.svelte'  
</script>

<Nav />
<Header />

<main>
    <h1>Cats</h1>
    <p>llllllllll
        ;lkdgojeuoghgjndlkfg
        djgoirfdmhutgjrnfldm
        uthwrgfjndso6iklrtklgad
        i3tjlaghnvu8otklgiouetrtound
    </p>

    <p>
        giervjktur,vjunguiagd
        igurfjoitfkaleehugros
        rkehabureifjndkegrhgrjgrek
        ghreia
    </p>
</main>

<Footer />
<style>
header { grid-area: h; }
nav    { grid-area: n; }
main   { grid-area: m; }

  body {
    display: grid;
    grid: "h    h    h  " auto 
          "m    m    m  " auto
          "nr    n    n  " auto
          /1fr  1fr  1fr;
  }
</style>