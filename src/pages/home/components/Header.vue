<template>
    <div class="header">
        <div class="header-left">
					<span class="iconfont icon-back">&#xe624;</span>
				</div>
        <div class="header-input">
					<span class="iconfont">&#xe632;</span>
					<span>输入城市/景点/游玩</span>
				</div>
        <div class="header-right">
					<span>城市</span>
					<i class="triangle"></i>
				</div>
    </div>
</template>
<script>
export default {
  name: 'HomeHeader',
}
</script>
<style lang="stylus" scoped>
	@import '~styles/varibles.styl'
	.header
		display flex
		align-items center
		line-height .86rem
		background $bgColor
		color #fff
		.header-left
			width .64rem
			float left
			text-align center
			.icon-back
				font-size .4rem
		.header-input
			flex 1
			height .64rem
			line-height .64rem
			padding-left .1rem
			color #666
			margin-left .2rem
			background #ffffff
			border-radius .1rem
		.header-right
			width 1.24rem
			float right
			text-align center
			display flex
			justify-content center
			align-items center
			.triangle
				width 0
				height 0
				border-width 7px
				border-color #fff transparent transparent transparent
				border-style solid
				margin-top 7px
				margin-left 5px
</style>