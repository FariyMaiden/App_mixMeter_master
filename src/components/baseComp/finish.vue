<template>
	<div v-if='show'>
	    <div class="weui-mask_transparent"></div>
	    <div class="weui-toast">
	        <i class="weui-icon-success-no-circle weui-icon_toast"></i>
	        <p class="weui-toast__content">已完成</p>
	    </div>
	</div>
</template>
<script>
export default{
	props:{
		show:{
			type:Boolean,
			required:true,
			defult:false,
		}
	}
}	
</script>
<style>
	
</style>