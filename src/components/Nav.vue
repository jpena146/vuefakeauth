<template>
<div class = "bg-purple-800 text-purple-200">
    <div class = "container mx-auto flex items-center justify-between ">
        <h1 class="tracking-tighter text-3xl font-thin">Vue<span class="font-normal">FakeAuth</span>
        </h1>

        <nav>
            <ul class = "flex space-x-4">
                <router-link to ="/"><li class="py-8 px-4 hover:cursor-pointer hover:bg-purple-500 hover:text-purple-800">Home
                </li> </router-link>
                <router-link to ="/about">
                <li class="py-8 px-4 hover:cursor-pointer hover:bg-purple-500 hover:text-purple-800">About
                </li></router-link>
                <router-link to ="/hello">
                <li class="py-8 px-4 hover:cursor-pointer hover:bg-purple-500 hover:text-purple-800">Hello</li></router-link>
                
            </ul>
        </nav>
    </div>
</div>
</template>