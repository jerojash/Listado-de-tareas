<template>
    <div class="bg-scroll" style="background-image: url(https://cdn.pixabay.com/photo/2017/07/01/19/48/background-2462431_960_720.jpg)">

        <TodoList/>
    </div>
        
    
</template>

<script>
import TodoList from './components/TodoList.vue'

export default {
    name: 'app',
    components: {
        TodoList
    } 
}
</script>