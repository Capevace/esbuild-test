<template>
    <h1 v-if="test">Hello, World!</h1>
</template>
<script type="text/javascript">
	export default {
		props: ['test']
	}
</script>