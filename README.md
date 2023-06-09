# Android Dev Notebook
### Description
This is a personal notebook where I keep track of my learnings and insights on various Android topics. It is meant to serve as a reference for my own future projects and to help me improve my skills as an Android developer.


### Table of Contents

- [Native Android](#native-android)


# Native-Android

### Advance Kotlin: 

* Lazy vs Lateinit 
    * lazy and lateinit are both used to delay the initialization of a variable in Kotlin, but they work in slightly different ways. So sometimes it becomes confusing which one should be used based on different use cases. 
    [Medium Blog](https://medium.com/huawei-developers/kotlin-lateinit-vs-by-lazy-initialization-example-tutorial-c19d84216480)

* Courotines
    * Different ways of handling Couroutine and the best practice.  [Medium Blog](https://medium.com/bobble-engineering/best-practices-using-coroutines-in-kotlin-31f19247ccd3) 
    
* WorkManager
    * Schedule task based on mobileNetwork, Battery percentage, etc. workmanager is the best solution. You can set OneTimeTask and Periodic task both with workmanager which will be executed whenever the requirements constraints match. [Medium Blog](https://androidgeek.co/getting-started-with-workmanager-beginner-in-depth-guide-8817df1ff7b)  [Youtube](https://www.youtube.com/watch?v=sHE5hjxznlI&ab_channel=AndroidGeek)

* Sealed Class
    * If you've ever felt the extension of Enum Class to take multiple state in the constructor or change the values ,then Sealed class is the solution. Also Sealed class provides abstraction in the same file only. [Read in Details.](https://blog.mindorks.com/learn-kotlin-sealed-classes/)
