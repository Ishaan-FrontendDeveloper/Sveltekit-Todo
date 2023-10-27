<script lang="ts">
	import '../app.postcss';
  import Header from './header.svelte'
  import TodoList from './todolist.svelte'
</script>


 
  <div class="flex font-bold  w-full justify-between">
  <TodoList/>
  <section class="w-full h-screen text-zinc-950">
  <slot/>
  </section>
  </div>
<style>
section{
background-color:#ffb699;
background-image:
radial-gradient(at 20% 86%, hsla(193,73%,77%,1) 0px, transparent 50%),
radial-gradient(at 60% 30%, hsla(111,89%,79%,1) 0px, transparent 50%),
radial-gradient(at 16% 1%, hsla(355,68%,65%,1) 0px, transparent 50%),
radial-gradient(at 34% 52%, hsla(286,66%,66%,1) 0px, transparent 50%),
radial-gradient(at 65% 42%, hsla(354,79%,72%,1) 0px, transparent 50%),
radial-gradient(at 42% 5%, hsla(85,62%,79%,1) 0px, transparent 50%),
radial-gradient(at 19% 65%, hsla(286,77%,63%,1) 0px, transparent 50%);
}
</style>
