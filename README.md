<p align="right">
   <strong>中文</strong> | <a href="./README.en.md">English</a>
</p>

<p align="center">
   <picture>
   <img style="width: 80%" src="https://pic1.imgdb.cn/item/6846e33158cb8da5c83eb1eb.png" alt="image__3_-removebg-preview.png"> 
    </picture>
</p>

<div align="center">

_本项目是基于[one-hub](https://github.com/MartialBE/one-api)二次开发而来的_

<a href="https://t.me/+LGKwlC_xa-E5ZDk9">
  <img src="https://img.shields.io/badge/Telegram-AI Wave交流群-0088cc?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram 交流群" />
</a>

<sup><i>AI Wave 社群</i></sup> · <sup><i>(群内提供公益API、AI机器人)</i></sup>

### [📚 原项目文档](https://one-hub-doc.vercel.app/)

</div>


## 目前与原版(最新镜像)的区别

- 支持 /gemini 原生生图请求的额外参数透传
- 支持 /gemini 原生对话请求的思考参数
- 支持 gemini-2.0-flash-preview-image-generation 文生图/图生图，并兼容 OpenAI 对话接口
- 支持批量删除渠道
- 支持 VertexAI 渠道下可配置多个 Region , 每次请求随机选取 Region
- 新增分析功能中的 RPM / TPM / CPM 展示
- 新增分析功能-充值统计中的时间周期条件
- 新增批量添加渠道的用户分组功能
- 新增邀请充值返利功能（可选类型: 固定/百分比）
- 新增空回复是否计费配置 （默认:计费）
- 修复若干用户额度缓存与DB数据不一致的导致计费异常的 bug
- 修复邀请记录字段缺失的 bug
- 修复系统初始化http环境下登录异常的 bug
- 删除日志功能中无意义的原始价格相关样式
- ...

## 部署

> 按照原版部署教程将镜像替换为 `deanxv/done-hub` 即可。

> 数据库兼容，原版可直接拉取此镜像迁移。

## 感谢

- 本程序使用了以下开源项目
    - [one-hub](https://github.com/MartialBE/one-api)为本项目的基础
  
感谢以上项目的作者和贡献者
