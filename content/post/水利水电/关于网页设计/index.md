---
title: 关于网页设计
description: 王亮
date: 2023-06-27
slug: 
image: 0.jpg
categories:
    - 作业
    - 王亮
    - 网页设计
---

# 期末考试

{{< quote >}}
```
<!doctype html>
<html>

<head>
    <meta charset="utf-8">
    <title>综合实例——招商银行</title>
    <style>
        /* CSS Document */

        * {
            margin: 0px;
            padding: 0px;
        }

        body {
            font-size: 12px;
            background-image: url(bg.gif);
            background-repeat: no-repeat;
            background-position: center top;
        }

        #wrapper {
            width: 980px;
            margin: 0 auto;
        }


        /*页首样式*/
        header {
            padding-bottom: 15px;
            background-image: url(main_line.jpg);
            background-repeat: repeat-x;
            background-position: bottom;
        }

        /*主导航样式*/
        .mainnavi {
            background-image: url(main_menu_bg.gif);
            background-repeat: repeat-x;
        }

        .mainnavi ul {
            font-size: 14.7px;
            font-weight: bold;
            padding-top: 9px;
            padding-bottom: 8px;
            margin-left: 30px;
        }

        .mainnavi li {
            display: inline;
            padding-right: 20px;
            padding-left: 17px;
            border-right-width: 1px;
            border-right-style: solid;
            border-right-color: #88180F;
        }

        /*副导航样式*/
        .subnavi ul {
            text-align: center;
            font-size: 12px;
            padding-top: 10px;
            padding-bottom: 10px;
        }

        .subnavi li {
            display: inline;
            border-right-width: 1px;
            border-right-style: solid;
            border-right-color: #999;
            padding-right: 10px;
            margin-right: 7px;
        }


        /*左侧边栏样式*/
        .leftsider {
            clear: none;
            float: left;
            width: 210px;
            border-right-width: 1px;
            border-bottom-width: 1px;
            border-left-width: 1px;
            border-right-style: solid;
            border-bottom-style: solid;
            border-left-style: solid;
            border-right-color: #CCC;
            border-bottom-color: #CCC;
            border-left-color: #CCC;
        }

        .leftsider ul {
            list-style-type: none;
            background-image: url(directory_bg_big.gif);
            padding-left: 50px;
        }

        .leftsider li {
            padding-top: 9px;
            padding-bottom: 7px;
        }

        .leftsider a:link,
        .leftsider a:visited {
            color: #000;
            text-decoration: none;
        }

        .leftsider a:hover {
            color: #F00;
        }

        /*右侧正文样式*/
        .content {
            clear: none;
            float: right;
            width: 723px;
            padding-left: 20px;
            border: 1px solid #CCC;
        }

        .content header {
            margin-left: -20px;
            background-image: url(content_bg.jpg);
            padding: 0px;
        }

        .content h1 {
            font-size: 14.7px;
            padding-top: 8px;
            padding-bottom: 7px;
            padding-left: 55px;
        }

        .content h2 {
            font-size: 12px;
            margin-top: 25px;
            margin-bottom: 10px;
        }

        .content p {
            line-height: 1.5em;
            margin-top: 10px;
            margin-bottom: 10px;
        }

        /*页底样式*/

        .clear {
            clear: both;
        }

        footer {
            background-image: url(bottom_bg.gif);
            background-repeat: repeat-x;
            margin-top: 15px;
        }

        footer ul {
            list-style-type: none;
            text-align: center;
            padding-top: 10px;
            padding-bottom: 10px;
        }

        footer li {
            display: inline;
            border-right-width: 1px;
            border-right-style: solid;
            border-right-color: #999;
            padding-right: 10px;
            margin-right: 7px;
        }

        /*主/副导航条、底部导航条超链接样式*/
        .mainnavi a:link,
        .mainnavi a:visited,
        footer a:link,
        footer a:visited {
            color: #FFF;
            text-decoration: none;
        }

        .mainnavi a:hover,
        footer a:hover {
            color: #000;
        }

        .subnavi a:link,
        .subnavi a:visited {
            color: #666;
            text-decoration: none;
        }

        .subnavi a:hover {
            color: #F00;
        }

        /*主/副导航条、底部导航条去掉边框*/
        .mainnavi .noborder,
        .subnavi .noborder,
        footer .noborder {
            border: none;
        }
    </style>
</head>

<body>
    <!-- 页面开始 -->
    <div id="wrapper">

        <!-- 页首开始 -->
        <header><a href="http://www.cmbchina.com/"><img src="logo.jpg" /></a>
            <!-- 主导航开始 -->
            <nav class="mainnavi">
                <ul>
                    <li><a href="#">主页</a></li>
                    <li><a href="#">个人业务</a></li>
                    <li><a href="#">公司业务</a></li>
                    <li><a href="#">小企业</a></li>
                    <li><a href="#">信用卡</a></li>
                    <li><a href="#">i理财</a></li>
                    <li><a href="#">商旅预定</a> </li>
                    <li class="noborder"><a href="#">今日招行</a></li>
                </ul>
            </nav>
            <!-- 主导航结束 -->
            <!-- 副导航开始 -->
            <nav class="subnavi">
                <ul>
                    <li><a href="#">金葵花理财</a></li>
                    <li><a href="#">私人银行</a></li>
                    <li><a href="#">出国金融</a></li>
                    <li><a href="#">个人贷款</a></li>
                    <li><a href="#">空中银行</a></li>
                    <li><a href="#">一卡通</a></li>
                    <li><a href="#">财富账户</a></li>
                    <li><a href="#">伙伴一生</a></li>
                    <li><a href="#">电子银行</a></li>
                    <li><a href="#">居家生活</a></li>
                    <li><a href="#">储蓄业务</a></li>
                    <li><a href="#">投资理财</a></li>
                    <li class="noborder"><a href="#">网上个人银行</a></li>
                </ul>
            </nav>
            <!-- 副导航结束 -->
        </header>
        <!-- 页首结束 -->

        <!-- 左侧边栏开始 -->
        <div class="leftsider">
            <aside>
                <nav>
                    <ul>
                        <li><a href="#">生意贷</a></li>
                        <li><a href="#">生意一卡通</a></li>
                        <li><a href="#">特色创新功能</a></li>
                        <li><a href="#">一手住房贷款</a></li>
                        <li><a href="#">二手住房贷款</a></li>
                        <li><a href="#">购房专享装修贷款</a></li>
                        <li><a href="#">购房专享车位贷款</a></li>
                        <li><a href="#">个人消费贷款</a></li>
                        <li><a href="#">信用贷款</a></li>
                        <li><a href="#">金葵花客户尊享贷款</a></li>
                        <li><a href="#">金卡客户专享贷款</a></li>
                        <li><a href="#">工资贷款</a></li>
                        <li><a href="#">个人汽车贷款</a></li>
                        <li><a href="#">商业用房贷款</a></li>
                        <li><a href="#">个人留学贷款</a></li>
                        <li><a href="#">全国个贷中心</a></li>
                        <li><a href="#">按揭贷款月供计算器</a></li>
                    </ul>
                </nav>
            </aside>
        </div>
        <!-- 左侧边栏结束 -->

        <!-- 右侧正文开始 -->
        <div class="content">
            <article>
                <header>
                    <h1>个人消费贷款</h1>
                </header>
                <section>
                    <h2>适用客户</h2>
                    <p>所有需要申请个人消费贷款的客户</p>
                    <p>购车、装修、旅游、留学……各种用途任您选择！贷款金额最高可达2000万元！30年超长期限，全方位满足您各种消费需求！把您的房产变成提款机，尽情享用！</p>
                    <p>期限：授信期限最长可达30年</p>
                    <p>成数：最高7成</p>
                </section>
                <section>
                    <h2>办理流程</h2>
                    <p>距您成功贷款，只有三步！</p>
                    <p>第一步：提交申请</p>
                    <p>第二步：银行审批</p>
                    <p>第三步：提款消费</p>
                </section>
                <section>
                    <h2>您需要准备的贷款申请资料</h2>
                    <p>1.身份证、婚姻证明</p>
                    <p>2.房产证</p>
                    <p>3.住址证明【至少任选其一】：水、电、气、电话或物管等费用账单</p>
                    <p>4.收入证明【至少任选其一】：工资证明/银行流水/所得税税单/社保记录/其他收入证明</p>
                    <p>5.用途证明：提供相应的交易证明材料 </p>
                </section>
                <section>
                    <h2>如何找到招商银行个人贷款？</h2>
                    <p>1.欢迎致电招商银行客户经理。</p>
                    <p>2.向就近招商银行网点提出申请。</p>
                    <p>3.拨打全国统一服务热线95555。</p>
                </section>
            </article>
        </div>
        <!-- 右侧正文结束 -->

        <div class="clear"></div>
        <!-- 页脚开始 -->
        <footer>
            <ul>
                <li><a href="#">安全说明</a></li>
                <li><a href="#">网站声明</a></li>
                <li><a href="#">隐私保密条款</a></li>
                <li><a href="#">网站地图</a></li>
                <li><a href="#">友情链接</a></li>
                <li><a href="#">加入收藏夹</a></li>
                <li><a href="#">人才招聘</a></li>
                <li class="noborder"><a href="#">手机一网通</a></li>
            </ul>
        </footer>
        <!-- 页脚结束 -->

    </div>
    <!-- 页面结束 -->
</body>

</html>

```
{{< /quote >}}

# 效果图
![效果图](1.png)

# 5.20作业
{{< quote >}}
```
<!DOCTYPE html>
<html lang="">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        h1 {
            text-align: center;
            color:#fff;
            font-size: 25px;
        }
        body {
            background: #eee url(bg.jpg) repeat-x 50% 50% fixed;
            text-decoration: none;
        }
        a:link {
            color: #eee;
        }
        a:hover {
            color: orange;
        }
        a:active {
            color: red;
        }
        a:visited {
            color: deepskyblue;
        }
        p:first-letter {
            font-weight: bold;
        }
        p+p+p {
            font-size: 18px;
        }
    </style>
</head>
<body>
    <h1>中国官方：预计“五一”假期后局部地区新冠疫情可能会出现小幅反弹</h1>
    <p>中新社北京5月8日电（记者 李京泽）中国国家疾病预防控制局传染病防控司副司长刘清8日在北京表示，预计“五一”假期后中国局部地区新完</p >
    <p>刘清说，近期，全国发热门诊监测结果显示，“五一”期间部分地区疫情出现小幅上升，但各地在院重症病例数均未出现大幅增加，医疗。</p >
    <p>刘清指出，专家研判认为，由于人群接种疫苗和新冠病毒感染后的免疫力存在随时间衰减的客观规律，全国疫情在2023年4月上旬达到202。</p >
    <p>他表示，人群免疫力衰退是一个逐步渐进的过程，当前中国人群总体免疫保护水平仍然较高。“五一”期间人群聚集和流动性增强，客观。</p >
    <p>关于如何做好防护，北京大学第一医院感染疾病科主任王贵强强调，从临床角度要关注重症高风险人群，即高龄老人、有严重基础病者，</p >
    <p>对于民众关心的二次感染新冠病毒怎么办，王贵强回应称，无论是二次感染还是新变异株导致的感染，临床表现目前看都是类似的，主要。</p >
</body>
</html>

```
{{< /quote >}}

# 5.24作业
{{< quote>}}
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        div{
            width:800px;
            margin: 10px auto;
            border: 1px solid #ccc;
            padding: 20px;
            background-color: #fafafa;
        }
        h1{
            text-align: center;
            margin: 30px 0;
        }
        .p1{
            font-size: 15px;
            color: #666;
            line-height: 1.8em;
            border: 1px solid #ccc;
            padding: 15px;
        }
        span{
            font-size: 35px;
            font-weight: bold;
            float: left;
            margin: 10px 3px 0 0;
        }
        h2{
            font-size: 18px;
        }
        li{
            list-style-type: none;
            height: 1.5em;
            margin-left: -38px;
        }
       a:link{
           color: deepskyblue;
        }
        a:hover{
            color: orange;
        }
        a:active{
            color: palevioletred;
        }
        a:visited{
            color: lawngreen;
        }
    </style>
</head>
<body>
<div>
    <a name="#top"></a><h1>城市长大并不是城市化</h1>
    <p class="p1"><span>从</span>数据看，自从1978年那场伟大变革开始，中国的城市化进程取得令人炫目的成就。1978年，中国的城市化水平还徘徊于8.5%上下。2012年，根据 中国社会科学院发布的《2012年社会蓝皮书》，2011年中国城镇人口数千年来首次超过农业人口，达到总人口50%以上。</p>
    
<h2>文章导读：</h2>
<ul>
<li><a href="#a1">城市化绝对不是土地的城市化</a></li>
<li><a href="#a2">“城市化大跃进”？</a></li>
<li><a href="#a3">城市化快了还是慢了</a></li>
<li><a href="#a4">城市化仍是未来发展动力</a></li>
</ul>
<p>鄂尔多斯康巴什，人烟稀少，被舆论成为中国各地新城中最为极端的缩影。</p>
<p>按照官方标准，中国的城市化率已经超过50%。国际历史表明，城市化率达到50%会进入加速过程，60%至70%进入减速阶段。</p>
<p>从数据看，自从1978年那场伟大变革开始，中国的城市化进程取得令人炫目的成就。1978年，中国的城市化水平还徘徊于8.5%上下。2012年，根据中 国社会科学院发布的《2012年社会蓝皮书》，2011年中国城镇人口数千年来首次超过农业人口，达到总人口50%以上。</p>
<p>正如上述不同的衡量标准一样，历经30多年发展之后，如何评价今日中国的城市化进程呢？</p>
<a name="a1"></a><h3>城市化绝对不是土地的城市化</h3>
<p>谈及中国城市化，第一个争论就是：到底什么是城市化？2012年初夏，中国社科院发布《2012年社会蓝皮书》说"我国人口城市化率已达50%"，这包含了没有城市户口的常住人口，它公布说城市户籍人口为33%。</p>
<p>对此，复旦大学发展与政策研究中心主任陆铭告诉《瞭望东方周刊》："国际上的城市化指标是城市人口占总人口的比重。国内外对城市人口的定义存在着巨大差异。 国外按照人口密度，一个地区人口达到一定密度称为城市，区域内的人全是城市人口。但中国城市人口定义分为城市户籍人口和城市常住人口。"</p>
<p>众所周知，常住人口与本地城市人口，享受到的服务存在差异。陆铭举例，公租房、廉租房在大多数城市并不覆盖非户籍人口。</p>
<p>北京大学城环学院旅游研究与规划中心主任吴必虎把这一情况视为"半城市化"。他说："这个群体在城市上班，户口还在农村，但在人口统计时算城镇化人口。而地 方政府为了节约社会保险、医疗保险、农民工子女就学等开支，不太愿意把他们纳入城市户口。所以人口的职业城市化快于人口社会地位的城市化，表现为半城市化的现象。" 在中国，比人口城市化更快的是土地城市化。据陆铭研究，城市扩张现象在西部最为严重，中部其次。他对280多个城市建成区的扩张 速度与非农业人口增长速度之比进行了分析：全国来看，这个速度比是两倍。东部城市差别不大，西部是非农业人口增速的三倍。他认为，中国土地城市化扩张过快 主要在于内地。</p>
<p>吴必虎说："城市面积扩张过快源于地方政府急切渴求土地，一些城市征用土地报给国务院审批时，可能已经提前用完了未来二十年的土地。地方政府、开发商及建筑商等利益链上的人为获得更多收益，热衷于推动土地城市化。"</p>
<p>"城市化绝对不是土地的城市化。但只要国家政策允许，地方政府尽量把农业用地转化成非农业用地，为了财政创收和经济的增长。"陆铭说。</p>
<a name="a2"></a><h3>"城市化大跃进"？</h3>
<p> 中国科学院院士陆大道曾认为："城市化大跃进"已超出城市化正常轨道，出现了盲目追求大规模以及严重浪费土地等令人不安的一些趋向。</p>
<p>近年来，尽管国务院三令五申控制开发区和城市土地占用，但城市"大"规划和建成区蔓延式大扩张的现象还在继续。</p>
<p>吴必虎认为，这带来的最大危害是社会不公。"大量土地是来自附近农村，在征用过程中，地方政府以低价从农民手里获得土地，转手以几倍甚至上百倍的价格卖出，即所谓的土地财政。"</p>
<p>已经被城市化的土地又是如何被利用的呢？吴必虎介绍："不少城市在建第二座城市，以工业开发区、高科技开发区、工业园区等形式出现，这些开发区60%以上是不成功的，出现大量圈地抛荒现象。新区房子卖不掉，工厂垮台。" 鄂尔多斯康巴什新城，曾引起极大关注，由于工业区没有工业，住宅区人烟稀少，被外界称作"鬼城"，被舆论称为中国各地新城中最为极端的缩影。</p>
<p>陆铭说，这反映了用地指标超过实际用地需求。人们试图给内地城市更多用地指标，提供更多经济发展的空间，却忽略了经济发展的客观规律。</p>
<p>陆铭团队的研究成果显示，与发达国家、同等发展水平的国家相比，中国虽然劳动力丰富，但经济发展创造就业的能力是相对偏低的。目前的用地政策在鼓励偏资本的产业，影响经济吸纳就业的能力。</p>
<p>"内地土地利用效率低，导致城市面积扩张，实际上没有招来那么多厂，创造不了预期的就业，农业人口变成非农业人口速度就慢了。"陆铭说。</p>
<p>在急速的城市土地扩张中，最令陆铭担忧的是，哪里地便宜企业去往哪里，不少企业搬离东部，造成一种产业转移的假象。企业的生产和运输成本上升，尤其对于外贸企业而言，远离港口成本倍增，不利于中国产品与东南亚国家竞争。 相比西部出现的土地抛荒，东部地区土地可谓寸土寸金，不少城市瞄上海滩山头，于是出现了大量填海削山，造出工业、农业用地的情况。</p>
<p>"这种代价高昂的拓地方法，严重破坏生态环境，一些岛屿已经消失。土地资源按照计划经济的方式配置，未来十年内必须要改变。纠错成本也是一种资源浪费。"陆铭说。</p>
<a name="a3"></a><h3>城市化快了还是慢了</h3>
<p>"正常的城市化是历史发展的必然趋势，但过快的城市化弊大于利，我们应当认真考虑城市化速度了。"吴必虎说，为谋求高速发展，近年在一些党政部门甚至兴起一股"5+2、白加黑"的作风。</p>
<p>"强 调短期内必须把路修好、设施建好。跟老百姓商量来商量去，土地开发不成，因此催生强拆现象。很多城市没有规划好就仓促上马，有的边规划边建设，更有城市建 设后补规划。"吴必虎说，"为什么城市下水道没人投资，为什么一些地方农民子弟学校被拆掉？土地开发出GDP，而服务业、农业、基础设施、民政福利投资等 对GDP快速增长很难起到立竿见影的效果，所以地方政府不太愿投这个钱。"</p>
<p>吴必虎认为，一些地方政府单纯理解经济建设就是GDP增长。</p>
<p>不过陆铭认为，中国城市化的速度还是太慢了。目前城市化的进程应与工业化的进程相配套，中国二、三产业占GDP总量90%，官方公布的50%的城镇人口在从事占GDP10%的第一产业，一个直接后果是城乡收入差距拉大。</p>
<p>从上世纪80年代开始，中国就有不少学者开始倡导小城镇建设，认为发展中小城镇可以避免大城市存在的问题。一直以来，鼓励小城镇发展也是中国一项重要政策。包括目前的户籍制度改革重点也是中小城市，大城市限制仍旧比较严格。</p>
<p>"这 种提法未必是正确的。我们没有充分认识到大城市发展的好处，大城市有更大的创造就业，增加收入，提升劳动生产率的作用。大城市人口密度高，有节约能源、占 地的好处。大城市出现拥挤、污染、犯罪率高的问题，放在全世界看，并不一定与城市规模正相关。这些问题，可以通过技术和管理加以改进，而不能通过限制城市 的发展来逃避这些现象。"陆铭说。</p>
<p>陆铭认为，长期以来，我国的户籍制度制约着人口城市化的进程。经济发展，产业的成长没有充分吸纳农民进城。不少农村人在城市打工，回老家盖房，在城市干不动了还是告老回乡，从这个角度看，中国的城市化进程实际上是慢的。 对于中国户籍制度，陆铭曾在多家媒体写文章呼吁改革。"户籍制度本身造成大量成本，比如收入不均等、劳动力市场机会不均等，一些大城市形成外来人口聚集区，居民幸福指数不高，对于政府的信任程度下降。政府大量的维稳成本一定程度上也在为户籍管理带来的负面效应埋单。"</p>
<p>他 呼吁加快户籍放宽的速度，降低门槛。在他看来，上海40%的外地人，广东一些城市50%到70%的人口没有本地户籍，这种管理太严格了。其实一些高门槛没 有必要，分工差异使得大城市更能为低技能劳动者创造就业机会，而这些岗位又是大城市所必需的。户籍制度造成高低技能劳动者身份的差距，对城市和谐发展是不 利的。</p>
<p>"要以是否长期稳定就业，缴纳社会保障金来衡量是否获得户籍。一个在上海送了十年牛奶的人，为什么就不能长期在上海待下去呢，既然大家都需要这样的服务？"陆铭说。</p>
<a name="a4"></a><h3>城市化仍是未来发展动力</h3>
<p>按照官方标准，中国的城市化率已经超过50%。国际历史表明，城市化率达到50%会进入加速过程，60%至70%进入减速阶段。</p>
<p>"随着政策对人口自由流动限制的放宽，城市化的速度还会加快。"陆铭说。 吴必虎认为，中国各地城市化水平不尽相同：西部处于初步阶段，中部进入快速发展期，而像北京这样的东部大城市已进入了后工业化的时代，城市化基本完成。 "东部城市大框架已经拉好，城市服务和管理还跟不上。政府应从市民生活质量上考虑，比如下水道、城市交通的建设等等。具体项目和规划，需要长远的考虑，不能这一届政府做得小模小样的，下一届再重新修。欧洲的下水道一百多年历史还在使用，而我们不断地在修。"吴必虎说。</p>
<p>与大多数学者一样，陆铭和吴必虎都认为，中国的城市化是支持未来中国发展的主要动力。</p>
<p>这种观点认为，目前中国经济发展过于依赖投资，而拉动消费，很少有人意识到大城市的发展创造着多大的消费潜能。</p>
<p>根据陆铭的研究，在收入、工作等相似的情况下，没有城市户口的人比拥有城镇户籍的人消费低30%。大量城镇常住人口的农转非，意味着巨大的消费空间。 "不管从提高劳动生产率，促进产业结构调整，帮助中国经济摆脱，城市化无疑是推动社会发展的重大引擎。"陆铭说。</p>
<p>社会经济的发展需要内在动力。"以往，工业是社会发展的引擎，但未来现代制造业水平很高，少数高知识或职业技能的人即可操控完成。农业的机械化，生产效率的提高，导致农村土地不需要那么多人耕种了。"吴必虎说。</p>
<p>他认为，未来城市化主要靠服务业，现代服务业包含创业产业、旅游业、金融服务业等等，未来城市化，很多人不需要从事体力活动。大家希望在有限的资源和能源供给下，都能在城市中生活好。</p>
<p>欧美以往曾走过大量消耗煤、石油等能源，大量占用土地的方式。"这种模式在中国行不通，中国人口太多，必须另辟新径，如何发展现代服务业推动城市化，中国人似乎还没有完全做好准备。"吴必虎表示。</p>
<p align="center"style="text-indent:0; "><a href="#top">返回顶部</a></p>
</div>
</body>
</html>
```
{{< /quote >}}

### 效果图
![效果图](效果图.jpg)


# 5.30作业
{{< quote>}}
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        .all{
            width: 800px;
            height: 500px;
            border: 1px solid #ccc;
            margin: 50px auto;
            box-shadow: #ddd 10px 10px 10px;
            padding: 50px;
        }
        .left{
            width: 200px;
            height: 500px;
            text-align: center;
            float: left;
        }
        .top{
            width: 200px;
            height: 400px;
            background-color: #afafaf;
            display: table-cell;
            vertical-align: middle;
        }
        .bottom{
            margin: 50px;
        }
        .right{
            width: 550px;
            height: 500px;
            border: 1px solid #ccc;
            float: right;
        }
    </style>
</head>
<body>
<div class="all">
    <div class="left">
        <div class="top">头像</div>
        <div class="bottom">姓名</div>
    </div>
    <div class="right">自我描述</div>
</div>
</body>
</html>
```
{{< /quote >}}

### 效果图
![效果图](2.png)

# 5.31作业
{{< quote>}}
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        * {
            /* 通配符，目的是消除所有默认格式中的距离影响 */
            padding: 0;
            margin: 0;
        }

        .container {
            width: 800px;
            border: 1px solid #888;
            margin: 30px auto;
        }

        .header {
            width: 800px;
            background-color: #eee;
            padding: 20px 0;
        }

        h1 {
            text-align: center;
            font-size: 28px;
            font-weight: normal;
        }

        .main {
            width: 800px;
            overflow: hidden;
        }

        .sidebar {
            width: 120px;
            height: 450px;
            background: url("grey-shadow-top.gif") repeat-x #eee;
            padding: 20px 0 0 20px;
            float: left;
        }

        h2 {
            font-size: 20px;
            margin-bottom: 20px;
        }

        ul {
            padding-left: 20px;
            line-height: 2em;
        }

        a {
            color: black;
            text-decoration: none;
        }

        a:hover {
            color: orange;
        }

        .content {
            width: 500px;
            background: url("white-shadow-top.gif") repeat-x;
            padding: 20px 10px;
            float: left;
        }

        p {
            margin-top: 1.5em;
            text-indent: 2em;
            line-height: 1.5em;
        }

        .footer {
            background-color: #ddd;
            padding: 15px;
        }
    </style>
</head>
<body>
<div class="container">
    <div class="header">
        <h1>页面标题</h1>
    </div>
    <div class="main">
        <div class="sidebar">
            <h2>左侧边栏</h2>
            <ul>
                <li><a href="#">链接一</a></li>
                <li><a href="#">链接二</a></li>
                <li><a href="#">链接三</a></li>
                <li><a href="#">链接四</a></li>
                <li><a href="#">链接五</a></li>
            </ul>
        </div>
        <div class="content">
            <h2>主体内容的标题</h2>
            <p>文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段。</p>
            <p>文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段。</p>
            <p>文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段。</p>
            <p>文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段落文章的段。</p>
        </div>
        <div class="sidebar">
            <h2>右侧边栏</h2>
            <ul>
                <li><a href="#">链接一</a></li>
                <li><a href="#">链接二</a></li>
                <li><a href="#">链接三</a></li>
                <li><a href="#">链接四</a></li>
                <li><a href="#">链接五</a></li>
                <li><a href="#">链接六</a></li>
                <li><a href="#">链接七</a></li>
            </ul>
        </div>
    </div>
    <div>
```
{{< /quote >}}
![效果图](3.png)
