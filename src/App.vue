<template>
	<div id="app">
		<nav>
			<router-link class="router-link" to="/" exact>Список заметок</router-link>
			<router-link class="router-link" to="/note" exact
			>Создать заметку</router-link
			>
		</nav>
		<hr />
		<router-view />
	</div>
</template>

<script>
    export default {
        name: "App"
    }
</script>