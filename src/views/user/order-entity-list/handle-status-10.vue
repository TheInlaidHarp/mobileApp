<template>
	<div slot="footer" class="order_list--footer_btn">
		<van-button size="small" @click="$emit('handle', 'cancelOrder')">取消</van-button>
		<van-button size="small" type="danger" @click="$emit('handle', 'toPay')">1</van-button>
	</div>	
</template>

<script>
</script>