# daolayer 5.35 (23 april 2016)
A dao layer over JPA. With this library, you work with objects and lists of objects. No sql. Select queries can be made with a Search or Search2 object.

You can download and open this project in NetBeans 8.1. It's a Java 8 maven project. So, dependencies are loaded automaticly from maven central. There are some test classes where you can learn how to use this library.

In MacOS terminal or Windows console, you can start the "test" suite with a Maven command :

mvn test

Project documentation here :
http://jcstritt.emf-informatique.ch/doc/daolayer<br>

New in release 5.35 :
* updateList(...) in JpaDaoAPI now returns an integer Array : [0]=number of updated objects, [1]=number of added objects
