<template>
   
   
    <div class="container mx-auto px-4 py-20 flex flex-col flex-wrap">
        
        <h1 class="font-hairline text-6xl text-center text-gray-500">List of Task</h1>

        <todo-card class=" bg-gray-200 mx-auto mt-4 h-120 w-full max-w-lg">
            <h1 class="font-hairline text-3xl text-center text-black-500">Task</h1>
            
        
                <div class="text-center">

                <h1>First Activity
                <button style="margin: 10px" class="  bg-red-500 hover:bg-red-400 text-white font-bold py-2 px-4 border-b-4 border-red-700 hover:border-blue-500 rounded">
                    Delete
              
                </button>
            

                <button class=" bg-blue-500 hover:bg-blue-400 text-white font-bold py-2 px-4 border-b-4 border-blue-700 hover:border-blue-500 rounded">
                    Edit
                </button>
                    <input  style="margin: 10px" type="checkbox" name="" id="">
                </h1>
                </div>
            
    

                  
                  <hr>            
                 <div class="text-center">
                <h1>Second Activity
               
                <button style="margin: 10px" class="  bg-red-500 hover:bg-red-400 text-white font-bold py-2 px-4 border-b-4 border-red-700 hover:border-blue-500 rounded">
                    Delete
                </button>
            

                <button class=" bg-blue-500 hover:bg-blue-400 text-white font-bold py-2 px-4 border-b-4 border-blue-700 hover:border-blue-500 rounded">
                    Edit
                </button>
                    <input style="margin: 10px" type="checkbox" name="" id="">
                </h1>
                </div>
            
            
                <hr>
                <div class="text-center">
                <h1>Third Activity
               
                <button style="margin: 10px" class="  bg-red-500 hover:bg-red-400 text-white font-bold py-2 px-4 border-b-4 border-red-700 hover:border-blue-500 rounded">
                    Delete
                </button>
            

                <button class=" bg-blue-500 hover:bg-blue-400 text-white font-bold py-2 px-4 border-b-4 border-blue-700 hover:border-blue-500 rounded">
                    Edit
                </button>
                    <input style="margin: 10px" type="checkbox" name="" id="">
                </h1>
                  </div>
            
        </todo-card>
        <todo-card class=" bg-blue-100 mx-auto mt-10 w-full max-w-lg">
            <div class="text-center">
                <input class="bg-white focus:outline-none focus:shadow-outline border border-gray-300 rounded-lg py-2 px-4 block w-full appearance-none leading-normal" type="email" placeholder="Write a task...">
            <br>
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