<div align="center">

# <image src="Assets/AppLogo_AppLogo.svg" height="32"/> 北京师范大学南山附属学校 ClassIsland 集控仓库

#### **bsdnsxx-classisland-mgmt-cfg**

集控管理员QQ号: 2068364343

[![Release](https://img.shields.io/github/v/release/WilsonHuangDev/bsdnsxx-classisland-mgmt-cfg?style=flat-round&color=%233fb950&label=Release)](https://github.com/WilsonHuangDev/bsdnsxx-classisland-mgmt-cfg/releases/latest)

</div>

<br>

## 提醒

1. 若发现任何错误/过时信息，请通过[添加 `Issue` ](https://github.com/WilsonHuangDev/bsdnsxx-classisland-mgmt-cfg/issues/new)使我知晓。当然，您也可以自行[创建 `Pull Request` ](https://github.com/WilsonHuangDev/bsdnsxx-classisland-mgmt-cfg/pulls)修改。
2. 欢迎添加内容/班级！请[创建 `Pull Request` ](https://github.com/WilsonHuangDev/bsdnsxx-classisland-mgmt-cfg/pulls)，按照当前已有格式添加，我会在审核通过后合并至仓库。
3. 对于 ClassIsland 软件本体的错误，应[在 ClassIsland 仓库发起 `Issue`](https://github.com/ClassIsland/ClassIsland/issues)，而不是在本仓库发起 `Issue` 。
4. 对于 ClassIsland 软件本体的使用方法，请参阅[ClassIsland 文档](https://docs.classisland.tech/)。

## 仓库目录结构

> 1 [.github 文件夹](.github): Github 仓库 Issue 模版和工作流配置文件目录
>
> > 1.1 [ISSUE_TEMPLATE 文件夹](.github/ISSUE_TEMPLATE): Github 仓库 Issue 模版目录
> >
> > > 1.1.1 [BugReport.yml](.github/ISSUE_TEMPLATE/BugReport.yml): 有关 Bug 的 Issue 模版
> > > 
> > > 1.1.2 [FeatureRequest.yml](.github/ISSUE_TEMPLATE/FeatureRequest.yml): 有关新功能的 Issue 模版
> > > 
> > > 1.1.3 [OptimizationRequest.yml](.github/ISSUE_TEMPLATE/OptimizationRequest.yml): 有关功能优化的 Issue 模版
> > 
> > 1.2 [workflows 文件夹](.github/workflows): Github 仓库工作流配置文件目录
> > 
> > > 1.2.1 [defender-for-devops.yml](.github/workflows/defender-for-devops.yml): Microsoft Defender For Devops 工作流配置文件
>
> 2 [Assets](Assets): ClassIsland 图片目录
>
> > 2.1 [AppLogo.ico](Assets/AppLogo.ico): ClassIsland Logo Icon
> > 
> > 2.2 AppLogo*.png: ClassIsland Logo Picture
> > 
> > 2.3 [AppLogo_AppLogo.svg](Assets/AppLogo_AppLogo.svg): ClassIsland Logo 矢量图
> > 
> > 2.4 [AppLogo_Fade.png](Assets/AppLogo_Fade.png): ClassIsland Logo Fade Picture
> > 
> > 2.5 [AsciiLogo.txt](Assets/AsciiLogo.txt): 文本版 ClassIsland Logo
> > 
> > 2.6 [Banner.png](Assets/Banner.png): ClassIsland 宣传图
> > 
> > 2.7 [ClassIsland.ai](Assets/ClassIsland.ai): ClassIsland Logo 的 Adobe illustrator 工程文件
> > 
> > 2.8 [LICENSE](Assets/LICENSE): 本图片目录开源许可证&版权
>
> 3 [Tools 文件夹](Tools): 软件工具包目录
>
> > 3.1 [添加ClassIsland开机自启(x64文件夹).reg](Tools/添加ClassIsland开机自启(x64文件夹).reg): 为存放在 C 盘 Program Files 文件夹下的 ClassIsland 软件添加开机自启
> > 
> > 3.2 [添加ClassIsland开机自启(x86文件夹).reg](Tools/添加ClassIsland开机自启(x86文件夹).reg): 为存放在 C 盘 Program Files (x86) 文件夹下的 ClassIsland 软件添加开机自启
> > 
> > 3.3 [隐藏ClassIsland集控配置文件(x64文件夹).exe](Tools/隐藏ClassIsland集控配置文件(x64文件夹).exe): 隐藏存放在 C 盘 Program Files 文件夹下的 ClassIsland 集控配置文件
> > 
> > 3.4 [隐藏ClassIsland集控配置文件(x86文件夹).exe](Tools/隐藏ClassIsland集控配置文件(x86文件夹).exe): 隐藏存放在 C 盘 Program Files (x86) 文件夹下的 ClassIsland 集控配置文件
>
> 4 [beta 文件夹](beta): 测试版集控配置文件和测试版 ClassIsland 软件目录(仅存在于 `beta` 分支中)
>
> > 4.1 [ClassIsland 文件夹](beta/ClassIsland): 测试版 ClassIsland 软件目录(测试版本来源于[ ClassIsland 仓库](https://github.com/ClassIsland/ClassIsland)的 `Pre-release` 预发布版本)
> > 
> > > 4.1.1 [Config 文件夹](beta/ClassIsland/Config): 测试版 ClassIsland 组件/插件的配置文件目录
> > >
> > > 4.1.2 [Plugins 文件夹](beta/ClassIsland/Plugins): 测试版 ClassIsland 插件目录
> > >
> > > 4.1.3 [Profiles 文件夹](beta/ClassIsland/Profiles): 测试版 ClassIsland 课程表/时间表/科目档案目录
> > >
> > > 4.1.4 [ClassIsland.exe](beta/ClassIsland/ClassIsland.exe): 测试版 ClassIsland 软件本体
> > >
> > > 4.1.5 [ManagementPreset.json](beta/ClassIsland/ManagementPreset.json): 测试版 ClassIsland 客户端集控配置文件
> > >
> > > 4.1.6 [Settings.json](beta/ClassIsland/Settings.json): 测试版 ClassIsland 应用设置文件
> 
> 5 班级 ID 文件夹: 各班集控配置文件和集控版 ClassIsland 软件目录
> 
> > 5.1 classplans.json: 各班集控课程表档案
> > 
> > 5.2 timelayouts.json: 各班集控时间表档案
> > 
> > 5.3 ClassIsland 文件夹: 各班集控版 ClassIsland 软件目录
> >
> > > 5.3.1 Config 文件夹: ClassIsland 组件/插件的配置文件目录
> > >
> > > 5.3.2 Plugins 文件夹: ClassIsland 插件目录
> > >
> > > 5.3.3 Profiles 文件夹: ClassIsland 课程表/时间表/科目档案目录
> > >
> > > 5.3.4 ClassIsland.exe: ClassIsland 软件本体
> > >
> > > 5.3.5 ManagementPreset.json: ClassIsland 客户端集控配置文件
> > >
> > > 5.3.6 Settings.json: ClassIsland 应用设置文件
>
> 6 [.gitignore](.gitignore): Git Ignore 配置文件
>
> 7 [LICENSE](LICENSE): 本仓库开源许可证&版权
>
> 8 [README.md](README.md): 本仓库说明文档
> 
> 9 [manifest.json](manifest.json): 集控清单
> 
> 10 [policy.json](policy.json): 集控策略文件
> 
> 11 [settings.json](settings.json): 集控应用设置模板
> 
> 12 [subjects.json](subjects.json): 集控科目档案

## 许可证

本项目基于 [GNU General Public License v3.0](LICENSE) 获得许可。
