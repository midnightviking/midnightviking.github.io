<script>
	import Avatar from '$lib/components/Avatar.svelte';
	const yearsOfWork = ()=>{ return (new Date().getFullYear())-2006 };

</script>
<div class="vertical_header">
	<Avatar />
	<div class="info">
		<h2 class="my-name ">
			Hi, I'm <br class="hide-for-small" /> Mike Durbin
		</h2>
		<hr />
		<div class="year2 ">
			<div class="exp">
				{yearsOfWork()}
				<span>yrs</span>
			</div>
			<div class="role">
				<div class="first-line">Full Stack</div>
				<div class="second-line">Web Developer</div>
			</div>
		</div>
	</div>
	<div class="lb"></div>
	<div class="primary-skills">
		PHP &middot; MySQL &middot; Javascript &middot; HTML/CSS
	</div>
	<div class="looking-for">Looking for Remote Employment!</div>
	<div class="resume">
		<a href="https://docs.google.com/document/d/1m8hkFp60IQgOcNkZMKJub4FAQYF1ffbTa91tGZAyamI/edit?usp=sharing" target="_blank" rel="noreferrer nofollow">
			Download/view Resume
		</a>
	</div>
</div>