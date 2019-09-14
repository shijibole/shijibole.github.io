<template>
	<div>
		<h1>list s3 music</h1>
		<amplify-authenticator></amplify-authenticator>
	</div>
</template>

<script>
// import { AmplifyEventBus } from 'aws-amplify-vue';

export default {
	name: 'home',
	data () {
		return {
			userinfo: {
				username: '',
				password: '',
			}
		};
	},
	created () {
	},
}
</script>
