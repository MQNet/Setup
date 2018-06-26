# Setup Programming Enviroment for .NET programming MacroQuest

## First Thread Introducing .NET / C# Plugin and "Program" API

https://www.redguides.com/forums/threads/65606-NET-C-Plugin-and-quot-Program-quot-API

1. Download Visual Studio (2017) Community
  * https://visualstudio.microsoft.com/ -> Visual Studio IDE
  * Select .net development when installing (other options up to you)
  * Launch Visual Studio 
  * Register for Microsoft Account if you do not have one (including passing CAPTCHA)
  * Upon Sign In choose C# Enviroment and color scheme of your choice
  * New Project -> Class Library(.NET Standard (Framework adds more cruft but should work too))
  * Project -> Add Reference MQ2DotNet.dll ONLY! NetLoader is not needed at this step
  * Write Your program per example given in OG thread
  * Build Solution as Release
  * copy from project/bin/release all .dll files to /MQ2/Release folder
  * also copy MQ2DotNetLoader.dll to same  /Release
  * Load EQ instance and MQ2
  * /plugin mq2dotnetloader
  * /netrun MyProg (omit .dll extension)
