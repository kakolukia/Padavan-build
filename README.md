# Padavan-build说明

源码采用 https://github.com/MeIsReallyBa/padavan-4.4

## 步骤
1. 点击右上角的 Fork，进入自己 fork 后的仓库。  
2. 编辑 /workflows/build-padavan.yml  
>1. 修改机型：将 TNAME: K2P 中的 K2P 修改为你需要编译的型号，注意名称要与 https://github.com/MeIsReallyBa/padavan-4.4/configs/templates/ 目录下的名字相同。  
>2. 根据文件内说明和示例自定义编译所需要的插件（插件目录 https://github.com/MeIsReallyBa/padavan-4.4/tree/main/trunk/user ）。  
3. 完成编辑后，点击页面上部的Actions按钮，点击 `I understand my workflows，go ahead and enable them`，启用 Action。  
4. 点击右上角的 Star 按钮即可开始自动编译。（每次编译都需要重新点击 Star 变灰后再次点亮才会编译）  
5. 根据编译文件包含大小区别，等待几分到几十分钟不等，完成后可在 Actions 页面下载固件。  
