# 根据标题或关键字生成内容-免费api接口

### 官网在线体验:
www.lycecho.com

### 请求API:
http://www.lycecho.com/api/getContent


### 请求方式:
POST

| 名称  | 类型  | 必填  | 说明  |
| :------------: | :------------: | :------------: | :------------: |
|title         	|string	|是|主标题|
|secretkey         |string	|是|接口密钥可在购买接口后，我的服务里获取|
|image         	|int	|否|自动配图， 默认值：0，1/开启|
|tag           	|int	|否|自动标签， 默认值：0，1/开启|
|quantity          |int	|否|聚合数量， 默认值：5，最大聚合数量10|
|limit         	|int	|否|单聚字符数限制，默认值：0（不限制，推荐）|
|type          	|string	|否|返回输出类型，默认：JSON，JSON / HTML|
|log           	|int	|否|增加锚点目录， 默认值：0，1/开启|
|logname           |string	|否|锚点目录名，默认：“本文目录”|
|order         	|int	|否|增加序列号， 默认值：0，1/开启|
|h2            	|int	|否|保留h2标签， 默认值：0，1/开启|
|class         	|string	|否|自定义class样式名， 默认值：“zltheme”|
|twoTyle           |int	|否|启用双标题，默认：0/关闭，1/开启（需自定义符号）   |
|topParagraph      |string	|否|自定义首段落“{主关键词}”，“{副关键词}”|
|endParagraph      |string	|否|自定义尾段落“{主关键词}”，“{副关键词}”|
|f1            	|string	|否|自定义中间分隔符号，启用双标题才生效|
|f2            	|string	|否|自定义结尾符号，启用双标题才生效|
|filter            |string	|否|自定义过滤内容，英文“,”逗号分隔|
|originalToken            |string	|否|伪原创token|
|originalV            |int	|否|伪原创6个级别 1,2,3,6,7,9|


### 联系方式
<img src="http://cj.lycecho.com/article/wp-content/uploads/2022/10/%E5%BE%AE%E4%BF%A1%E5%8F%B7-220x300.jpg" width="200">


### 返回实例:
```json
{"code":1,
  "data":{
    "sid":"529a0eefa1d15795b9561fd9e4ed0cdb",
    "title":"在国外，资深的软件测试人员大多是手动测试，他们厉害之处在于测试用例的设计，但在国内，很多测试人员都把自动化测试当成很厉害的资本，为什么",
    "content":"\u003cdiv class=\"_article\"\u003e\u003cp\u003e\u003cp\u003e我看到国外开发工具有自动化 测试工具，觉得很厉害，但没有用过，他开发好了代码就输入数据自动进行测试，类似深度学习的测试，然后统计出准确率。这些数据类似测试用例？国内外谁用手动还是自动，我觉得网页测试都是手动的，为了让测试有活干，往往程序没写好就开始测试。\u003c/p\u003e\u003c/p\u003e\u003cp\u003e\u003cp\u003e软件测试行业近年来可谓发展得风生水起，许多人都想转行从事软件测试工作，希望在软件测试行业有所建树。那么大家最关心的肯定就是软件测试好不好就业了，今天优就业小编就来为大家解答一下。\u003c/p\u003e\u003cp\u003e一直以来国内的软件行业都更加重视软件开发，而一定程度上忽略了软件测试，导致国内测试人员与开发人员的比例严重失衡。国外软件测试人员与开发人员的比例接近1比1，国外的软件公司十分重视软件的质量与用户体验，重视软件测试工作，所以他们的软件质量往往比较好。而国内的软件测试人员与开发人员的比例还不足1比4，这就意味着软件测试人才在国内是极度缺乏的。而现在很多国内的软件公司慢慢意识到了软件质量的重要性，也在逐步增加对软件测试人才的招聘。在未来的几年甚至十几年内，软件测试的人才缺口会非常大，所以完全不用担心软件测试的就业问题，软件测试人才短时间内并不会饱和。\u003c/p\u003e\u003cp\u003e而且软件测试行业的就业面也十分广，不像你学一种开发语言就只能做这种开发语言的工作。软件测试分为功能测试、性能测试、自动化测试、接口测试几个大方向，你可以选择自己感兴趣并且擅长的方向从事测试工作。另外各个行业，只要有软件开发的地方就需要软件测试。除了互联网行业以外，金融行业、电商行业、大数据行业也需要大量的软件测试人才，包括近几年比较火的安全测试等等。而且软件测试岗位的升职加薪空间也很大，因为软件测试需要全局的把控能力与良好的沟通能力，软件测试工程师因此也更容易升职到产品经理岗位。\u003c/p\u003e\u003cp\u003e综上所述，软件测试无论从行业的需求还是岗位本身的发展来看，就业前景都是非常好的，所以想要加入软件测试行业，现在还为时不晚。\u003c/p\u003e\u003c/p\u003e\u003cp\u003e\u003cp\u003e\u003cp\u003e我36岁，做了10年软件开发，刚经历了35岁职业危机，谈下我的切身感想吧。\u003c/p\u003e首先说下为什么会有35岁职业危机？\u003cp\u003e我的理解：35岁应该是鉴定一个人\"年轻人\"与\"中年人\"一个分水岭。人过了30岁，不管你承不承认，至少你的生理机能就开始走下坡路了：精力没那么地旺盛、记忆力开始减退、坐下了能不动就不想动，到了35岁时可能就感觉更明显了。\u003c/p\u003e\u003cp\u003e另外一个我觉得很重要的原因是：体制内的单位（国企、事业单位、公务员）只收35岁以下的员工。\u003c/p\u003e\u003cp\u003e所以：生理机能的衰退 + 体制内单位35岁招聘限制，两种最重要因素合在一起造就中国式的“35岁职业危机”。\u003c/p\u003e\u003cp\u003e  我觉得这个“35岁职业危机”不是软件行业的问题，是各行各业员工都要面对的问题。\u003c/p\u003e明白了35岁职业危机的根源，再来回答下你的问题\u003cp\u003e35岁了，人已开始进入中年，精力没那么旺盛，做什么事情可能都没什么兴趣。\u003c/p\u003e\u003cp\u003e转测试也是要有很多学习成本的，甚至要写自动化测试脚本，继续搞编程，而且一般测试团队在公司的地位不怎么高，在项目时间安排上会做得很紧凑，这样一旦来了项目，测试的加班概率会大很多（我以前的腾讯团队里就是这样，项目到了末期测试时，包括他们的TeamLeader在内的所有测试人员几乎每天都是晚上12点以后下班，苦！），工作性质与工作节奏、强度并没有大的改观，但工资却降低了一个档次，所以他并不是适合“35岁级程序员”转岗目标。\u003c/p\u003e推荐岗位\u003cp\u003e那程序员35岁之后，适合干点啥呢？\u003c/p\u003e\u003cp\u003e我觉得必须要按自己的实际情况来考量：\u003c/p\u003e\u003cp\u003e1、如果你喜欢写代码，前（钱）途也还可以，那就继续走技术路线打怪升级：初级-中级-高级-专家-高级别专家走下去，到了后面肯定是可以带一些技术团队的，这是每个刚毕业IT学生娃职业规划的理想状态，我当初以为我也会是这么走下去，结果计划总是赶不上变化。\u003c/p\u003e\u003cp\u003e2、如果你还是很喜欢这个行业，产品经理其实是一个很好的转岗方向，我有几个同事就转了产品经理。如果要转，思维方式就要变，以前写代码是专注细节方面，做产品经理，就要专注产品的业务逻辑、运营方式方法等，考虑的都是很大的方面。但如果你细节都明了，产品宏观方面的思考模式多做几个项目应该就能建立起来，以后你做产品既能做好宏观面又能体察实现细节，这样的产品经理会很受程序员的欢迎，过需求研讨会过得很快。\u003c/p\u003e\u003cp\u003e3、如果实在是厌倦了这个行业，那可以去应聘下体制内的相应岗位，在激烈的市场竞争中生存下来的工程师，胜任体制内的岗位其实是比较绰绰有余的，毕竟那里面的竞争与需求比外面平静太多了。\u003c/p\u003e\u003cp\u003e我就是那种进了体制内单位的软件工程师，2017年因为种种原因从一线城市回到了三线城市发展，一开始做了IT外包公司的技术经理、技术总监，结果发现自己终究是做不动了，不能很好的静下心来研究新东西，所以干脆在35岁那年应聘了这里的一家国企，很惊险，笔面试都没问题，年龄两个月后就不满足条件了。\u003c/p\u003e\u003cp\u003e进来后，才知道什么是“隔行如隔山”，工作强度陡然降低了一个级别，真有点不太适应.....\u003c/p\u003e\u003cp\u003e现在，我才体验到什么是真正的生活：早上八点上班，下午5:30准点下班，而后遛娃，周末带娃四处游玩，偶尔走走亲戚、搞搞自驾游，这在以前我那个996（实际是995，但行业特性里的学习任务、学习节奏会压得你周末也要抽时间在家搞学习大半天，所以写成996了）的一线城市几乎是不可能达成的奢望。\u003c/p\u003e\u003cp\u003e好了，就分享这么多吧，有什么问题在留言区留言，我知无不答~！\u003c/p\u003e\u003cp\u003e留最后一张图和大家一起勉力前行吧\u003c/p\u003e\u003c/p\u003e\u003c/p\u003e\u003cp\u003e\u003cp\u003e压力测试，表示在一个给定的基准下，能执行的最好情况。例如，在没有负重的情况下，你跑100米需要花多少时间（这边，没有负重是基准）。\u003c/p\u003e\u003cp\u003e负载测试，也是性能测试，但是他是在不同的负载下的。对于刚才那个例子，如果扩展为：在50公斤、100公斤……等情况下，你跑100米需要花多少时间。\u003c/p\u003e\u003cp\u003e容量测试，是在容量情况下的性能测试。对于刚才那个例子，如果改为：在一阵强风的情况下，你在负重或没有负重的情况下，跑100米需要花多少时间。\u003c/p\u003e\u003cp\u003e负载测试、容量测试、压力测试、强度测试都属于性能测试，性能测试是指在给定条件基准的前提下能达到的运行程度，测试软件在系统中的运行性能，度量系统与预定义目标的差距。\u003c/p\u003e\u003cp\u003e负载测试是模拟在超负 荷环境中运行，通过不断加载（如逐渐增加模拟用户的数量）或其它加载方式来观察不同负载下系统的响应时间和数据吞吐量、系统占用的资源（如CPU、内存）等，以检验系统的行为和特性，以发现系统可能存在的性能瓶颈、内存泄漏、不能实时同步等问题。负载测试更多地体现了一种方法或一种技术。\u003c/p\u003e\u003cp\u003e压力测试（强度测试）：压力测试是在强负载（大数据量、大量并发用户等）下的测试，查看应用系统在峰值使用情况下操作行为，从而有效地发现系统的某项功能隐患、系统是否具有良好的容错能力和可恢复能力。压力测试分为高负载下的长时间（如24小时以上）的稳定性压力测试和极限负载情况下导致系统崩溃的破坏性压力测试。\u003c/p\u003e\u003cp\u003e容量测试目的是通过测试预先分析出反映软件系统应用特征的某项指标的极限值（如最大并发用户数、数据库记录数等），系统在其极限值状态下没有出现任何软件故障或还能保持主要功能正常运行。容量测试是面向数据的，并且它的目的是显示系统可以处理目标内确定的数据容量。\u003c/p\u003e\u003cp\u003e针对上述负载测试、压力测试、容量测试举个例子：例：一个人背X斤。\u003c/p\u003e\u003cp\u003e负载测试：200斤情况下，是否能坚持5分钟。\u003c/p\u003e\u003cp\u003e压力测试：200,300,400... 斤情况下，他的表现，什么时候失败，失败之后什么表现，重新扛200是否正常。\u003c/p\u003e\u003cp\u003e容量测试：在坚持5分钟的情况下，他一次最多能扛多少斤。\u003c/p\u003e\u003c/p\u003e\u003cp\u003e\u003cp\u003e随着测试行业的不断发展，我们对测试开发与测试之间的认识也在发生着一些细微的变化。\u003c/p\u003e\u003cp\u003e较以往，我们会说测试开发与测试的共同点是都需要懂测试，懂业务，掌握测试基础理论、测试方式、测试流程，都是围绕着产品质量提供测试服务。其次测试开发需要站在测试的角度，通过技术应用对产品或项目进行效率或质量方面的优化和保障，更全面、高效支撑测试。\u003c/p\u003e\u003cp\u003e同样，我们也在强调测试开发人员一定需要懂测试、懂业务，否则不了解测试的情况下，盲目的接受开发会出现什么情况?——比如，难以客观的评估业务是否具备开展自动化等测试技术的条件，难以全面的把控自动化等测试技术实施过程中的风险，难以主动的感知业务测试潜在的技术需求等等。仅仅具备开发能力而不具备业务测试能力及对业务测试理论、流程的理解，很难高效高质的做好测试开发工作。\u003c/p\u003e\u003cp\u003e随着敏捷、类敏捷、Devops等模式的发展和应用，系统架构也由单体架构到SOA再到微服务等架构的演变，以及大数据治理、AI人工智能的应用，软件交付周期逐渐缩短，技术复杂度不断提升，对测试人员提出了越来越高的要求。\u003c/p\u003e\u003cp\u003e在这样的行业发展背景与趋势之下，我们不难得出 测试逐渐向测试开发过渡 已经是一种显在的趋势，具备一定的编程基础将成为测试人员的基本能力要求，无论我们决定将来走技术路线还是管理路线。\u003c/p\u003e\u003cp\u003e这时，我们更加清楚的认识到，具备了一定的开发基础 并不等同于能够做好测试，同时之所有测试开发成为一种趋势，是因为在具备优秀需求分析、测试设计等测试能力的基础之上，若我们同时能够具备一定的开发能力和技术解决思维，便能够更好的从质量、效率、风险、成本之间寻求一种平衡。\u003c/p\u003e\u003c/p\u003e\u003c/div\u003e"
  }
}
```
