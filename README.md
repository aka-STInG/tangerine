Tangerine
=========

Tngerine is a tool for inspecting Windows Phone applications. Based on [XAPSpy](http://github.com/sensepost/xapspy). It allows you to do three things:

 - Automate all routine work with XAP files (parsing, deploying etc.)
 - Log method calls, including parameters values and return values
 - Run your own code on method enter, on method exit or instead of a method
 - Change parameters values using method code

Current limitations on functions for instrumentating:
 - does not support functions with user types (e.g. custom type Product)
 - does not support out parameters
 - does not support method overloads

Currently supports Windows Phone 7 applications only. Support for Windows Phone 8 applications is coming soon!

Minimum requirements: .NET Framework 4.0, Windows Phone SDK 7.0

More detailed documentation will be uploaded.

Contributors:
* Andrey Chasovskikh
* Evgeny Bechkalo
* Dmitriy Evdokimov
