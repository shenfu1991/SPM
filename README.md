# SPM



创建项目

<pre>
$ mkdir MyLib    
$ cd MyLib         
$ swift package init	//初始化包，不带参数的话默认是Library
Creating library package: MyLib
Creating Package.swift
Creating README.md
Creating .gitignore
Creating Sources/
Creating Sources/MyLib/MyLib.swift
Creating Tests/
Creating Tests/LinuxMain.swift
Creating Tests/MyLibTests/
Creating Tests/MyLibTests/MyLibTests.swift
</pre>


生成Xcode工程
<pre>
swift package generate-xcodeproj
</pre>

编译、运行项目
<pre>
swift build
swift run
</pre>

ubuntu上安装swift，设置路径
<pre>
$ export PATH=swift文件夹路径/usr/bin:"${PATH}"
</pre>
