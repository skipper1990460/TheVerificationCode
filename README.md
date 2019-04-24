# TheVerificationCode
VUE组件，帆布图片验证码
通过VUE单文件组件导入至项目中，即可使用。
props: {
      identifyCode: { //默认注册码
        type: String,
        default: ''
      },
      fontSizeMin: { // 字体最小值
        type: Number,
        default: 15
      },
      fontSizeMax: { // 字体最大值
        type: Number,
        default: 25
      },
      backgroundColorMin: { // 验证码图片背景色最小值
        type: Number,
        default: 200
      },
      backgroundColorMax: {  // 验证码图片背景色最大值
        type: Number,
        default: 220
      },
      dotColorMin: { // 背景干扰点最小值
        type: Number,
        default: 35
      },
      dotColorMax: { // 背景干扰点最大值
        type: Number,
        default: 70
      },
      contentWidth: { //容器宽度
        type: Number,
        default: 87
      },
      contentHeight: { //容器高度
        type: Number,
        default: 28
      },
    },
