src/
├─ router/          # 路由配置
│  └─ index.js      # 路由表
├─ layouts/         # 全局布局组件
│  └─ DashboardLayout.vue  # 仪表盘布局（含侧边栏、顶部导航）
├─ pages/           # 路由直接映射的页面
│  └─ dashboard/    # 仪表盘主目录
│     ├─ Dashboard.vue  # 仪表盘主页面（包含子视图）
│     ├─ views/       # 仪表盘内部子视图
│     │  ├─ Overview.vue  # 概览卡片
│     │  ├─ SalesChart.vue  # 销售图表
│     │  └─ UserTable.vue  # 用户表格
│     └─ components/  # 仪表盘专用组件
│        ├─ StatCard.vue  # 统计卡片
│        └─ ProgressBar.vue  # 进度条
└─ components/      # 全局通用组件（可被多个页面复用）
├─ ChartWidget.vue  # 通用图表组件
└─ DataTable.vue  # 通用表格组件