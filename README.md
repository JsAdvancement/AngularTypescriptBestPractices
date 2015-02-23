# AngularTypescriptBestPractices
Fostering best practices in Angular projects using Typescript.

## Why Typescript?
Let's make ES6 our reality now. It's coming, so lets use it now. A year from now, how many of us will be still writing JS ES5 code? Let's lead! Not Folow.

_Frameworks come and go in Javascript land._ *The only thing that you can be sure about coming is Javscript ES6.*

## 10 Reasons to start using Typescript now

1) Typescript is opensource. Yes, Microsoft created it, but you can fork the source on [github](https://github.com/Microsoft/TypeScript)

2) Start using the next version of javascript ES6, today in fairly mature 1.4+ version language. The ES6 language adds features such as modules and classes. Typescript will track the emerging ES6 standard and add those features as they become solid.

3) Typescript is a superscript of javascript so you can begin to use it incrementally. The first step can be to change *.js to *.ts and immediately see the benefits of some internal type checking.

4) Typescript produces idiomatic javascript without any need for runtime libs. So it you want to ditch typescript you can and just start using the javascript files it produces. It does the type checking on the compile step so no extra code is added. [ES6 transpilers like traceur require a runtime lib as well]

5) Type safety. Typescript has an optional typesafety feature so that if you only want typesafe signatures on the public apis then you only pay that price on the public API.

6) Get the benefits of a nice syntax like Coffeescript, but with type checking and the emerging standard ES6 syntax as well

7) Typescript works well with all of your existing javascript libraries. Want to do just a few modules in Typescript and have it integrate with your existing codebase” no problem. [This is more difficult to do with Dart]. Actually, because Typescript is a superset of javascript, it makes it possible to cut-n-paste existig javascript solutions.

8) If you are coming from languages like java or C#, then familiar design patterns (like GoF) fit right in instead of having to learn the all the javascript design patterns (many of which rely upon closures for modularity).

9) Its framework agnostic use it with whatever framework you want *Typescript don't care its a Honey Badger*. And the code it produces is idiomatic javascript.

10) Use whatever tooling you want. It is just a command-line compiler. Grunt, Gulp whatever... Want full ide support use WebStorm or Visual Studio (they have intelligent support for Typescript). Want something lightweight use Sublime Text (there are Typescript plugins available as well).
