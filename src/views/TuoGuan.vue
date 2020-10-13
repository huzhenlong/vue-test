<template>
  <div>
    <van-nav-bar>
      <template #title>
        <span class="tle">首付款托管</span>
      </template>
      <template #left>
        <van-icon name="arrow-left" size="18" color="#000"/>
      </template>
    </van-nav-bar>

    <div class="con">
      <div style="margin-bottom: 16px;">
        <van-row type="flex" justify="center">
          <van-col span="8">
            <van-button round color="#926ef8" style="width: 100px;">我是买方</van-button>
          </van-col>
          <van-col span="8">
            <van-button round type="default" style="width: 100px;">我是卖方</van-button>
          </van-col>
        </van-row>
      </div>


      <div class="mb-10">

        <van-cell title="存量房资金托管协议号" title-class="cellTle"
                  value-class="cellVal" value="23758293403284"/>

        <van-grid :border="false" :column-num="3">
          <van-grid-item>
            <p class="fw-b">98万</p>
            <sapn class="txt-14">房源交易总价</sapn>
          </van-grid-item>
          <van-grid-item>
            <p class="fw-b">30万</p>
            <sapn class="txt-14">首付款金额</sapn>
          </van-grid-item>
          <van-grid-item>
            <p class="fw-b" style="color: #926ef8">待支付</p>
            <sapn class="txt-14">状态</sapn>
          </van-grid-item>
        </van-grid>

        <div style="background: white">
          <van-row>
            <van-col span="18">
                <span>
                  <img src="../assets/user.jpg" alt="" style="width: 16px;margin: 0 4px;">
                </span>

              <span style="color: #afafaf;line-height: 33px;font-size: 14px;">付款账户：张三/付款账户：李四</span>
            </van-col>
            <van-col span="6">
              <van-button round color="#926ef8" style="width: 89px;height: 33px;">去支付</van-button>
            </van-col>
          </van-row>
        </div>


      </div>

      <div class="mb-10">

        <van-cell title="存量房资金托管协议号" title-class="cellTle"
                  value-class="cellVal" value="23758293403284"/>

        <van-grid :border="false" :column-num="3">
          <van-grid-item>
            <p class="fw-b">98万</p>
            <sapn class="txt-14">房源交易总价</sapn>
          </van-grid-item>
          <van-grid-item>
            <p class="fw-b">30万</p>
            <sapn class="txt-14">首付款金额</sapn>
          </van-grid-item>
          <van-grid-item>
            <p class="fw-b" style="color: #926ef8">已支付</p>
            <sapn class="txt-14">状态</sapn>
          </van-grid-item>
        </van-grid>

        <div style="background: white">
          <van-row>
            <van-col span="18">
                <span>
                  <img src="../assets/user.jpg" alt="" style="width: 16px;margin: 0 4px;">
                </span>

              <span style="color: #afafaf;line-height: 33px;font-size: 14px;">付款账户：张三/付款账户：李四</span>
            </van-col>
            <van-col span="6">
              <van-button round color="#f5af11" style="width: 89px;height: 33px;">信息查看</van-button>
            </van-col>
          </van-row>
        </div>


      </div>

      <div class="mb-10">

        <van-cell title="存量房资金托管协议号" title-class="cellTle"
                  value-class="cellVal" value="23758293403284"/>

        <van-grid :border="false" :column-num="3">
          <van-grid-item>
            <p class="fw-b">98万</p>
            <sapn class="txt-14">房源交易总价</sapn>
          </van-grid-item>
          <van-grid-item>
            <p class="fw-b">30万</p>
            <sapn class="txt-14">首付款金额</sapn>
          </van-grid-item>
          <van-grid-item>
            <p class="fw-b" style="color: #926ef8">已支付</p>
            <sapn class="txt-14">状态</sapn>
          </van-grid-item>
        </van-grid>

        <div style="background: white">
          <van-row>
            <van-col span="18">
                <span>
                  <img src="../assets/user.jpg" alt="" style="width: 16px;margin: 0 4px;">
                </span>

              <span style="color: #afafaf;line-height: 33px;font-size: 14px;">付款账户：张三/付款账户：李四</span>
            </van-col>
            <van-col span="6">
              <van-button round color="#f5af11" style="width: 89px;height: 33px;">信息查看</van-button>
            </van-col>
          </van-row>
        </div>


      </div>

      <van-button round color="#926ef8" size="large">开启支付</van-button>

    </div>

  </div>
</template>

<script>

export default {
  name: "TuoGuan"
}
</script>

<style scoped>
.tle {
  font-size: 18px;
  font-weight: bold;
  letter-spacing: 1px;
}

.cellTle {
  font-size: 15px;
  font-weight: bold;
  letter-spacing: 1px;
}

.cellVal {
  color: #000;
}
.txt-14{
  color: #afafaf;
  font-size: 14px;
}
.fw-b{
  font-weight: bold;
}

.con {
  background: #f5f5f5;
  padding: 16px;
}

.mb-10 {
  margin-bottom: 12px;
  padding: 8px;
  background: white;
  border-radius: 12px;
}
</style>