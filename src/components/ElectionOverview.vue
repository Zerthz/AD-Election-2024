<script setup></script>

<template>
	<main>
		<article>
			<h2>Current Leader</h2>
			<p class="article-text">
				The current Elected Monark, Lord Opinion Director Isak.
			</p>
			<p><q class="quoted"> Your thoughts, My ideas. </q></p>
		</article>
		<article>
			<p>
				Corrupti ipsa eligendi odio quisquam maxime earum praesentium
				voluptatum asperiores debitis! Neque at omnis eum quos adipisci
				error nostrum est odio doloribus voluptates. Sequi, aliquam
				necessitatibus. Sapiente iure quas eveniet.
			</p>
		</article>
		<article>
			<p>
				Repellendus dicta laboriosam tenetur provident animi quam,
				assumenda recusandae. Ut, maiores repudiandae laudantium, labore
				accusamus voluptate alias adipisci mollitia dolorem autem
				aspernatur! Illo vel dignissimos eos beatae fuga, earum iusto?
			</p>
		</article>
	</main>
</template>

<style scoped>
main {
	container-type: inline-size;
}
p {
	max-width: 64ch;
}
p:has(:first-child) {
	text-align: center;
}
article {
	p {
		margin-inline: auto;
	}
}
.quoted {
	font-style: italic;
	color: #333;
}

@container (width > 800px) {
	article {
		max-width: 1000px;
		margin-inline: auto;
	}
}
</style>
