<script>
	import {
		Icon,
		WrenchScrewdriver,
		HomeModern,
		Cake,
		CheckCircle,
		ArrowLongRight
	} from 'svelte-hero-icons';
</script>

<div class="pt-10">
	<h2 class="h2">Our Services</h2>
	<div class="grid grid-cols-1 md:grid-cols-3 md:gap-16">
		<div class="card my-8">
			<div class="card">
				<header class="card-header">
					<div class="flex">
						<Icon src={WrenchScrewdriver} size="30" />
						<h2 class="h2 pl-6">Home Repair</h2>
					</div>
				</header>
				<section class="p-4">
					<ol class="list">
						<li>
							<span> <Icon src={CheckCircle} size="20" /> </span>
							<span class="flex-auto">Plumbing </span>
						</li>
						<li>
							<span> <Icon src={CheckCircle} size="20" /> </span>
							<span class="flex-auto"> Electrical </span>
						</li>
						<li>
							<span> <Icon src={CheckCircle} size="20" /> </span>
							<span class="flex-auto"> Carpenting </span>
						</li>
					</ol>
				</section>
				<footer class="card-footer">
					<div class="flex justify-between">
						<p>and more...</p>
						<div class=" flex">
							<a class="anchor" href="/services">View our work</a>
							<Icon src={ArrowLongRight} size="20" class="pt-2 text-primary-500" />
						</div>
					</div>
				</footer>
			</div>
		</div>
		<div class="card my-8">
			<div class="card">
				<header class="card-header">
					<div class="flex">
						<Icon src={HomeModern} size="30" />
						<h2 class="h2 pl-6">Homecare</h2>
					</div>
				</header>
				<section class="p-4">
					<ol class="list">
						<li>
							<span> <Icon src={CheckCircle} size="20" /> </span>
							<span class="flex-auto">Lawncare </span>
						</li>
						<li>
							<span> <Icon src={CheckCircle} size="20" /> </span>
							<span class="flex-auto"> Pressure Washing </span>
						</li>
						<li>
							<span> <Icon src={CheckCircle} size="20" /> </span>
							<span class="flex-auto">Carpet Cleaning</span>
						</li>
					</ol>
				</section>
				<footer class="card-footer">
					<div class="flex justify-between">
						<p>and more...</p>
						<div class=" flex">
							<a class="anchor" href="/services">View our work</a>
							<Icon src={ArrowLongRight} size="20" class="pt-2 text-primary-500" />
						</div>
					</div>
				</footer>
			</div>
		</div>
		<div class="card my-8">
			<div class="card">
				<header class="card-header">
					<div class="flex">
						<Icon src={Cake} size="30" />
						<h2 class="h2 pl-6">Event Service</h2>
					</div>
				</header>
				<section class="p-4">
					<ol class="list">
						<li>
							<span> <Icon src={CheckCircle} size="20" /> </span>
							<span class="flex-auto">Waiter Service</span>
						</li>
						<li>
							<span> <Icon src={CheckCircle} size="20" /> </span>
							<span class="flex-auto">Event Setup</span>
						</li>
						<li>
							<span> <Icon src={CheckCircle} size="20" /> </span>
							<span class="flex-auto">Event Takedown</span>
						</li>
					</ol>
				</section>
				<footer class="card-footer">
					<div class="flex justify-between">
						<p>and more...</p>
						<div class=" flex">
							<a class="anchor" href="/services">View our work</a>
							<Icon src={ArrowLongRight} size="20" class="pt-2 text-primary-500" />
						</div>
					</div>
				</footer>
			</div>
		</div>
	</div>
</div>
