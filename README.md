#炳盛级
兵圣帝国排行榜
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>兵圣帝国正统排行榜</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            font-family: 'Microsoft YaHei', 'PingFang SC', sans-serif;
            background: #fff;
            color: #333;
            min-height: 100vh;
            font-size: 15px;
            line-height: 1.8;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 40px 30px;
        }

        h1 {
            font-size: 28px;
            font-weight: bold;
            color: #000;
            margin-bottom: 5px;
            letter-spacing: 2px;
        }
        h2 {
            font-size: 18px;
            font-weight: bold;
            color: #c00;
            margin: 30px 0 15px;
            letter-spacing: 1px;
        }
        h3 {
            font-size: 16px;
            font-weight: bold;
            color: #000;
            margin: 25px 0 10px;
        }

        .info-block {
            margin-bottom: 8px;
            color: #333;
        }
        .info-block .label {
            font-weight: bold;
            color: #000;
        }

        .notice {
            color: #c00;
            margin: 15px 0 25px;
            line-height: 2;
        }

        .org-list {
            line-height: 2.2;
            color: #333;
        }
        .org-list .tier-name {
    字体粗细：粗体；
    颜色：#000；
    右边距：5px；
        }

    .divider{
    边框：无；
    border-top:1px实体#ddd；
    页边距：25px0；
        }

    .nav{
    文本对齐：右；
    底边距：20px；
    font-size:14px；
        }
    .nav a{
    颜色：#666；
    文字修饰：无；
    margin-left:20px；
    光标：指针；
        }
    .nav a：悬停{color：#000；}

    .modal-bg{
    显示：无；
    位置：固定；
    top:0；
    左：0；
    右：0；
            bottom: 0;
            background: rgba(0,0,0,0.5);
            z-index: 200;
            align-items: center;
            justify-content: center;
        }
        .modal-bg.on {
            display: flex !important;
        }
        .modal-box {
            background: #fff;
            border: 1px solid #ccc;
            padding: 40px 50px;
            text-align: center;
            min-width: 300px;
        }
        .modal-box h3 {
            margin-bottom: 15px;
            font-size: 16px;
            color: #333;
        }
        .modal-box .qq {
            font-size: 28px;
            font-weight: bold;
            color: #c00;
            margin: 15px 0;
            letter-spacing: 3px;
        }
        .modal-box .hint {
            color: #666;
            font-size: 14px;
            margin-bottom: 20px;
        }
        .modal-box button {
            padding: 10px 40px;
            border: 1px solid #999;
            background: #fff;
            cursor: pointer;
            font-size: 14px;
        }
        .modal-box button:hover {
            background: #f5f5f5;
        }

        .page { display: none; }
        .page.on { display: block; }
    </style>
</head>
<body>

<div class="container">

    <div class="nav">
        <a href="javascript:void(0)" onclick="go('home')">首页</a>
        <a href="javascript:void(0)" onclick="go('about')">关于</a>
        <a href="javascript:void(0)" onclick="showModal()">投稿</a>
    </div>

    <!-- ===== 首页 ===== -->
    <div id="home" class="page on">
        <h1>兵圣帝国正统排行榜</h1>

        <h2>（副标题待填写）</h2>

        <div class="info-block">本榜依据公示统计，接受公众监督。异议请于公示期内反馈。</div>

    <div class="info-block"><span class="label">排行榜人：</span>(待填写)</div>
    <div class="info-block"><span class="label">时间：</span>(待填写)</div>

    <div class="notice">
    <span class="label">公告：</span>（待填写）
    </div>

    <h3>组织排行榜：</h3>

    <div class="组织列表">
    <div><span class="tier-name">T1：</span>虚位以待</div>
    <div><span class="tier-name">T2：</span>虚位以待</div>
    <div><span class="tier-name">T3：</span>虚位以待</div>
    <div><span class="tier-name">T4：</span>虚位以待</div>
    </div>
    </div>

    <! -- ===== 关于页 ===== -->
    <div id="about"class="page">
    <h1>关于兵圣帝国</h1>

    <div class="info-block"style="margin-top:30px；"><span class="label">成立时间：</span>2024年</div>
    <div class="info-block"><span class="label">性质：</span>正规官方排名榜站</div>
    <div class="info-block"><span class="label">来源地：</span>左丘明旗下</div>

    <hr class="divider">

    <h3>历史沿革</h3>
    <div class="组织列表">
    <div><span class="tier-name">前身：</span>神影-SY(联部制度)</div>
    <div><span class="tier-name">演变：</span>兵社（赧染旗下）</div>
    <div><span class="tier-name">现制：</span>圣社（合制度）</div>
    </div>

    <hr class="divider">

    <div style="color：#333；线高度：2；上距：30px；">
本排名无个人恩怨，无利益冲突，仅为各组织提供一个参考依据。<溴><溴>
            为人民服务，公平公正。
    </div>        为人民服务，公平公正。>
    </div>div>

</div>

<div班级="modal-bg”<身份标准="形态">
<div班级="模态框">
        <H3>官方交流群</H3>
<div班级="qq">707302999</div>
        <div班级="提示">加入群聊进行投稿</div>
<按钮onClick="hideModal()">关闭</按钮>
    </div>
</div>

<脚本>
    功能 去(身份标识) {
文件。querySelectorAll('.page').forEach(功能(p){
p.classList.remove('开')；
        });
文件。getElementById(身份标识).classList.add('开')；
窗户。scrollTo(0，0)；
    }

功能ShowModal(){功能ShowModal(){
功能ShowModal(){
    
形态。classList。添加('开')；
    }

功能hideModal(){功能hideModal(){
var模态的=文档.getElementById('modal')；var模态的=文档.getElementById('modal')；
模态。 风格.显示='无';
形态。classList。移除('开')；
    }

文件。getElementById('modal').addEventListener('单击'，功能(e){
如果(e.目标===这){
hideModal()；
        }
    });
</脚本>

</身体>
</超文本标记语言>
