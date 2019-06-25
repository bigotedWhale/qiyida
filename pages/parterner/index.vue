<template>
	<view class="content">
    <view class="nav" @click="choose('agent')">
      <text class="icon-font font-lg">&#xe798;</text>
      <text>我是经销商</text>
    </view>
    <view class="nav" @click="choose('carrier')">
      <text class="icon-font font-lg">&#xe78a;</text>
      <text>我是承运商</text>
    </view>
    <view class="nav" @click="choose('supplier')">
      <text class="icon-font font-lg">&#xe799;</text>
      <text>我是供应商</text>
    </view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
			}
		},
		methods: {
      choose (path) {
          uni.navigateTo({
            url: path
          })
      }
		}
	}
</script>

<style>
	.content {
		text-align: center;
		height: auto;
	}
    
  .nav {
    display: flex;
    height: auto;
    flex-direction: column;
    padding: 48upx;
    margin: 48upx;
    background-color: #1db0b8;
    color: #fff;
  }
  
  .nav:nth-child(2) {
    background-color: #536d8a;
  }
  
  .nav:nth-child(3) {
    background-color: #ff9900;
  }
</style>
