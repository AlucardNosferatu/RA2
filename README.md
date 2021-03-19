### 简介
* Ares为经典游戏红色警戒2-尤里的复仇的非官方扩展程序，它通过动态注入的方式将原版程序的代码逻辑引入到Ares自己的动态链接库中去处理，实现了不修改原始二进制文件而干预游戏逻辑的效果。
* 官方Ares开发团队现在仅剩AlexB一人在继续开发和维护，目前版本已经演进到了3.0。
* 非官方Ares的Fork版本目前已知的有AresEx和Hares，本仓库及相关文案资料由Hares团队建立和维护。

### 须知
* 使用前请阅读[应该具有的心态](https://gitee.com/Zero_Fanker/Ares/wikis/%E5%BA%94%E8%AF%A5%E5%85%B7%E6%9C%89%E7%9A%84%E5%BF%83%E6%80%81?sort_id=1907760)
* 本仓库为Ares官版0.A码云镜像微调修正版下载后即可直接编译。相关仓库为:https://gitee.com/Zero_Fanker/YRpp 。
* Ares官方版本已经演进到3.0，而github上的源代码只更新到了0.A，其中YRPP更新到了0.B，所以我们只能提供0.A版本的原始代码。
* Ares 0.A需要Visual Studio 2015及以上版本以支持其语言特性和编译。

### 使用说明
1. 建议使用git工具将本仓库拉取到本地
2. 运行update_codes.bat，如果你已经正确安装了git工具，依赖库YRPP会自动下载到预设位置；
3. 本仓库包含VS项目配置文件，使用VS2017创建，预设的SDK是10.0.17763.0(Win10)，需要兼容XP系统的话需要自己下载WinSDK7.1A并应用到项目设置中去；
4. 编译完成后使用本仓库提供的inj文件，勿使用其它Ares版本的inj控制文件。
5. [教学导航见wiki](https://gitee.com/Zero_Fanker/Ares/wikis/%E5%BC%95%E8%A8%80)

### 帮助与支持
* 欢迎爱好者们参与Ares的开发，我们乐于与大家分享开发Ares的知识与经验，同时我们也欢迎大家踊跃贡献自己的代码成果，或是指正我们存在的问题。
* 如果你在开发的过程中遇到任何问题，可以在Issues页面提交求助。
* 我们Hares团队与AlexB来往密切，如果有任何想咨询官方版开发者的问题，可以经由我们和AlexB联络。

### 相关链接

* Ares官方github首页：https://github.com/Ares-Developers

* Ares官方github主库：https://github.com/Ares-Developers/Ares

* Ares官方github依赖库：https://github.com/Ares-Developers/YRpp

* Ares官方Launchpad成品下载页：https://launchpad.net/ares/+download

* Ares官方主页（恢复不久，但内容陈旧）：https://www.ares.strategy-x.com/

* ModEnc：https://www.modenc.renegadeprojects.com/Main_Page