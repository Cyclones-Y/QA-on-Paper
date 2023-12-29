# QA-on-Paper

该项目为demo项目，仅为提供思路，项目均使用百度API，运行代码需要先到[百度智能云](https://console.bce.baidu.com/tools/?_=1703819521077#/api?product=AI&project=%E6%96%87%E5%AD%97%E8%AF%86%E5%88%AB&parent=%E9%89%B4%E6%9D%83%E8%AE%A4%E8%AF%81%E6%9C%BA%E5%88%B6&api=oauth%2F2.0%2Ftoken&method=post)领取权限，开通API key

问答部分使用的是文心一言4.0API，同样也需要先到[千帆大模型平台](https://console.bce.baidu.com/tools/?_=1703819521077#/api?product=AI&project=%E5%8D%83%E5%B8%86%E5%A4%A7%E6%A8%A1%E5%9E%8B%E5%B9%B3%E5%8F%B0&parent=%E9%89%B4%E6%9D%83%E8%AE%A4%E8%AF%81%E6%9C%BA%E5%88%B6&api=oauth%2F2.0%2Ftoken&method=post)下开通API

## OCR扫描纸质文档，对内容进行问答

- 试卷的题目解答
- 合同内容的总结
- 开会笔记总结
- 纸质内容转word、excel
- .....

## introduce

该项目启动Gradio网页，在手机端打开公网链接进行测试

- 拍摄/上传带有文字的照片

- 选取所需要的文字内容，便能进行总结或答疑
- 在网页端实现流式输出

## Run
填入相对应的KEY_API

