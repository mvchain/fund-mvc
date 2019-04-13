<template>
    <div class="hello">
        <div class="banner">
            <div class="banner-item">
                <p>TTBTC Bitcoin investment fund</p>
                <p>下载TTpay手机客户端，参与基金理财</p>
                <p>
                    <button>Android下载</button>
                </p>
            </div>
        </div>
        <div class="advertising1">
            <div class="advertising1-item">
                <div>
                    <p>Fund raising period: April 15, 2019 to April 30, 2019 </p>
                    <p>Fund cycl:6 months</p>
                </div>
                <div>
                    <button>coming soon</button>
                </div>
            </div>
        </div>
        <div class="fund-top">
            <div class="fund-top-text">
                <div class="fund-top-text-title">
                    <p>TTBTC Bitcoin </p>
                    <p>Investment Fund</p>
                    <p class=""></p>
                </div>
                <div class="fund-top-text-container">
                    <p>Bitcoin is the greatest asset in human history Accumulating bitcoin is the most correct strategy at the moment</p>
                    <div>
                        <pre>
                            If you are eager to earn more bitcoin If you expect a solid BTC return
                        </pre>
                        <pre>
                            if you expect a solid BTC return
                        </pre>
                        <pre>
                            if you want to hedge the risk of currency price fluctuations
                        </pre>
                    </div>
                </div>
            </div>
            <div class="fund-top-img"></div>
        </div>
        <div class="advertising2"></div>
        <div class="fund-middle"></div>
        <div class="advertising3"></div>
        <div class="fund-bottom"></div>
        <div class="footer"></div>
    </div>
</template>

<script>
    export default {
        name: 'HelloWorld',

    }
</script>

<style scoped>
    button{
        color:#fff;
        border:0;
        outline: none;
        cursor: pointer;
    }
    .banner{
        background: url("../assets/banner.jpg") no-repeat 0 -100px;
        background-size: 100%;
        height:618px;
        text-align: center;
        padding-top:250px;
        line-height: 80px;
    }
    .banner .banner-item p:first-child{
        font-size:60px;
    }
    .banner .banner-item p:nth-child(2){
        font-size:28px;
    }
    .banner .banner-item p:last-child button{
        font-size:16px;
        display: inline-block;
        width: 153px;
        height:44px;
        background: #DD2C41;
        border-radius: 10px;
        text-align: center;
        line-height: 44px;

    }



    .advertising1{
        height:180px;
        background:#DD2C41;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .advertising1 .advertising1-item{
        width:1080px;
        height:180px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .advertising1 .advertising1-item > div:first-child{
        font-size:28px;
        color:#fff;
        line-height: 40px;
    }
    .advertising1 .advertising1-item > div:last-child button{
        width:183px;
        height:48px;
        background:#fff;
        font-size:18px;
        color:#0F0F0F;
    }


    .fund-top{
        height:760px;
        display: flex;
        justify-content: space-between;
    }
    .fund-top-text{
        display: flex;
        flex:1;
        flex-direction: column;
        justify-content: center;
        align-items: left;
        text-indent: 360px;
    }
    .fund-top-text-title{
        font-size:56px;
        color:#282828;
    }
    .fund-top-text-title p{
        font-weight: 900;
    }
    .fund-top-text-container{}
    .fund-top-img{
        width:749px;

        background:url("../assets/ttbtc.jpg") no-repeat 0 120px;
        background-size:100%;
    }




    .advertising2{}
    .fund-middle{}
    .advertising3{}
    .fund-bottom{}
    .footer{}
</style>
