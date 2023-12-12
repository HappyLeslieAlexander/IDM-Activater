# IDM-Activater
IDM激活器
   
使用此脚本可以轻松激活IDM（Internet下载管理器）或重置其激活状态。
   
打开此脚本，输入1激活IDM，输入2重置IDM的激活状态，输入3打开或关闭Windows防火墙，输入4查看此脚本的文档，输入5退出脚本。
   
此脚本安全无病毒，不包含任何可能损坏计算机的特洛伊病毒或后门。
   
！！！请注意，此脚本仅用于学习和研究目的。请不要将此脚本用于任何盗版行为。请在下载后24小时内删除。IDM（互联网下载管理器）的版权归Tonec股份有限公司所有。
   
激活：
此脚本应用注册表锁定方法来激活Internet下载管理器（IDM）。
   
此方法需要在激活时使用Internet。
   
IDM更新可以直接安装，而无需再次激活。
   
激活后，如果在某些情况下，IDM将提示盗版，那么只需再次运行激活选项。
   
重置IDM激活/试用：
   
Internet下载管理器提供30天的试用期，您可以随时使用此脚本重置此激活/试用期。
   
如果IDM报告伪串行密钥和其他类似错误，此选项也可用于恢复状态。
   
操作系统要求：仅支持Windows 7/8/8.1/10/11及其等效服务器。
高级信息：
   
要在无人参与模式下激活，请运行带有/act参数的脚本。
   
要在无人参与模式下重置，请运行带有/res参数的脚本。
   
要使用以上两种方法启用静默模式，请运行带有/s参数的脚本。
   
故障排除步骤：
   
如果以前使用过任何其他激活器来激活IDM，请先卸载它
   
一些安全程序可能会阻止此脚本，这是错误的，请禁止防病毒软件的保护或添加排除
   
IDM激活脚本
   
电子邮件地址HappyLeslieAlexander@duck.com
   
电报@LeslieAlexander
   
作者：Leslie Alexander  

The Script Author is WindowsAddict

Credits:

@Dukun Cabul - Original researcher of this IDM trial reset and activation logic, made an Autoit tool for these methods, IDM-AIO_2020_Final nsaneforums.com/topic/371047--/?do=findComment&comment=1632062

@WindowsAddict - Ported the above Autoit tool to a batch script

@AveYo aka @BAU - Snippet to set registry ownership and permission recursively pastebin.com/XTPt0JSC

@abbodi1406 - Awesome batch script tricks and help

@dbenham - Set buffer height independently of window height stackoverflow.com/a/13351373

@ModByPiash (Me) - Add and fix some missing features.

@vavavr00m - Changed set name to prompt for a name

   
Use this script to easily activate IDM (Internet Download Manager) or reset its activation status.

Open this script, enter 1 to activate IDM, enter 2 to reset the activation status of IDM, enter 3 to turn on or off Windows Firewall, enter 4 to view the documentation of this script, and enter 5 to exit the script.

This script is safe and virus free, and does not contain any Trojan viruses or backdoors that may damage the computer.

!!!Note that this script is for learning and research purposes only. Please do not use this script for any piracy behavior. Please delete it within 24 hours after downloading. The copyright of IDM (Internet Download Manager) belongs to Tonec Inc.

_________________________________

   Activation:
_________________________________

 - This script applies registry lock method to activate Internet download manager (IDM).

 - This method requires Internet at the time of activation.

 - IDM updates can be installed directly without having to activate again.

 - After the activation, if in some case, the IDM starts to show activation nag screen, 
   then just run the activation option again.

_________________________________

   Reset IDM Activation / Trial:
_________________________________

 - Internet download manager provides 30 days trial period, you can use this script to 
   reset this Activation / Trial period whenever you want.
 
 - This option also can be used to restore status if in case the IDM reports fake serial
   key and other similar errors.

_________________________________

   OS requirement:
_________________________________

 - Project is supported only for Windows 7/8/8.1/10/11 and their Server equivalent.

_________________________________

 - Advanced Info:
_________________________________

   - To add a custom name in IDM license info, edit the line number 5 in the script file.

   - For activation in unattended mode, run the script with /act parameter.
   - For reset in unattended mode, run the script with /res parameter.
   - To enable silent mode with above two methods, run the script with /s parameter.

Possible accepted values,

"IAS_xxxxxxxx.cmd" /act
"IAS_xxxxxxxx.cmd" /res
"IAS_xxxxxxxx.cmd" /act /s
"IAS_xxxxxxxx.cmd" /res /s

_________________________________

 - Troubleshooting steps:
_________________________________

   - If any other activator was used to activate IDM previously then make sure to properly
     uninstall it with that same activator (if there is an option), this is especially important
     if any registry / firewall block method was used.

   - Uninstall the IDM from control panel.

   - Make sure the latest original IDM setup is used for the installation,
     you can download it from https://www.internetdownloadmanager.com/download.html

   - Now install the IDM and use the activate option in this script and if failed then,

     - Disable windows firewall with the script option, this help in case of leftover entries of
       previously used activator (some file patch method also creates firewall entries).

     - Some security programs may block this script, this is false-positive, as long as you 
       downloaded the file from original post (mentioned below in this page), temporary suspend
       Antivirus realtime protection, or exclude the downloaded file/extracted folder from scanning.


____________________________________________________________________________________________________

   Credits:
____________________________________________________________________________________________________

   IDM Activation Script
   E-mail at HappyLeslieAlexander@duck.com
   Telegram @LeslieAlexander
   
   By Leslie Alexander

   The Script Author is WindowsAddict

@Dukun Cabul - Original researcher of this IDM trial reset and activation logic, made an Autoit tool for these methods, IDM-AIO_2020_Final nsaneforums.com/topic/371047--/?do=findComment&comment=1632062

@WindowsAddict - Ported the above Autoit tool to a batch script

@AveYo aka @BAU - Snippet to set registry ownership and permission recursively pastebin.com/XTPt0JSC

@abbodi1406 - Awesome batch script tricks and help

@dbenham - Set buffer height independently of window height stackoverflow.com/a/13351373

@ModByPiash (Me) - Add and fix some missing features.

@vavavr00m - Changed set name to prompt for a name


____________________________________________________________________________________________________
