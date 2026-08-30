# 破壳有范 · 更新动态

公开更新摘要（自 2026-07 起）。业务源码在私有仓，本仓**仅日志**。

- 私有工程：[`LaEirt/pk`](https://github.com/LaEirt/pk)（需协作权限）
- 本页同步自私有仓根目录 `README.md` →「更新动态」
- 同步日：2026-08-30

---

## 更新动态

### 2026-08-30

- **工作台 · 经营分析跨仪表板跳转**：分析 Tab 可配「点击后跳转仪表板」；预览点维度会带着当前筛选与日期打开目标板（`jump_dashboard`）。见 `workbench_bi_plan.md` FR-P2-02。
- **工作台 · 经营分析平台构成 2×2（Sheet01b）**：全 IP 大盘新增树图 / 月销堆积（数量·金额）/ 平台趋势折线；平台固定色板。见 `workbench_bi_plan.md` §4.6.8。
- **工作台 · 经营分析自定义日期 + 复制链接**：预览可选绝对日期区间（URL `from`/`to`）；「复制本页链接」带走页签与筛选。见 `workbench_bi_plan.md` C-BI-16。
- **工作台 · 经营分析查询耗时提示（L-06）**：组件标题旁显示耗时/是否缓存；「…」菜单可看「查询耗时」。见 `workbench_bi_plan.md`。
- **工作台 · 经营分析排行六卡（Sheet03）**：全 IP 大盘「03 排行」补齐 IP/商品/同事 × 数量/金额 2×3；旧两卡自动升级；前三名高亮。见 `workbench_bi_plan.md` FR-P2-01。
- **工作台 · 经营分析目标参考线（GAP-13）**：柱/线/组合/条形图可配橙色目标虚线（`style.referenceLines`）；编辑器分析 Tab 填标签与数值。见 `workbench_bi_plan.md` FR-P2-05。
- **工作台 · 经营分析多选联动 + 页签跳转**：同字段可点多个维度做 IN 筛选（URL `f_字段=a|b`）；分析 Tab 可配「点击后跳转页签」；排行榜可点；水印优先显示登录名。见 `workbench_bi_plan.md` FR-P2-02。
- **工作台 · 经营分析图表联动（FR-P2-02）**：预览态 KPI/柱线饼等点击维度会筛同页其它图；URL 同步 `sheet`/`date`/`f_<字段>`；组件可关「接收联动」；刷新失败保留上次图（GAP-03）。见 `workbench_bi_plan.md`。
- **工作台 · 经营分析 UAT 勾选表 + 门户类型筛**：人工签字表 `bi_uat_checklist.md`（V1–V7 / S1–S7）；门户增加仪表板/外链类型筛选与筛选空态。
- **工作台 · 经营分析编辑器对齐主流 BI**：沉浸全屏编辑、快捷键（Ctrl+S/Z/Del）、页签重命名/删除、画布缩放与拖拽栅格、颜色槽拆系列、本图筛选架、时间维按日/周/月、拖入后自动更新。见 `workbench_bi_plan.md` §3.5.3。
- **工作台 · 经营分析 P0–P2 续落地**：可查数据表扩至全域订单 / 直播订单汇总 / 私域直播 / 部门绩效；编辑器新增折线·面积·条形·堆积柱；分析页同环比；制作台版本回滚；管理员可「查看 SQL」。见 `workbench_bi_plan.md` FR-P1-13 / FR-P2-01/05/06。
- **工作台 · 经营分析画布缩放对齐主流**：选中图表后四角+四边拖动手柄放大缩小、标题栏拖移、拖动时 HUD 提示；配置区面板搜索与筛选条「查询向导」；首编引导增加缩放一步。见 `workbench_bi_plan.md` §3.5.3b。
- **工作台 · 经营分析全链路对标（§3.8）**：文档对齐 Quick BI / Power BI / Tableau 等「仓表→数据源→数据集→查询→仪表板→门户」八层；明确本仓 ADS 宽表 + 薄语义 + 薄报告；缺口 L-01～L-11 与 FR-P1-13。见 `workbench_bi_plan.md`。
- **工作台 · 经营分析数据表可选 + 白话 UI**：`GET /bi/datasets/` 目录；编辑器按图切换「数据表」；维度/度量改为分类/数值；Studio→制作台、去 JSON/rev/ACL 黑话；门户/授权页文案普通人可读。见 `workbench_bi_plan.md` §3.7.2b。
- **工作台 · 经营分析建板引导 / 数字格式**：编辑器首访 3 步 tour（加图→配字段→保存发布）+ 顶栏步骤条；样式页数字格式（智能万/强制万/整数/原值）；助手知识库改为侧栏门户/制作台。见 `workbench_bi_plan.md` FR-P1-10。
- **工作台 · 经营分析 BI 自助深化**：样式标题/色、布局疏密、预览水印用户名、查询控件配置、制作台轻量文件夹、编辑态查看数据。见 `workbench_bi_plan.md` §3.7。
- **工作台 · 经营分析 BI 自助编辑（§3.7）**：新建模板/默认图、保存≠发布角标、下线、重新发布、多度量字段架、画布拖缩放、自动保存；目标=BI 人员 GUI 全流程、不依赖 Agent 改表。
- **工作台 · 经营分析对照参考图补交互**：预览按 layout 12 列组件网格；查询控件条 +「本页怎么用」；门户主 CTA「打开全IP数据大盘」；编辑「更新」画布出数；`BiWidgetHost`/`BiWidgetRender` 共用。

### 2026-08-28

- **短信发送 · 刷新回执**：修复阿里云明细常无 BizId 时误报「回执 BizId 与发送记录不匹配」、已送达仍显示「待回执」；QuerySendDetails 须带明文手机号。见 `sms_landing_shortlink_plan.md`。
- **短信推广 · 指定商品 ID 未命中文案**：全域订单查无时主标题不再回落成裸 ID，检索表不展示假「命中」行；预览标明「未在全域订单出现」。
- **集成 · 小红书商品 ID 改用 itemId**：`skuList[].itemId` → ODS/ADS `商品id`；`skuId` 单独成列；CPS `goodsId` 不再入 ADS。见 `integrations/小红书/README.md`（`README.md`）、`25_xhs_item_id_switch.sql`。
- **集成 · 小红书 ODS 全量原文**：订单列表/CPS/售后三表补 `list_raw`/`detail_raw`（对齐小鹅拉数标准）；详情见 `integrations/小红书/README.md`（`README.md`）。
- **商城运营台 · 外渠兑换权益**：`/store/admin/order-redeems` 可查个人中心兑换记录，联动小鹅通 API 做**确认 / 手动开通 / 取消**；见 `storefront_order_redeem_plan.md` §5.1b。

### 2026-08-27

- **商城 · 个人中心订单号开通课程**：外渠（抖音等）订单可在 `/user/profile` 用平台订单号兑换小鹅通开课（绑手机 → `create_task`）；兑换失败「联系客服」弹企微二维码；见 `storefront_order_redeem_plan.md`。
- **商城 · 验证码登录用户改密**：个人中心支持手机/邮箱验证码设置新密码（无需旧密码）；保留旧密码改密路径。

### 2026-08-26

- **短信推广 · 文档对齐（plan §2.8.1 / §2.9.6 / API-SL-10a）**：配置跳过不落任务表；指定商品 ID 回查/检索（花名册 IP→ADS）；验收 SL-T-03a～03c。见 `sms_landing_shortlink_plan.md`。
- **短信推广 · 商品 ID 搜索分词**：粘贴「简称 · 全称」卡片标题可拆词命中；已绑列表即生效，搜索区仅用于再添加。见 plan §2.9.6。
- **短信推广 · 配置跳过不记任务**：平台/商品 ID/无短链/无手机号等闸门跳过只计编排统计，**不写**发送任务表；任务与结果默认也不展示存量「跳过」行。见 plan §2.8.1。
- **短信推广 · 商品 ID 名称检索增强**：按名称/IP 检索时合并花名册与全域订单；已绑定且回查成功的商品参与本地匹配，并提示全域订单中的真实简称。见 plan §2.9.6。
- **短信推广 · 指定商品 ID 点选**：配置台可用订单号/商品名称从 `日报.全域订单` 检索并选中对应 `商品id`（仍可粘贴 ID）；不再从小鹅通商品库选。
- **短信推广 · 小鹅通商品 ID 回填修复**：`日报.全域订单状态更新` 近窗 cast 兼容 `支付时间='--'`；ADS 回填**仅** `xiaoe_tech_order.商品ID`。见 plan §2.9.4 · `integrations/小鹅通/README.md`（`README.md`）。
- **商城 · 常军课程助手开闸**：百炼独立 KB 已建并同步 6 课（`cases_16`）；注册表 `chang_jun`→`live`；黄金问集 + CT-69。工作台须建自动规则（简称「厌学抑郁16大案例」）。见 `course_tutor_agent_plan.md` D10。

### 2026-08-25

- **商城 · 常军课程助手 P2**：Raw 迁入「厌学抑郁16大案例」；注册表 `cases_16` + 人设；清洗 6 课双写 `knowledge/chang_jun/`；仍 `preparing`（待百炼独立 KB）。见 `course_tutor_agent_plan.md` D10。
- **小鹅通其余 Beat 拉数 · 全量入库**：商品 list/detail、用户、推广员、直播 list/overview 统一写入 `list_raw`/`detail_raw`/`overview_raw` + 关键投影（价格/微信 openId/等级/直播状态等）。DDL `sql/xiaoe/23_xiaoe_ods_api_full.sql`。见 `integrations/小鹅通/README.md`（`README.md`）。
- **小鹅通售后 ODS · 全量入库**：`after_sale.list` 发现 + `after_sale.detail` 写入 `xiaoe_tech_order_refund.detail_raw` 及用户/物流/备注等投影列。见 `integrations/小鹅通/README.md`（`README.md`） · `sql/xiaoe/22_xiaoe_aftersale_detail_full.sql`。
- **小鹅通订单 ODS · 全量入库**：`xiaoe_tech_order.detail_raw` 存 order.detail 整包；并投影推广员ID / resource_id·spu_id / 支付方式等；缺 `detail_raw` 会补拉。见 `integrations/小鹅通/README.md`（`README.md`） · `sql/xiaoe/21_xiaoe_order_detail_full.sql`。
- **短信推广 · 小鹅通商品 ID**：订单详情 API 的 `resource_id`/`spu_id` 写入 `xiaoe_tech_order.商品ID`；ADS 回填**仅**该表（不 join 商品库、不采用「小鹅通订单总表」）；配置台「指定商品ID」仅粘贴 + 回查 `日报.全域订单`。映射见 `integrations/小鹅通/README.md`（`README.md`）。
- **短信推广 · 指定商品ID ToC**：绑定区改为卡片（ADS 回查名称/平台/店铺）；W5 拆成「优先规则 / 其余订单走这里」兜底块，去掉晦涩 priority 数字心智。
- **短信推广 · 指定商品ID 绑链**：绑定商品新增 `match_mode=goods_id`（可多 ID）；发信 `resolve` 优先按 ADS `商品id` 命中；投流专用品挂本链号池即可，不在 W5 写商品 ID 规则。见 `sms_landing_shortlink_plan.md`。
- **短信推广 · W5 规则形态**：商品 ID 规则改为「专用品 → 助教池 A/B/C/D」（多选），工作台普通 when 行不再混排商品 ID；ADS 近窗回填微信/抖音/快手/小鹅通/小红书 ODS `商品id` 入 `日报.全域订单`。见 `sms_landing_shortlink_plan.md` §2.9。
- **商城 · 微信登录接口预置**：网站应用审核通过后落地 `/api-data/store/oauth/wechat/*`（与支付宝同表）；`SECRET`+回调域配齐后登录/个人中心去灰。见 `storefront_wechat_oauth_login_plan.md` · `integrations/微信开放平台`（`README.md`）。
- **短信推广 · 订单级动态路由（W5）**：发信冻结 `route_context`；短链可配规则（平台/流量来源/商品 ID/分销）再分助教；公开 assign 返回 `rule_id`；工作台可试跑。见 `sms_landing_shortlink_plan.md` §2.9。
- **抖音订单 ODS 断更修复**：仅将 `密文_买家手机号` 扩为 `TEXT`（encrypt 超 255 整批回滚）；小时 Celery 失败邮件改为去重摘要并对 DirectMail 拒信降级重试。见 `integrations/抖音/README.md`（`README.md`）。
- **工作台 · 短信推广号池按平台分流**：同一商品仍只建一条短链；号池每行可标「接单平台」（空=不限），买家点加助教时按短信归因订单平台过滤后再分流。见 `sms_landing_shortlink_plan.md` §2.6 / SL-T-67。
- **工作台 · 短信推广号库上百人**：助教号库与选入对话框分页；批量粘贴会对照号库（已有链接不重复建）；可按组挂入或复制其他短链号池。见 plan SL-T-68/69。

### 2026-08-24

- **工作台 · 短信推广流量来源闸门**：短链购后发送可「不限 / 仅允许 / 排除」流量来源（对齐 `日报.全域订单.流量来源`）；编排跳过 `skipped_traffic_source`（**2026-08-26 起配置类跳过不落发送任务表**）；任务与结果展示并筛选流量来源。见 `sms_landing_shortlink_plan.md` §2.8.1 / SL-T-66。
- **工作台 · 短信任务与结果性能**：首屏默认近 30 天；KPI 与列表并行加载；发送列表批量关联漏斗；应发未发短链内存索引，缓解超时与默认空表。
- **工作台 · 短信推广运营台**：主模板切 NOTICE；发送页升级为「任务与结果」含应发未发 Tab、首屏 KPI 与单条/批量补发；SL-T-60～63。
- **商城 · 站点图标**：破壳小鸡 LOGO 作 favicon（`/favicon.ico`、48px PNG）；供搜索摘要与浏览器标签展示。`/terms`、`/privacy` 同步修订（生效日 2026-08-24）；覆盖线上课程、第三方支付、课程助手、第三方共享与 Cookie 说明。
- **商城 · 首页首屏性能**：Element Plus 改 `@element-plus/nuxt` 按需加载（主包约 1.34MB → 428KB）；轮播上传自动 WebP 压缩（≤100KB）；首图 `preload` + OSS 展示 WebP；SSR 仅阻塞 banners/精选，渠道与老师 `ClientOnly`；首页 `swr: 60` 降 TTFB。
- **商城 · 退款关课状态补强**：`user_order` 新增 `refunded_at` / `revoke_status` / `revoke_at` / `revoke_detail`；关课走 `purchase.delete` 短延迟重试 + `permission.check` 确认，失败由 `store_course_revoke_retry` 补扫。见 benchmark §6.6 / TB-T-DLV-08…09（`storefront_toc_benchmark_plan.md`）。
- **商城 · 收银台微信支付上线**：`/order/pay/:id` 双通道（Native 出码轮询 / H5 跳转）；WP-03/05/06/09 单测 green；运营台原路退按 `store_payment.channel` 分流。见 `storefront_wechat_pay_plan.md`。

### 2026-08-21

- **商城 · 支付后开课 ToC**：支付结果页/订单详情用四步进度（付款→账号就绪→开通→可上课）+ 小鹅通登录指引 + 企微客服；叙事「您只需付款，注册与开课自动完成」。见 benchmark §7.4（`storefront_toc_benchmark_plan.md`）。
- **商城 · 收银双渠目录规整**：`pay/alipay/` 与 `pay/wechat/` 并列；根目录仅留 `views` / `repo` / 跨渠薄 `gateway`·`refund`，消除支付宝平铺与微信嵌套重叠。见 `pay/README.md`（`README.md`）。
- **商城 · 微信支付 P0 接口落地**：`channel=wechat` prepare（Native/H5/JSAPI 门控）+ `/store/pay/wechat/notify` 验签解密置 payed + 查单/关单接入惰性对账 + 售后按 channel 退款分流；方案与待补齐见 `storefront_wechat_pay_plan.md` §0/§14（当前关联 AppID 为小程序，网页 JSAPI 需服务号）。
- **商城 · 个人中心主流对齐（UX-15）**：订单图标条（待付款/待发货/已发货/售后）、身份卡脱敏、移动 chips、登录态改密、取消收藏/清空足迹；验收 TB-TOC-PROF-01…06。见 benchmark §4.11（`storefront_toc_benchmark_plan.md`）。
- **商城 · 登录/个人中心/收银台主流对齐**：登录+注册共用「其他登录方式」圆标行；个人中心第三方左标列表；收银台支付宝品牌选中卡 + 微信灰显「即将开通」。见 alipay oauth §6（`storefront_alipay_oauth_login_plan.md`） · benchmark UX-03（`storefront_toc_benchmark_plan.md`）。
- **商城 · 微信登录 / 微信支付 SDD**：与支付宝对齐的两份规划文档（同表 OAuth 扩展 · 收银双通道 Native/H5/JSAPI）；枢纽 `integrations/微信开放平台`（`README.md`）。见 `storefront_wechat_oauth_login_plan.md` · `storefront_wechat_pay_plan.md`。
- **集成 · 支付宝 From 蚂蚁全量订阅入库**：开放平台已订阅 19 类消息均落 `支付宝_push`（专用 `evt_*` + Celery）；映射见 `subscribed-messages.md`。
- **集成 · 支付宝推送 URL 对齐**：From 蚂蚁应用网关改为 `POST /api-data/push_from/alipay/api_alipay_push`；全渠推送链接汇总见 `integrations/push_urls.md`（`push_urls.md`）。
- **商城 · 支付宝登录 / 第三方绑定（P0–P1）**：登录页支付宝入口、授权回调关联向导、个人中心绑/解绑；表 `user_info.user_oauth_*`；开放平台 App「思维重塑」`2021006129602982` 已上线（与收款同 App）。见 `storefront_alipay_oauth_login_plan.md`（冷启动 login UAT 待再验）。
- **工作台 · 短信推广**：发送记录默认只看购后推广（排除验证码）；修复购后编排自 8/12 起因时区 aware/naive 比较崩溃导致水位停摆、快手应发漏发。见 `sms_landing_shortlink_plan.md`。
- **商城 · 李伟文课程助手**：人设禁追问、课内讲透与数字忠实；`/course-tutor` 对齐主流交互 P0–P2（复制/停止/换行/建议问/改标题/重试/流式揭示/重生/编辑末问/额度/搜索/反馈；**不做**导出分享）。见 `course_tutor_agent_plan.md`。

### 2026-08-20

- **工作台 · 公开能力页业务流程图**：`/workbench/public` **总览** iframe 为「多源汇入 → 主干加工 → 办事/看板/合作商分叉 + 补录回写」权威图；展台仅 CTA 跳转总览，避免双图重复。见 `UI_DESIGN.md` §5.3。
- **工作台 · 公开能力页 ToC 展台**：非管理员增加能力域环图、分组条形图与场景卡片（结构计数无假业绩）；入场动效尊重 `prefers-reduced-motion`。
- **商城 · 支付成功/开课/吊权链路**：Celery 开通结果不再误用 `_finish`（成功也 KeyError）；吊权与开通共用小鹅 resource 映射；退款 `revoked` 覆盖 pending；支付结果页等开通终态再显「去上课」。见 benchmark §7（`storefront_toc_benchmark_plan.md`）。
- **商城 · 支付/退款硬化**：notify 幂等补漏开课入队；部分退款不标整单 `refunded`；运营台退款金额认请求体；线上课下单 BE 校验已绑手机。见 benchmark §6.6（`storefront_toc_benchmark_plan.md`）。
- **商城 · 注册登录审计 P0–P2**：绑手机可认领「仅手机无消费」壳账号；找回发码统一文案；邮箱验证码 consume + TTL 单源；OTP 新用户 `is_new_user` 设密引导；邮箱重置清登录锁；FE 文案/错误透传/会话 fail-closed。见 benchmark §5.4（`storefront_toc_benchmark_plan.md`）。
- **商城 · 课程老师拟人回复**：去掉人设里的 `**` 示范；system 禁 Markdown；回复后处理剥加粗/标题；气泡仍为纯文本。见 `course_tutor_agent_plan.md`。
- **商城 · 手机 OTP 自动建号**：修复未注册登录 500（`email=''` 撞 `uk_user_email`）；建号改写 `NULL`；邮箱注册同理 `phone=NULL`。见 benchmark §5.4（`storefront_toc_benchmark_plan.md`）。
- **店铺运营 · 与商品管理解耦**：仅 `store_ops_*` 可进 `/store/admin`；工作台 Admin「店铺运营」模块卡 / 预设「店铺客服·履约·全量」授予；侧栏文案同步。见 `workbench_rbac.md` §4、ops §3.3（`storefront_ops_console_plan.md`）。
- **工作台 · 商城运营可直接授予**：Admin 用户/角色模块卡新增「店铺运营」（`store_ops`）；亦可选用预设。见 `workbench_rbac.md` §4。
- **商城运营台 · 本地登录跳转**：环回回落 `:3001`，避免打到商城 404。见 ops §3.3（`storefront_ops_console_plan.md`）。
- **商城运营台 · 首页图片**：主视觉轮播与老师介绍图可在 `/store/admin/home-media` 上传维护；有启用轮播时首页优先展示，否则仍回退精选商品封面。见 ops §11.10（`storefront_ops_console_plan.md`）。
- **商城 · 首页回访加速**：首页 keepalive + 客户端不阻塞导航；recommend/hot 90s 缓存、列表不回传详情 HTML；二次进首页接近瞬时。见 benchmark §8.3（`storefront_toc_benchmark_plan.md`）。
- **工作台 · 课程助手知识上传 P0.5/P1**：下载预填 YAML 模板、复制清洗提示词、分类失败文案、上传后试问引导、已入库文稿列表（API-W15/W16）。见 `course_tutor_agent_plan.md` §7.4.2。
- **商城运营台 · 商品筛选**：IP/简称下拉（商品列表匹配花名册）、关键词含 IP、热卖/精选/小鹅通关联筛选。见 ops §11.6（`storefront_ops_console_plan.md`）。
- **商城 · 联系我们**：帮助中心 `/help#contact` 上线企微客服官方二维码；页脚「企业微信客服 / 联系我们」直达。见 `UI_DESIGN.md`。
- **商城 · 自动开课**：手机号未在小鹅通时先注册再开课；购物/支付结果引导「去上课」到小鹅通并用同手机号登录。见 benchmark §7（`storefront_toc_benchmark_plan.md`）。
- **商城 · 首页老师介绍联动课程讲解**：开通讲解的老师（当前李伟文）主入口进 `/course-tutor?teacher=`，专场为次 CTA。见 `UI_DESIGN.md` §4.3.3。
- **商城 · 首页楼层销量口径**：本周精选按 `日报.全域订单` 小鹅通本周销量；大家在看按全平台累计销量（对齐上架商品名/简称/小鹅 id）。见 benchmark §8.3 F7（`storefront_toc_benchmark_plan.md`）。
- **商城 · 首页老师介绍（UX-14）**：桌面/移动双端定稿布局 I（大图横滑）；陈聪/李伟文/王培霖/常军；图上 OSS `products/teachers/home/*.webp`。见 `UI_DESIGN.md` §4.3.3。
- **商城买家 · 淘宝式购物车/订单/购买（§14 FE）**：购物车失效行与混选拦截、移动端隐藏 tabbar；订单列表实付卡+去支付倒计时/去上课/物流/售后/再买一单与待发货 Tab；结算可改数量与默认最优券；pay-return 认 `out_trade_no`；微信内收银台提示。见 benchmark §14（`storefront_toc_benchmark_plan.md`）。
- **商城运营台 · 售后 P1**：类型 `ticket_type`、`refund_amount`、进度条、超时/配送筛选、内部备注；淘宝式同意退款。见 ops §11.9（`storefront_ops_console_plan.md`）。
- **商城运营台 · 售后/订单一期对齐淘宝京东**：待付款状态码、待发货/已发货 Tab、售后列表订单号+买家、售后中禁发货、退款回库存+小鹅通吊权、批量发货禁止假运单。见 ops §11.8（`storefront_ops_console_plan.md`）。
- **商城 · 售后原路退款前后端打通**：工单详情认领→「原路退款并解决」调支付宝退款；订单/流水 uuid 兼容；运营台 Nuxt 已发 ECS。见 benchmark plan（`storefront_toc_benchmark_plan.md`） §6.6。
- **商城 · 暖底与主色**：页面底改为暖中性 `#faf6f4`，消除渠道置顶冷灰白条；登录/搜索等 primary 按钮强制破壳珊瑚，避免 Element Plus 默认蓝回潮。见 `UI_DESIGN.md`。
- **课程助手 · 术语通俗化**：人设与 system 强制「先白话、后术语」；专业词须紧跟「说白了就是…」类解释，减少金融黑话堆砌。见 `course_tutor_agent_plan.md`。

### 2026-08-19

- **课程讲解 · 历史标题**：新对话首轮用短模型总结侧栏标题（失败则截断问句）；续聊与手改标题不覆盖。见 `course_tutor_agent_plan.md` §0.7 / D8。
- **商城 · UX-13 首页观感落地**：精选轮播置顶、渠道下移 compact、楼层口语副标题、商品卡精选/热卖角标、导购 chips。见 `UI_DESIGN.md` §4.3.2。
- **课程讲解 · 历史会话稳定性**：LLM 失败不再留下空会话；连点历史不串泡；发送失败回滚气泡并还原输入；API-05 回带 `teacher_id` 防串老师；DELETE 204 空 body 不再误判。见 `course_tutor_agent_plan.md` §0.7 / API-05。
- **课程讲解 · 历史会话**：`/course-tutor` 桌面侧栏 / 移动抽屉；列表、还原续聊、新对话、删除；API DELETE/PATCH 会话。见 `course_tutor_agent_plan.md` §0.7。
- **课程助手 · 独立 schema**：业务 8 表迁入 `course_agent`（迁移 0095，对齐 `sms`）。见 plan §3.0。
- **商城支付宝 P0–P2**：交易 notify 验签剔除 `sign_type`；回跳不再误关在途单；关单前 query/close；免登录结果页轮询 30s。见 benchmark plan（`storefront_toc_benchmark_plan.md`） §6。
- **商城 · 店铺渠道**：首页「我们还有这些店铺渠道」；含抖店二维码（OSS）；运营台「引流店铺」可改链接/上传码；顶栏品牌 logo；OSS 按 `brand/logo` 与 `channels/qr/{平台}` 分类。见 `storefront_ops_console_plan.md` §11.7。
- **商城运营台 · 跨端互跳防 404**：未登录不再相对跳 `/workbench/login`（本地会打到商城 :3000）；改走 `NUXT_PUBLIC_WORKBENCH_ORIGIN`（dev `:3001`），环回 host 与地址栏对齐以免 Cookie 丢失。见 `storefront_ops_console_plan.md`。
- **商城运营台 · 商品编辑左编右预**：发布/编辑页对标工作台短信落地短链——白话 intro、四步锚点、右侧实时预览（图文步手机商详）+ 就绪勾选；小白可按 1→4 上架。见 `storefront_ops_console_plan.md` §11.6.6。
- **课程助手 · 李伟文对齐**：展示名统一 **李伟文**；人设进 system（不进课稿 KB）；对话 RAG 改百炼 OpenAPI Retrieve；授权用户多轮命中实调 PASS。见 `course_tutor_agent_plan.md`。
- **商城 · 课程讲解全屏**：顶栏 Tab「课程讲解」→ `/course-tutor`；全幅 IP 海报 + **铺满**半透明对话层；工作台「设置」可上传海报（OSS `products/course_agent/teachers/…`）。见 `PORTRAIT_SPEC.md`。
- **商城 · 手机号登录**：未注册号也会真实发短信验证码；验证通过后自动创建买家账号（随机口令，可后续设密）。见 `STOREFRONT_SCHEME.md` §5.2。
- **课程助手 · 李伟文文稿已清洗入百炼**：Raw 仅 `web/智能体原始稿/李纬文课程逐字稿/`；清洗稿同步百炼 KB。见 `course_tutor_agent_plan.md`。
- **工作台 · 智能体管理**：授权用户 / 订单开通 / 自动规则 / 限流 / 知识上传 / **IP 海报上传**；权限码 `course_agent_acl_read/write`。
- **课程助手 · 多老师隔离与编排修补**：拒答、退款作废、导入并集、对话超时与切老师丢弃进行中回复。

### 2026-08-18

- **工作台 · 短信推广编辑预览**：右侧实时预览铺满当前高度，按「绑定商品 / 号池 / 发送时间 / 落地页 / 成效」展示更完整的配置摘要（KPI、名单、就绪检查）。见 `sms_landing_shortlink_plan.md` §10.2。
- **工作台 · 同事分组同步全域订单**：分销账号「同事分组」保存后立即把 `日报.全域订单` 的分组/次级分组对齐 `抖音订单.同事_分组`（含历史行）；存量回填 `scripts/db/align_quanyu_colleague_group.py`。见 `colleague_group_ads_sync_plan.md`。
- **工程 · `.env` 只放密钥/账号**：JWT/导出 TTL、OSS 前缀、短信验证码 TTL/日限、落地 schema 与短链 host、退款宽限、引导智能体日限/RPM、通知合并窗口、财务定稿批上限、罗盘心跳等改为 `settings.py` 字面量；运维回滚仍用 `DW_ENTITLEMENT_REFUND_LEGACY`。见 `env-secrets-only.mdc`。

### 2026-08-17

- **工作台 · 短信推广未打开补发**：短链可开「发送后未打开落地页则等待后再发」；可配等待时长与最多再发次数（默认关 / 24 小时 / 1 次）。见 `sms_landing_shortlink_plan.md` §2.8.2。
- **工作台 · 短信推广封面可选**：短链可开关「展示封面图」；仅开启时要求上传且公开落地页出图；换图/清空时自动删除旧 OSS `sms_landing/` 对象。见 `sms_landing_shortlink_plan.md` FR-05。
- **工作台 · 短信推广短链平台闸门**：落地短链可配置购后短信「不限 / 仅允许 / 排除」平台（对齐全域订单平台原文）；编排跳过记 `skipped_platform`。见 `sms_landing_shortlink_plan.md` §2.8.1。
- **工作台 · 短信推广分配规则默认轮询**：新建短链默认 `round_robin`；号池从「单号」扩到多号时自动切到轮询（不再默认权重随机）。
- **工作台 · 短信推广选品去掉排除**：绑定商品仅保留搜索 + IP/平台/店铺纳入筛选。
- **工作台 · 短信推广编辑页锚点滚动**：合并号池与分配规则；一页纵向配置 + sticky 锚点跳转，右侧预览跟随当前区块。
- **集成 · 快手小店订单推送入库**：新增 `POST /api-data/push_from/kuaishou/api_kuaishou_push`（`快手订单_push`）；已按官方消息文档对齐订单状态/新增/地址/费用变更与售后新增·更新（AES `messageSecret`）。见 `integrations/快手/push/index.md`（`index.md`）。
- **集成 · 小红书订单推送入库**：新增 `POST /api-data/push_from/xiaohongshu/api_xiaohongshu_push`（`小红书_push` 总表/`evt_*`/Celery）；对接开放平台应用消息推送验签与 `{"test":true}` 探测。见 `integrations/小红书/push/index.md`（`index.md`）、`push_data_spec.md` §2.6。

### 2026-08-14

- **工作台 · 分销账号申请文案澄清**：按钮改为「一键申请绑定到我」；明确仅登录本人、不能代他人换绑；页内三步条/弹窗/RAG/tour 同步。见 `account_oa_approval_plan.md`。
- **工作台 · 分销账号变更申请视觉引导**：页内「查询→确认→申请」三步条；无结果时一键按钮灰色；历史/成功页彩色状态标签；el-tour 升为 `account_v2`；RAG/capability 同步「先搜后申」。见 `account_oa_approval_plan.md`。
- **数仓 · 企微 schema 治理二期**：引导智能体企微消息落 `企业微信_push.evt_guide_agent_text`（可走统一 `push_from`）；员工/部门表 `wecome_*` rename 为 `wecom_employee` / `wecom_department`。见 `wecom_bank_schema_governance_plan.md` §7.2。
- **数仓 · schema 切流漏网补丁**：现网清零「企微与农行」函数引用（含支付宝 bank seed / 全域刷新旁路 / quick_bi）；对外收款 HTTP 补 AEAD 第二层；工作台姓名源与认领 JOIN 对齐 `企业微信`。见 `wecom_bank_schema_governance_plan.md`。
- **数仓 · 企微 / 银行 schema 拆分完成**：宽表与推送落 `企业微信` / `企业微信_push`；对公收款 schema rename 为 `其他银行收款`；ADS/认领相关 SQL 已切流；OA 推送以 push 总表为准（ORM 双写默认关）。见 `wecom_bank_schema_governance_plan.md`。
- **数仓 · 直播订单汇总补快手**：`refresh_直播订单汇总` / `sql/直播数据.sql` 按抖音同口径纳入快手公域（`带货人视频号=账号` + 直播流量 + 时间窗）；`/me` 直播 tab 与结算快照随 ADS 带上。见 `me_live_orders_plan.md`。
- **工作台 · 分销账号一键审批增强**：一键按钮常显；新 Tab「历史申请记录」；企微历史 OA 最长 365 天回填入申请单；引导/tour 强化「先搜索再申请」。见 `account_oa_approval_plan.md`。
- **工作台 · 分销账号一键企微审批（P0 收尾）**：OA-03/21 全绿；RBAC §5.4 / 引导知识库 / capability map 改为「一键申请（截图降级）」；ECS 部署脚本 `deploy_account_oa_ecs.py`。见 `account_oa_approval_plan.md`。
- **工作台 · 分销账号一键企微审批（P0）**：查询有结果后可「一键申请绑定到我」；`oa_template` / `oa_apply` / `oa_detail`；对照真实模板控件；通过后**不**自动写维表。见 `account_oa_approval_plan.md`。
- **工作台 · 结算快照「有变更」误标修复**：生成期指纹改为落盘 round-trip 后再哈希；并对 `2026-07` V7 回填标签（全员误「有变更」→ 约半数「与上版一致」）。见 `order_settlement_snapshot_plan.md` T21a。

### 2026-08-12

- **工作台 · 系统公告体验**：弹窗加宽；正文图片可点击全屏预览；管理列表中文状态色标 +「生效中」+ 更新时间，便于区分新旧与当前是否在投。见 `announcement_enterprise_gap_plan.md` UX-IMG / UX-LIST。
- **工作台 · 功能引导助手 · 知识库自动同步**：`python manage.py sync_guide_agent_kb [--commit]` 经百炼 OpenAPI 上传 `knowledge/*.md`（无需改工作台 OSS）。见 `aliyun_bailian_llm.md` §3.2、GA-27。
- **工作台 · 功能引导助手 · 防冲突四件套**：能力表优先短答闸（改密/结算等跳过 LLM 瞎编）；黄金问集 ≥30 离线门禁；发版须导出知识+测全绿+覆盖上传百炼。见 `workbench_guide_agent_plan.md` GA-24～26。
- **工作台 · 个人中心文案**：TOC「经营数据」改为「个人订单」；「我的文件」三路来源；引导助手知识库 07–09（含纠正「不支持改密」）。见 `me_personal_files_plan.md`、`workbench_guide_agent_plan.md`。
- **工作台 · 功能引导助手 · 按钮去重 + 多轮评估**：同 scene 重复「去订单认领/页」合并为规范双入口；预发多轮可用性剧本见 plan GA-UAT-02。
- **工作台 · 功能引导助手 · 知识库补齐**：导出包新增认领/歧义说明与分场景 howto；对话按问句注入检索片段（缺单强制附操作说明），操作正文不再只靠 `constants`/`tools`。见 `workbench_guide_agent_plan.md` GA-15、`aliyun_bailian_llm.md` §3（需覆盖上传 05/06）。
- **工作台 · 功能引导助手（P0–P2）**：右下角浮球；三段式浮层；百炼对话 + **function calling**（打开页面/重放引导/列功能）+ 知识库 RAG + 记忆库；可选企微收消息。总闸 `SIWEICHONGSU_GUIDE_AGENT_ENABLED`。见 `workbench_guide_agent_plan.md`、`aliyun_bailian_llm.md`。
- **运维 · 短信发送审计（任务记录+消耗统计）**：工作台发送记录页拆「短信记录 / 消耗统计」；明细对齐控制台送达与报告时间、链接点击；日汇总条数/金额估算（`sms_send_log`×单价）。见 `sms_landing_shortlink_plan.md` SL-T-58。
- **运维 · 短信发送记录 ↔ 阿里云对齐**：工作台「送达结果」列（与控制台发送成功/失败一致）；Beat 每 5 分钟自动 `QuerySendDetails` 刷新 pending；试发 `run_aliyun_sms_send.py --promo --write-log`。见 `sms_landing_shortlink_plan.md` §5.6。
- **运维 · 短信落地 · 公开页 TOC 多端**：`s.siweichongsu.com/{code}` 三步激活条 + 双栏布局（桌面 sticky TOC / 移动横滑）；单 CTA 与 assign 埋点不变；工作台预览同步。见 `sms_landing_shortlink_plan.md` §10.1。
- **运维 · 短信落地 · 助教成效统计**：按助教/短链看 CTA 与加人（编辑页「号池成效」、号库跨链汇总）；事件与日表冗余 `assistant_id`；加人率口径统一为加人÷CTA。见 `sms_landing_shortlink_plan.md` SL-T-56/57。
- **运维 · 短信落地 · 助教号细粒度审计**：配置保存写短链级 + 每变更号级审计（权重/启停/增删）；审计页可按助教名过滤。见 `sms_landing_shortlink_plan.md` SL-T-55。
- **工作台 · 提醒文案 · 通知对象**：支持「仅销售 / 业务圈定 / 指定同事」；指定同事多选联动工作台账号；侧栏展示摘要。见 `workbench_notify_hub_plan.md` NH-12/13。
- 短信落地：`s.siweichongsu.com` nginx 切到 Django 公开页（修商城 404）；SendSms 参数 `${product_name}`+`${code}`；选品为花名册纳入筛选。见 `sms_landing_shortlink_plan.md`。
- **工作台 · 结算快照指纹比对列**：内容指纹仅比对订单状态、商品金额/数量、直播类列、特殊情况列；可用 `recompute_order_snapshot_fingerprints --settlement-month YYYY-MM --commit` 回填标签。见 `order_settlement_snapshot_plan.md` T21a。

### 2026-08-11

- **运维 · 短信落地 · W4 硬化**：overview 含加人成功/加人率；PATCH 改主键不丢次键；OTP 发送记录强制掩码；企微 `friend_request` 事件失败可重试；缺 match 行时 resolve 回退。见 `sms_landing_shortlink_plan.md` §15 SL-T-49～53。
- **运维 · 短信落地 · W4 多商品 + 加人成功**：一短链可绑多个匹配键（`sms.sms_landing_match`）；CTA assign 注入 `customer_channel`；企微获客 `friend_request` 回调归因写入 `add_success`；工作台漏斗展示加人。见 `sms_landing_shortlink_plan.md`。
- **工作台 · 短信发送记录 · 手机号全量展示**：列表/详情/CSV 展示完整手机号（`sms.sms_send_log.phone`）；OTP 验证码仍脱敏。见 `sms_landing_shortlink_plan.md` §5.6。
- **工作台 · 短信推广 · 整页编辑与花名册选品**：新建/编辑为独立页（顶栏模块 Tab + 左表单/右预览）；绑定商品目录同源花名册「商品名称与简称」（表格+IP/平台/店铺筛选，不手填）；新建默认延迟 5 分钟。见 `sms_landing_shortlink_plan.md` §10.2。
- **工作台 · 短信推广独立导航与权限**：侧栏新建「短信推广」（落地短链 / 审计 / 发送记录）；权限码 `sms_promo_read` / `sms_promo_write`，与「小鹅通权益开通」解耦；Admin 可单独授权。见 `sms_landing_shortlink_plan.md`、`workbench_rbac.md`。
- **运维 · 短信落地 · 购后推广编排（W2.7）**：水位 `sms_send_watermark` 初始化为上线时刻、不扫历史；Celery Beat `sms_promo_orchestrator_tick` 捞 `日报.全域订单` 新增有手机号订单，命中短链后发推广短信并写 `sms_send_log`；支持 `run_sms_promo_orchestrator` dry-run。见 `sms_landing_shortlink_plan.md` §2.8 / §5.6。
- **运维 · 短信 · OTP 入发送记录**：工作台绑手机/登录等验证码发送成败写入 `sms.sms_send_log`（`sms_type=otp`，快照掩码验证码）；与推广 TemplateCode 强制隔离（SL-T-12 / SL-T-30）。见 `sms_landing_shortlink_plan.md` §5.6、`aliyun_sms.md`。
- **运维 · 短信落地 · 发送记录（物料）**：短信推广「发送记录」；`sms.sms_send_log` 记发送/回执双状态、内容快照、计费条数；支持刷新回执（QuerySendDetails）、失败单条重试、CSV 导出与短链打开/CTA 漏斗。见 `sms_landing_shortlink_plan.md` §5.6 / §10.4。
- **运维 · 短信落地 · 独立 schema**：业务表在 PostgreSQL schema `sms`（`settings.SMS_SCHEMA`）；与 `public` / 咨询域隔离；后续发送表同 schema。见 `sms_landing_shortlink_plan.md` §5.0。
- **运维 · 短信落地 · 推广发送时间**：短链可配「尽快 / 每日时段 / 每日定点」与延迟；窗外延后，编排遵从该窗。见 `sms_landing_shortlink_plan.md` §2.8.1。
- **运维 · 短信落地 · 配置审计页**：短信推广「落地短链审计」；支持按动作/操作者/短码/商品键/日期筛选，详情含字段级前后对比与完整 JSON。见 `sms_landing_shortlink_plan.md` §10.3。
- **运维 · 短信落地短链 · 号池效率（P0/P1）**：批量粘贴 / 复制号池；助教号库与助教组多选挂入；页内「落地短链 / 助教号库 / 助教组」三 Tab。见 `sms_landing_shortlink_plan.md` §2.7。
- **运维 · 短信落地短链 · 多号分流**：同一商品短链可挂多个企微获客号，支持加权/轮询/粘性/优先级等 `route_mode`；公开页 CTA 先 `assign` 再跳转。见 `sms_landing_shortlink_plan.md`。
- **运维 · 短信落地短链（自建）**：公开域 `s.siweichongsu.com/{code}` 挤压页（点击跳转企微获客）；工作台按商品名/简称分配企微链；PV/CTA 事件与日汇总可统计。见 `sms_landing_shortlink_plan.md`。

### 2026-08-10

- **商城 · 买家账号对齐 ToC（P0–P2）**：手机 OTP 登录/注册/短信找回；改密吊销会话（token `pv`）；失败锁定；Cookie 双提交 CSRF（`sf_csrf`）。见 `storefront_toc_benchmark_plan.md` §5.4、`STOREFRONT_SCHEME.md` §5。
- **工作台 · 登录页适配手机号登录**：账号表单内「密码登录 / 手机号登录」同级分段 Tab；说明条 + 验证码行内获取；页脚链路收敛。见 `UI_DESIGN.md` §5.8。
- **商城 · 短信绑手机已落地**：`POST store/user/send_phone_code` / `bind_phone`（OTP purpose=`store_bind`，与工作台隔离）；个人中心去绑定、线上课结算拦截、订单 `need_phone` 可绑后重试开通。见 `storefront_toc_benchmark_plan.md` §7.2、`aliyun_sms_plan.md`。
- **工作台 · 短信登录生产开通**：ECS 补全签名「广州市思维重塑文化科技」+ 模板 `SMS_333355524`；清理手机号重复绑定并加唯一索引；企微空号写入跳过已被占用号码。试发/生产发码已对 `173****8673`、`189****6197` 通过。见 `aliyun_sms_plan.md`。
- **工程 · 公开更新日志仓**：新增 [`LaEirt/pk-changelog`](https://github.com/LaEirt/pk-changelog)，与根 `README`「更新动态」全文同步；脚本 `scripts/sync_pk_changelog.py`。

### 2026-08-08

- **工作台 · 通知中台**：提醒文案改为纯中文编辑（无 `{{…}}`）；月份/笔数系统拼接；另含保存 diff、歧义合并、免打扰、企微 textcard、发送记录与再次提醒冷却。见 `workbench_notify_hub_plan.md`。
- **工作台 · 企业式结算触达（§16）**：落盘后提醒查看（不推附件）；站内必达 + 企微尽力；按人/可降噪/可熔断；每人×通道审计（Q44）。见 `order_settlement_snapshot_plan.md` §16。
- **数仓 · 全域订单售后标签/退款闭环已上线**：`classify` + ODS/ADS；历史 **QR-01=0**；日批 DQ（Beat 07:30，非零邮件 `QUANYU_REFUND_DQ_TO`）。见 `quanyu_order_refund_status_plan.md`。
- **工作台 · 用户管理搜索姓名 + 表内排序**：`q` 覆盖 `first_name`（列表与角色页批量加人）；表头支持 ID/用户名/姓名/邮箱/状态/最后登录服务端排序。见 `workbench_admin_users_plan.md` §5.1。
- **数仓 · ORDER_CLAIM 迁出小鹅通 schema**：全量函数 `SEARCH_PATH=业务表`；辅助视图改为 `业务表.同事表` / `业务表.对内歧义订单`，并 `DROP` 旧 `小鹅通.*` 同名视图；企微歧义同意可写 `企业内账号id`。见 `业务表.ORDER_CLAIM.sql`、`wecom_unclaimed_decouple_plan.md` G3。
- **工作台 · 结算快照生成撤回**：已发布批可撤回（软删个人盘系统/总包 + 清批真源 → `withdrawn`）；与「备份已清理」同义、列表只显示「已撤回」；详情「更多 → 撤回本批」；UAT 清场见 plan §15。见 `order_settlement_snapshot_plan.md` Q43 / OS-24*。

### 2026-08-07

- **工作台 · 财务定稿抗量 P0–P2**：上传分批（≤50）+ 同草稿 append；确认改 Celery 异步（202 + 轮询）；部分成功可重试失败文件；单文件/批/草稿硬上限。见 `order_settlement_snapshot_plan.md` OS-23*。
- **工作台 · 导出审计列补齐**：系统管理「导出审计」展示创建者 **姓名 / 用户名 / 手机**（`scope=all`）；§5 登记另存为 API-08。见 `workbench_async_export_plan.md` EX-19。
- **工作台 · 结算企微通知改邮箱解析**：不再依赖企微 binding；用 `auth_user.email`（`@fakeer.ltd`）调 `get_userid_by_email` 再发应用消息。见 `order_settlement_snapshot_plan.md` T20。
- **工作台 · 结算快照 Q42 已落地**：重生仍全员落盘；片级 content_status；内容指纹用规范化 CSV（非 xlsx 字节）；默认仅通知变更/新增。见 `order_settlement_snapshot_plan.md` Q42 / T21。
- **工作台 · 结算财务 Group 名对齐**：默认认 `财务group`（不再误用/误建空组「财务」）；可用 `ORDER_SNAPSHOT_FINANCE_GROUP_NAME` 覆盖。见 `order_settlement_snapshot_plan.md`。
- **工作台 · 订单认领银行收款必填**：平台=`银行收款` 时提交/导入须同时有有效「同事」与「商品名称」（列表提交与批量导入预览同步拦截）。见 `wecom_unclaimed_decouple_plan.md` T5 / WU-08·09。
- **工作台 · 结算生成记录防误导**：批真源清理后列表显示「成功 · 备份已清理」，详情不可再补发/定向投递。见 `order_settlement_snapshot_plan.md` OS-21。
- **工作台 · 结算与「我的订单」交互一致性**：个人中心 Tip 指向「我的文件 → 我的订单/月结算」；直播去掉「财务结算用」误导；定向投递禁止写入财务定稿；Admin 夹/标签显示为「总包」；批真源清理后清空 manifest，缺失真源返回 `ARTIFACT_MISSING`。见 `order_settlement_snapshot_plan.md`。
- **工作台 · 结算快照 UAT 断连通知**：站内公告 + 企微默认关闭（`ORDER_SNAPSHOT_NOTIFY_ENABLED`）；可跑全链路分发演示；正式开通知设 env=`1`。见 `order_settlement_snapshot_plan.md` Q36。
- **工作台 · 我的文件 ToC 下一波**：文件夹树可折叠展开（记忆展开态）；列表多选批量下载 / 移入回收站 / 还原 / 彻底删除。见 `me_personal_files_plan.md` §7.2。
- **工作台 · 我的文件 ToC 体验**：拖拽上传、空态行动、类型图标/来源标签、可读体量与时间、紧凑工具栏与配额卡、搜索防抖。见 `me_personal_files_plan.md` §7.2。
- **工作台 · 我的文件回收站可见性**：软删「结算/订单」等夹内文件后，回收站根可直接看到；嵌套软删夹挂到回收站树根；还原文件夹连带还原子树文件。见 `me_personal_files_plan.md` PF-07b。
- **工作台 · 财务定稿备查去重**：确认分发时若接收人就是操作者，不再二次写入备查，避免「我的文件」同目录出现 `文件(2)`。见 `order_settlement_snapshot_plan.md` Q26 / OS-14d。
- **工作台 · 财务定稿 / 定向选人改前端拼音**：一次拉用户列表 + `usePinyinSelectFilter`；定稿未匹配行改为搜索指派。见 `order_settlement_snapshot_plan.md` API-02e。
- **工作台 · 财务定稿上传对齐对公/比对**：管理页改为 `el-upload` 拖拽多选 + 上传中遮罩；仍走 multipart API-08。见 `order_settlement_snapshot_plan.md` Q24。
- **工作台 · 发给指定同事支持其他用户**：详情页可切「本批同事 / 其他用户」；其他用户按姓名/拼音/邮箱/编号搜索，可发给任意活跃用户（不排除管理员）。见 `order_settlement_snapshot_plan.md` API-02e。
- **工作台 · 发给指定同事再简化**：姓名联想（本批唯一已注册同事）、行级「选并带出同事」、按勾选自动跟建议文件夹、文件筛选；≤3 文件确认降为一行。见 `order_settlement_snapshot_plan.md`。
- **工作台 · 结算快照详情整页**：批详情由侧栏改为整页展开；「指定投递」改为三步「发给指定同事」；毛玻璃分层（`--wb-glass-*`）。见 `order_settlement_snapshot_plan.md` FR-17。
- **工作台 · 结算批可取消生成**：排队中/生成中可取消（API-02d）；Worker 协作中止；管理页列表与详情有入口。见 `order_settlement_snapshot_plan.md`。
- **工作台 · 结算预览 ZIP 改仅本地**：`build_package` 不再上传 `order_snapshots/preview/`；落 `EXPORT_STORAGE_ROOT/order_snapshot_previews/`（24h）；管理页「预览并下载」自动拉流，刷新后可「重新下载」。见 `order_settlement_snapshot_plan.md` API-00a / FR-01b。
- **工作台 · 结算快照审计修补**：水位查询改用 `transaction.atomic` 隔离失败 SQL（修复 stale 警示失效）；定向 dry_run 全失败时前端不再误确认；财务/系统预览 ZIP 可读 blob 错误文案。见 `order_settlement_snapshot_plan.md`。
- **工作台 · 结算快照定向投递 + 财务定稿预览**：管理页批详情可勾选真源文件投到指定用户（系统/Admin/财务定稿）；财务定稿 staging 可下载预览 ZIP（不落员工盘）。见 `order_settlement_snapshot_plan.md` Q40/Q41。
- **工作台 · 结算快照批级真源 + 分发**：生成先写 `order_snapshots/batches/{id}/v{n}/`（含未注册片），再按注册投递个人夹；管理页「补投递未注册」从真源分发（不重切 ADS）。见 `order_settlement_snapshot_plan.md` Q39/Q38。

### 2026-08-06

- **工作台 · 结算预览升级为完整 ZIP**：`build_package` 生成与正式批同目录结构的包，上传工作台 OSS（或本地回退），鉴权下载；**不写个人盘、不发通知**。见 `order_settlement_snapshot_plan.md` API-00a。
- **工作台 · 结算快照审计修补**：同月 PENDING/RUNNING 互斥；财务 staging 24h 过期与写盘失败回退；schema_drift 列差；水位扩到认领/填报；比对选盘捷径与 tip 单源。见 `order_settlement_snapshot_plan.md`。
- **工作台 · 结算快照验收收口**：OS 自动化用例全绿（重生/补写/超限/drift/stale/通知/另存）；数据比对选盘增加「我的订单 / 最近结算月 / Admin 总包」捷径。见 `order_settlement_snapshot_plan.md`、`data_compare_plan.md` §14。
- **工作台 · 数据比对「从我的文件选盘」**：A/B 槽位可切本机上传或我的文件（面包屑+文件卡片，禁裸下拉）；表头不一致时禁用比对并列出差列。见 `data_compare_plan.md` §14。
- **工作台 · 订单结算快照落地**：系统批（`日报.直播订单汇总` → 财务盘 `Admin/V*` + 员工 `系统/V*`）+ 财务定稿预校验确认分发；管理页 `/admin/order_snapshots`；下载任务可另存「我保存的下载文件」。见 `order_settlement_snapshot_plan.md`。
- **商城 · 支付宝收银台（W3）代码落地**：`prepare` / 异步 `notify` / `pay_status`；伪支付下线（410）；买家端 `/order/pay/[id]` 与 `/order/pay-return`；生产收款仍待支付宝产品签约审核。见 `storefront_toc_benchmark_plan.md` §6。
- **Celery · 微信订单 realtime 锁跳过降噪**：`wechat_order_realtime` 单飞 + 过期丢弃积压任务；FakerOrder merge 短重试；小时告警邮件不再把 `LOCK_SKIP:*` 当硬失败刷屏（仍入库可查）。

### 2026-08-05

- **工作台 · 个人中心「我的文件」落地**：多级文件夹、1GB/20MB 配额进度条、STS/multipart 上传、软删回收站 30 天、闲置 365 天延长；入口 `/me?tab=files`（导出任务与账户安全之间）。见 `me_personal_files_plan.md`。
- **商城运营台 · 课程选小鹅通商品名**：商品编辑「小鹅通 ID」改为可搜索下拉（名称→自动填 `resource_id`）；选项与选中态展示封面 / 类型 / 分组 / 价格 / 简介；`GET store/admin/products/xiaoe_options/` 读维表并关联小鹅通详情。见 `storefront_toc_benchmark_plan.md` §8.4 / API-G6。
- **商城 · 管理端↔买家对齐整理**：详情图集消费运营台 `images[]`；文档统一商详网格/≤5MB/API-G2=`goods_detail_text`；对照表见 ops §11.6.8。`tags` 暂缓。
- **商城 · 商详图进 OSS + 运营台网格编辑**：详情 HTML 内小鹅通 CDN 迁自有桶并改引用；编辑页对标抖店「商详图片」网格（拖拽/上传/从主图填入/高级 HTML + 手机预览）。见 ops §11.6.7、`aliyun_oss.md`。
- **商城运营台 · 编辑页对齐抖店图文**：顶部分区 Tab；主图多槽位；「从主图填入」详情；右侧手机预览；类型履约 tip。不做 AI/视频/多规格 SKU。见 ops §11.6.6。
- **商城运营台 · 商品管理二轮对齐**：空态 CTA、标题进编辑、复制 ID、类型筛、销量列、`?tab=`、分页规格、更多菜单；编辑页面包屑 / 未保存离开 / 缺封面确认。见 ops §11.6.5。
- **商城运营台 · 商品编辑整页对标**：去掉侧栏 Drawer；发布/编辑走 `/store/admin/products/new` 与 `/products/:id`（分区锚点 + 底栏保存）；列表仍含出售中 Tab / 批量上下架。见 `storefront_ops_console_plan.md` §11.6。
- **商城 OSS · 商品图公开读已开通**：关闭「阻止公共访问」+ 桶策略 `products/*` 匿名只读；上传无对象 ACL；试传 `--check-public` 匿名 GET 200。见 `aliyun_oss.md`。
- **商城运营台 · UI/UX 对标抖店/微信小店**：分组侧栏、待办角标、中文状态 Tag、筛选卡、可点 KPI、统一页头；见 `storefront_ops_console_plan.md` §11.5。
- **商城 · 工程余项落地**：开通 T6 去重；软库存 `product_id` 双写；运营台订单「重试开通」；商品图 CDN→OSS 迁移脚本；FE 验收 TB-T-FE-01/03。见 `storefront_toc_benchmark_plan.md`。
- **OSS 已开通**：双桶试传 put/delete 通过；`aliyun_oss.md` / INDEX 标已开通；商城 `storefront_public_url` 内网 Endpoint 自动回退外网域名。见 `aliyun_oss.md`。
- **侧栏/顶栏刷新丢栏位**：工作台权限集改为 permissions∪capabilities，hydrate 后清过期 capabilities；商城会话 `sessionValidated` + 分类加载失败可重试。见工作台 `workbenchNavAccess` / 商城 `stores/user`。
- **商城 · 非支付/短信能力落地**：运营台商品 CRUD + OSS 上传；支付成功入队小鹅通开通 + 订单「去上课」；搜索联想与 `/category/[name]`；支付宝/短信仍**审核中**。见 `storefront_toc_benchmark_plan.md`。
- **商城 · W1 商品本地化落地**：`user_info.storefront_product` DDL + 小鹅通第一批快照 seed（234 条）；列表/详情/热门/推荐改读本地；精选标记替代写死「视频课」；下单 `delivery_type` 服务端聚合。见同上 §8。
- **工作台 · 阿里云 OSS 接入**：工作台桶 `siweichongsu-workbench`（**杭州**，与 ECS 同地域可走内网）与商城桶（北京）分桶分地域；导出 + 公告图走工作台桶；导出保留 **14 日**。见 `aliyun_oss.md`。
- **商城 · ToC UX 落地（W2 部分）**：IP 老师宫格改末字圆形头像（禁歧义功能图标）；移动底部 tabbar、详情页购买 CTA 层级纠正、首页轮播可点、空态统一、清理「我的课程」虚假文案、页脚/帮助客服渠道可配置；支付宝支付与短信标为**审核中**（生产切流待通过）。见同上 benchmark plan。
- **工作台 · 阿里云短信接入**：复用思维重塑 RAM 经 Dysmsapi；登录态绑手机 + **游客手机号验证码登录**（须先绑定）；登录页 / 个人中心 UI。见 `aliyun_sms_plan.md`。
- **商城 · ToC 对标上线方案（规划中）**：主流电商差异点（功能/UI）、支付宝收银台（page.pay/wap.pay + notify）、支付成功自动开通小鹅通课程 + 「去上课」引导、商品从小鹅通 ODS 切本地 `storefront_product` + 运营台商家自录；秒杀/拼团/砍价明确不做。见同上 benchmark plan。
- **商城 · 文档与代码对齐**：全站 SSR 已落地（买家交易页 + `/store/admin`）；P1.5 独立能力与运营台 P0–P2 标「代码齐 · 待预发 UAT」；测试基线 Vitest 26 / Playwright 24；`web/vue-storefront/` 已从仓库移除，相关引用清理。见 `web/nuxt-siwei-storefront/IMPROVEMENTS.md` §10。
- **规范 · 拉数控制面 R5 落地**：抖店/微信/快手/企微深窗 DLQ；`common.retry`（含 5xx/超时）接入主 HTTP；plan 标已上线。见 `api_pull_control_plane_rollout_plan.md`。
- **规范 · 拉数控制面 R1–R4 已接入**：微信/抖店/小鹅/快手/小红书/螳螂/微伴/企微主 `run_*` 经 `jobs/common/pull_wrap.run_controlled` 写 `api_data.pull_*`；replay CLI 已扩登记。
- **规范 · 拉数控制面试点通过并推广**：支付宝为 `api_data.pull_*` + `jobs/common` **参考实现**；全 `JOBS_INGEST_PACKAGES` 波次见同上 plan。
- **文档 · `.cursor/project` 按域收紧**：`API_CONTRACT_BACKFILL` → `workbench/platform/`；支付宝 SDD → `integration/alipay/`；Flask 完结 plan → `integration/_archive/`；SQL 评估报告 → `sql/eval_reports/`；精简 `INDEX.md`，补 `storefront/README.md`。
- **集成 · 支付宝退款总表键与平台店铺**：`merge_refund_order_total` 售后单号改为 `refund_{商户退款请求号}`（空则流水号）；未入全域时平台/店铺兜底为「银行收款/支付宝」（经营码）或「支付宝/{数据来源}」。
- **集成 · Flask→Django 迁移标已完结**：推送/OAuth/Token 与内部运营 Web 均归档至 `web/归档/flask/`；根 `flask/` 仅 README；工作台无 Flask 依赖。见 `flask_push_to_django_migration_plan.md`。
- **数仓 · 赠课退款规则与开通同源**：`refresh_refund_candidate_gift` 改读 `dim_giftcourse_rule`；开通排除权威为 `dim_exclude_course`。见 `xiaoe_delivery_improvement_plan.md`。
- **集成 · 支付宝切换收尾对账**：农行历史单一次性回补 ADS（`sql/alipay/53_backfill_ads_orders_from_bank.sql`，数据来源=`银行回补`）；重刷 `日报.全域订单(2024-12-01, today)`；经营码支路与全域金额对齐（孤儿清零）；运维脚本 `scripts/local/run_alipay_cutover_remediation.py`。

### 2026-08-04

- **集成 · 支付宝对公上传停用 + 认领单写**：对公填报不再上传/同步 `企微与农行.支付宝`；ORDER_CLAIM / 实时 sync 只回写 `"支付宝"."支付宝订单"`；农行种子默认关闭。
- **集成 · 退款总表支付宝源切换**：`日报.merge_refund_order_total` 改为读 `"支付宝".alipay_data_bill_accountlog_query`（`交易退款`）；售后单号现为 `refund_{商户退款请求号}`（见 08-05）；清理旧键防双计。
- **集成 · 支付宝 ETL 收入防抹零**：窗内仅有退款流水时回挂全量 sell；UPSERT 不用 0 覆盖已有收入/退款。例：`2026071623001434161446222509` 已恢复 6980。
- **集成 · 支付宝交易状态「成功（有退款）」**：`update_user_id_status` / ETL 在 sell 成功且退款额>0 时写入新状态；全域订单映射为「已完成(部分退款)」并带出退款金额。见 `小鹅通.update_user_id_status.sql`。
- **集成 · 支付宝删除 trade.query 表与遗留列**：`DROP` `alipay_trade_query`（及旧名）；`支付宝订单` 去掉「平台交易状态/买家账号/资金渠道json」。见 `sql/alipay/46_drop_alipay_trade_query.sql`。
- **集成 · 支付宝 enrichment 回填**：从 `企微与农行.支付宝` 全量补空「同事/姓名/联系方式/产品」（脚本 `sql/alipay/52_backfill_enrichment_from_bank.sql`）。
- **集成 · 支付宝退役 trade.query**：同步代码与 Beat 已移除；表/列删除见上条。见 `integrations/支付宝/`（`README.md`）。
- **集成 · 支付宝订单模型收敛**：废弃 `"支付宝订单认领"`；同事/姓名/联系方式/产品/直播标题并入 `"支付宝订单"`；ETL 不覆盖 enrichment；全域订单 / ORDER_CLAIM / seed 已对齐。见 `integrations/支付宝/`（`README.md`）。
- **工作台 · 订单认领顶栏导出对齐**：认领 / 企微填报共用 `WorkbenchExportDropdown`（导出本页即时下载、导出全部异步任务）；企微新增 kind `unclaimed_order.wecom_product_fill`。见 `wecom_unclaimed_decouple_plan.md`。
- **工作台 · 订单认领首访引导同步企微解耦**：`el-tour` 升为 `unclaimed_v2`（已看过旧引导的用户会再看一次）；覆盖顶栏「订单认领 / 企微填报」、筛选、编辑提交与帮助重放。见 `workbench_toc_ux_evolution_plan.md`。

### 2026-08-03

- **工作台 · 企微与订单认领解耦**：企微不再写入 `订单认领汇总`；认领页 Topbar「企微填报」交互对齐认领台（仅同事不可改），直写 ODS。见 `wecom_unclaimed_decouple_plan.md`。
- **工作台 · 未验证登录引导**：密码正确但未邮箱验证时，提示改为可行动说明，并提供「去注册页完成邮箱验证」直达验证码步骤。
- **工作台 · 注册邮箱输入预检**：填写邮箱时 debounce/失焦调用 `POST /api-data/auth/register/check-email`，已占用当场行内提示；未激活可继续并提示将重发验证码。
- **工作台 · 同邮箱禁止无限注册**：同一 `@fakeer.ltd` 邮箱若已有激活账号则拒绝；未激活则复用该行重发验证码，不再新建第二号（WW-BE-12）。见 `wework_oauth_login_plan.md`。
- **工作台 · 登录 P2**：多账号选号会话写入 sessionStorage，硬刷新不丢选号；清理失效 `redirectToWebLogin` / SSO 展示函数等死代码。
- **工作台 · 登录排查修复**：真 handoff 才恢复企微等待态；改用邮箱/关绑定会清空残留；`/me` 绑定 intent 不泄漏；Chrome 加载企微 JSSDK 不再误判 Webview。
- **工作台 · 登录默认**：首屏改为邮箱密码；角标切「企业微信登录」进入页内面板（扫码续接/选账号仍回企微态）。
- **工作台 · 登录/注册 ToC 交互**：共享 `AuthShell`；字段顶对齐 label + 失焦行内错误；注册两步引导 + 确认密码/强度。见 `UI_DESIGN.md` §5.8 / §5.12。
- **工作台 · 注册页**：新增二次确认密码（不一致不可提交）。见 `Register.vue` / `validateRegisterPasswords`。
- **工作台 · 企微登录 P2**：`/me` 绑定对齐登录——页内面板 callback 优先、自适应绑定导语，「在桌面端打开」仅 handoff 兜底。见 `wework_oauth_login_plan.md` §11.6。- **工作台 · 企微登录 P1**：页内面板按桌面端登录态切换「一键确认 / 扫码」文案；登录主路径仅 `code` 直兑，不再预开 handoff；「在桌面端打开」教育仅兜底。见 `wework_oauth_login_plan.md` §11.6。
- **工作台 · 企微登录主路径更正**：整页 `wwlogin` 在装桌面端时会唤起企微内打开工作台、Chrome 不回跳；默认改回页内登录面板（可快速登录/扫码，`code` 留在浏览器）。见 `wework_oauth_login_plan.md` §11.3。
- **集成 · 支付宝调度**：三 ODS（accountlog / sell / trade_query）改为**每小时**错开刷新；`"支付宝".etl_alipay_order_from_ods` 挂入 `siwei_query_auto_run_slow`（整点）。见 `alipay_account_log_sync_plan.md`。
- **工作台 · 未激活邮箱注册死胡同修复**：未验证账号可在注册页用新密码重发验证码；找回密码对未激活明确报错并引导注册页（不再假成功）。见 `wework_oauth_login_plan.md` WW-BE-10/11。
- **工作台 · 企微扫码同步态可追踪**：BE `wework_auth milestone=` + FE Console `[wework_login]`，串联 state/exchange/handoff/poll 排查卡在「正在同步登录状态」。见 `wework_oauth_login_plan.md` §8.1。
- **集成 · 支付宝按拉数规范全面重设**：`jobs/common` + `api_data.pull_*`；ODS 按 API 命名；新建 ADS `"支付宝订单"` + enrichment `"支付宝订单认领"`。见 `integrations/支付宝/`（`README.md`）。
- **规范 · API 三件套企业级补强**：`api_pull_spec.md`（水位/DLQ/SLI/限流/PII）；`push_data_spec.md` §7；新建 `workbench_api_spec.md`（trace/幂等/版本）。
- **规范 · API 拉数统一约定**：沉淀拉数 `jobs/` 分层与 skip/fail（已被上一子弹吸收增强）。
- **集成 · 支付宝统一收单交易查询落库**：`alipay.trade.query` → `"支付宝"."交易查询"`。见 `integrations/支付宝/api/trade-query.md`（`trade-query.md`）。

### 2026-07-31

- **集成 · 支付宝 ODS/DWD 分层**：`账务明细` 退回纯 ODS；新建 ETL `支付宝订单`（交易号）/ `支付宝退款`（流水号）；拉数后自动 ETL。见 `integrations/支付宝/`（`README.md`）。
- **集成 · 支付宝账务明细扩列 + 归档回填**：（已被上一层分层取代；归档 enrichment 进订单表。）
- **工程 · 第三方集成目录归拢**：平台备忘 / 接口目录 / notebook 统一迁入 `integrations/`（`README.md`）（无根目录兼容层）；拉数仍 `jobs/`、推送仍 `push_data/`。
- **集成 · 支付宝 From 蚂蚁消息回调**：应用网关 `POST /api-data/push_from/alipay/api_alipay_push` → `支付宝_push`；URL 汇总 `integrations/push_urls.md`（`push_urls.md`）；接口目录见 `integrations/支付宝/api/index.md`（`index.md`）。
- **集成 · 支付宝账务明细 OpenAPI 拉数**：`alipay.data.bill.accountlog.query` → `"支付宝"."账务明细"`；目录同上 + `alipay_account_log_sync_plan.md`。
- **工作台 · 订单认领筛选全量自动搜索**：平台/店铺/同事/时间/订单号等条件变更后 debounce 自动刷新；仍可点「搜索」立即查询。见 `unclaimed_order` + UI_DESIGN §5.6.5。
- **工作台 · 默认权限页首访引导扩覆盖**：公域/私域直播填报、订单认领、歧义订单、分销账号均挂 `el-tour`（独立 pageKey，可跳过/帮助重放）；与 Hub 一并覆盖默认权限可达场景；**非默认包（绩效考核）不下挂**。见 `workbench_toc_ux_evolution_plan.md` UX-17。
- **工作台 ToC 体验演进 · P0 第一批**：核心列表页（绩效目标 / 咨询交付 / 订单查询 / 个人中心订单）首载改骨架屏、刷新走局部遮罩；原生 `alert()` 清零，统一 ElMessage/ElMessageBox 反馈；新增通用 `WbEmptyState` / `WbPageHeader` 组件与 `useFirstLoadSkeleton`。方案与验收见 `workbench_toc_ux_evolution_plan.md`（UX-01～04 green）；设计规范见 `UI_DESIGN.md`（§2.2 ToB×ToC 决策、§5.9–5.14 新模式板块）。
- **工作台 ToC 体验演进 · P0 第二批 + P1/P2 全量（plan 已完结）**：空态/页头全站铺开（`el-empty` 清零）；**Ctrl+K 命令面板**（能力地图单源 + 权限过滤 + 拼音检索 + 最近访问）+ 顶栏位置指示 + `?` 快捷键速查；首访 `el-tour` 引导（可跳过/可重放、公告互斥）+ Hub 时段问候/新手清单；KPI 数值滚动 + 字段级 `?` 帮助（8 落点）；**暗色模式**（顶栏 light/dark/system 三态切换、echarts 联动、正文对比度 ≥4.5:1 测试锁定）；轻量筛选即时化（下拉/开关 debounce 自动查询，重查询保留按钮）。UX-01～16 全部 green（FE vitest 684/687，3 例失败为咨询域存量另案）。

### 2026-07-30

- **对公转账退款 · 双档导出**：列表页「导出本页 / 导出全部」；全部走异步 `corporate_receipt.refund_transfer`（权限同对公收款查看）。见 `workbench_async_export_plan.md`。
- **绩效预测 EOM · 全链路优化**：剩余量按 `forecast_date > as_of` 计防双计；run-rate 地板 + 校准只作用剩余防 Outlook 贴 MTD；S1 改 WMAPE 且 collapse 只看冻结时质量位；Commit 窗口 D2–D3 + 新增 `backfill_commit.py` 播种历史展望；看板已结束月分列 S1（预测准度）与 S2（达成缺口）。见 `perf_forecast_eom_accuracy_plan.md`。
- **绩效预测 EOM · P1**：只读 API `outlook_versions` / `eom_accuracy`；看板展示 Commit/Rolling、策略缺口与贴 MTD 质量提示；FVA CLI。
- **绩效预测 EOM · P0**：Official=`Actual_MTD+Remaininĝ`；默认写 `predict.perf_forecast_snapshot`；CLI `diff_forecast_snapshots` / `score_eom_outlook`。

### 2026-07-29

- **工作台 · 咨询预约日对话框场次卡**：展示完整订单号，并补手机号 / 商品名 / 非 1「本场次数」；对话框宽 760。见 `consult_appointment_plan.md` §6.4.1d。
- **工作台 · 咨询导出对齐列表**：已预约导出补「本场次数」与状态中文；主表全量导出退款状态中文；操作记录「有效/无效」；合并历史「迁入流水条数」。见 `consult_delivery_plan.md` EXP-ALIGN。
- **工作台 · 咨询预约日对话框**：安排新咨询改为三步分区（找/选/安排）；2×2 搜单 + 短搜索钮；未选单不展示确认区。见 `consult_appointment_plan.md` §6.4.1d。
- **工作台 · 咨询交付合并审计导出**：操作记录 / 补录滞后 / 次数变更的次数列导出为 Excel numeric（float），半次交付（0.5）与列表 `delivery_records` 对齐。见 `consult_delivery_plan.md` LAG-07。

### 2026-07-28

- **工作台 · 咨询交付补录滞后合计**：`backfill_delta_sum` 不再 `::int` 四舍五入，半次交付（如 0.5）与展开明细对齐。见 `consult_delivery_plan.md` LAG-06。
- **集成 · Flask 推送入口归档**：星橙/小红书 OAuth/小鹅 Token 三入口迁至 `web/归档/flask/`（只读）；`flask/` 仅余 `siweichongsu_web`。平台回调/密钥签收仍待 Ops。见 `flask_push_to_django_migration_plan.md`。

### 2026-07-27

- **工作台 · 歧义历史下单时间清洗**：`业务表.歧义订单_历史.下单时间` 收敛为 `timestamp(0)`（ISO/`YYYYMMDD` 转换，脏值置空）；去掉 `try_timestamp0`；`ORDER_CLAIM` / 对内歧义订单直接读类型列。DDL：`sql/api_data/ambiguous_order_history_timestamp_fix_ddl.sql`。
- **工作台 · 订单认领导入放宽同事**：批量导入仅「订单号」必填；同事与其它明细列一样，有列且有值才更新（空不覆盖）。
- **工作台 · 订单认领列类型收敛**：`业务表.订单认领汇总` 的 `下单时间`/`最近一次更新时间`→`timestamp(0)`，`商品金额`→`numeric(18,2)`，`特殊情况`→`text`；认领 API 去掉 `::varchar`/`::timestamp` 过滤转换。DDL：`sql/api_data/unclaimed_order_column_types_ddl.sql`。
- **工作台 · 订单认领导入预览**：解析后以状态预览表替代「已忽略」提示（将导入 / 不在花名册）。
- **工作台 · 订单认领操作人**：`业务表.订单认领汇总` 新增 `操作人`；bulk/import/admin_clear 写入当前登录用户；列表与导出展示操作人与最近更新时间。DDL：`sql/api_data/unclaimed_order_operator_ddl.sql`。
- **工作台 · 订单认领导入可选列**：批量导入在「订单号」外支持同事/商品名称/用户昵称/买家手机号/直播标题/特殊情况；有列且有值才更新。
- **工作台 · 订单认领去重入口**：移除认领页「歧义订单」遗留页签及 `unclaimed_orders/ambiguous-search/`；歧义流程统一侧栏 `/ambiguous_order`。见 `ambiguous_order_plan.md`。
- **工作台 · 下线游客账号**：库内已无 guest 用户/组；移除写 API `wb_guest` 闸门与登录页/顶栏游客公告；登录/注册/Admin 建用户拒绝历史游客用户名。见 `workbench_rbac.md` §9。
- **工作台 · 个人订单平台/店铺多选**：经营数据「我的订单」筛选支持平台、店铺多选（拼音）；API 逗号分隔精确匹配。见 `me_personal_orders_plan.md` T16/T19。
- **工作台 · 账号安全 P1–P3**：已登录改密锁定/脱敏绑定邮箱；改密后 JWT `pwh` 使全部会话失效；近 5 次密码不可复用；密码强度提示；退出登录独立区块。见 `password_security.py` / `UserPasswordSecurity`。
- **工作台 · 登录/改密主流对齐**：登录「忘记密码」同卡整屏切换；个人中心/顶栏改密默认旧密码，「忘记旧密码？」切邮箱验证；共用密码规则。见 `passwordAuth.ts` / `LoginAccountForm` / `WorkbenchPasswordChangeForm`。
- **工作台 · 个人中心改密**：与登录页一致，支持邮箱验证码重置（仍可选旧密码）；顶栏「修改密码」共用同一表单。见 `WorkbenchPasswordChangeForm.vue`。
- **工作台 · 公告 ToC-A**：顶栏未读角标、全部已读、面板内 Drawer 读正文、相对时间与类型 Tab；`inbox_read_at` + `mark_read`/`mark_all_read`。见 `announcement_enterprise_gap_plan.md` §13.5。
- **工作台 · 公告 ToC 侧规格**：对照主流消息中心，补全差距矩阵 G-TOC-01～24 与 TOC-A/B/C 分层（同 plan §13.5～§13.7）。
- **工作台 · 顶栏公告面板**：右上角「公告」与「下载任务」同簇；点击弹出生效公告摘要（角标红底白字）；修复 inbox 误按 `max_impressions` 过滤导致「已弹过就看不到」。见同 plan §13.4。
- **工作台 · 咨询交付反写预约**：交付登记默认记入预约日历（无同日候选时 `deliver_reverse`）；撤销/以交付为准与预约台账同步；见 `consult_appointment_plan.md` §3.10 D5。
- **运维 · 5～7 月交付回写预约**：已将 2026-05～07 未关联活跃交付 **2023** 条反写为已完成预约（`scripts/db/backfill_appointments_from_delivery.py`）。

### 2026-07-24

- **工作台 · 直播订单快捷筛选**：明细默认「本月至今」，快捷按钮顺序为本月 / 上月 / 近 7 天 / 近 30 天；见 `me_live_orders_plan.md` T12。
- **工作台 · 表格 CSS 竞态修复**：数据填报（直播填报/认领/歧义）样式进主包并加页面根前缀；对公收款命名空间化易串页的 `.section-card`/表格类；直播填报人员多选共用拼音缓存。
- **工作台 · 直播填报人员多选**：公域/私域主播、助播等角色改为多选（拼音/首字母），落库仍 `/` 拼接；见 `stream_data_reporting_plan.md` §2.4。
- **工作台 · 直播订单管理员结算**：`wb_admin` 可切「全部明细」（`scope=all`）并「导出全部」异步下载；与「切换查看对象」并存。见 `me_live_orders_plan.md` T21/T22。
- **工作台 · 个人中心图表下钻引导**：经营数据与直播订单共用「可下钻」提示条与反馈文案，交互风格统一。见 `mePageCopy.analyticsDrill`。
- **工作台 · 直播订单刷新日历**：默认结算上月（+本月至今）；场次池随订单窗推导为 N-3～order_end，不再挂到今天。见 `me_live_orders_plan.md` T2/T14/T16。
- **工作台 · 直播订单回放窗**：私域「直播（回放）」仅挂订单月起往前 **N-3** 自然月内开播场次；更早不计回放出单。见 `me_live_orders_plan.md` T16。
- **工作台 · 下线演示页**：侧栏与路由不再挂「UI 风格选型」「项目进度演示」；源码归档至 `web/nuxt-siwei-workbench/archive/demo/`（不再注册 URL）。
- **工作台 · 直播订单缺失引导**：空态与明细区引导用户前往「直播填报」补录场次班底（`/stream_data`）。见 `me_live_orders_plan.md` T18。
- **工作台 · 直播订单回填起点**：自 `web.直播数据总表` 最早开播月（现网 2024-10）分段刷入 `日报.直播订单汇总`；场次池随订单窗前推 N-3 月。见 `me_live_orders_plan.md` T16/T17。
- **工作台 · 个人中心 TOC BI**：经营数据与直播订单支持图表下钻筛选、「同步时间到明细」、KPI 环比、本页导出；直播补状态/主播/场次维度与 analytics 缓存；概览窗/明细窗双标签。见 `me_live_orders_plan.md` / `me_personal_orders_plan.md`。
- **工作台 · 直播订单回填**：`日报.直播订单汇总` 已分段刷近 12 月（约 12.7 万行）；场次池录播抽样通过；`/me` 角色子 tab 查询硬化。见 `me_live_orders_plan.md`。
- **工作台 · 个人中心 · 直播订单 UI**：对齐 Soft UI / 表格 L1（`WbPagerBar`、`table-wrap`、KPI 与分销一致、角色 segment、空态）；TOC slider 仅 `transform` 动效。见 `me_live_orders_plan.md`。
- **工作台 · 个人中心 · 直播订单**：旁路表 `日报.直播订单汇总` + 每日 09:00 刷新；`/me` 新增「直播订单」tab（按角色粗略匹配），替代月汇总拆表与企微分发。见 `me_live_orders_plan.md`。
- **工作台 · 咨询交付 · MERG-DEL 正式启用**：UAT 通过后 `web_consult.consult_case_merge_history.migrated_delivery_ids` 已加列；合并自动迁子单交付流水、解绑按 id 写回。见 `consult_delivery_plan.md` §3.10.1a。
- **工作台 · 咨询交付 · MERG-OPS / MERG-DEL-07**：合并清空子单运营列并迁入主单（退款留子单）；`delivery_migrate_enabled` 对齐预览与确认文案。见同 plan §3.10 / §8.9.1。

### 2026-07-22

- **工作台 · 咨询交付**：禁止「咨询师咨询次数」写 `Name+0`/`+0`；有交付后名单不含未交付占位；提供清理脚本 `cleanup_consultant_count_plus_zero.py`。见 `consult_delivery_plan.md`。
- **工作台 · 咨询交付**：多咨询师分配列更名为「咨询师分配咨询总次数」，并新增「当前订单咨询师单价」（金额÷分配次数，保存/重算默认补全）。见 `consult_delivery_plan.md` §3.12。
- **工作台 · 咨询交付**：主表新增「咨询师保护期内」（ETL：下单日是否落在心驿站合作开始后 180 天）；支持筛选与排序。见 `consult_delivery_plan.md` §5.1。
- **工作台 · 交付咨询师设定**：心驿站 / 销售助理映射 / 花名册三表支持「导出本页 / 导出全部」（CSV、Excel）；按当前搜索与筛选拉数。见 `consult_delivery_plan.md` §3.6。

### 2026-07-22

- **工作台 · 公告图片粘贴**：管理端正文支持 Ctrl+V / 拖拽 / 选文件上传（`POST …/upload_image/`，同源 media 读取）。
- **工作台 · 公告触达 500 修复**：`USE_TZ=False` 下 `impressions` 调用 `timezone.localdate()` 抛错；改为 `service_local_date()`（兼容朴素/感知时间）。

### 2026-07-21

- **工作台 · 公告主流补齐**：正文 TipTap 富文本（色/图/链）+ bleach 受限 `color`；用户侧「公告中心」`/announcements` + 顶栏铃铛（`GET …/inbox/`）。见 `announcement_enterprise_gap_plan.md` 主流 ToB 补齐。
- **工作台 · 公告预览同构**：新建/编辑右侧预览与消费端共用 `workbench-announcement-shell.css`，五种 placement（含 CTA/倒计时/ack）与线上一致。
- **工作台 · 系统公告适配**：修复定向投放因 nav 解析回落 `home/home` 导致的失效；`announcementNav` / §10 与现网菜单对齐；Host 包 `ClientOnly`。见 `announcement_modal_plan.md` §9.2。
- **规则整理**：同类型薄 `.mdc` 并入域主文件（门面→`agents-doc-router`；文案→`nuxt-code-style`；FE 路径→`frontend-apps`；运维+Celery→`django-ops`）。
- **工作台 · 用户文案**：去掉面向 AI/工程的界面说明（如助理解析顺序、GENERATED/ADS 等）；禁令见 `nuxt-code-style.mdc` §用户可见文案。
- **工作台 · el-table 固定列串色**：行/列着色改为不透明底 + `--wb-table-fixed-cell-bg`；含固定列时外层不再 `overflow-x:auto`（交给表内滚动）。影响咨询设定/交付、预约、绩效、对公退款、花名册、导出任务等。
- **咨询设定 · 合作期**：心驿站咨询师 / 咨询师花名册新增「合作开始时间」「合作结束时间」「合作状态」（默认 `1999-01-01` / `2099-01-01` / `合作中`）；设定页可编辑；迁移 `0054`。
- **日报金额列 numeric**：`全域订单`/`月初留档`/`退款订单总表`/`撤销退款总表`/`王培林与张敬轩ip` 的退款/应付金额 → `numeric(18,2)`；依赖视图自动重建；个人中心订单列表直读 numeric。
- **咨询交付 · 用户类型**：新增「咨询评估」；原「引流品首次转化」更名为「咨询评估转化」（存量行需跑 DB 更名 SQL）。
- **工作台 · 个人中心经营数据（IA-B+CH-A）**：`/me` 合并为「经营数据」综合体（KPI + ECharts + 分销账号 + 订单）；图表可筛时间窗，并按「订单量/金额」切换分类度量。
- **工作台 · 个人订单可视化**：`/me`「我的订单」TOC 概览新增本月成单趋势、平台/状态分布、同事|IP 归属构成（Soft UI）。
- **工作台 · 咨询交付**：`{统计日起}前交付次数` 改为订单级合计纯数字（不再按咨询师 `A+N` 拆分）；区间交付列仍按咨询师拆分。
- **工作台 · 个人订单**：归属匹配改为 `同事 = 姓名 OR ip = 姓名`；管理员代查支持手输姓名、订单表展示 `ip`（老师做 IP 可查）。
- **商城体验补齐**：顶栏/页脚售后入口；订单列表「申请售后」；个人中心领券/收藏/足迹；售后选已付款订单；工作台侧栏「商城运营」；SF-T01/T04 规则单测。
- **商城运营后台 P0–P2**：`/store/admin/*`（售后状态机、订单发货、看板、库存/运费/券、导出与批量发货）+ `/api-data/store/admin/`；工作台 JWT + `store_ops_*` RBAC。
- **商城全站 SSR**：去掉交易页长期 `ssr: false`；买家端与运营台统一 Nuxt SSR（`IMPROVEMENTS` §10.6）。
- **商城动效系统**：`UI_DESIGN.md` §3.3.1 定稿主流 C 端转化向动效；全局 `motion.css` + duration/ease token；顶栏滚动阴影、角标脉冲、CTA 按压、交易页入场统一。
- **商城 P1.5 独立能力**：规格落地（多地址、软库存、运费、售后工单、访客车、满减券、订单邮件、收藏足迹）；真实支付/短信/微信登录/快递轨迹仍排除。见 `IMPROVEMENTS.md` §7.1 与 `.cursor/project/storefront/storefront_solo_capabilities_plan.md`。
- **商城商品主数据切源**：storefront 商品读写统一走破壳有范DB `小鹅通.xiaoe_product_*`（不再读 `破壳有范shop.product_info` 副本）；用户/购物车/订单仍在 `shop` 库。

### 2026-07-20

- **咨询交付 · 补录滞后筛选**：新增交付日期、咨询师筛选；咨询师/操作人统一为 `el-select`（选项 `delivery_audit_options`）；合并历史/操作记录/次数变更的操作人同步改为下拉。
- **咨询交付 · 补录滞后汇总**：交付合并 & 历史新增「补录滞后」Tab；按 `created_time − consult_deliver_date ≥ 60 天`（可调）从 `consult_delivery_counts` 按订单汇总（含 **案例ID**）；导出按各表当前筛选时间（四表时间口径不同，不再共用单一日期）。
- **咨询交付主表**：废弃并 DROP `consult_order.是否对接`；新增 `{统计日起}前交付次数` 列；已交付渐变改为 `(已交付+退款)/咨询次数`；筛选「累计已交付」更名为 **已交付次数**，并新增 **咨询次数 / 剩余交付次数** 数值比较筛选。

### 2026-07-16

- **全课程简称平台/店铺兜底修复**：`日报.全域订单状态更新` 按 `btrim(商品名称)` 回填空平台/店铺（不再因尾空格双行漏补）；已跑历史回填合并空格重复行。
- **公开架构页能力说明刷新**：`workbenchCapabilityMap.json` v2（咨询交付、数据接入、个人中心订单/导出/企微、合作商开放接口等）；`regen_architecture_from_map.py` 同步 public/full HTML。
- **P0–P1 Ops 闭合**：架构页匿名 `architecture/full` → **403**；异步导出 `EXPORT_STORAGE_ROOT`；Nuxt **G4**（dist 归档 + 关灰度 Cookie）；罗盘 agent zip + nginx WS；星橙 DDL；全域订单 P1 列裁剪（timing **−24.6%**，G-05 ✅）。
- **操作日志 payload jsonb**：`web.web_operation_log.request_payload` 由 TEXT 改为 JSONB（存量安全迁移）；管理端 API 仍返回截断 JSON 字符串。
- **冗余/错误清理**：修 `hasDefaultReportDataPackage` 未导入、歧义订单 `permSet` 未定义；删除百度同步「冲突文件」；去掉分页常量重复 re-export；相关 vitest 已绿。
- **CI ruff 门禁修复**：修 ECS 脚本 `try` 缩进 / `legacy_ssh_tuple` 导入与 `pwd` 笔误；整理 import 与未使用变量；本地 `python -m ruff check .` 已通过。

### 2026-07-15

- **仓库门面规则**：根 `README.md`「更新动态」须与业务同批 commit/push（现并入 `agents-doc-router.mdc` §B）。
- **工程规范落地**：工作台交付 / 预约 FE 拆分（`ConsultOrderDrawers`、预约 Filter·Pending·Scheduled·Dialog）；`ENGINEERING_GUIDE` 增补 §5 契约硬门禁；根目录 CI（`.github/workflows/ci.yml`）。
- **咨询预约契约**：`api/consult/types.ts` 补齐预约请求/响应命名类型，与 `consult_appointment_plan` §5 对齐。
- **个人中心订单**、**分销账号**、**异步导出**等近期能力见下方 commit 系列（`个人中心订单` / `分销账号更新` / `异步导出与任务中心` / `咨询1.0～1.02`）。
