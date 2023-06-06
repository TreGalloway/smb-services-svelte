<script>
	let src =
		'https://images.unsplash.com/photo-1510627489930-0c1b0bfb6785?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1770&q=80';
	import { Icon, ClipboardDocumentList } from 'svelte-hero-icons';
</script>

<div>
	<div class="">
		<div class=" flex flex-wrap">
			<img
				{src}
				alt="outside of a house"
				class=" rounded-t-lg md:rounded-l-lg md:max-w-md sm:max-w-sm"
				width=""
			/>
			<div class="pl-4">
				<div class="">
					<header class="card-header">
						<h1 class="h1">
							<span
								class="bg-gradient-to-br from-red-500 to-yellow-500 bg-clip-text text-transparent box-decoration-clone"
								>SMB Services For Hire</span
							>
						</h1>
					</header>
					<section class="p-4">The one stop for all your needs</section>
					<footer class="card-footer"><p class=" ">25 Years of Experience</p></footer>
				</div>
				<div class=" pb-4">
					<button type="button" class="btn variant-filled">
						<span> <Icon src={ClipboardDocumentList} size="25" /> </span>
						<span>Get Your Quote!</span>
					</button>
				</div>
			</div>
		</div>
	</div>
</div>
