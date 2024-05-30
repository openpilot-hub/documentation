# Visual Studio Code Manual

[中文](README_VSCode.md) ｜ [English](README_VSCode_EN.md)

## Installation
1. When Visual Studio Code is installed, click Extensions in the side navigation, search for DevPilot, find it and click Install.

![](/static/docs/devpilot/vscode-marketplace.png)

2. Reload Visual Studio Code，After successful restart, select the corresponding login method to log in to the account based on the user type (public users scan the qr code to follow our wechat offical account), you can start your intelligent coding journey.

## Login

![](/static/docs/devpilot/vscode-login.png)

Users can click Login to jump to the login page to log in.

![](/static/docs/devpilot/login_page.png)

Public users scan the qr code to follow our wechat offical account.

## Configuration

Use the 'command+', or navigate to the configuration page from the Code > Preferences > Settings > DevPilot menu

![](/static/docs/devpilot/settings.png)

## Functionality

DevPilot provides developers with rich capabilities to help developers avoid tedious test cases and comments, to help developers write more efficient code, and to help troubleshoot code problems.

### Code Completions

When you enter a part of the code, or a line feed and other operations, DevPilot will use the context of the current code association, and complete the code operation, the user can use Tab to accept the completed code, if not satisfied with the ESC to cancel the acceptance code.

### AI Chat

Devilot supports the dialog ability, and the dialog page can be opened by right-clicking or the entrance of the right sidebar.

![](/static/docs/devpilot/menu_chat.png)

You can write questions in the dialog box, send chat questions by carriage return or send button, and then DevPilot will return the answer and output it on the current page.

![](/static/docs/devpilot/chat.png)

### Generate Tests

Users can generate test cases through DevPilot. The user directly click 'Test' on the method block or select a method and then right-clicks 'Generate Tests'.

![](/static/docs/devpilot/menu_chat_test.png)

Then the window will automatically open and the window will return the relevant test case, the user can directly copy the test, or directly choose to insert or replace the relevant code at the cursor, or even create a new test class file.

![](/static/docs/devpilot/testcase_result.png)

### Generate Comments

The plugin supports the generation of code block/function level comments. Users can directly click 'Summary' on a method block or function.
After that, the window will automatically open and return the related comment result, and the user can choose whether to accept the corresponding comment.

![](/static/docs/devpilot/menu_chat_comment.png)

### Fix Code

DevPilot support the ability to fix code. Users click 'Fix' directly on the method block, or select the block and then right-click 'Fix This'.

![](/static/docs/devpilot/menu_chat_fix.png)

After that, the window will automatically open and return the relevant repair suggestions, and the user can modify the code according to the suggestions.

![](/static/docs/devpilot/fix_bug_result.png)

### Review Code

DevPilot supports the ability to audit code. Users select the code block and then right-click on 'Code Review'.

![](/static/docs/devpilot/menu_chat_performance.png)

### Proformance Check

DevPilot supports performance checking of the code. Users can select the code block and right-click on 'Performance Check'.

![](/static/docs/devpilot/menu_chat_performance.png)

Then the window will automatically open to return the relevant performance test results, users can optimize the code according to the results of the code, problems, suggestions.

![](/static/docs/devpilot/performance_check_result.png)