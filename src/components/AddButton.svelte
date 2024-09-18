<script lang="ts">
  export let handleClick;
</script>

<div class="d-grid gap-2 d-md-flex justify-content-md-center">
  <button class="btn btn-primary me-md-2" type="button" on:click={handleClick}>+</button>
</div>