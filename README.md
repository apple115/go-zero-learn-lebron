项目结构
./
├── apps
│   ├── app
│   │   └── api
│   ├── cart 购物车的增删改查
│   │   ├── admin
│   │   ├── rmq
│   │   └── rpc
│   ├── order 生成订单，订单管理
│   │   ├── admin
│   │   ├── rmq
│   │   └── rpc
│   ├── pay 通过调用第三方支付实现支付功能
│   │   ├── admin
│   │   ├── rmq
│   │   └── rpc
│   ├── product 商品的添加、信息查询、库存管理等功能
│   │   ├── admin
│   │   ├── rmq
│   │   └── rpc
│   ├── recommend 首页商品推荐
│   │   └── rpc
│   ├── reply 商品的评论功能、评论的回复功能
│   │   ├── admin
│   │   ├── rmq
│   │   └── rpc
│   └── user 用户信息、等级、封禁、地址管理
│       ├── admin
│       ├── rmq
│       └── rpc
├── go.mod
├── pkg
└── README.md

第一天 构建完这个这个项目结构
