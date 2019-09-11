<template>
    <div class="all_parameter">
        <div class="input_data">
            <div class="container">
                <form method="post">
                    <!--                男-->
                    <div class="male row">
                        <div class="sex_man col-md-2">男生</div>
                        <div class="surname_m col-md-3">
                            <input type="text" class="" placeholder="姓氏">
                            <input type="text" class="" placeholder="名字">
                        </div>
                        <div class="zodiac_m col-md-2">
                            <select class="">
                                <option value="属鼠">&nbsp;属鼠</option>
                                <option value="属牛">&nbsp;属牛</option>
                                <option value="属虎">&nbsp;属虎</option>
                                <option value="属兔">&nbsp;属兔</option>
                                <option value="属龙">&nbsp;属龙</option>
                                <option value="属蛇">&nbsp;属蛇</option>
                                <option value="属马">&nbsp;属马</option>
                                <option value="属羊">&nbsp;属羊</option>
                                <option value="属猴">&nbsp;属猴</option>
                                <option value="属鸡">&nbsp;属鸡</option>
                                <option value="属狗">&nbsp;属狗</option>
                                <option value="属猪">&nbsp;属猪</option>
                            </select>
                        </div>
                        <div class="month_m col-md-3">
                            <select class="">
                                <option value="1月">&nbsp;1月</option>
                                <option value="2月">&nbsp;2月</option>
                                <option value="3月">&nbsp;3月</option>
                                <option value="4月">&nbsp;4月</option>
                                <option value="5月">&nbsp;5月</option>
                                <option value="6月">&nbsp;6月</option>
                                <option value="7月">&nbsp;7月</option>
                                <option value="8月">&nbsp;8月</option>
                                <option value="9月">&nbsp;9月</option>
                                <option value="10月">&nbsp;10月</option>
                                <option value="11月">&nbsp;11月</option>
                                <option value="12月">&nbsp;12月</option>
                            </select>
                            <select>
                                <option value="1日">&nbsp;1日</option>
                                <option value="2日">&nbsp;2日</option>
                                <option value="3日">&nbsp;3日</option>
                                <option value="4日">&nbsp;4日</option>
                                <option value="5日">&nbsp;5日</option>
                                <option value="6日">&nbsp;6日</option>
                                <option value="7日">&nbsp;7日</option>
                                <option value="8日">&nbsp;8日</option>
                                <option value="9日">&nbsp;9日</option>
                                <option value="10日">&nbsp;10日</option>
                                <option value="11日">&nbsp;11日</option>
                                <option value="12日">&nbsp;12日</option>
                                <option value="13日">&nbsp;13日</option>
                                <option value="14日">&nbsp;14日</option>
                                <option value="15日">&nbsp;15日</option>
                                <option value="16日">&nbsp;16日</option>
                                <option value="17日">&nbsp;17日</option>
                                <option value="18日">&nbsp;18日</option>
                                <option value="19日">&nbsp;19日</option>
                                <option value="20日">&nbsp;20日</option>
                                <option value="21日">&nbsp;21日</option>
                                <option value="22日">&nbsp;22日</option>
                                <option value="23日">&nbsp;23日</option>
                                <option value="24日">&nbsp;24日</option>
                                <option value="25日">&nbsp;25日</option>
                                <option value="26日">&nbsp;26日</option>
                                <option value="27日">&nbsp;27日</option>
                                <option value="28日">&nbsp;28日</option>
                                <option value="29日">&nbsp;29日</option>
                                <option value="30日">&nbsp;30日</option>
                                <option value="31日">&nbsp;31日</option>
                            </select>
                        </div>
                        <div class="constellation_m col-md-2">
                            <select class="">
                                <option value="白羊座">&nbsp;白羊座</option>
                                <option value="金牛座">&nbsp;金牛座</option>
                                <option value="双子座">&nbsp;双子座</option>
                                <option value="巨蟹座">&nbsp;巨蟹座</option>
                                <option value="狮子座">&nbsp;狮子座</option>
                                <option value="处女座">&nbsp;处女座</option>
                                <option value="天秤座">&nbsp;天秤座</option>
                                <option value="天蝎座">&nbsp;天蝎座</option>
                                <option value="射手座">&nbsp;射手座</option>
                                <option value="魔蝎座">&nbsp;魔蝎座</option>
                                <option value="水瓶座">&nbsp;水瓶座</option>
                                <option value="双鱼座">&nbsp;双鱼座</option>
                            </select>
                        </div>
                    </div>
                    <div class="female row">
                        <div class="sex_women col-md-2">女生</div>
                        <div class="surname_f col-md-3">
                            <input type="text" class="" placeholder="姓氏">
                            <input type="text" class="" placeholder="名字">
                        </div>
                        <div class="zodiac_f col-md-2">
                            <select class="">
                                <option value="属鼠">&nbsp;属鼠</option>
                                <option value="属牛">&nbsp;属牛</option>
                                <option value="属虎">&nbsp;属虎</option>
                                <option value="属兔">&nbsp;属兔</option>
                                <option value="属龙">&nbsp;属龙</option>
                                <option value="属蛇">&nbsp;属蛇</option>
                                <option value="属马">&nbsp;属马</option>
                                <option value="属羊">&nbsp;属羊</option>
                                <option value="属猴">&nbsp;属猴</option>
                                <option value="属鸡">&nbsp;属鸡</option>
                                <option value="属狗">&nbsp;属狗</option>
                                <option value="属猪">&nbsp;属猪</option>
                            </select>
                        </div>
                        <div class="month_f col-md-3">
                            <select class="">
                                <option value="1月">&nbsp;1月</option>
                                <option value="2月">&nbsp;2月</option>
                                <option value="3月">&nbsp;3月</option>
                                <option value="4月">&nbsp;4月</option>
                                <option value="5月">&nbsp;5月</option>
                                <option value="6月">&nbsp;6月</option>
                                <option value="7月">&nbsp;7月</option>
                                <option value="8月">&nbsp;8月</option>
                                <option value="9月">&nbsp;9月</option>
                                <option value="10月">&nbsp;10月</option>
                                <option value="11月">&nbsp;11月</option>
                                <option value="12月">&nbsp;12月</option>
                            </select>
                            <select>
                                <option value="1日">&nbsp;1日</option>
                                <option value="2日">&nbsp;2日</option>
                                <option value="3日">&nbsp;3日</option>
                                <option value="4日">&nbsp;4日</option>
                                <option value="5日">&nbsp;5日</option>
                                <option value="6日">&nbsp;6日</option>
                                <option value="7日">&nbsp;7日</option>
                                <option value="8日">&nbsp;8日</option>
                                <option value="9日">&nbsp;9日</option>
                                <option value="10日">&nbsp;10日</option>
                                <option value="11日">&nbsp;11日</option>
                                <option value="12日">&nbsp;12日</option>
                                <option value="13日">&nbsp;13日</option>
                                <option value="14日">&nbsp;14日</option>
                                <option value="15日">&nbsp;15日</option>
                                <option value="16日">&nbsp;16日</option>
                                <option value="17日">&nbsp;17日</option>
                                <option value="18日">&nbsp;18日</option>
                                <option value="19日">&nbsp;19日</option>
                                <option value="20日">&nbsp;20日</option>
                                <option value="21日">&nbsp;21日</option>
                                <option value="22日">&nbsp;22日</option>
                                <option value="23日">&nbsp;23日</option>
                                <option value="24日">&nbsp;24日</option>
                                <option value="25日">&nbsp;25日</option>
                                <option value="26日">&nbsp;26日</option>
                                <option value="27日">&nbsp;27日</option>
                                <option value="28日">&nbsp;28日</option>
                                <option value="29日">&nbsp;29日</option>
                                <option value="30日">&nbsp;30日</option>
                                <option value="31日">&nbsp;31日</option>
                            </select>
                        </div>
                        <div class="constellation_f col-md-2">
                            <select class="">
                                <option value="白羊座">&nbsp;白羊座</option>
                                <option value="金牛座">&nbsp;金牛座</option>
                                <option value="双子座">&nbsp;双子座</option>
                                <option value="巨蟹座">&nbsp;巨蟹座</option>
                                <option value="狮子座">&nbsp;狮子座</option>
                                <option value="处女座">&nbsp;处女座</option>
                                <option value="天秤座">&nbsp;天秤座</option>
                                <option value="天蝎座">&nbsp;天蝎座</option>
                                <option value="射手座">&nbsp;射手座</option>
                                <option value="魔蝎座">&nbsp;魔蝎座</option>
                                <option value="水瓶座">&nbsp;水瓶座</option>
                                <option value="双鱼座">&nbsp;双鱼座</option>
                            </select>
                        </div>
                    </div>
                    <div class="start_test">
                        <input name="" type="submit" value="开始测试" style="background: orange;">
                    </div>
                </form>
            </div>
        </div>
        <div class="res col-md-10">
            <div class="res_header">
                <h2>配对结果：</h2>
            </div>
            <div class="friendly_score col-md-12">
                <h3>友情指数：★★★</h3>
            </div>
            <div class="love_score col-md-12">
                <h3>爱情指数：★★★★</h3>
            </div>
            <div class="marriage_score col-md-12">
                <h3>婚姻指数：★★★</h3>
            </div>
            <div class="family_score col-md-12">
                <h3>亲情指数：★★★★</h3>
            </div>
            <div class="content col-md-12">
                <h3>详细分析：</h3>
                <p></p>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "InputData"
    }
</script>

<style type="text/css">

.all_parameter {
    background: #EEEEEE;
    width: 100%;
    height: auto;
    margin: 0 auto;
}
.input_data input{
    width: 75px;
    padding: 2px;
}
.input_data select{
    width: 75px;
    padding: 2px;
}
.input_data{
    width: 800px;
    margin: 0 auto;
}
.male {
    height: auto;
    margin: 0 auto;
    padding: 20px;
    background: #EEEEEE;
    border: 3px solid #D1D1D1;

}
.female {
    height: auto;
    margin: 0 auto;
    padding: 20px;
    background: lightblue;
}
.start_test {
    height: auto;
    margin: 0 auto;
    background: burlywood;
}
.sex_man{
    width: 60px;
    height: auto;
    text-align: center;
    padding: 5px;
    background: aliceblue;
}
.sex_women{
    width: 60px;
    height: auto;
    text-align: center;
    padding: 5px;
    background: aliceblue;
}
.surname_m {
    width: 60px;
    height: auto;
    padding: 5px;
    background: aquamarine;
}
.zodiac_m {
    width: 60px;
    height: auto;

    padding: 5px;
    background: blanchedalmond;
}
.month_m {
    width: 60px;
    height: auto;
    padding: 5px;
    background: lightblue;
}
.constellation_m {
    width: 60px;
    height: auto;
    padding: 5px;
    background: chocolate;
}

.sex_women{
    width: 60px;
    height: 30px;
    text-align: center;
    padding: 5px;
    background: aliceblue;
}
.surname_f {
    width: 60px;
    height: auto;
    padding: 5px;
    background: aquamarine;
}
.zodiac_f {
    width: 60px;
    height: auto;

    padding: 5px;
    background: blanchedalmond;
}
.month_f {
    width: 60px;
    height: auto;
    padding: 5px;
    background: crimson;
}
.constellation_f {
    width: 60px;
    height: auto;
    padding: 5px;
    background: chocolate;
}

.res {
    width: 800px;
    margin: 0 auto;
    background: lavender;
}
.res_header {
    text-align: left;
    margin: 20px;
}
.friendly_score {
    text-align: left;
    margin: 10px;
}
.love_score {
    text-align: left;
    margin: 10px;
}
.marriage_score {
    text-align: left;
    margin: 10px;
}
.family_score {
    text-align: left;
    margin: 10px;
}
.content {
    text-align: left;
    margin: 10px;
}
</style>