# Google Play上架基本信息配置篇

## 前期准备
- 开发者账号注册缴费25美元并且进行认证,开通谷歌支付的话须填写收款信息。
- AAB文件格式的安装包（注：安装包大于150M，要采用谷歌的分包机制。参考：<https://developer.android.google.cn/guide/playcore/asset-delivery?hl=zh_cn>）
- 签名秘钥文件
- 图片素材
  + PNG 或 JPEG 格式，大小不得超过 1 MB，尺寸为 512 x 512 像素的图标
  + PNG 或 JPEG 格式，大小不得超过 1 MB，尺寸为 1024 x 500 像素的置顶大图
  + 2 到 8 张PNG 或 JPEG 格式，每张的大小不得超过 8 MB，宽高比为 16:9 或 9:16，各条边的尺寸介于 320 像素和 3840 像素之间
    * 手机屏幕截图、7 英寸平板电脑屏幕截图、10 英寸平板电脑屏幕截图都需要按照上述标准
- 上架市场需要的app资料（例如：APP名称、简介、分类、联系方式、隐私协议网页、语言翻译、分级等等）
## 提审
### 一、创建app
#### 1. 使用已经注册完成的 Google play 开发者账号登录[Google Play Console][1]，应用名称、默认语言、应用或游戏、免费或付费根据证实情况填写。
[1]:<https://play.google.com/console/developers> 
![img.png](image/basic_info/img.png)
### 二、填写 app 信息
   ![img_1.png](image/basic_info/img_1.png)
   **注：设置应用栏：应用访问权限、广告、 内容分级、 目标受众群体、 新闻应用、 新冠肺炎 (COVID-19) 接触者追踪应用和感染状况应用、 数据安全、 隐私权政策 全部必填项**
#### 1. 应用访问权限（根据实际情况填写即可）
---
![img_2.png](image/basic_info/img_2.png)
#### 2. 广告（根据实际情况填写即可）
---
![img_3.png](image/basic_info/img_3.png)
#### 3. 内容分级（根据实际情况填写即可）
---
![img_4.png](image/basic_info/img_4.png)
#### 4. 目标受众群体（根据实际情况填写即可）
---
![img_5.png](image/basic_info/img_5.png)
#### 5. 新闻应用（根据实际情况填写即可）                                              
---
![img_6.png](image/basic_info/img_6.png)
#### 6. 新冠肺炎 (COVID-19) 接触者追踪应用和感染状况应用（根据实际情况填写即可）
---
![img_7.png](image/basic_info/img_7.png)
#### 7. 数据安全（根据实际情况填写即可，需要填写隐私协议地址）
---
![img_8.png](image/basic_info/img_8.png)
#### 8. 应用类别（根据实际情况填写即可）
---
![img_9.png](image/basic_info/img_9.png)
#### 9.主要商品详情（须注意：如果需要支持多语言的话、该处可以选择上传多个语言对应的信息）
---
![img_10.png](image/basic_info/img_10.png)