<template>
    <div class="container mx-auto px-4 py-20 flex flex-col flex-wrap">
        <h1 class="font-hairline text-6xl text-center text-gray-500">List of Task</h1>

        <todo-card class="mx-auto mt-4 h-64 w-full max-w-lg">
            <h1 class="font-hairline text-center text-gray-500">Task</h1>
            <div class="flex mb-4">
            <div class="w-3/2 bg-gray-500 h-12">
                <h1>Primera Tarea
                <button class="  bg-blue-500 hover:bg-blue-400 text-white font-bold py-2 px-4 border-b-4 border-blue-700 hover:border-blue-500 rounded">
                    Delete
                </button>
                <div class="text-right"></div>
                <button class=" bg-blue-500 hover:bg-blue-400 text-white font-bold py-2 px-4 border-b-4 border-blue-700 hover:border-blue-500 rounded">
                    Edit
                </button>
                    <input type="checkbox" name="" id="">
                </h1>
            </div>
            </div>
        </todo-card>
        <todo-card class="mx-auto mt-10 w-full max-w-lg">
            <div class="text-center">
                <input class="appearance-none bg-transparent border-none w-full text-gray-700 mr-3 py-1 px-2 leading-tight focus:outline-none" type="text" placeholder="Escribir tarea" aria-label="Full name">
                <button class=" text-left bg-blue-500 hover:bg-blue-400 text-white font-bold py-2 px-4 border-b-4 border-blue-700 hover:border-blue-500 rounded">
                    Submit
                </button>                    
            </div>
        </todo-card>
    </div>
</template>

<script>
export default {
    props: {

    },

    data () {
        return {
            tasks: [
                {
                    id: 1,
                    title: 'Example task',
                    done: false
                }
            ]
        };
    },

    mounted () {

    },

    methods: {

    }
}
</script>