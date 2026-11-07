# 弈竹围棋 · Yizhu Weiqi

**Windows 围棋学习软件 / Go learning and practice for Windows**

## 中文简介

弈竹围棋是一款采用中国水墨风格界面的 Windows 围棋学习软件，提供题库练习、棋谱编辑与回放、学习记录及本地师生教学功能。核心本地功能无需先部署服务器。

此仓库用于发布 Windows 下载包，不包含项目开发环境或用户学习数据。

请打开本仓库 **Releases**，下载版本附件中的 `YizhuWeiqi-win-x64-*.zip`，完整解压后运行 `WeiqiStudy.exe`。不要下载自动生成的 Source code 包代替程序。

- 64位 Windows；具体兼容性与已知限制见各版本说明。
- 本地题库和练习无需先部署服务器；联网师生服务需另行配置。
- 未做代码签名，请核对下载来源及随版本提供的SHA256；不要关闭安全软件。
- 请在更新前备份个人学习记录。

软件包中的第三方组件、题库和素材按各自授权使用，本仓库的公开可见性不代表授予所有内容任意再分发权。

## English

Yizhu Weiqi is a Windows app for learning and practicing Go (Baduk/Weiqi), with a Chinese ink-wash interface. It provides problem sets, game-record editing and replay, learning records, and local teacher–student tools. Core local features do not require a server deployment.

This repository distributes Windows releases only. It does not publish the development workspace or users' learning data.

### Download and run

Open this repository's **Releases**, download the attached `YizhuWeiqi-win-x64-*.zip`, extract the entire archive, and run `WeiqiStudy.exe`. This is a portable distribution, not an installer. Do not download GitHub's automatically generated **Source code** archives as a substitute for the application.

### Important notes

- Intended for 64-bit Windows. See each release for verification scope and known limitations.
- Online teacher–student features require a separately configured service.
- The application is not code-signed. Verify the download source and the published SHA256; do not disable security software or bypass malware warnings.
- Local AI depends on compatible OpenCL drivers and may require first-run tuning; it is not guaranteed to work on every GPU.
- Back up your learning records before updating.
- The interface and included teaching content are primarily in Chinese. This bilingual description does not imply a fully English-language application.

Third-party components, problem sets, and artwork remain subject to their respective licenses and permissions. Making this download repository public does not grant unrestricted redistribution rights to all bundled content.
