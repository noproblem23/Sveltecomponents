<script lang="ts">
  import { Spinner } from 'sveltestrap';
  const colors = [
    'primary',
    'secondary',
    'success',
    'danger',
    'warning',
    'info',
    'light',
    'dark'
  ];
</script>

<div>
  {#each colors as color}
    <Spinner {color} type="border" class="m-1" />
  {/each}
</div>

<div>
  {#each colors as color}
    <Spinner {color} type="grow" class="m-1" />
  {/each}
</div>
