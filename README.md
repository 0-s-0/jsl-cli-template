## 主要文件夹解释
my-vue-project/
├── node_modules/              # 项目依赖包
├── public/                    # 静态文件
│   ├── index.html             # HTML入口文件
│   └── favicon.ico            # 网站图标
├── src/                       # 源代码目录
│   ├── assets/                # 静态资源文件（图片、字体、样式等）
│   │   ├── images/            # 存放图片资源
│   │   └── styles/            # 存放全局样式（例如 SASS/LESS、CSS）
│   ├── components/            # Vue组件文件夹
│   │   ├── Header.vue         # 头部组件
│   │   └── Footer.vue         # 页脚组件
│   ├── pages/                 # 页面级组件
│   │   ├── Home.vue           # 首页组件
│   │   └── About.vue          # 关于页组件
│   ├── router/                # 路由配置
│   │   └── index.js           # Vue Router配置
│   ├── store/                 # Vuex 状态管理
│   │   └── index.js           # Vuex配置
│   ├── services/              # API 请求
│   │   └── api.js             # API请求封装
│   ├── utils/                 # 工具函数
│   │   └── format.js          # 格式化工具函数
│   ├── App.vue                # 根组件
│   └── main.js                # 项目入口文件
├── tests/                     # 测试文件夹
│   ├── unit/                  # 单元测试
│   └── e2e/                   # 端到端测试
├── .gitignore                 # Git 忽略文件
├── package.json               # 项目描述与依赖
└── README.md                  # 项目说明文件
