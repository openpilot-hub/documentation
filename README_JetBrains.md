# JetBrains IDEs插件使用手册

[中文](README_JetBrains.md) ｜ [English](README_JetBrains_EN.md)

## 以 IntelliJ IDEA 为例安装插件

目前插件对于JetBrains的版本有要求，**最低版本要求为2021.2，建议版本为2022.1以上**

**请大家及时更新至最新版本插件以避免功能不可用**

1. 已安装Intellij IDEA的情况下：
<ul>
<li>Mac：Intellij IDEA菜单下点击设置</li>
<li>Windows：文件菜单下点击设置</li>
</ul>

2. 插件市场或本地安装
插件市场安装：点击Plugins -> Marketplace, 搜索DevPilot后，点击安装。

![](/static/docs/devpilot/JetBrains-marketplace.png)

本地安装：点击Plugins -> settings -> install plugin from Disk，选择从应用市场下载的[zip](https://plugins.jetbrains.com/plugin/download?rel=true&updateId=530394)文件后安装。

![](/static/docs/devpilot/JetBrains-install-from-disk.png)

3. 重启 Jetbrains IDEA，重启成功后基于用户类型选择对应的登录方式登录账号（微信用户扫码关注公众号），即可开启智能编码之旅。

## 配置插件

插件安装成功后，在idea设置页面的Tools中就能找到DevPilot的配置页面

![](/static/docs/devpilot/config1.png)

在配置页面可以切换插件的中英文，以及选择是否开启代码自动补全，用户名则是在对话时在页面展示时使用。

![](/static/docs/devpilot/config2.png)

**请注意，在最新版本中必须要登录SSO用户才能够使用对话和补全功能，微信用户关注公众号即可使用对话功能！**

## 插件功能

DevPilot为开发者提供了丰富的能力来协助开发者能够省去繁琐的测试用例和注释编写，也能够帮助开发者编写更加高效的代码，同时也能帮助排查代码的问题等等。

### 代码自动补全

当你输入部分代码，或者是换行等操作时，DevPilot会通过上下文对当前代码进行联想，并完成代码补全操作，用户可以使用Tab来接受补全的代码，如果不满意可使用ESC取消接受代码

![](/static/docs/devpilot/completion1.png)

![](/static/docs/devpilot/completion2.png)

### 生成式AI对话

插件支持对话能力，通过右键或者是右边侧边栏的入口可以打开对话的页面

![](/static/docs/devpilot/chat1.png)

![](/static/docs/devpilot/chat2.png)

在对话框中可以编写问题，通过回车或者是发送按钮进行聊天问题的发送，后续OpenAI会返回回答并在当前页面输出

![](/static/docs/devpilot/chat3.png)

### 生成测试用例

用户可以通过我们插件来生成测试用例。用户直接在方法块上选择`生成单测`或选中某个方法后右键点击`生成单测`

![](/static/docs/devpilot/JetBrains-Test.png)

之后窗口会自动打开然后窗口会返回相关的测试用例，用户可以直接复制测试，或者直接选择在光标处插入或者替换相关的代码，甚至还可以新建测试类文件

![](/static/docs/devpilot/test2.png)

### 生成注释

#### 函数注释

插件支持代码块/函数级注释的生成功能。用户可直接在方法块、函数上点击`函数注释`
之后窗口自动打开并返回相关的注释结果，用户可以自行选择是否接受对应的注释。

![](/static/docs/devpilot/comment2.png)

#### 行内注释

插件支持代码行内注释的生成功能。用户在代码块、函数上点击`行内注释`，或选中代码块后右键点击`行内注释`

![](/static/docs/devpilot/comment1.png)

之后窗口自动打开会返回相关的注释结果，并且在编辑器中会自动将生成注释后的结果和原先的代码进行diff，用户可以自行进行比对接受对应的注释。

![](/static/docs/devpilot/comment3.png)

### 修复代码

插件支持修复代码的能力。用户直接在方法块上点击`修复代码`，或选中代码块后右键点击`修复代码`

![](/static/docs/devpilot/fix1.png)

之后窗口自动打开会返回相关的修复建议，用户可以根据建议修改代码

![](/static/docs/devpilot/fix2.png)

### 审核代码

插件支持审核代码的能力。用户选中代码块后右键点击`代码审核`即可

![](/static/docs/devpilot/review1.png)

之后窗口自动打开会返回相关的审核结果，用户可以根据结果来编辑自己的代码逻辑

![](/static/docs/devpilot/review2.png)

### 性能检测

插件支持对代码进行性能检测。用户选中代码块后右键点击`性能检测`即可

![](/static/docs/devpilot/performance1.png)

之后窗口自动打开会返回相关的性能检测结果，用户可以根据结果中代码、问题、建议来优化代码

![](/static/docs/devpilot/performance2.png)

### 清理上下文

插件整体的相关能力都是附带上下文的，但是上下文可能会存在相互影响的情况，并且大语言模型都会存在token的限制，超出限制会导致响应不符合预期。因此我们提供清理的上下文的能力，在对话输入框左侧点击清除按钮就可以将当前会话记录清空。

![](/static/docs/devpilot/clear1.png)
