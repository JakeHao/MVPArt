# MVPArt
[ ![Bintray](https://img.shields.io/badge/bintray-v2.1.0-brightgreen.svg) ](https://bintray.com/jessyancoding/maven/MVPArt/2.1.0/link)
[ ![Build Status](https://travis-ci.org/JessYanCoding/MVPArt.svg?branch=complete) ](https://travis-ci.org/JessYanCoding/MVPArt)
[ ![API](https://img.shields.io/badge/API-15%2B-blue.svg?style=flat-square) ](https://developer.android.com/about/versions/android-4.0.3.html)
[ ![License](http://img.shields.io/badge/License-Apache%202.0-blue.svg?style=flat-square) ](http://www.apache.org/licenses/LICENSE-2.0)
[ ![QQGroup](https://img.shields.io/badge/QQ群-301733278-ff69b4.svg) ](https://shang.qq.com/wpa/qunwpa?idkey=1a5dc5e9b2e40a780522f46877ba243eeb64405d42398643d544d3eec6624917)

[中文说明](README-zh.md)

## A New Android MVP Architecture
**This framework is designed to solve the traditional **MVP** class and interface too much, and **Presenter** and **View** communicate too complicated through the interface, reuse **Presenter** too much cost**


## Architectural
<img src="https://github.com/JessYanCoding/MVPArt/raw/master/image/Architecture.png" width="80%" height="80%">

## Introduction
> [**Master** Branch](https://github.com/JessYanCoding/MVPArt/tree/master)
>> **Master** branch is a simple framework without network layer, mainly through the four **Demo** introduced the framework of the ideas, features and use of methods, compact and flexible has a set of existing framework but need to refactor For **MVP** structure of the project, but no matter which branch you are using is strongly recommended that you first look at **Master** branch **Demo**
  
> [**Complete** Branch](https://github.com/JessYanCoding/MVPArt/tree/complete)
>> **Complete** branch is a complete framework with a network layer, **Retrofit** as a network layer and use **Dagger2** to manage all objects, mature and powerful for new projects

## Notice
* This framework is a lightweight framework, more suitable for small and medium-sized projects, large-scale projects please use [MVPArms](https://github.com/JessYanCoding/MVPArms)

* Traditional MVP corresponds to a **Presenter**, and most **Presenter** has only one or two methods, which leads to the existence of a large number of very few tags **Presenter**, this framework is designed to solve the reuse **Presenter** need to achieve too many redundant interface method, encourage developers to write similar logic in a **Presenter**, constantly reuse **Presenter**, reduce a large number of class files
* Of course, many different logic is written in a **Presenter**, although you can write a lot of classes, but behind the expansion is certainly not good, so the size of their own control, but for the outsourcing project is very useful


## Download
``` gradle
 compile 'me.jessyan:art:2.1.0'  //rxjava2

 compile 'me.jessyan:art:1.4.3' //rxjava1(Not maintained)
```

## About Me
* **Email**: <jess.yan.effort@gmail.com>  
* **Home**: <http://jessyan.me>
* **掘金**: <https://gold.xitu.io/user/57a9dbd9165abd0061714613>
* **简书**: <http://www.jianshu.com/u/1d0c0bc634db>

## License
```
 Copyright 2017, jessyan

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```
