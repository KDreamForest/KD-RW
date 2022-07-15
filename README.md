### DR-WR Readme
### ==================PROGRAMMER WANTED==================
In order to finish our project in CrossFire[CN].

We need more people to help us to finish the amazing work.

Our studio is located in China, but we welcome programmers from all over the world to contribute our work.
### ====================================================
#### What's this project?
This project is a simple project with a amazing kernel module driver. The driver can hide itself by using the function "MiProcessLoaderEntry", **It's a undocumented function. So if you want to use it in your own computer or other versions of Windows. You must get the base address of the function on your own.** Luckily, it's not too difficult. And I'm preparing to make a certain tool to get the base address of un-doc functions.
#### How can I use it?
I build this project with Visual Studio 2022.

Here is the list of SDK:
- Windows Driver Kit 10.0.22621.0 or Higher
- Windows SDK 10.0.22621.0 or Higher

In fact, you can build this project in lower versions of SDKs if you want. The project didn't use any new functions added in the new SDK.
#### Oh, I found some bugs!
It's normal that you can find some bugs in this project.
In fact I'm not good at kernel programing. So if you found some bugs,you can pull a request with fixed codes or email me at dreamforestmaple@gmail.com
#### Why I get a blue screen when I run this project?
After Windows 1809, the function "MiProcessLoaderEntry" can also trigger PatchGuard. If you want to run this project freely, you can try to some projects like [Shark](https://github.com/9176324/Shark) to kill PatchGuard.

===Enduring as the universe===