# MSBuild

[创建用于代码生成的自定义任务](https://learn.microsoft.com/zh-cn/visualstudio/msbuild/tutorial-custom-task-code-generation?view=vs-2022)

[项目文件中的已知属性（知道了这些，就不会随便在 csproj 中写死常量啦） - walterlv](http://blog.walterlv.com/post/known-properties-in-csproj.html)

[如何更精准地设置 C# / .NET Core 项目的输出路径？（包括添加和删除各种前后缀） - walterlv](https://blog.walterlv.com/post/the-properties-that-affetcs-project-output-path.html)

[在 Target 中获取项目引用的所有依赖（dll/NuGet/Project）的路径 - walterlv](https://blog.walterlv.com/post/resolve-project-references-using-target.html)

[.NET/C# 项目如何优雅地设置条件编译符号？ - walterlv - 博客园](https://www.cnblogs.com/walterlv/p/10236373.html)

[使用 MSBuild 响应文件 (rsp) 来指定 dotnet build 命令行编译时的大量参数 - walterlv - 博客园](https://www.cnblogs.com/walterlv/p/10236473.html)

[.NET/C# 中你可以在代码中写多个 Main 函数，然后按需要随时切换 - walterlv - 博客园](https://www.cnblogs.com/walterlv/p/10236408.html)

[docs.microsoft.com-nuget/Creating-a-Package.md at main · NuGet/docs.microsoft.com-nuget · GitHub](https://github.com/NuGet/docs.microsoft.com-nuget/blob/main/docs/create-packages/Creating-a-Package.md)

[Roslyn 在项目文件使用条件判断](https://lindexi.gitee.io/post/Roslyn-%E5%9C%A8%E9%A1%B9%E7%9B%AE%E6%96%87%E4%BB%B6%E4%BD%BF%E7%94%A8%E6%9D%A1%E4%BB%B6%E5%88%A4%E6%96%AD.html)

[Roslyn 打包 NuGet 包添加改动日志](https://blog.lindexi.com/post/Roslyn-%E6%89%93%E5%8C%85-NuGet-%E5%8C%85%E6%B7%BB%E5%8A%A0%E6%94%B9%E5%8A%A8%E6%97%A5%E5%BF%97.html)

[Roslyn 使用 WriteLinesToFile 解决参数过长无法传入](https://lindexi.gitee.io/post/Roslyn-%E4%BD%BF%E7%94%A8-WriteLinesToFile-%E8%A7%A3%E5%86%B3%E5%8F%82%E6%95%B0%E8%BF%87%E9%95%BF%E6%97%A0%E6%B3%95%E4%BC%A0%E5%85%A5.html)

[msbuild 修改 VisualStudio 文件复制到输出目录的路径](https://blog.lindexi.com/post/msbuild-%E4%BF%AE%E6%94%B9-VisualStudio-%E6%96%87%E4%BB%B6%E5%A4%8D%E5%88%B6%E5%88%B0%E8%BE%93%E5%87%BA%E7%9B%AE%E5%BD%95%E7%9A%84%E8%B7%AF%E5%BE%84.html)

[Roslyn 如何了解某个项目在 msbuild 中所有用到的属性以及构建过程](https://blog.lindexi.com/post/Roslyn-%E5%A6%82%E4%BD%95%E4%BA%86%E8%A7%A3%E6%9F%90%E4%B8%AA%E9%A1%B9%E7%9B%AE%E5%9C%A8-msbuild-%E4%B8%AD%E6%89%80%E6%9C%89%E7%94%A8%E5%88%B0%E7%9A%84%E5%B1%9E%E6%80%A7%E4%BB%A5%E5%8F%8A%E6%9E%84%E5%BB%BA%E8%BF%87%E7%A8%8B.html)

[Roslyn 禁止 sdk style csproj 默认引用 Compile 代码文件](https://blog.lindexi.com/post/Roslyn-%E7%A6%81%E6%AD%A2-sdk-style-csproj-%E9%BB%98%E8%AE%A4%E5%BC%95%E7%94%A8-Compile-%E4%BB%A3%E7%A0%81%E6%96%87%E4%BB%B6.html)

[Roslyn 使用 Directory.Build.props 文件定义编译](https://lindexi.gitee.io/post/Roslyn-%E4%BD%BF%E7%94%A8-Directory.Build.props-%E6%96%87%E4%BB%B6%E5%AE%9A%E4%B9%89%E7%BC%96%E8%AF%91.html)

[Roslyn 打包自定义的文件到 NuGet 包](https://blog.lindexi.com/post/Roslyn-%E6%89%93%E5%8C%85%E8%87%AA%E5%AE%9A%E4%B9%89%E7%9A%84%E6%96%87%E4%BB%B6%E5%88%B0-NuGet-%E5%8C%85.html)

[Roslyn 在 NuGet 包中放注释 xml 文件的方法](https://blog.lindexi.com/post/Roslyn-%E5%9C%A8-NuGet-%E5%8C%85%E4%B8%AD%E6%94%BE%E6%B3%A8%E9%87%8A-xml-%E6%96%87%E4%BB%B6%E7%9A%84%E6%96%B9%E6%B3%95.html)

[Roslyn 打包 NuGet 包 BuildTransitive 文件夹用于穿透依赖传递拷贝文件](https://blog.lindexi.com/post/Roslyn-%E6%89%93%E5%8C%85-NuGet-%E5%8C%85-BuildTransitive-%E6%96%87%E4%BB%B6%E5%A4%B9%E7%94%A8%E4%BA%8E%E7%A9%BF%E9%80%8F%E4%BE%9D%E8%B5%96%E4%BC%A0%E9%80%92%E6%8B%B7%E8%B4%9D%E6%96%87%E4%BB%B6.html)

[Roslyn 读取 PackageReference 的版本号和内容](https://blog.lindexi.com/post/Roslyn-%E8%AF%BB%E5%8F%96-PackageReference-%E7%9A%84%E7%89%88%E6%9C%AC%E5%8F%B7%E5%92%8C%E5%86%85%E5%AE%B9.html)

[Roslyn 解决 dotnet core 应用进程间引用找不到 runtimeconfig 依赖文件](https://blog.lindexi.com/post/Roslyn-%E8%A7%A3%E5%86%B3-dotnet-core-%E5%BA%94%E7%94%A8%E8%BF%9B%E7%A8%8B%E9%97%B4%E5%BC%95%E7%94%A8%E6%89%BE%E4%B8%8D%E5%88%B0-runtimeconfig-%E4%BE%9D%E8%B5%96%E6%96%87%E4%BB%B6.html)

[Roslyn 理解 msbuild 的清理过程](https://blog.lindexi.com/post/Roslyn-%E7%90%86%E8%A7%A3-msbuild-%E7%9A%84%E6%B8%85%E7%90%86%E8%BF%87%E7%A8%8B.html)

[Roslyn 使用 Target 替换占位符方式生成 nuget 打包](https://blog.lindexi.com/post/Roslyn-%E4%BD%BF%E7%94%A8-Target-%E6%9B%BF%E6%8D%A2%E5%8D%A0%E4%BD%8D%E7%AC%A6%E6%96%B9%E5%BC%8F%E7%94%9F%E6%88%90-nuget-%E6%89%93%E5%8C%85.html)

[Roslyn 通过 NuGet 库修改应用程序入口函数](https://blog.lindexi.com/post/Roslyn-%E9%80%9A%E8%BF%87-NuGet-%E5%BA%93%E4%BF%AE%E6%94%B9%E5%BA%94%E7%94%A8%E7%A8%8B%E5%BA%8F%E5%85%A5%E5%8F%A3%E5%87%BD%E6%95%B0.html)

[Roslyn 让 VisualStudio 急速调试底层库方法](https://blog.lindexi.com/post/Roslyn-%E8%AE%A9-VisualStudio-%E6%80%A5%E9%80%9F%E8%B0%83%E8%AF%95%E5%BA%95%E5%B1%82%E5%BA%93%E6%96%B9%E6%B3%95.html)

[在 .NET Core 中使用 Microsoft.Build 包时缺少 SDK](https://blog.rsuter.com/missing-sdk-when-using-the-microsoft-build-package-in-net-core/)

### 问题排查
[[MSB4018] Could not load file or assembly "System.Runtime"...](https://stackoverflow.com/questions/73257163/custom-msbuild-task-net-6-0-runs-with-dotnet-but-not-in-vs)

由于自定义Task所在的项目是.NET Core版本，在vs中执行Task调用的是vs中自带的msbuild（在 .NET Framework 上运行），所以需要将Task所在的项目改成.NET Standard 2.0版本即可。

![image](https://github.com/chrisdaiii/msbuild/assets/67849861/4f4c3661-25f6-4c44-b429-5b20503a7d7d)


