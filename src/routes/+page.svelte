

<div class="container h-full mx-auto flex justify-center items-center">
	<div class="space-y-10 text-center flex flex-col items-center">
		<h2 class="h2">Hello there, I'm Team</h2>
		<h2 class="h3">Hello there, I'm Team</h2>
		<div class="flex justify-center space-x-2">
			
			<!--OldButtons -->
			<!-- <a
				id="button1"
				class="btn rounded variant-filled transition duration-300"
				href="https://portfolio.teammer.xyz"
				target="_blank"
				rel="noreferrer"
			>
				Portfolio
			</a>
			
			<a
			id="btn1"
			class="btn rounded variant-filled transition duration-300"
			href="https://github.com/teammrr"
			target="_blank"
			rel="noreferrer"
			>
			Github
		</a> -->

		<!--NewButtons -->


		
		<a href="https://portfolio.teammer.xyz" class="flex mx-4 xs:mx-0 justify-center items0-center gap-2 px-4 py-2 font-medium transition duration-200 text-gray-900 bg-white border border-gray-200 rounded-lg hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:outline-none focus:ring-gray-200 focus:text-blue-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700 dark:focus:ring-gray-700"><svg class="w-5 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="none" viewBox="0 0 20 20">
			<path stroke="currentColor" stroke-linecap="round" stroke-width="2" d="M1 10c1.5 1.5 5.25 3 9 3s7.5-1.5 9-3m-9-1h.01M2 19h16a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1H2a1 1 0 0 0-1 1v12a1 1 0 0 0 1 1ZM14 5V3a2 2 0 0 0-2-2H8a2 2 0 0 0-2 2v2h8Z"/>
		  </svg>Portfolio</a>
		
		<a href="https://github.com/teammrr" class="flex mx-4 xs:mx-0 justify-center items0-center gap-2 px-4 py-2 font-medium transition duration-200 text-gray-900 bg-white border border-gray-200 rounded-lg hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:outline-none focus:ring-gray-200 focus:text-blue-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700 dark:focus:ring-gray-700"><svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 20 16">
			<path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 4 1 8l4 4m10-8 4 4-4 4M11 1 9 15"/>
		  </svg>Github</a>

		</div>
		
	</div>
</div>

<style lang="postcss">	
	.h3 {
		@apply absolute z-[-1] rounded-full blur-[50px] transition-all;
		animation: pulse 5s cubic-bezier(0, 0, 0, 0.5) infinite,
			glow 5s linear infinite;
	}
	@keyframes glow {
		0% {
			@apply bg-primary-400/50;
		}
		33% {
			@apply bg-secondary-400/50;
		}
		66% {
			@apply bg-tertiary-400/50;
		}
		100% {
			@apply bg-primary-400/50;
		}
	}
	@keyframes pulse {
		50% {
			transform: scale(6);
		}
	}
</style>

<script lang='ts'>

</script>
