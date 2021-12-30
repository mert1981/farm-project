<template>
  <div id="nav" class="h-screen flex-col justify-between rounded-md" >
    
     <div class=" h-full ">
        <div class="flex pt-6 justify-center">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Apple_logo_grey.svg/800px-Apple_logo_grey.svg.png" alt="">
            </div>
                <div class="pt-6">

                    <h1 class="text-2xl font-bold text-gray-800">Özçiftlik</h1>
                        <span class="text-m block text-gray-800">Tarladan...</span>
                </div>
                <div class="pt-24">
                <ul class="space-y-8 pt-10 ">
                    <li class="flex space-x-4 items-center hover:bg-white  cursor-pointer">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12" fill="none" viewBox="0 0 24 24"
                            stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4" />
                        </svg>
                        <a href="" >
                            Settings
                            </a>
                    </li>
                    <li class="flex space-x-4 items-center hover:bg-white cursor-pointer">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12" fill="none" viewBox="0 0 24 24"
                            stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4" />
                        </svg>
                        <a href="">Settings</a>
                    </li>
                    
                    
                    <li class="flex space-x-4 items-center  hover:bg-white cursor-pointer">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12" fill="none" viewBox="0 0 24 24"
                            stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4" />
                        </svg>
                        <a href="">Settings</a>
                    </li>
                </ul>
            </div>
         
        </div> 
        
        <div class="flex items-center space-x-4 pb-0 hover:bg-white cursor-pointer">
		<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
			<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
				d="M17 16l4-4m0 0l-4-4m4 4H7m6 4v1a3 3 0 01-3 3H6a3 3 0 01-3-3V7a3 3 0 013-3h4a3 3 0 013 3v1" />
		</svg>
		<a href="/loguot">Logout</a>
	</div>
      


  </div>
   
</template>
<script>
export default {
  name: "side-bar",
};
</script>
