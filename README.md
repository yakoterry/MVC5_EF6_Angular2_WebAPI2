#  Single Page Application Using Pro MVC5 EF6 Angular2 WebAPI2 Tutorial


## Contents at Glance

* [About starting this tutorial](#start)
* [Create your first application](#create)



## <a name="start">About Starting this Tutorial


>### What Do I Need to Know?

>To get the most from this tutorial, you should be familiar with the basics of web development, have an understanding of how HTML and CSS work
and a working knowledge of C# and Javascript. Don't worry if you are a beginner, there are a lot of examples and I will introduce step by step from sever-side to client-side.


>### What Is the Structure of This Tutorial

>This tutorial is split into 2 parts, each of which covers a set of related topics.

>#### Part 1:Server-Side Development

>I start this tutorial by creating a real online store single page application so that you know how to create, update database in sql sever by using Code
First Pattern in EntityFramework 6. And also you will touch on major features of  the ASP.NET MVC Framework and WebAPI2.

>#### Part 2:Client-Side Development

>In Part2, I explain how to bind angular with ASP.NET MVC5 and WebAPI2 so that you can success in creating a Single Page Application. Furthermore, I will
also show you how each feature works in angular, explain the role and guide it play in client side.


>### What Software Do I Need for This Book?

>The only software you need for this tutorial is Visual Studio 2015, which contains everything you need to get started; An administration-free editon of Sql Sever 2012 or above;
node.js for getting the latest Angualr 2.
There are several different versions [Visual Studio Downlaod]("https://www.visualstudio.com/downloads/"), each of them would work fine. Once you have installed Visual Studio
,Sql Sever,NodeJs, you are ready to go.

>### Summary
>In this chaper, I explained the structure of this tutorial and the software that you will require to follow the examples.
    In next chaper, you'll see how to start a project in a expandable way.


## <a name="start">Create Your First Application


>### Create a Blank Solution
>Select ***New Project*** from the ***File*** menu to open the ***New Project*** dialog. If you select the ***Installed*** and open ***Other Project Types***. You 
will see the ***Blank Solution*** project.Select this project type. As shown in below

>![Figure 1](http://img.blog.csdn.net/20160926133130631?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center)


> Set the name of the solution to **Tutorial** and click the ***Ok*** button to continue.Then, right click the Solution in Solution Explorer, Select ***Add*** and click
on ***New Project***. As shown in below

>![Figure 2](http://img.blog.csdn.net/20160926133235569)

>You are seeing the New Project dialog again, this time please select ***Web*** Template, you will see the ***ASP.NET Web Application*** project template. Select this project
type as shown in below

>![Figure 2](http://img.blog.csdn.net/20160926115607728)

>Set the name of the project to **WebUI**, it will contains all the features of MVC and Angular we use for online store. Click the ***OK*** button to continue. You will see
another dialog box, shown in below, which asks you to set the initial content for ASP.NET project.To keep things simple and tell you the knowledge from beginning:select the
***Empty*** option and check the ***MVC*** box in the ***Add folders and core references*** section, as shown in the figure.This will create basic web application which
contains MVC5 reference.Click the ***OK*** button to create the new project. 
