<script>
	const unEmail = "durbindesign@gmail.com";
	const handleEmail = e => {
		e.preventDefault();
		window.location.href="mailto:" + unEmail;
		return false;
	};

	
</script>
<section class="contact">
	<h2>Contact Me</h2>
	<p>
		Email is the best way to get ahold of me. &nbsp;
		<span class="obfuscarios">
			<a href="#top" onClick={handleEmail}>
				moc.laimg@ngisednibrud
			</a>
		</span>
	</p>
</section>