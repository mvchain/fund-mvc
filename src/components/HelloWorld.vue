<template>
    <div class="hello">
        <div class="banner">
            <button class="zh-en" @click="totalLang">{{!this.langFlag ? '中 文' : 'EN'}}</button>
            <div class="banner-item">
                <p>{{language.investment}}</p>
                <p>{{language.joinFund}}</p>
                <p>
                    <button @click="downAndroid">{{language.androidDown}}</button>
                </p>
            </div>
        </div>
        <div class="advertising1">
            <div class="advertising1-item">
                <div>
                    <p>{{language.comingSoon}}</p>
                    <p>{{language.April}}</p>
                </div>
                <div>
                    <button @click="moreHandler">{{language.more}}</button>
                </div>
            </div>
        </div>
        <div class="fund-top">
            <div class="fund-top-text">
                <div class="fund-top-text-title">
                    <p>{{language.investment1}}</p>
                    <p>{{language.investment2}}</p>
                    <p class="fund-top-text-inline"></p>
                </div>
                <div class="fund-top-text-container">
                    <p>
                        {{language.greatest}}
                        <br/>
                        {{language.greatest2}}</p>
                    <div class="fund-top-text-container-pre">
                        <pre>

               {{language.ifYou1}}

               {{language.ifYou2}}

               {{language.ifYou3}}
                        </pre>
                    </div>
                    <div style="font-weight: 900;font-size:26px;font-style: italic;margin-top:40px;">{{language.product}}
                    </div>
                </div>
            </div>
            <div class="fund-top-img"></div>
        </div>
        <div class="advertising2">
            <div>
                <p>{{language.retracement}}</p>
                <p>{{language.floating}}</p>
            </div>
        </div>
        <div class="fund-middle">
            <div class="fund-middle-left">
                <div>
                    <p>{{language.intro1}}</p>
                    <p>{{language.intro2}}</p>
                    <p></p>
                </div>
            </div>
            <div class="fund-middle-right">
                <ul>
                    <li>
                        <b>{{language.issuer}}</b>
                        <span>{{language.issuerInfo}}</span>
                    </li>
                    <li>
                        <b>{{language.channel}}</b>
                        <span>{{language.channelInfo}}</span>
                    </li>
                    <li class="fund-middle-right-margin">
                        <b>
                            {{language.pricing}}
                        </b>
                        <span>{{language.pricingInfo}}</span>
                    </li>
                    <li>
                        <b>
                            {{language.strategy}}
                        </b>
                        <span>
                             {{language.strategyInfo}}
                        </span>
                    </li>
                    <li>
                        <b>
                            {{language.strategyStyle}}
                        </b>
                        <span>
                             {{language.strategyStyleInfo}}
                        </span>
                    </li>
                    <li>
                        <b>
                            {{language.major}}
                        </b>
                        <span>
                           {{language.majorInfo}}
                        </span>
                    </li>
                    <li>
                        <b></b>
                        <span></span>
                    </li>
                    <li class="fund-middle-right-margin">
                        <b>
                            {{language.cycle}}
                        </b>
                        <span>{{language.cycleInfo}}</span>
                    </li>
                    <li>
                        <b>{{language.revenue}}</b>
                        <span>
                           {{language.revenueInfo}}
                        </span>
                    </li>
                    <li>
                        <b>
                            {{language.highest}}
                        </b>
                        <span>
                            {{language.highestInfo}}
                        </span>
                    </li>
                    <li>
                        <b>
                            {{language.Estimated}}
                        </b>
                        <span>
                             {{language.EstimatedInfo}}
                        </span>
                    </li>
                </ul>
            </div>
        </div>
        <div class="advertising3">
            <div>
                <p>{{language.historyPer1}}</p>
                <p>{{language.historyPer2}}</p>
                <p></p>
            </div>
        </div>
        <div class="fund-bottom">
            <div class="fund-bottom-con">
                <div class="fund-bottom-item">
                    <p>{{language.fund1}}</p>
                    <div>
                        <img :src="language.fund1Img" alt="">
                    </div>
                </div>
                <div class="fund-bottom-item">
                    <p>{{language.fund2}}</p>
                    <div>
                        <img :src="language.fund2Img" alt="">
                    </div>
                </div>
            </div>
        </div>
        <div class="footer">
            <div class="footer-con">
                <p>{{language.downloadNow}}</p>
                <button @click="downAndroid">{{language.androidDown}}</button>
            </div>
        </div>
    </div>
</template>

<script>
    const lan = {
        en: {
            investment: 'TTBTC Bitcoin investment fund',
            joinFund: 'Download TTPay APP to join the fund',
            investment1: 'TTBTC Bitcoin',
            investment2: 'Investment fund',
            androidDown: 'Android Download',
            comingSoon: 'TTBTC Bitcoin investment fund Ⅱ is coming',
            April: 'Fund raising period: April 15, 2019 to April 30, 2019',
            more: 'MORE',
            greatest: 'Bitcoin is the greatest asset in human history',
            greatest2: 'Accumulating bitcoin is the most correct strategy at the moment',
            ifYou1: 'If you are eager to earn more bitcoin If you expect a solid BTC return',
            ifYou2: 'if you expect a solid BTC return',
            ifYou3: 'if you want to hedge the risk of currency price fluctuations',
            product: 'TTBTC is the product you need',
            retracement: 'Low Retracement Rates High ROI',
            floating: 'TTBTC Bitcoin investment fund is a floating return of crypto assets fund',
            intro1: 'TTBTC Fund ',
            intro2: 'Intro',
            issuer: 'Issuer: ',
            issuerInfo: 'TTBTC.com ',
            channel: 'Distribution channel: ',
            channelInfo: 'TTPay.info',
            pricing: 'Pricing and settlement unit:',
            pricingInfo: 'BTC',
            strategy: 'Investment strategy：',
            strategyInfo: 'Our strategy is to make BTC as the investment target for investors to achieve BTC growth in the short and medium term. We adopt real-time dynamic adjustment of the trading model, trading in BTC futures and options market and create stable returns for investors',
            strategyStyle: 'Strategy style：',
            strategyStyleInfo: 'Purdent strategy, the largest single retracement in history is no more than 3%',
            major: 'Major trading products: ',
            majorInfo: 'BTC and its financial derivatives (Bitmex BTC futures contract, Deribit BTC options)',
            cycle: 'Fund cycle: ',
            cycleInfo: '6 months',
            revenue: 'Revenue rules: ',
            revenueInfo: 'For every 30% profit realized, the profit part of BTC can be withdrawn, and the full principal and profit BTC can be withdrawn on the 6-month maturity date. The actual income is based on the result of maturity date, and the investor obtains 70% of the total profit.',
            highest: 'The highest retracement:',
            highestInfo: '30%, close to the 30% retracement will immediately close all positions and liquidate the fund ( only for extreme situation, which almost never happened, our prudent strategy maximum retracement in history is 3.03%)',
            Estimated: 'Estimated income:',
            EstimatedInfo: '120% ~ + annualized income',
            historyPer1: 'History',
            historyPer2: 'performance',
            fund1: 'TTBTC Bitcoin investment fund I',
            fund2: 'TTBTC Bitcoin investment fund Ⅱ',
            fund1Img: 'https://ico-list.oss-cn-hangzhou.aliyuncs.com/cryptovalut/15553068063925kSCeRXpKF.png',
            fund2Img: 'https://ico-list.oss-cn-hangzhou.aliyuncs.com/cryptovalut/1555306783686X3RGW5ynaS.png',
            downloadNow: 'Download TTpay APP , Participate in fund management'
        },
        cn: {
            investment: 'TTBTC稳健型复合策略基金',
            joinFund: '下载TTpay手机客户端，参与基金理财',
            androidDown: 'Android下载',
            investment1: 'TTBTC 比特币',
            investment2: '稳健型复合策略基金',
            comingSoon: 'TTBTC稳健型复合策略基金二期即将开始',
            April: '产品募集期：2019/4/15-2019/4/30',
            more: '更多',
            greatest: '比特币BTC是人类有史以来最伟大的资产单品',
            greatest2: '囤积比特币是当下最正确的策略',
            ifYou1: '如果你渴望赚取更多的比特币',
            ifYou2: '如果你期望稳健的BTC回报',
            ifYou3: '如果你希望对冲币价波动风险',
            product: 'TTBTC就是你需要的产品',
            retracement: '低回撤  高回报',
            floating: 'TTBTC稳健型复合策略基金是数字资产浮动收益类产品',
            intro1: 'TTBTC基金',
            intro2: '介绍',
            issuer: '发行方：',
            issuerInfo: 'TTBTC.com',
            channel: '发行渠道：',
            channelInfo: 'TTPay.info',
            pricing: '计价及结算方式：',
            pricingInfo: 'BTC币本位',
            strategy: '投资策略：',
            strategyInfo: '以BTC为标的为投资者在中短期内实现币量增长，实时动态调整交易模型，通过期货与期权的投资组合，适应多种类型的市场，无论币价波动率高低或币价涨跌，皆可为投资者创造稳健收益',
            strategyStyle: '策略风格：',
            strategyStyleInfo: '稳健型，历史最大单次回撤不超过3%',
            major: '主要交易产品',
            majorInfo: 'BTC现货及其金融衍生品（Bitmex BTC期货合约、Deribit BTC期权）',
            cycle: '基金周期',
            cycleInfo: '6个月',
            revenue: '收益规则',
            revenueInfo: '每实现30%盈利可提现利润币，6个月到期日可提现全部本金及利润币，实际收益以到期日兑付值为准，投资者获得总收益的70%',
            highest: '最高回撤',
            highestInfo: '30%，接近30%回撤位将立即平仓全部仓位并清盘结算，超过30%的亏损风险无需投资人承担(仅适用于几乎不会发生的极端情况，我们稳健型策略的历史最大回撤仅为3.03%)',
            Estimated: '预计收益：',
            EstimatedInfo: '120%～+∞年化收益',
            historyPer1: '历史成绩',
            historyPer2: '',
            fund1: 'TTBTC稳健型复合策略基金一期',
            fund2: 'TTBTC稳健型复合策略基金二期',
            fund1Img: 'https://ico-list.oss-cn-hangzhou.aliyuncs.com/cryptovalut/1555306765869TwD26JQGSp.png',
            fund2Img: 'https://ico-list.oss-cn-hangzhou.aliyuncs.com/cryptovalut/1555306795651KcSimzc7hx.png',
            downloadNow: '立即下载TTpay手机客户端，参与基金理财'
        }
    }
    export default {
        name: 'HelloWorld',
        watch: {
            'langFlag':{
                handler(v) {
                    if (v) {
                        this.language = this.lan.cn
                    } else {
                        this.language = this.lan.en
                    }
                }
            }
        },
        mounted() {
            let language = (navigator.language || navigator.browserLanguage).toLowerCase();
            if (language.indexOf('en') > -1) {
                this.langFlag = false;
            } else {
                this.langFlag = true;
            }
        },
        data() {
            return {
                lan: lan,
                language:{},
                langFlag: false
            }
        },
        methods: {
            moreHandler() {
                alert('更多')
            },
            downAndroid() {
                alert('下载安卓')
            },
            totalLang() {
                this.langFlag = !this.langFlag
            }
        }
    }
</script>

<style scoped>
    button {
        color: #fff;
        border: 0;
        outline: none;
        cursor: pointer;
    }

    .zh-en {
        position: absolute;
        top: 50px;
        right: 100px;
        background: #DD2C41;
        width: 90px;
        height: 30px;
        line-height: 30px;
        color: #fff;
        text-align: center;
        border-radius: 18px;
    }

    .banner {
        background: url("../assets/banner.jpg") no-repeat 0 -100px;
        background-size: 100%;
        height: 618px;
        width: 1920px;
        text-align: center;
        padding-top: 250px;
        line-height: 80px;
        position: relative;
    }

    .banner .banner-item p:first-child {
        font-size: 60px;
    }

    .banner .banner-item p:nth-child(2) {
        font-size: 28px;
    }

    .banner .banner-item p:last-child button {
        font-size: 16px;
        display: inline-block;
        width: 153px;
        height: 44px;
        background: #DD2C41;
        border-radius: 10px;
        text-align: center;
        line-height: 44px;

    }

    .advertising1 {
        height: 180px;
        width: 1920px;
        background: #DD2C41;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .advertising1 .advertising1-item {
        width: 1080px;
        height: 180px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .advertising1 .advertising1-item > div:first-child {
        font-size: 28px;
        color: #fff;
        line-height: 40px;
    }

    .advertising1 .advertising1-item > div:first-child p:first-child {
        font-size: 36px;
    }

    .advertising1 .advertising1-item > div:first-child p:last-child {
        font-size: 28px;
    }

    .advertising1 .advertising1-item > div:last-child button {
        width: 183px;
        height: 48px;
        background: #fff;
        font-size: 18px;
        color: #0F0F0F;
        border-radius: 18px;
    }

    .fund-top {
        width: 1920px;
        height: 760px;
        display: flex;
        justify-content: space-between;
    }

    .fund-top-text {
        display: flex;
        flex: 1;

        flex-direction: column;
        justify-content: center;
        align-items: left;
        padding: 0 100px 0 360px;
    }

    .fund-top-text-title {
        font-size: 56px;
        color: #282828;
    }

    .fund-top-text-title .fund-top-text-inline {
        width: 60px;
        height: 8px;
        background: #DD2C41;
        margin: 30px 0;

    }

    .fund-top-text-title p {
        font-weight: 900;
    }

    .fund-top-text-container {

    }

    .fund-top-text-container-pre {
        position: relative;
        margin-top: 20px;
    }

    .fund-top-text-container-pre:before {
        content: "\"";
        font-size: 50px;
    }

    .fund-top-text-container-pre:after {
        content: "\"";
        font-size: 50px;
        position: absolute;
        right: 0;
    }

    .fund-top-text-container p {
        font-size: 22px;
        color: #282828;
        line-height: 30px;
    }

    .fund-top-img {
        width: 749px;

        background: url("../assets/ttbtc.jpg") no-repeat 0 120px;
        background-size: 100%;
    }

    .advertising2 {
        width: 1920px;
        text-align: center;
        height: 180px;
        display: flex;
        align-items: center;
        justify-content: center;
        background: #FAFAFA;
    }

    .advertising2 div {
        line-height: 40px;
    }

    .advertising2 p:first-child {
        color: #DD2C41;
        font-size: 36px;
        font-weight: 900;
    }

    .advertising2 p:last-child {
        font-size: 22px;
        color: #282828;
    }

    .fund-middle {
        height: 1120px;
        width: 1920px;
        display: flex;
        margin: 120px 0;
    }

    .fund-middle .fund-middle-left {
        width: 750px;
        height: 1120px;
        background: url("../assets/fundintro.jpg") no-repeat;
        background-size: 100%;
        position: relative;
    }

    .fund-middle .fund-middle-left > div:first-child {
        position: absolute;
        top: 87px;
        right: 46px;
    }

    .fund-middle .fund-middle-left > div:first-child p:first-child,
    .fund-middle .fund-middle-left > div:first-child p:nth-child(2) {
        font-size: 56px;
        color: #282828;
        font-weight: 900;
    }

    .fund-middle .fund-middle-left > div:first-child p:last-child {
        width: 60px;
        height: 8px;
        background: #DD2C41;
        margin: 30px 0;
    }

    .fund-middle .fund-middle-right {
        width: 700px;
        font-size: 20px;
        line-height: 40px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .fund-middle .fund-middle-right .fund-middle-right-margin {
        margin-top: 30px;
    }

    .advertising3 {
        height: 300px;
        background: url("../assets/history.jpg") no-repeat;
        background-size: 100%;
        width: 1920px;
        padding-left: 360px;
        padding-top: 77px;

    }

    .advertising3 p:first-child {
        margin-top: 20px;
        font-size: 48px;
        color: #282828;
        font-weight: 900;
    }

    .advertising3 p:nth-child(2) {
        margin-top: 20px;
        font-size: 48px;
        color: #282828;
        font-weight: 900;
    }

    .advertising3 p:last-child {
        margin-top: 20px;
        width: 60px;
        height: 8px;
        background: #DD2C41;
    }

    .fund-bottom {
        width: 1920px;
    }

    .fund-bottom-con {
        width: 1080px;
        margin: 0 auto;
    }

    .fund-bottom .fund-bottom-item {

    }

    .fund-bottom .fund-bottom-item p {
        margin: 60px 0;
        color: #DD2C41;
        font-size: 30px;
        font-weight: 900;
    }

    .fund-bottom .fund-bottom-item img {
        width: 100%;
    }

    .footer {
        width: 1920px;
        margin-top: 120px;
        height: 240px;
        background: url("../assets/foot.jpg") no-repeat;
        display: flex;
        justify-content: center;
        align-items: center;

    }

    .footer p {
        font-size: 28px;
        color: #fff;
    }

    .footer-con {
        text-align: center;
    }

    .footer button {
        width: 153px;
        height: 44px;
        text-align: center;
        line-height: 44px;
        background: #DD2C41;
        border-radius: 10px;
        margin-top: 26px;
    }
</style>
