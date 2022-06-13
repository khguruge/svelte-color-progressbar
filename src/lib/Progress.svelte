<script>
  export let progress = 50;
  export let color = "blue";

  if (progress > 100) {
    progress = 100;
  } else if (progress <= 0) {
    progress = 0;
  }
</script>

<main>
  <div class="outer" style=" border: 1px solid {color};">
    <div class="inner" style="width : {progress}%; background : {color}" />
  </div>
</main>

<style>
  .inner,
  .outer {
    height: 40px;
    border-radius: 30px;
  }

  .outer {
    width: 100%;
    background: transparent;
  }
</style>
