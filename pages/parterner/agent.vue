<template>
  <view class="wrap">
    <view class="form-item column">
        <view class="title">经销商名称</view>
        <input class="uni-input" placeholder="经销商名称" />
    </view>
    <view class="form-item column">
        <view class="title">责任人姓名</view>
        <input class="uni-input" placeholder="请输入责任人姓名" />
    </view>
    <view class="form-item column">
        <view class="title">营业执照编号</view>
        <input class="uni-input" placeholder="请输入营业执照编号" />
    </view>
    <view class="form-item column">
        <view class="title">营业执照有效期</view>
        <input class="uni-input" placeholder="请输入营业执照有效期" />
    </view>
    
    <view class="form-item column">
        <view class="title">身份证</view>
        <input class="uni-input" placeholder="请输入身份证号码" />
    </view>
    
    <view class="form-item column">
        <view class="title">手机号</view>
        <input class="uni-input" placeholder="请输入营业执照有效期" />
    </view>
    <view class="form-item column">
        <view class="title">验证码</view>
        <input class="uni-input" placeholder="请输入营业执照有效期" />
        <button size="mini">发送验证码</button>
    </view>
  </view>
</template>

<script>
</script>

<style>
  .wrap {
    padding: 12px 0;
    min-height: calc(100vh - 24px);
    background-color: #fff;
  }
  
  .title {
    font-size: 28upx;
    height: 48upx;
    line-height: 48upx;
    margin-left: 24upx;
    color: #333;
  }
  input {
    height: 80upx;
    background-color: #fff;
    padding:0 24upx;
    color: #333;
  }
  
  .form-item {
    padding: 24upx 0;
    padding-bottom: 12upx;
    background-color: #fff;
    border-bottom: 2upx solid #f1f1f1;
    margin: 0 24upx;
  }
</style>
