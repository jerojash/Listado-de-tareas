<template>
   
   
    <div class="container mx-auto px-4 py-20 flex flex-col flex-wrap">
        
        <h1 class="font-hairline text-6xl text-center text-white-500">List of Task</h1>

        <todo-card class=" bg-gray-200 mx-auto mt-4 h-120 w-full max-w-lg">
            <h1 class="font-hairline text-3xl text-center text-black-500">Task</h1>
            
        
                <div class="text-center">

                <h1>First Activity
                <button style="margin: 10px" class="  bg-red-500 hover:bg-red-400 text-white font-bold py-1 px-1 border-b-4 border-red-700 hover:border-blue-500 rounded">
                    Delete
                    
              
                </button>
            

                <button class=" bg-blue-500 hover:bg-blue-400 text-white font-bold py-1 px-1 border-b-4 border-blue-700 hover:border-blue-500 rounded">
                    Edit
                </button>
                    <input  style="margin: 10px" type="checkbox" name="" id="">
                    <form action="../../form-result.php" target="_blank">

                       <p>
 
                        Realized Hours:
                    
                    <select name="opcion">

                           <option>Two Hours</option>
                           <option>Four Hours</option>
                           <option>Eight Hours</option>
                           <option>Ten Hours</option>
 
                        </select>

                       </p>

                     </form>
                </h1>
                </div>
            
    

                  
                  <hr>            
                 <div class="text-center">
                <h1>Second Activity
               
                <button style="margin: 10px" class="  bg-red-500 hover:bg-red-400 text-white font-bold py-1 px-1 border-b-4 border-red-700 hover:border-blue-500 rounded">
                    Delete
                </button>
            

                <button class=" bg-blue-500 hover:bg-blue-400 text-white font-bold py-1 px-1 border-b-4 border-blue-700 hover:border-blue-500 rounded">
                    Edit
                </button>
                    <input style="margin: 10px" type="checkbox" name="" id="">
                    <form action="../../form-result.php" target="_blank">

                       <p>
 
                        Realized Hours:
                    
                    <select name="opcion">

                           <option>Two Hours</option>
                           <option>Four Hours</option>
                           <option>Eight Hours</option>
                           <option>Ten Hours</option>
 
                        </select>

                       </p>

                     </form>
                </h1>
                </div>
            
            
                <hr>
                <div class="text-center">
                <h1>Third Activity
               
                <button style="margin: 10px" class="  bg-red-500 hover:bg-red-400 text-white font-bold py-1 px-1 border-b-4 border-red-700 hover:border-blue-500 rounded">
                    Delete
                </button>
            

                <button class=" bg-blue-500 hover:bg-blue-400 text-white font-bold py-1 px-1 border-b-4 border-blue-700 hover:border-blue-500 rounded">
                    Edit
                </button>
                    <input style="margin: 10px" type="checkbox" name="" id="">
                    <form action="../../form-result.php" target="_blank">
                      
                       <p>
 
                        Realized Hours:
                    
                    <select name="opcion">

                          <option>Two Hours</option>
                           <option>Four Hours</option>
                           <option>Eight Hours</option>
                           <option>Ten Hours</option>
 
                        </select>

                       </p>

                     </form>
                </h1>
                  </div>
            
        </todo-card>
        <todo-card class=" bg-gray-200 mx-auto mt-10 w-full max-w-lg">
            <h1 class="font-hairline text-3xl text-center text-black-500">Create a task
            </h1>
                <hr>
            <div class="text-center">
              <p>Name of task: <input type="text" name="nombre" required></p>
                  <hr>
                <p> Estimaded Hours:
                   
                    <select name="opcion">

                           <option>Two Hours</option>
                           <option>Four Hours</option>
                           <option>Six Hours</option>
                           <option>Eight Hours</option>
 
                        </select>
                </p>                  
             <hr>    
            </div>
             
              <div class="text-center">


             <button class=" bg-blue-500 hover:bg-blue-400 text-white font-bold py-1 px-1 border-b-4 border-blue-700 hover:border-blue-500 rounded ">
                    Accept
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