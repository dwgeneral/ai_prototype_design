你是资深的产品原型设计专家，设计一款小程序，
目标用户：
- 主要用户：25-45岁热爱旅游热爱海边的年轻人
 产品目标：
-支持用户选择喜爱的民宿进行民宿预定服务
-提供高端大气简洁的UI界面，让用户开心愉快的进行操作
我目前想到的核心功能如下：
1、用户可以选择订房日期，系统自动检索出所有房子此时间段的有房无房情况，以及价格
2、用户点击某个房子进入详情页，会轮播展示房子照片，下方列出房子具体信息，显示价格及预订按钮
3、点击预订按钮，进入订单确认页面，输入联系人信息，提交订单
4、完成支付后，可跳转到订单列表页面，查看具体订单信息
现在需要你帮我输出高保真的原型图，请通过以下方式帮我完成所有界面的原型设计，并确保这些原型界面可以直接用于开发：
1、用户体验分析：先分析这个小程序的主要功能和用户需求，确定核心交互逻辑。
2、产品界面规划：作为产品经理，定义关键界面，确保信息架构合理。
3、高保真 UI 设计：作为 UI 设计师，设计贴近真实小程序设计规范的界面，使用现代化的 UI 元素，使其具有良好的视觉体验。
4、HTML 原型实现：使用 HTML + Tailwind CSS（或 Bootstrap）生成所有原型界面，并使用 FontAwesome（或其他开源 UI 组件）让界面更加精美、接近真实的 小程序 设计。拆分代码文件，保持结构清晰：
5、每个界面应作为独立的 HTML 文件存放，例如 home.html、profile.html、settings.html 等。
- index.html 作为主入口，不直接写入所有界面的 HTML 代码，而是使用 iframe 的方式嵌入这些 HTML 片段，并将所有页面直接平铺展示在 index 页面中，而不是跳转链接。
- 真实感增强：  - 界面尺寸应模拟 iPhone 15 Pro，并让界面圆角化，使其更像真实的手机界面。 
- 使用真实的 UI 图片，而非占位符图片（可从 Unsplash、Pexels、Apple 官方 UI 资源中选择）。 
- 添加顶部状态栏（模拟 iOS 状态栏），并包含 App 导航栏（类似 iOS 底部 Tab Bar）。
  请按照以上要求生成完整的 HTML 代码，并确保其可用于实际开发。