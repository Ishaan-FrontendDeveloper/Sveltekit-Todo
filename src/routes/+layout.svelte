<script lang="ts">
	import '../app.postcss';
  import {AppShell} from '@skeletonlabs/skeleton'
  import Header from './header.svelte'
  import TodoList from './todolist.svelte'
</script>


<AppShell class="text-black font-bold flex justify-between">
  <svelte:fragment slot="header"><Header/></svelte:fragment>
  <div class="flex w-full justify-between">
  <TodoList/>
  <slot/>
  </div>
</AppShell>

