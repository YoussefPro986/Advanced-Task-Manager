# Advanced Task Manager

Advanced Task Manager is a program similar to Task Manager integrated with Windows. The program performs the same process, such as closing applications that do not respond and displaying processor and RAM consumption. 

Introduction
All people who are working on any version of the Windows operating system know about Task Manager. They might be using it very frequently to start, end or manage processes. Task Manager has been around for a long time and is commonly used in our daily work. However, it is still lacking some features which might be useful in certain situations. So, I designed this application to provide features which are not present in the built-in Windows Task Manager. This application was created in VS.NET 2003 using C# and Windows Forms.

![AdvancedTaskMgr32](https://user-images.githubusercontent.com/72635460/132960418-c90068b9-87b8-4dd5-afd1-4a2305975408.PNG)

In this article, I will first explain some features present in the application, and then I will discuss its design and coding.

Task Manager features

This application...

Displays all processes running in your system
Allows you to add and remove any process (task) on your local machine
Highlights current executing processes
Enables connection to any machine and displays its process list
Allows you to set or get the priority of any process running on your local machine
Enables monitoring of .NET CLR managed memory
Creating the application
First, create a new Windows Application in VS.NET 2003 using C# and name it CustomizedTaskManager. Then design the main start-up form as shown below:
