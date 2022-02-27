<template>
<div class = "bg-yellow-800 text-yellow-200">
    <div class = "container mx-auto flex items-center justify-between ">
        <h1 class="tracking-tighter text-3xl font-thin">Basic<span class="font-normal">Router</span>
        </h1>

        <nav>
            <ul class = "flex space-x-4">
                <router-link to ="/"><li class="py-8 px-4 hover:cursor-pointer hover:bg-yellow-500 hover:text-yellow-800">Home
                </li> </router-link>
                <router-link to ="/about">
                <li class="py-8 px-4 hover:cursor-pointer hover:bg-yellow-500 hover:text-yellow-800">About
                </li></router-link>
                <router-link to ="/hello">
                <li class="py-8 px-4 hover:cursor-pointer hover:bg-yellow-500 hover:text-yellow-800">Hello</li></router-link>
                
            </ul>
        </nav>
    </div>
</div>
</template>