<template>
	<div class="login_home_container">
		<main class="login_home_main">
			<p class="login_home_title">MeshKit 日志客户端</p>
			<Button class="login_home_btn" @click="handleLoginClick">
				<span class="btn_text">登陆</span>
			</Button>
		</main>
	</div>
</template>

<script lang="ts">
	import { defineComponent } from 'vue'
	import { Button } from 'ant-design-vue';

	export default defineComponent({
		name: 'login-home',
		components: {
			Button,
		},
		methods: {
			handleLoginClick()
			{
			}
		}
	})
</script>

<!-- 
	somehow css modules just doesn't work
	so we just use scoped css
-->
<style lang='less' scoped>
	.login_home_container {
		width: 100vw;
		height: 100vh;
		margin: 0;
		padding: 0;
		background-image: url("@/assets/png/pic-signup-bg.png");
		background-repeat: no-repeat;
		background-size: 100% 100%;
		.login_home_main {
			position: relative;
			width: 654px;
			height: 100%;
			margin: 0 auto;
			display: flex;
			flex-direction: column;
			align-items: center;
			.login_home_title {
				position: absolute;
				top: 9.4rem;
				width: 645px;
				height: 129px;
				font-family: PingFangSC;
				font-size: 3.3rem;
				font-weight: 500;
				font-stretch: normal;
				font-style: normal;
				line-height: normal;
				letter-spacing: normal;
				text-align: center;
				color: #ffffff;
			}
			.login_home_btn {
				position: absolute;
				top: 18.5rem;
				width: 327px;
				height: 56px;
				border-radius: 4px;
				border: solid 1px #2b55da;
				background-color: #345ee6;
				.btn_text {
					width: 42px;
					height: 24px;
					font-family: PingFangSC;
					font-size: 18px;
					font-weight: 500;
					font-stretch: normal;
					font-style: normal;
					line-height: 1.33;
					letter-spacing: normal;
					text-align: center;
					color: #ffffff;
				}
			}
		}
	}
</style>