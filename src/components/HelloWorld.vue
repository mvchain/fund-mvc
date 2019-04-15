<template>
    <div class="hello">
        <div class="banner">
            <button class="zh-en">中 文</button>
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
                    <p>TTBTC Bitcoin investment fund Ⅱ is coming</p>
                    <p>Fund raising period: April 15, 2019 to April 30, 2019</p>
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
                    <p class="fund-top-text-inline"></p>
                </div>
                <div class="fund-top-text-container">
                    <p>
                        Bitcoin is the greatest asset in human history
                        <br/>
                        Accumulating bitcoin is the most correct strategy at the moment</p>
                    <div class="fund-top-text-container-pre">
                        <pre>

               If you are eager to earn more bitcoin If you expect a solid BTC return

               if you expect a solid BTC return

               if you want to hedge the risk of currency price fluctuations
                        </pre>
                    </div>
                </div>
            </div>
            <div class="fund-top-img"></div>
        </div>
        <div class="advertising2">
            <div>
                <p>Low Retracement Rates High ROI</p>
                <p>TTBTC Bitcoin investment fund is a floating return of crypto as</p>
            </div>
        </div>
        <div class="fund-middle">
            <div class="fund-middle-left">
                <div>
                    <p>TTBTC Fund </p>
                    <p>Intro</p>
                    <p></p>
                </div>
            </div>
            <div class="fund-middle-right">
                <ul>
                    <li>
                        <b>Issuer: </b>
                        <span>TTBTC.com </span>
                    </li>
                    <li>
                        <b>Distribution channel: </b>
                        <span>TTPay.info</span>
                    </li>
                    <li class="fund-middle-right-margin">
                        <b>
                            Pricing and settlement unit:
                        </b>
                        <span>BTC</span>
                    </li>
                    <li>
                        <b>
                            Investment strategy:
                        </b>
                        <span>
                             Our strategy is to make BTC as the investment target for investors to achieve BTC growth in the short and medium term. We adopt real-time dynamic adjustment of the trading model, trading in BTC futures and options market and create stable returns for investors
                        </span>
                    </li>
                    <li>
                        <b>
                            Strategy style:
                        </b>
                        <span>
                             Purdent strategy, the largest single retracement in history is no more than 3%
                        </span>
                    </li>
                    <li>
                        <b>
                            Major trading products:
                        </b>
                        <span>
                            BTC and its financial derivatives (Bitmex BTC futures contract, Deribit BTC options)
                        </span>
                    </li>
                    <li>
                        <b></b>
                        <span></span>
                    </li>
                    <li class="fund-middle-right-margin">
                        <b>
                            Fund cycle:
                        </b>
                        <span>6 months</span>
                    </li>
                    <li>
                        <b>Revenue rules:</b>
                        <span>
                             For every 30% profit realized, the profit part of BTC can be withdrawn, and the full principal and profit BTC can be withdrawn on the 6-month maturity date. The actual income is based on the result of maturity date, and the investor obtains 70% of the total profit.
                        </span>
                    </li>
                    <li>
                        <b>
                            The highest retracement:
                        </b>
                        <span>
                            30%, close to the 30% retracement will immediately close all positions and liquidate the fund ( only for extreme situation, which almost never happened, our prudent strategy maximum retracement in history is 3.03%)
                        </span>
                    </li>
                </ul>
            </div>
        </div>
        <div class="advertising3">
            <div>
                <p>History</p>
                <p>performance</p>
                <p></p>
            </div>
        </div>
        <div class="fund-bottom">
            <div class="fund-bottom-con">
                <div class="fund-bottom-item">
                    <p>TTBTC Bitcoin investment fund I</p>
                    <div>
                        <img src="../assets/1.jpg" alt="">
                    </div>
                </div>
                <div class="fund-bottom-item">
                    <p>TTBTC Bitcoin investment fund Ⅱ</p>
                    <div>
                        <img src="../assets/comingsoon.jpg" alt="">
                    </div>
                </div>
            </div>
        </div>
        <div class="footer">
            <div class="footer-con">
                <p>立即下载TTpay手机客户端，参与基金理财</p>
                <button>Android下载</button>
            </div>
        </div>
    </div>
</template>

<script>
    const lan = {
        en: {
            investment: 'TTBTC Bitcoin investment fund',
            joinFund: 'Download TTPay APP to join the fund',
            androidDown: 'Android Download',
            comingSoon: 'TTBTC Bitcoin investment fund Ⅱ is coming',
            April: 'Fund raising period: April 15, 2019 to April 30, 2019',
            more: 'MORE',
            greatest: 'Bitcoin is the greatest asset in human history\n' +
            'Accumulating bitcoin is the most correct strategy at the moment\n' +
            '                        '
        },
        zh: {
            investment: 'TTBTC稳健型复合策略基金',
            joinFund: '下载TTpay手机客户端，参与基金理财',
            androidDown: 'Android下载',
            comingSoon: 'TTBTC稳健型复合策略基金二期即将开始',
            April: '产品募集期：2019/4/15-2019/4/30',
            more: '更多',
            greatest: ''
        }
    }
    export default {
        name: 'HelloWorld',
        data() {
            return {
                lan: lan
            }
        }
    }
</script>

<style scoped>
    button{
        color:#fff;
        border:0;
        outline: none;
        cursor: pointer;
    }
    .zh-en{
        position: absolute;
        top:50px;
        right:100px;
        background: #DD2C41;
        width:90px;
        height:30px;
        line-height: 30px;
        color:#fff;
        text-align: center;
        border-radius: 18px;
    }
    .banner{
        background: url("../assets/banner.jpg") no-repeat 0 -100px;
        background-size: 100%;
        height:618px;
        width:1920px;
        text-align: center;
        padding-top:250px;
        line-height: 80px;
        position: relative;
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
        width:1920px;
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
    .advertising1 .advertising1-item > div:first-child p:first-child{
        font-size:36px;
    }
    .advertising1 .advertising1-item > div:first-child p:last-child{
        font-size:28px;
    }
    .advertising1 .advertising1-item > div:last-child button{
        width:183px;
        height:48px;
        background:#fff;
        font-size:18px;
        color:#0F0F0F;
        border-radius: 18px;
    }


    .fund-top{
        width:1920px;
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
        padding: 0 100px 0 360px;
    }
    .fund-top-text-title{
        font-size:56px;
        color:#282828;
    }
    .fund-top-text-title .fund-top-text-inline{
        width:60px;
        height:8px;
        background:#DD2C41;
        margin:30px 0;

    }
    .fund-top-text-title p{
        font-weight: 900;
    }
    .fund-top-text-container{

    }
    .fund-top-text-container-pre{
        position: relative;
        margin-top:20px;
    }
    .fund-top-text-container-pre:before{
        content: "\"";
        font-size:50px;
    }
    .fund-top-text-container-pre:after{
        content:  "\"";
        font-size:50px;
        position: absolute;
        right:0;
    }
    .fund-top-text-container p{
        font-size:22px;
        color:#282828;
        line-height: 30px;
    }
    .fund-top-img{
        width:749px;

        background:url("../assets/ttbtc.jpg") no-repeat 0 120px;
        background-size:100%;
    }




    .advertising2{
        width:1920px;
        text-align: center;
        height:180px;
        display: flex;
        align-items: center;
        justify-content: center;
        background: #FAFAFA;
    }
    .advertising2 div{
        line-height: 40px;
    }
    .advertising2 p:first-child{
        color:#DD2C41;
        font-size:36px;
        font-weight: 900;
    }
    .advertising2 p:last-child{
        font-size:22px;
        color:#282828;
    }



    .fund-middle{
        height:1120px;
        width:1920px;
        display: flex;
        margin:120px 0;
    }
    .fund-middle .fund-middle-left{
        width:750px;
        height:1120px;
        background: url("../assets/fundintro.jpg") no-repeat;
        background-size: 100%;
        position: relative;
    }
    .fund-middle .fund-middle-left > div:first-child{
        position: absolute;
        top:87px;
        right:46px;
    }
    .fund-middle .fund-middle-left > div:first-child p:first-child,
    .fund-middle .fund-middle-left > div:first-child p:nth-child(2){
        font-size:56px;
        color:#282828;
        font-weight: 900;
    }
    .fund-middle .fund-middle-left > div:first-child p:last-child{
        width: 60px;
        height: 8px;
        background: #DD2C41;
        margin: 30px 0;
    }
    .fund-middle .fund-middle-right{
        width:700px;
        font-size:20px;
        line-height: 40px;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .fund-middle .fund-middle-right .fund-middle-right-margin{
        margin-top:30px;
    }




    .advertising3{
        height:300px;
        background: url("../assets/history.jpg") no-repeat;
        background-size: 100%;
        width:1920px;
        padding-left:360px;
        padding-top:77px;

    }
    .advertising3 p:first-child{
        margin-top:20px;
        font-size:48px;
        color:#282828;
        font-weight: 900;
    }
    .advertising3 p:nth-child(2) {
        margin-top:20px;
        font-size:48px;
        color:#282828;
        font-weight: 900;
    }
    .advertising3 p:last-child{
        margin-top:20px;
        width: 60px;
        height:8px;
        background: #DD2C41;
    }




    .fund-bottom{
        width:1920px;
    }
    .fund-bottom-con{
        width:1080px;
        margin:0 auto;
    }
    .fund-bottom .fund-bottom-item{

    }
    .fund-bottom .fund-bottom-item p{
        margin: 60px 0;
        color:#DD2C41;
        font-size:30px;
        font-weight: 900;
    }
    .fund-bottom .fund-bottom-item img{
        width: 100%;
    }





    .footer{
        width:1920px;
        margin-top:120px;
        height:240px;
        background: url("../assets/foot.jpg") no-repeat;
        display: flex;
        justify-content: center;
        align-items: center;

    }
    .footer p{
        font-size:28px;
        color:#fff;
    }
    .footer-con{
        text-align: center;
    }
    .footer button{
        width: 153px;
        height:44px;
        text-align: center;
        line-height: 44px;
        background: #DD2C41;
        border-radius: 10px;
        margin-top:26px;
    }
</style>
