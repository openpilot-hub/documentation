# Visual Studio Code插件使用手册

[中文](README_VSCode.md) ｜ [English](README_VSCode_EN.md)

## 安装

### 在 Visual Studio Code 中安装

1. 已安装 Visual Studio Code 的情况下，在侧边导航上点击扩展。 搜索DevPilot，找到后点击安装。

![](/static/docs/devpilot/vscode-marketplace.png)

2. 重启 Visual Studio Code，重启成功后基于用户类型选择对应的登录方式登录账号（微信用户扫码关注公众号），即可开启智能编码之旅。

## 登录

![](/static/docs/devpilot/vscode-login.png)

用户可以点击登录跳转到登录页面进行登录

![](/static/docs/devpilot/login_page.png)

之后选择相应的登录方式即可

## 配置

使用快捷键`command+,`或者通过菜单Code ❯ Preferences ❯ Settings > DevPilot 定位到配置页面

![](/static/docs/devpilot/settings.png)

## 插件功能

DevPilot为开发者提供了丰富的能力来协助开发者能够省去繁琐的测试用例和注释编写，也能够帮助开发者编写更加高效的代码，同时也能帮助排查代码的问题等等。

### 生成式AI对话

插件支持对话能力，通过右键可以打开对话的页面

![](/static/docs/devpilot/menu_chat.png)

在对话框中可以编写问题，通过回车或者是发送按钮进行聊天问题的发送，后续DevPilot会返回回答并在当前页面输出

![](/static/docs/devpilot/chat.png)

### 生成测试用例

用户可以通过我们插件来生成测试用例。用户直接在方法块上选择`Test`或选中某个方法右键点击`Generate Tests`

![](/static/docs/devpilot/menu_chat_test.png)

之后窗口会自动打开然后窗口会返回相关的测试用例，用户可以直接复制测试，或者直接选择在光标处插入或者替换相关的代码，甚至还可以新建测试类文件

![](/static/docs/devpilot/testcase_result.png)

### 生成注释

插件支持代码注释的生成功能。用户选中代码块后右键点击`Generate comments`或着直接在方法块上选择`Comments`生成行内注释以及在方法块上选择`Summary`生成函数注释

![](/static/docs/devpilot/menu_chat_comment.png)

### 修复代码

插件支持修复代码的能力。用户直接在方法块上选择`Fix`或选中代码块后右键点击`Fix This`

![](/static/docs/devpilot/menu_chat_fix.png)

之后窗口自动打开会返回相关的修复建议，用户可以根据建议修改代码

![](/static/docs/devpilot/fix_bug_result.png)

### review代码

插件支持review代码的能力。用户选中代码块后右键点击`Review Code`

![](/static/docs/devpilot/menu_chat_performance.png)

### 性能检测

插件支持对代码进行性能检测。用户选中代码块后右键点击`Performance Check`

![](/static/docs/devpilot/menu_chat_performance.png)

之后窗口自动打开会返回相关的性能检测结果，并且在编辑器中会自动将代码优化后的结果和原先的代码进行diff，用户可以根据结果来优化代码

![](/static/docs/devpilot/performance_check_result.png)