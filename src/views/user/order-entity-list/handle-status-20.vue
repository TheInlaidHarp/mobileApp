<template>
	<div slot="footer" class="order_list--footer_btn">
		<van-button size="small" type="danger" @click="$emit('handle', 'reminderOrder')" :disabled="!reminder">提醒</van-button>
	</div>	
</template>

<script>
	export default {
		props: {
			reminder: Boolean
		}
	}
</script>