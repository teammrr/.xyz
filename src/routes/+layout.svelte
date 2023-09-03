<script lang='ts'>
	// The ordering of these imports is critical to your app working properly
	import '@skeletonlabs/skeleton/themes/theme-skeleton.css';

	import { DarkMode } from 'flowbite-svelte';
	let btnClass = 'transition text-gray-500 dark:text-gray-400 hover:scale-125 hover:bg-gray-100 dark:hover:bg-gray-700 duration-300 rounded-lg text-xl p-2 ';
	
	//Page transition

	// If you have source.organizeImports set to true in VSCode, then it will auto change this ordering
	import '@skeletonlabs/skeleton/styles/skeleton.css';
	// Most of your app wide CSS should be put in this file
	import '../app.postcss';
	import { AppShell, AppBar } from '@skeletonlabs/skeleton';
</script>

<!-- App Shell -->
<AppShell>
	<svelte:fragment slot="header">
	
		<!-- App Bar -->

		<nav class="invisible md:visible  bg-white border-gray-200 absolute shadow-[0_8px_30px_rgb(0,0,0,0.12)] inset-x-2 top-2 rounded-lg dark:bg-transparent ">

			<div class="ax-w-screen flex flex-wrap items-center justify-between mx-auto p-4 ">
			<a href="https://teammer.xyz/" class="flex items-center">
				<img src="https://sv1.picz.in.th/images/2023/08/28/dWi9Wja.png" class="h-11 " alt="Team Logo" />
				<span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white"> </span>
			</a>
			<div class="flex md:order-2">
				<div class="relative hidden md:block">
					<!-- <LightSwitch /> -->
					<DarkMode {btnClass} />
				  </div>
				  <!-- Menu button -->
				  <button
					data-collapse-toggle="navbar-search"
					type="button"
					class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
					aria-controls="navbar-search"
					aria-expanded="false"
				  >
					<span class="sr-only">Open main menu</span>
					<svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
					  <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 1h15M1 7h15M1 13h15"/>
					</svg>
				  </button>
			</div>
			  <div class="items-center justify-between hidden w-full md:flex md:w-auto md:order-1" id="navbar-search">
				<div class="relative mt-3 md:hidden">
				  <div class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none">
					<svg class="w-4 h-4 text-gray-500 dark:text-gray-400" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 20 20">
					  <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m19 19-4-4m0-7A7 7 0 1 1 1 8a7 7 0 0 1 14 0Z"/>
					</svg>
				  </div>
				</div>

			
				<ul class="flex flex-col p-4 md:p-0 mt-4 font-medium border border-gray-100 rounded-lg bg-gray-50 md:flex-row md:space-x-8 md:mt-0 md:border-0 md:bg-white dark:bg-gray-800 md:dark:bg-transparent dark:border-gray-700">
				  <li>
					<a href="/" class="block py-2 pl-3 pr-4 transition 
					duration-100 text-white bg-blue-700 rounded md:bg-transparent md:text-blue-700 md:p-0 md:dark:text-blue-500" aria-current="page">Home</a>
				  </li>
				  <li>
					<a href="/timeline" class="block py-2 pl-3 pr-4 transition 
					duration-100 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Timeline</a>
				  </li>
				  <li>
					<a href="/projects" class="block py-2 pl-3 pr-4 transition 
					duration-100 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Projects</a>
				  </li>
				</ul>
			  </div>
			</div>

	</nav>
		  
		  
		<!-- <div class="fixed top-4 right-6 group" >

		</div> -->

	</svelte:fragment>
	<!-- Page Route Content -->
	<slot />
</AppShell>
