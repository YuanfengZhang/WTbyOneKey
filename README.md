# WTbyOneKey Aim
Run Windows Terminal Preview by one key

This script is the most simplified version. **For usage and detailed introduction, please visit**  https://blog.danskingdom.com/Bring-up-the-Windows-Terminal-in-a-keystroke/

Thanks Daniel Schroeder a lot. Finally I found a correct way to launch Windows Terminal Preview by custom key there. Here is his Github profile: https://github.com/deadlydog

# READ AFTER HIS BLOG


For users of Windows Terminal Preview and Windows 11, it should be noticed that there are **two "wt"s** in your computer, the bulit-in wt and the preview one. The right one is located in **`%USERPROFILE/AppData/Local/Microsoft/WindowsApps/Microsoft.WindowsTerminalPreview_8wekyb3d8bbwe`**, not `C:/ProgramFiles/WindowsApps/Microsoft.WindowsTerminalPreview_$(changing version number)__8wekyb3d8bbwe`

So here I offer the simplified version for wt preview. You can just download the wtp.exe file, put it into Windows Task Scheduler or Startup.

————————————————————————————————————————————
# 一键运行Windows Terminal Preview
再也不用WIN+SHITF+CTRL+$NUM了，也不用鼠标连点好几下才能开终端了，只要一键。如果自己想设置按键，请去 https://blog.danskingdom.com/Bring-up-the-Windows-Terminal-in-a-keystroke/ 查看具体操作流程，并且注意：真正可执行的Windows Terminal Preview的wt.exe位于 **`%USERPROFILE/AppData/Local/Microsoft/WindowsApps/Microsoft.WindowsTerminalPreview_8wekyb3d8bbwe`**。其他地方的都不行。

# 懒人看这里
下载wtp.exe，打开文件管理器，输入shell:Startup，把wtp.exe扔进去，万事大吉。或者打开任务计划程序，把这个程序设置成每次登录时启动一次。
