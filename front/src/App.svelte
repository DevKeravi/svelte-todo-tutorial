
<script lang='ts'>
  import Todos from './components/Todos.svelte'
  type TODO_TYPE = {id: number, name : string, completed: boolean};
    const todos : Array<TODO_TYPE> = [
    { id: 1, name: "Create a Svelte starter app", completed: true },
    { id: 2, name: "Create your first component", completed: true },
    { id: 3, name: "Complete the rest of the tutorial", completed: false }
    ]
</script>

<Todos {todos}/>