# TheVerificationCode
VUE组件，帆布图片验证码
通过VUE单文件组件导入至项目中，即可使用。

//默认注册码
identifyCode: { 
  type: String,
  default: ''
},

// 字体最小值
fontSizeMin: { 
  type: Number,
  default: 15
},

// 字体最大值
fontSizeMax: {
  type: Number,
  default: 25
},

// 验证码图片背景色最小值
backgroundColorMin: { 
  type: Number,
  default: 200
},

// 验证码图片背景色最大值
backgroundColorMax: {  
  type: Number,
  default: 220
},

// 背景干扰点最小值
dotColorMin: { 
  type: Number,
  default: 35
},

// 背景干扰点最大值
dotColorMax: { 
  type: Number,
  default: 70
},

//容器宽度
contentWidth: { 
  type: Number,
  default: 87
},

//容器高度
contentHeight: { 
  type: Number,
  default: 28
},
