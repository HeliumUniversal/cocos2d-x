# cocos2d-x
Helium's Cocos2d headers

This api contains headers of Cocos2d for using with Geometry Dash, that i use in my own toolchain, so it can be compatible to work with the [framework](https://github.com/HeliumUniversal/framework).

# Usage

Create a DLL Project on Visual Studio Community 2019

Download the latest version and unzip it (in my case i unzip it on a folder called Libs in my project)

Add those Include directories to the project 
``` $(SolutionDir)Libs\cocos2d-x\cocos
$(SolutionDir)Libs\cocos2d-x\cocos\include
 $(SolutionDir)Libs\cocos2d-x\cocos\kazmath\include
  $(SolutionDir)Libs\cocos2d-x\cocos\platform   

$(SolutionDir)Libs\cocos2d-x\cocos\platform\win32
$(SolutionDir)Libs\cocos2d-x\cocos\platform\third_party                                           
$(SolutionDir)Libs\cocos2d-x\cocos\platform\third_party\win32
$(SolutionDir)Libs\cocos2d-x\cocos\platform\third_party\win32\OGLES
$(SolutionDir)Libs\cocos2d-x\extensions
```

But if you have the framework in your project, read the framework wiki

For using this api you need:

Knowledge of hooking, of C++ and Cocos

Visual Studio Community 2019

Geometry Dash 2.113

                                       
                       
          
                  

