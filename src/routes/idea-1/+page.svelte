<script lang="ts">
    import type { PageData } from './$types';
    export let data: PageData;
</script>
<div class="flex flex-row h-full font-artifakt ">
    <div class="hero bg-white ">
        <div class="hero-content flex-col lg:flex-row-reverse">
          <div class="card flex-shrink-0 max-w-[66rem] shadow-sm rounded-md border bg-white border-gray-200">
            <div class="card-body ">
                <div class="flex flex-row space-x-6">
                    <h1 class="text-black font-bold flex-1">Project Information Summary</h1>
                    <button class="flex flex-row align-middle">
                        <svg width="18px" height="18px" class="py-auto self-center " viewBox="0 0 24 24" stroke-width="1.5" fill="none" xmlns="http://www.w3.org/2000/svg" color="#000000"><path d="M14.363 5.652l1.48-1.48a2 2 0 012.829 0l1.414 1.414a2 2 0 010 2.828l-1.48 1.48m-4.243-4.242l-9.616 9.615a2 2 0 00-.578 1.238l-.242 2.74a1 1 0 001.084 1.085l2.74-.242a2 2 0 001.24-.578l9.615-9.616m-4.243-4.242l4.243 4.242" stroke="#000000" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></path></svg>
                        <h1 class="text-center">Edit</h1>
                    </button>
    
                </div>
                <div class="divider my-0"></div>
                <div class="flex flex-wrap">
                    <div class="w-80 px-2">
                        <label class="label" for="">
                            <span class="label-text">Project Name</span>
                        </label>
                        <input type="text" readonly placeholder="Mercedes-Benz Stadium" class="input input-bordered w-full">
                    </div>
                    <div class="w-80 px-2">
                        <label class="label" for="">
                            <span class="label-text">Project Number</span>
                        </label>
                        <input type="text" readonly placeholder="21-00000-00" class="input input-bordered w-full">
                    </div>
                </div>
                </div>
            </div>
        </div>
    </div>
    <div class="absolute z-10 w-96 border-gray-200 border-l pt-6 px-4 translate-x-full overflow-auto h-full bg-white right-0">
        <h1 class="text-xl">Menu</h1>
    </div> 
</div>
