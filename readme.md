# VPN登录指南

为保障九方智投学习机项目组非工作日的产品上线流程正常运转，相关项目组成员可参考本测试环境VPN登录指南远程接入办公环境。

访问 https://upload.techgp.cn/yzgd/EasyConnectInstaller.zip 下载VPN客户端配置文件压缩包，解压密码：rjhy-vpn，根据下述方法登录VPN。（测试通用vpn账号密码：**user：test，password：rjhy@test111111**，如果遇到问题，可直接跳到常见问题章节。） 

## 一、PC 端登录
### 1、解压压缩包，双击打开 EasyConnectInstaller文件：
![image](https://github.com/user-attachments/assets/22cc4516-a4ed-4dff-b638-f85486196370)

如果双击后无反应，鼠标右键“以管理员身份运行”：
![image](https://github.com/user-attachments/assets/e30104bc-e211-444e-8fd4-b7557eec1b6d)


### 2、选择同意，然后根据提示，一直下一步，直到安装完成：
![image](https://github.com/user-attachments/assets/6a2e39ad-e463-4328-97bf-8e25c2fc9a6f)

### 3、启动客户端文件，输入域名 [https://sslvpn2.techgp.cn:500](https://test-sslvpn1.techgp.cn:500/portal/#!/login)  然后回车。（**注意：此处必须用 https://upload.techgp.cn/yzgd/EasyConnectInstaller.zip 下载的VPN客户端连接，并且需要将配置文件config.yaml放置在安装目录根路径，浏览器无法直接访问测试环境VPN**）。

![image](https://github.com/user-attachments/assets/d505e885-99fd-46dd-993d-f6a885b9faf4)

### 4、步骤3完成后会弹出如下界面，输入“用户名/密码、验证码”登录即可。（测试环境用账号密码：**user：test，password：rjhy@test111111**,测试环境验证码：**111111**）
![image](https://github.com/user-attachments/assets/cf460eb0-a221-440e-865f-0aa413b2356c)


## 二、手机端登录
### 1. 在 APPStore、Android 商城或 PC 端深信服官网中检索深信服的“EasyConnect”APP进行下载并安装。
### 2.安装完后，打开“EasyConnect”。
### 3. 下载 https://upload.techgp.cn/yzgd/EasyConnectInstaller.zip ，解压后将config.yaml文件下载至本地，重命名为easyconnect.cer,然后同、通过手机浏览器将该配置文件导入至证书：
### 4.打开手机浏览器，访问 https://test-sslvpn1.techgp.cn:500/portal/#!/login ,“账号”选项卡输入VPN 的“用户名/密码”，点击登录。（测试环境用账号密码：**user：test，password：rjhy@test111111**,测试环境验证码：**111111**）

## 三、常见问题：
### 1. 若输入多次错误密码后，提示“用户尝试暴破登录，已被系统锁定”问题。

解决方法：等待10分钟，账户会被自动解锁。
![image](https://github.com/user-attachments/assets/43ec3fca-5c0f-407b-8fa3-38ee0ff32621)

### 2. 若出现“用户被禁用”的提示，表示Vpn已经到期或者被取消了。

解决方法：请联系项目组相关VPN负责人。
![image](https://github.com/user-attachments/assets/a2dc33d9-8428-4b14-92a0-41ceed4466d6)

### 3. 重置密码。
解决方法：若忘记密码，点击“忘记密码了？”，根据步骤进行重置。
特殊情况：
1) 用户被锁定。只需要等待10分钟后即可重置密码。
2) 用户被禁用。无法进行任何操作，请联系项目组相关VPN负责人。

### 4. VPN地址无法访问。
解决方法：企微主体切换至九方智投控股-九方云智能科技有限公司，联系vpn总负责人：王亮。
