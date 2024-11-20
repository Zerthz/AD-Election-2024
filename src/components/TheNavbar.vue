<script setup>
import "/src/assets/AD.svg";
</script>

<template>
	<div class="navbar">
		<div class="navbar-content">
			<img src="/src/assets/AD.svg" class="logo" />
			<ul class="nav-list">
				<li><a href="">Home</a></li>
				<li><a href="">Candidates</a></li>
				<li><a href="">Current Leader</a></li>
			</ul>
		</div>
	</div>
	<!-- <div class="hamburger">
		<h1>barfoo</h1>
	</div> -->
</template>

<style scoped>
.navbar {
	background: linear-gradient(#002e99, #0039bf);
	display: block;
	color: white;
	box-shadow: 0 3px 2px -2px gray;

	container-type: inline-size;
}
.navbar-content {
	display: flex;
	justify-content: space-between;
	max-width: 75%;
	margin: auto;
}

.nav-list {
	display: flex;
	align-items: center;
	gap: 1.5rem;

	list-style: none;

	a {
		display: block;
		color: white;
		text-decoration: none;

		transition: transform 70ms;
	}
	a:hover {
		text-decoration: underline;
		transform: scale(1.1);
	}
}
.logo {
	max-height: 3rem;
	margin-block: 0.5rem;
}

@container (width < 800px) {
	.navbar-content {
		display: none;
	}
}

/* .hamburger {
	container-type: inline-size;
	display: block;

	@container (width < 40rem) {
		display: none;
	}
} */
</style>
