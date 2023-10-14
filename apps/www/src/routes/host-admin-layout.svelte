<script lang="ts">
  import Sidebar from "$lib/registry/default/ui/sidebar.svelte";
  import MainContent from "$lib/registry/default/ui/main-content.svelte";
</script>

<div class="flex">
  <Sidebar>
    <slot name="sidebar"></slot>
  </Sidebar>
  <MainContent>
    <slot name="main-content"></slot>
  </MainContent>
</div>
