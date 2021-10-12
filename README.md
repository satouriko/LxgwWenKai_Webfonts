# LXGW WenKai / 霞鹜文楷 Web 字体

[![开源授权](https://img.shields.io/github/license/lxgw/LxgwWenKai)](https://github.com/lxgw/LxgwWenKai)
[![最新版](https://img.shields.io/github/release/satouriko/LxgwWenKai_Webfonts)](https://github.com/satouriko/LxgwWenKai_Webfonts/releases)

本仓库是 [霞鹜文楷](https://github.com/lxgw/LxgwWenKai/) 的 Web 字体，
使用与 [Google Fonts](https://fonts.google.com/) 相同的 [技术](https://github.com/fontsource/fontsource)
对中文字体进行分包和压缩，以便于用于网页端分发。

## 使用说明

**1. 引入 CSS 文件。** 可以按需只引入需要的。

```html
<!-- 霞鹜文楷 Regular -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/satouriko/LxgwWenKai_Webfonts@v1.101/dist/LXGWWenKai-Regular.css" />
<!-- 霞鹜文楷 Lite -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/satouriko/LxgwWenKai_Webfonts@v1.101/dist/LXGWWenKai-Light.css" />
<!-- 霞鹜文楷 Bold -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/satouriko/LxgwWenKai_Webfonts@v1.101/dist/LXGWWenKai-Bold.css" />
<!-- 霞鹜文楷 Mono Regular -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/satouriko/LxgwWenKai_Webfonts@v1.101/dist/LXGWWenKaiMono-Regular.css" />
<!-- 霞鹜文楷 Mono Lite -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/satouriko/LxgwWenKai_Webfonts@v1.101/dist/LXGWWenKaiMono-Light.css" />
<!-- 霞鹜文楷 Mono Bold -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/satouriko/LxgwWenKai_Webfonts@v1.101/dist/LXGWWenKaiMono-Bold.css" />
```

**2. 应用字体样式。** 浏览器会根据所显示文字、粗细动态加载资源。

```css
/* 霞鹜文楷 */
body {
  font-family: LXGWWenKai sans-serif;
}

/* 霞鹜文楷 Mono */
pre, code {
  font-family: LXGWWenKaiMono monospace;
}
```

## 字体预览

![](https://raw.githubusercontent.com/lxgw/LxgwWenKai/main/image/wenkai-1.png)

![](https://raw.githubusercontent.com/lxgw/LxgwWenKai/main/image/wenkai-2.png)

![](https://raw.githubusercontent.com/lxgw/LxgwWenKai/main/image/wenkai-3.png)

![](https://raw.githubusercontent.com/lxgw/LxgwWenKai/main/image/wenkai-7.png)

![](https://raw.githubusercontent.com/lxgw/LxgwWenKai/main/image/wenkai-4.png)

![](https://raw.githubusercontent.com/lxgw/LxgwWenKai/main/image/wenkai-8.png)

![](https://raw.githubusercontent.com/lxgw/LxgwWenKai/main/image/wenkai-5.png)

![](https://raw.githubusercontent.com/lxgw/LxgwWenKai/main/image/wenkai-6.png)

## 补字计划与更新记录

[查看更新记录。](https://github.com/lxgw/LxgwWenKai/blob/main/History.md)

历史版本的 Release，请在 [Release](https://github.com/lxgw/LxgwWenKai/releases) 页面查看。

### 简体部分

- [x] 补完原字库所含繁体字对应的简化字；
- [x] 补完简体中文 3603 常用汉字 <sup>①</sup>;
- [x] 补完「信息交换用汉字编码字符集（GB 2312-80）」 6763 个汉字；
- [x] 补完「通用规范汉字表」8105 个汉字；
- [ ] 修改及优化字形 *（范围为 GB 2312 及通用规范汉字表）*。目前修改字形的任务已基本完成，但仍有一些字形待优化。

**<sup>①</sup>** 包括「现代汉语常用字表」（老 3500 字）及「义务教育语文课程常用字表」（新 3500 字，《通用规范汉字表》一级字表），新老 3500 加一起共 3603 字。

### 繁体部分 

- [x] 补完繁体中文 4808 常用汉字 *（台湾地区「常用国字标准字体表」）* ；
- [x] 补完「GB/T 12345-90」6866 个汉字；
- [x] 补完 BIG5 一级（常用）汉字 5401 个；
- [x] 补完「通用规范汉字表」内汉字对应的繁体字或港台异体字；
- 补完常用粤语、闽南语、客家语用字。*（基于 [「常用香港外字表」](https://github.com/ichitenfont/suppchara)）*
  - [x] 常用香港外字表 A-C 级
  - [x] 常用香港外字表 1-2 级
  - [x] 常用香港外字表 3 级
  - [x] 台湾闽客汉字（外字表ㄅ级）

### 其他
- [ ] 补全常用谚文（韩文、朝鲜文）音节 2350 个。

## 下载字体

1. 进入 [Release](https://github.com/lxgw/LxgwWenKai/releases) 界面下载对应版本的 TTF 格式文件。以后 TTF 文件仅在 Release 页面更新。
3. 进入 [猫啃网](https://www.maoken.com/freefonts/9704.html) 进行下载。GitHub 项目更新后，会联系猫啃网站长进行同步更新。 **注意：** 其它收录免费商用字体的网站上可能也收录了本字体，但可能不是最新版。
3. 本仓库 FCP 文件夹内为增补字的 Font Creator 工程文件，包含 **部分** 笔画分离的字形，可用 Font Creator 打开查看。

## 注意事项

1. 截至 [1.100 版](https://github.com/lxgw/LxgwWenKai/releases/tag/v1.100)，本字体含有全部 CJK 基本区汉字，以及少量扩展 A~G 区汉字。 **如有补字需求，请在 [Issue #33](https://github.com/lxgw/LxgwWenKai/issues/33) 提出，不要另开 Issue。** 
2. 本人并不是专业的设计师，并未考虑设计美感，所以看起来可能略丑，补进去的字与原版可能略有违和感；此外由于时间仓促，并没有多余的时间细修，部分字的部件拼接会很生硬。**如有字形优化建议，请在 [Issue #14](https://github.com/lxgw/LxgwWenKai/issues/14) 提出，不要另开 Issue。**  
*（以上两个 issue 均已加上 long term 标签，且均已在 Issues 页面置顶。）*
3. 另，本字体也有供繁体中文用户和旧字形爱好者使用的 [繁体中文版](https://github.com/lxgw/LxgwWenkaiTC)，采用旧字形写法，目前仍处于测试阶段。
4. **由于原版「霞鹜文楷」Regular 字重在 PC 和 Android 屏幕上显示较细，而 Bold 字重需要在粗体模式下才能调用，特制作以 Bold 字重为基础的 [霞鹜文楷屏幕阅读版](https://github.com/lxgw/LxgwWenKai-Screen)，加粗后的「霞鹜文楷」与 Windows 默认英文字体 Segoe UI Regular 粗细相当，PC 和 Android 手机屏幕阅读更加舒适，无需特别调为粗体。**

## 协助完善

欢迎更多志同道合的朋友在此基础上继续让这款字体更臻完善，您可以通过以下方式与本人联系。

- **Telegram：** @lxgwtg
- **微信公众号：** 霞鹜 *（ID: lxgwshare）*
- **酷安：** [@落霞孤鹜lxgw](https://www.coolapk.com/u/633884)
- **微博：** [@孤鹜先森](https://weibo.com/6624339726)
- **Email：** calxgw2018@gmail.com srtong2006@126.com lxgw1999@qq.com

## 授权信息

本字体是基于 SIL Open Font License 1.1 改造的 FONTWORKS 开发并发布的 [Klee](https://github.com/fontworks-fonts/Klee) 开源项目。Klee 是 FONTWORKS 的商标。

### 许可

- 这款字体无论是个人还是企业都可以自由商用，无需付费，也无需知会或者标明原作者。 *（但如果告知，我会很感激。）*
- 这款字体可以自由传播、分享，或者将字体安装于系统、软件或APP中也是允许的，可以与任何软件捆绑再分发以及／或一并销售。
- 这款字体可以自由修改、改造，制作衍生字体。修改或改造后的字体也必须同样以 [SIL OFL](https://scripts.sil.org/OFL) 公开。

### 限制

- 在制作衍生字体时，字体名称不可使用原有字体的「保留名称」。
- 这款字体不能用于违法行为，如因使用这款字体产生纠纷或法律诉讼，作者不承担任何责任。
- 根据 [SIL Open Font License 1.1](https://scripts.sil.org/OFL) 的规定， **禁止单独出售字体文件(OTF/TTF文件)的行为。**
