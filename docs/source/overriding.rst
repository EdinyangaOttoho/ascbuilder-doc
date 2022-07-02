.. _overriding:

Overriding Default Methods
==========================

At default, there are two methods that are defined when a user opts in and when the application is created.

These two methods are :code:`OptIn()` and :code:`OnCreate()` respectively.

The default action in these routes is :code:`Approve()`, when there are no states or definitions to override them.


When a Global State is added (via Global state component), it is due to be created upon application creation.

Once that is set, the application creates them upon deployment.

Nevertheless, the behaviours for the scenarios of opt in and creation can be altered by creating methods, :code:`OptIn()` and :code:`OnCreate()` and adding nodes that should perform the intended functions.

Likewise, the behaviour of the clear Program can be altered by creating a :code:`clearProgram()` method and adding nodes to it.

Once these methods are created, the default :code:`Approve()` return value would be overriden in the Pyteal source code result returned.