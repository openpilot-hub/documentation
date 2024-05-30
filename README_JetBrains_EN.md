# JetBrains IDEs Manual

[中文](README_JetBrains.md) ｜ [English](README_JetBrains_EN.md)

## Use IntelliJ IDEA as an example to install

At present, the plugin has requirements for the version of JetBrains, **The minimum version requirement is 2021.2, the recommended version is 2022.1 or above**.

**Please update to the latest version of the plugin to avoid functionality unavailable**.

1. When Intellij IDEA is installed：
<ul>
<li>Mac：Click Settings under the Intellij IDEA menu</li>
<li>Windows：Click Settings under the File menu</li>
</ul>

2. Install from Marketplace or Install Plugin from Disk
Install from Marketplace：Click Plugins -> Marketplace, Search DevPilot，then click Install.

![](/static/docs/devpilot/JetBrains-marketplace.png)

Install Plugin from Disk：Click Plugins -> settings -> Install plugin from Disk，Select the [zip](https://plugins.jetbrains.com/plugin/download?rel=true&updateId=530394) file downloaded from the Marketplace and install it.

![](/static/docs/devpilot/JetBrains-install-from-disk.png)

3. Restart Jetbrains IDEA. After successful restart, select the corresponding login method to log in to the account based on the user type (public users scan the qr code to follow our wechat offical account), you can start your intelligent coding journey.

## DevPilot configurations

After DevPilot is installed, the DevPilot configuration page can be found in Tools on the idea setup page.

![](/static/docs/devpilot/config1.png)

On the configuration page, you can switch between the Chinese and English versions, and choose whether to enable automatic code completions. The user name is used in the dialog when the page is displayed.

![](/static/docs/devpilot/config2.png)

**Please note that the public users can use the dialogue function free by following the public account**

## 插件功能

DevPilot provides developers with rich capabilities to help developers avoid tedious test cases and comments, to help developers write more efficient code, and to help troubleshoot code problems.

### 代码自动补全

When you enter a part of the code, or a line feed and other operations, DevPilot will use the context of the current code association, and complete the code operation, the user can use Tab to accept the completed code, if not satisfied with the ESC to cancel the acceptance code.

![](/static/docs/devpilot/completion1.png)

![](/static/docs/devpilot/completion2.png)

### 生成式AI对话

Devilot supports the dialog ability, and the dialog page can be opened by right-clicking or the entrance of the right sidebar.

![](/static/docs/devpilot/chat1.png)

![](/static/docs/devpilot/chat2.png)

You can write questions in the dialog box, send chat questions by carriage return or send button, and then DevPilot will return the answer and output it on the current page.

![](/static/docs/devpilot/chat3.png)

### 生成测试用例

Users can generate test cases through DevPilot. The user directly click 'Test' on the method block or select a method and then right-clicks 'Generate Tests'.

![](/static/docs/devpilot/JetBrains-Test.png)

Then the window will automatically open and the window will return the relevant test case, the user can directly copy the test, or directly choose to insert or replace the relevant code at the cursor, or even create a new test class file.

![](/static/docs/devpilot/test2.png)

### Generate Comments

#### Summary

The plugin supports the generation of code block/function level comments. Users can directly click 'Summary' on a method block or function.
After that, the window will automatically open and return the related comment result, and the user can choose whether to accept the corresponding comment.

![](/static/docs/devpilot/comment2.png)

#### Comments

DevPilot supports the generation of in-line comments. Users click 'Comments' on a code block or function, or right-click 'Generate Comments' after selecting a code block.

![](/static/docs/devpilot/comment1.png)

Then the window will automatically open and return the related comment result, and the editor will automatically generate the result of the comment and the original code for diff, the user can compare and accept the corresponding comment.

![](/static/docs/devpilot/comment3.png)

### Fix Code

DevPilot support the ability to fix code. Users click 'Fix' directly on the method block, or select the block and then right-click 'Fix This'.

![](/static/docs/devpilot/fix1.png)

After that, the window will automatically open and return the relevant repair suggestions, and the user can modify the code according to the suggestions.

![](/static/docs/devpilot/fix2.png)

### Review Code

DevPilot supports the ability to audit code. Users select the code block and then right-click on 'Code Review'.

![](/static/docs/devpilot/review1.png)

Then the window will automatically open to return the relevant audit results, and users can edit their own code logic according to the results.

![](/static/docs/devpilot/review2.png)

### Proformance Check

DevPilot supports performance checking of the code. Users can select the code block and right-click on 'Performance Check'.

![](/static/docs/devpilot/performance1.png)

Then the window will automatically open to return the relevant performance test results, users can optimize the code according to the results of the code, problems, suggestions.

![](/static/docs/devpilot/performance2.png)

### Clear Context

The relevant capabilities of the whole plug-in are attached to the context, but the context may affect each other, and the large language model will have the token limit, beyond the limit will lead to the response does not meet the expectations. Therefore, we provide the ability to clear the context by clicking the Clear button on the left side of the dialog input box to clear the current session record.

![](/static/docs/devpilot/clear1.png)
