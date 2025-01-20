#### Chill Pro Bridging network description

* Windows
  - 安装运行环境依赖 golang，下载地址：[golang](https://dl.google.com/go/go1.23.4.windows-amd64.msi) 点击自动下载`默认安装即可，一直Next`
  - 下载`3x-ui` 下载地址：[3x-ui](https://github.com/MHSanaei/3x-ui/releases/download/v2.4.11/x-ui-windows-amd64.zip) 点击自动下载,解压到任意目录
  - 解压后进入文件夹，点击`main.exe`执行。
  - 在任意浏览器打开网址：[http://localhost:2053/](http://localhost:2053/), 可以看见如下界面

    ![image](https://github.com/user-attachments/assets/f581027f-b21b-4509-b864-9cfcfb9cb985)

  - 输入账号`admin` 密码`admin` 点击登录。进入如下界面：
 
    ![image](https://github.com/user-attachments/assets/4497640e-1eb5-40cb-9e0e-a9203b6d9d85)

  - 点击左侧菜单`xray设置` 选项进入`出站规则`->`添加出站`->选择`json`，输入`windows的链接地址`到输入框，然后点击旁边的图标按钮->`添加出站`。

    ![image](https://github.com/user-attachments/assets/c7a8aef9-32cf-4c38-95fc-625104516131)
    ![image](https://github.com/user-attachments/assets/d40552a4-a0a3-4026-8ad1-97241ec99956)
    ![image](https://github.com/user-attachments/assets/9b8c0b26-f91b-444c-a69b-f3846a848049)
    ![image](https://github.com/user-attachments/assets/94e280aa-2147-4f75-84a0-2f9caea071b9)
 
  - 最终效果
    
    ![image](https://github.com/user-attachments/assets/de5ea163-2c07-4b0a-85b2-7adb8dfa6321)

  - 然后点击顶部的`保存`按钮，然后点击`重新启动xray`按钮, 如果出现重启错误

    ![image](https://github.com/user-attachments/assets/cec790c7-9321-4a4c-9ebf-d02f86946cc4)
  - 进入`高级配置`->修改下列端口为`8080` 如图所示
    ![image](https://github.com/user-attachments/assets/1a79763a-bc3b-4079-bf99-5e7605c52087)
  - 然后点击`保存`按钮->点击`重新启动xray`按钮。
  - 完成windows的配置。




* Ios
  - 从apple store 下载 V2Box - V2ray Client App，安装后打开.
  - 下载地址：[V2Box - V2ray Client App](https://apps.apple.com/us/app/v2box-v2ray-client/id6446814690) 点击自动跳转到Apple Store
  - 安装完成后，你可以看见如下界面：
    ![f4598bf129e021982011882eeb66606](https://github.com/user-attachments/assets/c0cf2cbf-e7b9-433e-9492-0cff65b180d4)

  - 点击底部的`Config`按钮，然后点击顶部右上角的`+`按钮，然后点击`Add manual config`选项, 选择`json`添加一个新的配置，如下如所示

    ![image](https://github.com/user-attachments/assets/d50be42d-199a-4257-9c4a-b8efe183f068)
    ![image](https://github.com/user-attachments/assets/b4dc4be0-6aa3-439a-8f94-81f0cd06921c)
    ![image](https://github.com/user-attachments/assets/ab17be0a-3ce9-4278-aefa-68116e7cec39)
    ![1737387301597](https://github.com/user-attachments/assets/e9507979-15b2-4b77-9596-23e1d76cde6f)
    
  - `Remarks`可以随便填写，内容部分填写链接里面的内容-全部复制 然后粘贴到这里就可以，完成后效果图：

    ![image](https://github.com/user-attachments/assets/74e8eae2-3b95-46f7-8552-92d9afe4d342)

  - 然后，点击空白部分，滑动到底部，点击`Save`按钮，然后返回上一个界面。你可以得到如下图所示的效果。

    ![1737387612940](https://github.com/user-attachments/assets/2cdad0ae-1aeb-451b-a456-e4b194a8738a)
    ![1737387656688](https://github.com/user-attachments/assets/ab5b9af3-cbf0-42a1-916f-2692b904a9f1)
    
    `点击配置文件`
    
    ![1737387695579](https://github.com/user-attachments/assets/7b85c136-cac8-4dd4-b9bb-e5b4982adc07)

    
  - 最后，滑动`Slide to Connect`按钮，链接，就可以了。如图所示效果：
    
    ![1737387777469](https://github.com/user-attachments/assets/49761e84-385e-4c1d-ab23-a208d79805d8)

* Android
  - 下载地址：[v2rayNG](https://github.com/2dust/v2rayNG/releases/download/1.9.31/v2rayNG_1.9.31_arm64-v8a.apk) 点击自动下载，安装后打开
  - 界面配置URL: `Android_v2rayNG_1.json`，复制然后打开软件
  - 效果如下图：
    
    ![image](https://github.com/user-attachments/assets/8d722436-c672-4df8-8ac8-b570837ce5a8)

  - 点击顶部右上角的`+`按钮，然后点击`自定义配置`选项，选择`剪贴板URL导入自定义配置`选项添加一个新的配置，如下如所示

    ![image](https://github.com/user-attachments/assets/98ca2066-186b-4bc6-95f0-7d1c1d40e96c)
    ![image](https://github.com/user-attachments/assets/a2ea3e45-6006-4882-8638-e93d98bc9735)
    ![image](https://github.com/user-attachments/assets/162f819e-1f71-4d83-a407-565506effcf1)

  - 完成后效果如下图：

    ![image](https://github.com/user-attachments/assets/06332f75-c76e-4e7e-a17b-4186c3c82650)

  - 点击顶部左上角的`菜单`按钮，选择`设置`, 点击最下面的选项`Advanced Setting`，展开后 最后面的`Mode`从VPN，切换到`Proxy only`，如下图所示
    
    ![image](https://github.com/user-attachments/assets/58d7877a-5182-4ff3-b3dc-f0eff45f5b3a)
    ![image](https://github.com/user-attachments/assets/6ce896f9-e632-4a2e-a160-f04d471f38b2)
    ![image](https://github.com/user-attachments/assets/d98c62e9-22fe-4b5c-bc68-d179f0274dab)
    ![image](https://github.com/user-attachments/assets/a4e7b92b-2e80-4be3-b918-e910aefe6d38)
    ![image](https://github.com/user-attachments/assets/5f5c3624-864b-4938-897a-3270f8b40312)


  - 然后点击页面右下角的按钮，开启服务，如图所示：
    
    ![image](https://github.com/user-attachments/assets/a0a2837c-c874-4c2b-baf3-71236825f270)
    ![image](https://github.com/user-attachments/assets/dd5d5f25-4d65-4f6a-bb97-d2d05d815982)



