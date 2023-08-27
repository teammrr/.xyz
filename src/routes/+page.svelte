<div class="container h-full mx-auto flex justify-center items-center">
	<div class="space-y-10 text-center flex flex-col items-center">
		<h2 class="h2">Hello there, I'm Team👋🏻.</h2>
		<!-- <h2 class="h3">Hello there, I'm Team👋🏻.</h2> -->
		<div class="flex justify-center space-x-2">
			<!-- Button1 -->
			<a
				id="button1"
				class="btn variant-filled"
				href="https://portfolio.teammer.xyz"
				target="_blank"
				rel="noreferrer"
			>
				Portfolio
			</a>
			<a
			id="btn1"
			class="btn variant-filled"
			href="https://portfolio.teammer.xyz"
			target="_blank"
			rel="noreferrer"
		>
			Portfolio
			
		</a>
			<!-- Button 2 -->
			<!-- <a
			id="button1"
			class="btn variant-filled"
			href="https://portfolio.teammer.xyz"
			target="_blank"
			rel="noreferrer"
			>
				Portfolio
			</a>
			<a
			id="btn2"
			class="btn variant-filled"
			href="https://portfolio.teammer.xyz"
			target="_blank"
			rel="noreferrer"
			>
				Portfolio
			</a>		 -->
		</div>
	</div>
</div>

<style lang="postcss">
	#btn1 {
		@apply absolute z-[-1] rounded-full blur-[50px] transition-all;
		animation: pulse 5s cubic-bezier(0, 0, 0, 0.5) infinite,
			glow 5s linear infinite;
	}
	#btn2 {
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
			transform: scale(1.5);
		}
	}
</style>
