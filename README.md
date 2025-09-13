# 廿六三拼方案

## 简介

本方案是26键三拼方案，26键内实现三码输入一个带调音节，无重复音节，主要适用于实体键盘打字，编码方式是“声母+韵母+声调”，第三码是声调码，使用oeway五键输入五声，可省略声调成为普通双拼方案。

## 安装

本方案是 [李氏三拼](https://github.com/arsenali/rime-triple-pinyin-lssp) 系列方案之一，依赖于李氏三拼基础方案，安装本方案前请先安装 ℞ `rime-triple-pinyin-lssp`。

各平台安装方法同李氏三拼，请参考：

[安卓版和windows版](https://github.com/arsenali/rime-triple-pinyin-lssp/wiki/安卓版和windows版)

[苹果版](https://github.com/arsenali/rime-triple-pinyin-lssp/wiki/苹果版)

<br>

## 键位图

<div align="normal">
  <img src="https://github.com/user-attachments/assets/560ff954-61cd-4db9-8b88-db44adb92ce7" 
       alt="键盘布局" 
       width="100%"
       style="border: 1px solid #eee; 
              border-radius: 12px;
              box-shadow: 0 4px 12px rgba(0,0,0,0.15);
              margin: 20px 0;">
 <i> <p style="color: #666; font-style: italic; margin-top: 12px;">
    △键盘布局
  </p></i>
</div>

_截图使用的是“光明·黑暗”主題，“明图”配色_

本方案是26键方案，因此可使用任意26键主题皮肤，上图是适配廿六三拼的主题，其他主题亦可使用。

<br>

## 编码规则

本方案在自然码双拼基础上作适当调整，声母使用21键，韵母使用26键，声调使用5键，声母、声调编码区隔离，故省略声调不会造成重复音节。

调整基于注音逻辑，和原版自然码的区别在于声母yw和零声母：

- **声母y**

声母y开头的音节分为两类：

 1: y和以aoe开头的韵母（除了ong）相拼时以j输入，包括：ya, yo, ye, yai, yao, yan, yang, you共8个音节；
 
 2: y和以i,u开头的韵母以及韵母ong相拼时以f输入，包括：yi, yin, ying, yu, yuan, yue, yun, yong共8个音节。

- **声母w**

声母w以q输入。

- **零声母**

零声母er以f引导，其他零声母以x引导。

<br>

## 五类汉字编码

本方案和李氏三拼方案一样可输入原码、全拼、拼音、注音、国罗等五类汉字编码，具体请参考：

[五类汉字编码](https://github.com/arsenali/rime-triple-pinyin-lssp/wiki#五类汉字编码)


## 注音键盘

为注音用户定制了注音键盘：

<div align="normal">
  <img src="https://github.com/user-attachments/assets/470a43f6-e9fe-4999-8ce8-9f1e4b1ca7a8" 
       alt="键盘布局" 
       width="100%"
       style="border: 1px solid #eee; 
              border-radius: 12px;
              box-shadow: 0 4px 12px rgba(0,0,0,0.15);
              margin: 20px 0;">
 <i> <p style="color: #666; font-style: italic; margin-top: 12px;">
    △注音键盘布局
  </p></i>
</div>

<br>

---

音节合并参考了注音逻辑，声调编码参考了许氏注音，但声母、声调编码区隔离，故省略声调不会像许氏注音一样造成重复音节。声调码相当于直接辅助码。

另外，可连续输入笔画码筛选去重，用大写的“HSPNZ”输入“横、竖、撇、捺、折”，类似于搜狗拼音，笔画码相当于间接辅助码。

主题文件中自带简单教程，可点击“帮助”查看。

点击“反查”可使用拼音或笔画进行编码反查。

默认只载入地球拼音词库，加载“八股文”语言模型，如需使用万象等词库需自行下载并在词库列表文件terra_pinyin.extended.dict.yaml中启用，使用其他语言模型请修改grammar.custom.yaml文件。

下载地址：http://www.lssp.ysepan.com/

QQ群：[150478288](https://jq.qq.com/?_wv=1027&k=5wf1uTQ)


<br>

## 收藏和克隆

### &#8627; Stargazers
[![Stargazers repo roster for @arsenali/rime-triple-pinyin-lishi26](https://reporoster.com/stars/arsenali/rime-triple-pinyin-lishi26)](https://github.com/arsenali/rime-triple-pinyin-lishi26/stargazers)

### &#8627; Forkers
[![Forkers repo roster for @arsenali/rime-triple-pinyin-lishi26](https://reporoster.com/forks/arsenali/rime-triple-pinyin-lishi26)](https://github.com/arsenali/rime-triple-pinyin-lishi26/network/members)

