<script>
	import { Accordion, AccordionItem } from '@skeletonlabs/skeleton';
	import { Icon, QuestionMarkCircle, Banknotes, BuildingOffice2 } from 'svelte-hero-icons';
</script>

<div>
	<h2 class="h2">Frequently Asked Questions</h2>
	<Accordion autocollapse>
		<AccordionItem>
			<svelte:fragment slot="lead">
				<Icon src={QuestionMarkCircle} size="25" class="text-tertiary-400" />
			</svelte:fragment>
			<svelte:fragment slot="summary"><h3 class="h3">Question #1</h3></svelte:fragment>
			<svelte:fragment slot="content">Answer to the question....</svelte:fragment>
		</AccordionItem>
		<AccordionItem>
			<svelte:fragment slot="lead">
				<Icon src={Banknotes} size="25" class="text-tertiary-400" />
			</svelte:fragment>
			<svelte:fragment slot="summary"><h3 class="h3">Question #2</h3></svelte:fragment>
			<svelte:fragment slot="content">Answer to the question....</svelte:fragment>
		</AccordionItem>
		<AccordionItem>
			<svelte:fragment slot="lead">
				<Icon src={BuildingOffice2} size="25" class="text-tertiary-400" />
			</svelte:fragment>
			<svelte:fragment slot="summary"><h3 class="h3">Question #3</h3></svelte:fragment>
			<svelte:fragment slot="content">Answer to the question....</svelte:fragment>
		</AccordionItem>
		<!-- ... -->
	</Accordion>
</div>
