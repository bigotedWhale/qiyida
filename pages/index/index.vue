<template>
	<view class="content">
		<view class="header">
            <navigator class="header-nav" url="../order/order">
                <text class="icon-font font-lg">&#xe782;</text>
                <text class="font-sm">我的订单</text>
            </navigator>
            <navigator class="header-nav" url="../parterner/index">
                <text class="icon-font font-lg">&#xe78a;</text>
                <text class="font-sm">供应运输合作</text>
            </navigator>
		</view>
        <view class="address">
            <text class="icon-font font-sm">&#xe618;</text>
            <text>运送到：湘阴县文星镇</text>
        </view>
        <view class="list">
            <view v-for="(item, index) in list" :class="{item: true, active: index == current}" @click="choose(index)" :key="index">
                <text class="name">{{item.name}}</text>
                <text class="price">¥{{item.price}}</text>
            </view>
        </view>
        <button class="btn">快速下单</button>
	</view>
</template>

<script>
	export default {
		data() {
			return {
                current: 0,
                list: [{
                    name: '10吨',
                    price: 1000
                },{
                    name: '20吨',
                    price: 2000
                },{
                    name: '30吨',
                    price: 3000
                },{
                    name: '40吨',
                    price: 4000
                },{
                    name: '50吨',
                    price: 5000
                },]
			}
		},
		methods: {
            choose (index) {
                this.current = index
            }
		}
	}
</script>

<style>
	.content {
		text-align: center;
		height: auto;
	}

	.logo {
		height: 200upx;
		width: 200upx;
		margin-top: 200upx;
	}

	.title {
		font-size: 36upx;
		color: #fff;
	}
    
    .header {
        display: flex;
        justify-content: space-around;
        align-items: center;
        height: 300upx;
        background-color: #00B8F5;
        color: #fff;
    }
    
    .header-nav {
        display: flex;
        flex-direction: column;
    }
    
    .list {
        display: flex;
        padding: 0 12upx;
        justify-content: space-around;
        align-items: center;
        flex-wrap: wrap;
        box-sizing: content-box;
    }
    .list:after{
        display: block;
        width: 30%;
        content: "";
        border: 1upx solid transparent;
    }
    .item {
        width: 30%;
        height: 100upx;
        margin-top: 20upx;
        border: 1upx solid #dcdcdc;
        color: #ccc;
        border-radius: 4px;
        
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
    
    .item.active {
        border: 1upx solid #00B8F5;
        color: #00B8F5;
    }
    .name {
        font-size: 38upx;
    }
    
    .price {
        font-size: 24upx;
    }
    
    .address {
        display: flex;
        height: 100upx;
        justify-content: center;
        align-items: center;
        font-size: 28upx;
    }
    
    .btn {
        margin: 80upx 20upx;
        height: 80upx;
        font-size: 40upx;
        padding: 0;
        line-height: 80upx;
        align-items: center;
        color: #fff;
        background-color: #00B8F5;
    }
</style>
