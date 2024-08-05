<script>
export let title, date;
</script>

<div class="workplace">
	{#if $$slots.title}
		<h3 class="work-title">
			<slot name="title" >
				No Title
			</slot>
		</h3>
	{:else if title}
		<h3 class="work-title">
			{title}
		</h3>
	{/if}

	{#if $$slots.date}
		<p class="work-date">
			<slot name="date" />
		</p>
		{:else if date}
		<p class="work-date">
			{date}
		</p>
	{/if}

	{#if $$slots.description}
		<div class="description">
			<slot name="description" />
		</div>
	{/if}
</div>