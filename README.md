MvvmCross Binary
================
This is the binary build of MvvmCross from https://github.com/kennethxu/MvvmCross/tree/v3. 
Only Portable, MonoTouch, MonoDroid and WindowsPhone libraries are built here. For other platform,
check out https://github.com/slodge/MvvmCross-Binaries.

This one set of libraries can compile and run all tutorial applications starts with "Sample - " 
from https://github.com/kennethxu/MvvmCross-Tutorials. Tested to work with both Xamarin Studio 
(Mac and PC) and Xamarin for Visual Studio.

Libraries depended by MvvmCross are not included here. You'll need MonoPortable 
libraries that you can find in MonoPortable branch in this repository. You may also need Newtonsoft.Json
, C# Sqlite For WP7 and System.Windows.Interactivity which are not included here.

MonoPortable (https://github.com/kennethxu/binary/tree/MonoPortable) to run MonoTouch or MonoDroid apps.

C# Sqlite For WP7 (http://wp7sqlite.codeplex.com/releases/view/58167) for WindowsPhone uses SQLite. NuGet: https://nuget.org/packages/wp7sqlite/

Json.NET (http://james.newtonking.com/projects/json-net.aspx) for JSON support. NuGet: http://nuget.org/packages/Newtonsoft.Json/