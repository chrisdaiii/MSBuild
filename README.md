# MSBuild
MSBuild 学习资料

### 问题排查
[[MSB4018] Could not load file or assembly "System.Runtime"...](https://stackoverflow.com/questions/73257163/custom-msbuild-task-net-6-0-runs-with-dotnet-but-not-in-vs)

由于自定义Task所在的项目是.NET Core版本，在vs中执行Task调用的是vs中自带的msbuild（在 .NET Framework 上运行），所以需要将Task所在的项目改成.NET Standard 2.0版本即可。
![image](https://github.com/chrisdaiii/msbuild/assets/67849861/3204ca14-0b46-4e88-9885-0b03cb2fef6e)
