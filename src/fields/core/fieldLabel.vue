<template lang="pug">
	span {{ value }}
</template>

<script>
	import abstractField from "../abstractField";

	export default {
		mixins: [ abstractField ]
	};
</script>

<style lang="sass">
	.vue-form-generator .field-label span {
		display: block;
		width: 100%;
		margin-left: 12px;
    padding-top: 6px;
	}
</style>
