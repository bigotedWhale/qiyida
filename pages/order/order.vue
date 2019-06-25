<template>
  <view class="wrap">
    <view class="order">
      <view class="order-num">
        <text><text class="label">订单号：</text>2233212301</text>
        <text><text class="label">状态：</text><text class="status">确认中</text></text>
      </view>
      <view>
        <text class="label">配送地点：</text>
        <text>湖南省岳阳市湘阴县文星镇1101号</text>
      </view>
      <view>
        <text class="label">配送人：</text>
        <text>杨某某</text>
      </view>
      <view>
        <text class="label">联系方式：</text>
        <text>17373126151</text>
      </view>
      <view class="order-num">
        <text class="label">2019-06-25 14:20</text>
        <text class="price">3000元</text>
      </view>
    </view>
    <view class="order">
      <view class="order-num">
        <text><text class="label">订单号：</text>2233212301</text>
        <text><text class="label">状态：</text><text class="status">确认中</text></text>
      </view>
      <view>
        <text class="label">配送地点：</text>
        <text>湖南省岳阳市湘阴县文星镇1101号</text>
      </view>
      <view>
        <text class="label">配送人：</text>
        <text>杨某某</text>
      </view>
      <view>
        <text class="label">联系方式：</text>
        <text>17373126151</text>
      </view>
      <view class="order-num">
        <text class="label">2019-06-25 14:20</text>
        <text class="price">3000元</text>
      </view>
    </view>
    <view class="order">
      <view class="order-num">
        <text><text class="label">订单号：</text>2233212301</text>
        <text><text class="label">状态：</text><text class="status">确认中</text></text>
      </view>
      <view>
        <text class="label">配送地点：</text>
        <text>湖南省岳阳市湘阴县文星镇1101号</text>
      </view>
      <view>
        <text class="label">配送人：</text>
        <text>杨某某</text>
      </view>
      <view>
        <text class="label">联系方式：</text>
        <text>17373126151</text>
      </view>
      <view class="order-num">
        <text class="label">2019-06-25 14:20</text>
        <text class="price">3000元</text>
      </view>
    </view>
  </view>
</template>

<script>
</script>

<style>
  .wrap {
    padding: 12px 0;
    min-height: calc(100vh - 24px);
    background-color: #F1F1F1;
  }
  .order{
    background-color: #FFFFFF;
    padding:36upx 24upx;
    margin-bottom: 12px;
    font-size: 28upx;
    line-height: 60upx;
    color: #333333;
  }
  
  .label {
    color: #a3a3a3;
    font-size: 28upx;
  }
  
  .order-num {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  .status {
    color: #07c160;
  }
  
  .price {
    color: red;
  }
  
</style>
