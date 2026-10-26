---
name: mao-fangfa-lun
description: |
  用毛泽东著作里的方法论处理具体判断：先取证再表态、把混沌局面切成主要矛盾、在劣势中集中优势、把判断落到会议与汇报机制上。适用于决策前的取证与切分、资源不够时的取舍、组织落地与信息失真、多方博弈中的分寸把握、方案与汇报的结构体检、宣传与对外表达、谈判中的两手准备、组织精简与扩张后的资源投向、群众性经济活动的组织。不适用于纯事实查询、纯技术计算、以及需要专业资格判断的领域。
metadata:
  cangjie.generated-by: cangjie-tools v2.5.0
  cangjie.variant: single
  cangjie.bundle-id: mao-corpus-b1
  cangjie.capability-count: 113
  cangjie.entrypoint-count: 1
---
# 毛泽东著作方法论语料库（选集、文集、军事文选、文稿 1-13、政经批注、思想万岁、早期文稿） — 全书能力入口

## 触发与不触发

**适用**：与本书能力域相关的咨询与任务（见下方路由表的意图列）。
**不适用**：
- 纯事实查询与资料检索（这类需求直接查原文，不必加载能力卡）
- 需要专业资格的判断（医疗、法律、工程安全、财务审计）
- 对历史事件与人物的是非评价（本技能只取方法论，不评价历史）
- 单纯的情绪疏导与心理支持

## 核心原则（常驻速览，概览类问题读到这里即可回答）

1. 结论产生于调查的末尾，而不是先头；没有一手材料就没有发言权
2. 复杂局面先切分再决策：找影响力最大的那一条矛盾，而不是最急的那一件
3. 劣势方唯一的胜法是在一点上造出相对优势，并明确写出放弃清单
4. 正确的判断必须配落地机制：一般号召 + 个别指导 + 检查 + 总结，缺一步就停在纸上
5. 分清敌我友的精度决定成败；把中间力量推向对手是最常见的自伤
6. 写不清楚、不报告、不请示，都是组织病，要当工程问题治

## 场景包（不知道用哪个方法时先查这里）

路由表按「一句话意图」排 113 行，适合已知自己卡在哪。**若只知道自己面对什么局面、不知道用哪个方法**，先查 `references/index-scenes.md`：15 个场景包，每包给「主卡 + 标配组合」。

**组合里的第二张不是备选，是必需。** 单用主卡最常见的失败是判断对了但落不下去——会开了没结果，是因为配了人却没设免责线；文件发了没动，是因为发了文却没派人到位。

典型组合（完整 15 组见场景包）：

| 局面 | 主卡 | 必须补齐 |
|---|---|---|
| 会开了没结果 | `huiyi-juece` | `huiyi-peiren` + `mianze-xian` |
| 文件发了没动 | `yiban-haozhao` | `wenjian-shengxiao` + `renbudao-buxiafa` |
| 资源不够先做哪件 | `jizhong-youshi` | `quanju-jubu` + `zhuyao-maodun` |
| 出了问题怎么收场 | `jiubian-jizhi` | `juece-sandao-zha` + `liangce-jiabi` |
| 多方博弈的分寸 | `youli-youshi-youjie` | `sanfenfa` + `tanda-liangshou` |
| 汇报好、问题多 | `xinxi-shizhen` | `guiyin-xiangshang` + `dingxing-bili` |

## 能力路由（先读本表，按意图加载 1 张能力卡）

| 用户意图 | 先读 | 补读/备注 |
|---|---|---|
| 手上只有二手材料和印象，要下一个判断；一个结论被反复宣讲却从没在小范围验证过 | references/capabilities/shijian-renshi-xunhuan.md | references/capabilities/jielun-houzhi.md、references/capabilities/diaocha-quzheng.md |
| 要就自己没到过现场的问题表态；会议桌上出现大家都这么说 | references/capabilities/jielun-houzhi.md | references/capabilities/diaocha-quzheng.md、references/capabilities/shijian-renshi-xunhuan.md |
| 要摸清一个地方或一类客户的真实情况；现有信息全部来自汇报与报表 | references/capabilities/diaocha-quzheng.md | references/capabilities/jielun-houzhi.md、references/capabilities/jiepou-maque.md |
| 对象数量远超能逐一看完的规模；要尽快拿出可推广的处置方案 | references/capabilities/jiepou-maque.md | references/capabilities/juece-sandao-zha.md、references/capabilities/yiban-haozhao.md |
| 方针已定但推不动或反复出错；要定位一件事到底卡在哪里 | references/capabilities/juece-sandao-zha.md | references/capabilities/jiepou-maque.md、references/capabilities/guji-liuyudi.md |
| 定长期计划；向上报进度；估算一件新事要多久 | references/capabilities/guji-liuyudi.md | references/capabilities/juece-sandao-zha.md、references/capabilities/chuangzao-tiaojian.md |
| 手上七八件事同时压着、资源不够全做；全局处于劣势但必须有所斩获 | references/capabilities/jizhong-youshi.md | references/capabilities/quanju-jubu.md、references/capabilities/cengji-fanzhuan.md |
| 要推广到很多单位但做法五花八门；发了文件开了会，下面纹丝不动 | references/capabilities/yiban-haozhao.md | references/capabilities/qunzhong-luxian.md、references/capabilities/luoshi-jiezou.md |
| 决策需要一线配合才能生效；一线做法与文件要求有偏差 | references/capabilities/qunzhong-luxian.md | references/capabilities/yiban-haozhao.md、references/capabilities/xinxi-shizhen.md |
| 任务堆积、多头上级同时派活；团队每天在切换中消耗 | references/capabilities/yige-zhongxin.md | references/capabilities/jizhong-youshi.md、references/capabilities/huiyi-juece.md |
| 会议多但决策少；同一议题反复上会；会后没人认账 | references/capabilities/huiyi-juece.md | references/capabilities/baogao-zhidu.md、references/capabilities/sixiang-douzheng.md |
| 层级多、地域散、正在快速扩张；上级对一线了解全靠口头汇报 | references/capabilities/baogao-zhidu.md | references/capabilities/xinxi-shizhen.md、references/capabilities/huiyi-juece.md |
| 多方博弈，需要决定对谁硬对谁软；中间力量的向背可能决定胜负 | references/capabilities/sanfenfa.md | references/capabilities/youli-youshi-youjie.md、references/capabilities/buyao-simian-chuji.md |
| 必须回应攻击但还要长期共事；冲突有升级风险 | references/capabilities/youli-youshi-youjie.md | references/capabilities/sanfenfa.md、references/capabilities/buyao-simian-chuji.md |
| 一次改革牵动多个利益群体；各方同时反弹 | references/capabilities/buyao-simian-chuji.md | references/capabilities/sanfenfa.md、references/capabilities/zhuyao-maodun.md |
| 与更强的一方合作或被并入对方体系；担心合作中被逐步吸收 | references/capabilities/duli-zizhu.md | references/capabilities/sanfenfa.md、references/capabilities/youli-youshi-youjie.md |
| 多个问题彼此纠缠，资源只够主攻一个；局面混沌、优先级说不清 | references/capabilities/zhuyao-maodun.md | references/capabilities/fenxi-sanjie.md、references/capabilities/maodun-teshuxing.md |
| 要分析一个具体对象；手上的框架看起来可以套任何同类对象 | references/capabilities/maodun-teshuxing.md | references/capabilities/zhuyao-maodun.md、references/capabilities/fenxi-sanjie.md |
| 重要判断即将下发；结论被反复宣讲却无人质疑 | references/capabilities/fenxi-sanjie.md | references/capabilities/zhuyao-maodun.md、references/capabilities/shuangxiang-bianhua.md |
| 听到只要我们就能式的判断；要决定是否投入一个转型项目 | references/capabilities/zhuanhua-tiaojian.md | references/capabilities/maodun-teshuxing.md、references/capabilities/chuangzao-tiaojian.md |
| 冲突双方情绪激烈，要决定谈还是断 | references/capabilities/lianglei-maodun.md | references/capabilities/sixiang-douzheng.md、references/capabilities/sanfenfa.md |
| 一段正在进行的变化需要判断走势；数据单边、情绪两极 | references/capabilities/shuangxiang-bianhua.md | references/capabilities/yinsu-shixiao.md、references/capabilities/fenxi-sanjie.md |
| 同时管多个战场或多条业务线；注意力被最吵的问题带走 | references/capabilities/quanju-jubu.md | references/capabilities/jizhong-youshi.md、references/capabilities/chuzhan-sanyuanze.md |
| 一系列行动的第一步；开局定调、输不起 | references/capabilities/chuzhan-sanyuanze.md | references/capabilities/chuangzao-tiaojian.md、references/capabilities/quanju-jubu.md |
| 处于劣势还不能决战；想等条件成熟但不知等什么 | references/capabilities/chuangzao-tiaojian.md | references/capabilities/chuzhan-sanyuanze.md、references/capabilities/cengji-fanzhuan.md |
| 总体劣势但要长期熬；每次具体行动都必须有战果 | references/capabilities/cengji-fanzhuan.md | references/capabilities/shuangxiang-bianhua.md、references/capabilities/jizhong-youshi.md |
| 评估竞争格局或一个长期项目的胜算；短期与长期结论互相矛盾 | references/capabilities/yinsu-shixiao.md | references/capabilities/shuangxiang-bianhua.md、references/capabilities/zhilaohu.md |
| 面对看起来压倒性的对手或困难；团队在轻敌与畏缩之间摇摆 | references/capabilities/zhilaohu.md | references/capabilities/yinsu-shixiao.md、references/capabilities/chuangzao-tiaojian.md |
| 要写方案、汇报、提案；审阅别人写的方案看不出问题在哪 | references/capabilities/xie-qingchu.md | references/capabilities/huiyi-juece.md、references/capabilities/baogao-zhidu.md |
| 团队反复犯同类错误；分歧被和气压住不敢提 | references/capabilities/sixiang-douzheng.md | references/capabilities/lianglei-maodun.md、references/capabilities/xinxi-shizhen.md |
| 决议已发但执行情况无人掌握；重要项目反复延期 | references/capabilities/luoshi-jiezou.md | references/capabilities/yiban-haozhao.md、references/capabilities/baogao-zhidu.md |
| 关键信息全靠下级自报；汇报越来越顺、问题越来越少 | references/capabilities/xinxi-shizhen.md | references/capabilities/baogao-zhidu.md、references/capabilities/sixiang-douzheng.md |
| 进入一个陌生领域；要判断一个外部做法是否值得引进 | references/capabilities/gujin-zhongwai.md | references/capabilities/liangce-jiabi.md、references/capabilities/canshuhua-fuzhi.md |
| 要给一个做法定性；团队在激进与保守之间摇摆 | references/capabilities/liangce-jiabi.md | references/capabilities/fenxi-sanjie.md、references/capabilities/gujin-zhongwai.md |
| 一个点做成了要推广到几十个单位；经验写出来总是没法照做 | references/capabilities/canshuhua-fuzhi.md | references/capabilities/jiepou-maque.md、references/capabilities/yiban-haozhao.md |
| 面对一个分项极多的领域；资源有限但必须把整块业务带起来 | references/capabilities/jueding-dian.md | references/capabilities/quanju-jubu.md、references/capabilities/jizhong-youshi.md |
| 组织扩张、信息需要跨层同步；对外口径屡屡出错 | references/capabilities/xuanchuan-zuzhihua.md | references/capabilities/kouhao-jieti.md、references/capabilities/qudao-yuzi.md |
| 要推动一个群体接受较大变化；反复解释却说服不了对方 | references/capabilities/kouhao-jieti.md | references/capabilities/xuanchuan-zuzhihua.md、references/capabilities/qudao-yuzi.md |
| 对外沟通需要争取第三方；对手强硬、中间派观望 | references/capabilities/qudao-yuzi.md | references/capabilities/xuanchuan-zuzhihua.md、references/capabilities/sanfenfa.md |
| 需要别人长期配合但对方怕被吞掉；联盟里弱势方不信任你 | references/capabilities/sansanzhi.md | references/capabilities/duli-zizhu.md、references/capabilities/sanfenfa.md |
| 要压缩编制或组织臃肿决策变慢 | references/capabilities/jingjian-baogugan.md | references/capabilities/jiceng-youxian.md、references/capabilities/zhengce-chengtao.md |
| 一次推行多条相互依赖的政策；各地执行程度差异很大 | references/capabilities/zhengce-chengtao.md | references/capabilities/jiceng-youxian.md、references/capabilities/baogao-zhidu.md |
| 要对一次失败或运动做清算；下级开始用数量证明态度 | references/capabilities/jiubian-jizhi.md | references/capabilities/sixiang-douzheng.md、references/capabilities/lianglei-maodun.md |
| 要在不友好环境中推进工作 | references/capabilities/gongkai-mimi.md | references/capabilities/duli-zizhu.md、references/capabilities/jiceng-youxian.md |
| 刚完成一次扩张，资源该往哪倾斜 | references/capabilities/jiceng-youxian.md | references/capabilities/jingjian-baogugan.md、references/capabilities/zhengce-chengtao.md |
| 要向用户员工合作方持续索取 | references/capabilities/xiangei-houqu.md | references/capabilities/minban-gongzhu.md、references/capabilities/qunzhong-luxian.md |
| 要借助基层或外部力量办事 | references/capabilities/minban-gongzhu.md | references/capabilities/xiangei-houqu.md、references/capabilities/jiceng-youxian.md |
| 要做一次涉及利益重新分配的调整 | references/capabilities/qingsuan-siduan.md | references/capabilities/zhengce-chengtao.md、references/capabilities/jiubian-jizhi.md |
| 正在与对手谈判同时要保持行动自由 | references/capabilities/tanda-liangshou.md | references/capabilities/youli-youshi-youjie.md、references/capabilities/sanfenfa.md |
| 联盟或团队出现裂痕，要判断是人事还是结构问题 | references/capabilities/chengfen-liyi-bili.md | references/capabilities/sanfenfa.md、references/capabilities/liangce-jiabi.md |
| 对手有必须保护的要害；想一次解决两件事 | references/capabilities/weidian-dayuan.md | references/capabilities/gongjian-santqianti.md、references/capabilities/weizhi-shenji.md |
| 面临一次要不要 all in 的选择 | references/capabilities/juezhan-sanfen.md | references/capabilities/jizhong-youshi.md、references/capabilities/chuangzao-tiaojian.md |
| 被多方同时施压无法全面应战 | references/capabilities/fanbaowei.md | references/capabilities/fanbaowei.md、references/capabilities/jizhong-youshi.md |
| 跨部门协作上层都同意但推不动 | references/capabilities/sanjixietong.md | references/capabilities/yiban-haozhao.md、references/capabilities/huiyi-juece.md |
| 团队连续高强度输出开始出错 | references/capabilities/kaihe-jiezou.md | references/capabilities/luoshi-jiezou.md、references/capabilities/jizhong-youshi.md |
| 要派人去远处开辟新市场或分部 | references/capabilities/wailian-liucha.md | references/capabilities/zhanchang-liangdao.md、references/capabilities/gongjian-santqianti.md |
| 要攻克一个难啃的目标 | references/capabilities/gongjian-santqianti.md | references/capabilities/weidian-dayuan.md、references/capabilities/chuangzao-tiaojian.md |
| 一次行动失败要定位问题在哪 | references/capabilities/juexin-lian.md | references/capabilities/juece-sandao-zha.md、references/capabilities/fenxi-sanjie.md |
| 要判断资源投向哪里而重要的事很多 | references/capabilities/sanji-shuniu.md | references/capabilities/quanju-jubu.md、references/capabilities/jueding-dian.md |
| 要预判外部变化对自己的影响 | references/capabilities/weizhi-shenji.md | references/capabilities/juezhan-sanfen.md、references/capabilities/quanju-jubu.md |
| 要开辟新战场而资源投送有限 | references/capabilities/zhanchang-liangdao.md | references/capabilities/wailian-liucha.md、references/capabilities/xiangei-houqu.md |
| 想让一线参与决策但怕失控 | references/capabilities/junshi-minzhu.md | references/capabilities/huiyi-juece.md、references/capabilities/lianbing-rechao.md |
| 团队士气低、流失高且有平稳期 | references/capabilities/xinshi-zhengjun.md | references/capabilities/sixiang-douzheng.md、references/capabilities/lianbing-rechao.md |
| 要吸纳对手阵营的人员或渠道 | references/capabilities/fulu-zhengce.md | references/capabilities/chengfen-liyi-bili.md、references/capabilities/jungong-qujigei.md |
| 刚完成一次接管（并购、合并、系统替换） | references/capabilities/rucheng-santiaoxian.md | references/capabilities/qingsuan-siduan.md、references/capabilities/jiubian-jizhi.md |
| 关键资源长期依赖单一外部来源 | references/capabilities/jungong-qujigei.md | references/capabilities/zhanchang-liangdao.md、references/capabilities/duli-zizhu.md |
| 要从成熟团队抽人去支援新项目 | references/capabilities/bingli-jiegou.md | references/capabilities/jiceng-youxian.md、references/capabilities/jingjian-baogugan.md |
| 团队能力要整体提升但培训资源有限 | references/capabilities/lianbing-rechao.md | references/capabilities/xinshi-zhengjun.md、references/capabilities/junshi-minzhu.md |
| 要判断一次改善是暂时还是根本；指标回升但基础没变 | references/capabilities/santiaojian-zhuanhao.md | references/capabilities/juece-sandao-zha.md、references/capabilities/gujin-zhongwai.md |
| 要做高风险决策或写需批准的重大方案 | references/capabilities/liangwenti-fenceng.md | references/capabilities/juece-sandao-zha.md、references/capabilities/zhuanhua-tiaojian.md |
| 要向别人承诺这件事能做成 | references/capabilities/shuliang-menkan.md | references/capabilities/liangwenti-fenceng.md、references/capabilities/zhuanhua-tiaojian.md |
| 换了更强的对手或更难的场景原打法失效 | references/capabilities/anzhididing-guige.md | references/capabilities/jizhong-youshi.md、references/capabilities/shuangxiang-bianhua.md |
| 要执行有强制后果的行动（处罚清退追责） | references/capabilities/wen-zhun-hen.md | references/capabilities/jiubian-jizhi.md、references/capabilities/qingsuan-siduan.md |
| 要做全面清查而资源有限 | references/capabilities/sanceng-qingli.md | references/capabilities/jiubian-jizhi.md、references/capabilities/wen-zhun-hen.md |
| 上级要求加速团队想砍流程 | references/capabilities/jiasu-butiaoxu.md | references/capabilities/santiaojian-zhuanhao.md、references/capabilities/gaizao-luxiantu.md |
| 要调整已执行的政策且牵涉多方利益 | references/capabilities/zhengce-biangang.md | references/capabilities/jiubian-jizhi.md、references/capabilities/xinxi-shizhen.md |
| 政策在执行中变形各方各说各话 | references/capabilities/zhengce-jieshi.md | references/capabilities/zhengce-chengtao.md、references/capabilities/kuanyan-dangci.md |
| 要制定限制性或整顿性政策 | references/capabilities/huajie-sanwen.md | references/capabilities/kuanyan-dangci.md、references/capabilities/buyao-simian-chuji.md |
| 要处理大量同类案件且经办人分散 | references/capabilities/kuanyan-dangci.md | references/capabilities/huajie-sanwen.md、references/capabilities/shouli-guanli.md |
| 新规则首次执行，尺度没有共识 | references/capabilities/shouli-guanli.md | references/capabilities/kuanyan-dangci.md、references/capabilities/yiban-haozhao.md |
| 基层抱怨报表多会议多负担重 | references/capabilities/guiyin-xiangshang.md | references/capabilities/zhengce-chengtao.md、references/capabilities/jingjian-baogugan.md |
| 上级多头部署冲击主业需要缓冲阀 | references/capabilities/jiaoting-gailing.md | references/capabilities/huiyi-juece.md、references/capabilities/junshi-minzhu.md |
| 要制定规范标准或行为准则 | references/capabilities/duoshuren-zuode-dao.md | references/capabilities/zhengce-chengtao.md、references/capabilities/kuanyan-dangci.md |
| 要做长期结构性转型 | references/capabilities/gaizao-luxiantu.md | references/capabilities/jiasu-butiaoxu.md、references/capabilities/kaihe-jiezou.md |
| 政策经中间层后被明显改写 | references/capabilities/yiganzi-daodi.md | references/capabilities/xinxi-shizhen.md、references/capabilities/wenjian-shengxiao.md |
| 重要决策会容易开成表态会 | references/capabilities/huiyi-peiren.md | references/capabilities/huiyi-juece.md、references/capabilities/mianze-xian.md |
| 要往下派KPI或产量进度 | references/capabilities/zhibiao-sanjie.md | references/capabilities/liangwenti-fenceng.md、references/capabilities/dingxing-bili.md |
| 决定的人不承担后果，承担的人没决定权 | references/capabilities/quanze-duiqi.md | references/capabilities/jiceng-youxian.md、references/capabilities/zhengce-sijiaozhun.md |
| 设计或评审考核分配审批制度 | references/capabilities/guize-kesuan.md | references/capabilities/zhengce-sijiaozhun.md、references/capabilities/jianfu-yingbili.md |
| 要派人做调研审计访谈尽调 | references/capabilities/diaocha-shixiang.md | references/capabilities/jielun-houzhi.md、references/capabilities/jiceng-youxian.md |
| 听到普遍、严重、到处都是的描述 | references/capabilities/dingxing-bili.md | references/capabilities/fenxi-sanjie.md、references/capabilities/shuliang-menkan.md |
| 起草影响众人的政策制度合同条款 | references/capabilities/zhengce-sijiaozhun.md | references/capabilities/zhengce-chengtao.md、references/capabilities/duoshaonian-bubian.md |
| 重要文件发出后没有反应 | references/capabilities/wenjian-shengxiao.md | references/capabilities/baogao-zhidu.md、references/capabilities/renbudao-buxiafa.md |
| 要开大会传达重要方案 | references/capabilities/xianrang-zhixingzhe-gaigao.md | references/capabilities/huiyi-juece.md、references/capabilities/wenjian-shengxiao.md |
| 团队不敢讲真话会上只有附和 | references/capabilities/mianze-xian.md | references/capabilities/huiyi-peiren.md、references/capabilities/xinxi-shizhen.md |
| 集体失误需要追责但责任分散 | references/capabilities/xianrenzhang.md | references/capabilities/juece-sandao-zha.md、references/capabilities/jiubian-jizhi.md |
| 要变更影响长期投入的制度 | references/capabilities/duoshaonian-bubian.md | references/capabilities/zhengce-sijiaozhun.md、references/capabilities/zhengce-biangang.md |
| 要下发影响面大的文件或规则 | references/capabilities/renbudao-buxiafa.md | references/capabilities/wenjian-shengxiao.md、references/capabilities/yiganzi-daodi.md |
| 一项方法倡议多次推动无果 | references/capabilities/sidingxian-huanzhuti.md | references/capabilities/luoshi-jiezou.md、references/capabilities/jiaoting-gailing.md |
| 重大方案长期悬而未决或有人催着草率定案 | references/capabilities/liangjin-caoshuai-tuota.md | references/capabilities/jielun-houzhi.md、references/capabilities/liangwenti-fenceng.md |
| 要给过载系统减负（工作量课程报表会议） | references/capabilities/jianfu-yingbili.md | references/capabilities/guize-kesuan.md、references/capabilities/jingjian-baogugan.md |
| 体系出问题但症状分散说不清 | references/capabilities/liangdui-shipei.md | references/capabilities/fenxi-sanjie.md、references/capabilities/guize-kesuan.md |
| 计划预算由单一部门编，执行层觉得是被派的 | references/capabilities/jihua-douji.md | references/capabilities/quanze-duiqi.md、references/capabilities/wenjian-shengxiao.md |
| 计划一经批准就冻结，末端长期补窟窿 | references/capabilities/pingheng-gundong.md | references/capabilities/luoshi-jiezou.md、references/capabilities/jihua-douji.md |
| 多个方向都要推，资源有限各方争抢 | references/capabilities/bingju-qingdan.md | references/capabilities/quanju-jubu.md、references/capabilities/jizhong-youshi.md |
| 内部服务要不要收费、要不要内部结算 | references/capabilities/shangpin-diaobo.md | references/capabilities/quanze-duiqi.md、references/capabilities/xiangei-houqu.md |
| 要判断投入率（研发扩张加班）是否过高 | references/capabilities/jilei-anquan.md | references/capabilities/santiaojian-zhuanhao.md、references/capabilities/shuliang-menkan.md |
| 要设计或调整薪酬提成绩效方案 | references/capabilities/jichou-zhufu.md | references/capabilities/kuanyan-dangci.md、references/capabilities/wen-zhun-hen.md |
| 要建立长期训练但反复中断换方法 | references/capabilities/shenti-xunlian.md | references/capabilities/zhaji-sandongzuo.md、references/capabilities/guize-kesuan.md |
| 要推动一个方向但落不到具体事 | references/capabilities/wenti-zhuyi.md | references/capabilities/fenxi-sanjie.md、references/capabilities/jihua-douji.md |
| 进入新领域或带新人入门 | references/capabilities/zhixue-cixu.md | references/capabilities/zhaji-sandongzuo.md、references/capabilities/jielun-houzhi.md |
| 笔记越记越多但从不回看用不上 | references/capabilities/zhaji-sandongzuo.md | references/capabilities/zhixue-cixu.md、references/capabilities/jianfu-yingbili.md |
| 要组织跨部门协作但一开会就散 | references/capabilities/zui-xiao-lianhe.md | references/capabilities/jiceng-youxian.md、references/capabilities/huiyi-peiren.md |

**非能力类查询**：
- 书名/作者/章节/整书概览 → references/overview.md
- 术语解释 → references/glossary.md
- 决策规则速查（不需要原文依据时） → references/cheatsheet.md
- 完整意图与关键词索引（本表未覆盖的意图先查这里） → references/capability-index.md

## 加载规则

- 每次任务先读本文件，再按路由表加载 **1** 张能力卡；任务明确跨域时最多加载 2 张。
- 概览/书名类问题不加载能力卡，用「核心原则」与 overview.md 回答。
- 路由表与 capability-index.md 都无法命中的意图，明确告知超出本书范围，不要硬套。

## 边界与判停

- 用户要的是结论而非过程时，只给结论并标注依据的能力卡编号，不展开六段
- 信息不足以判断性质时，先执行「结论后置于调查」卡，不要硬套后续框架
- 问题超出六个主干（认识论/矛盾/战略/组织/策略/信息）时，明确告知超出范围
- 涉及不可逆的重大损失时，只做条件审计与风险提示，不代替决策
