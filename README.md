# Guide to Kotlin

This tutorial assumes that all you know is Java, but you want to learn Kotlin.

Please note that the resources are in the [**wiki page**](https://github.com/Zhuinden/guide-to-kotlin/wiki).

# Table of Content

## Syntax Quirks

- [inverted argument order, no semi-colons, void vs Unit, Object vs Any?, fun](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Syntax-Quirks#inverted-argument-order-no-semi-colons-void-vs-unit-object-vs-any-fun)

- [interfaces with val, var and fun](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Syntax-Quirks#interfaces-with-val-var-and-fun)

- [constructors, inheritance](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Syntax-Quirks#constructors-inheritance)

- [lateinit vars](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Syntax-Quirks#lateinit-vars)

- [enum class](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Syntax-Quirks#enum-class)

- [final by default vs open](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Syntax-Quirks#final-by-default-vs-open)

- [for loops (in ranges, until)](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Syntax-Quirks#for-loops-in-ranges-until)

- [object for singleton](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Syntax-Quirks#object-for-singleton)

- [statics via companion object, const val](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Syntax-Quirks#statics-via-companion-object-const-val)

- [visibility in Kotlin (public by default, private, protected, internal)](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Syntax-Quirks#visibility-in-kotlin-public-by-default-private-protected-internal)

- [static nested class in Java vs inner class in Kotlin](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Syntax-Quirks#static-nested-class-in-java-vs-inner-class-in-kotlin)

- [backticks for reserved keywords (Mockito.when, $) and import aliases](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Syntax-Quirks#backticks-for-reserved-keywords-mockitowhen--and-import-aliases)

- [is instead of instanceof, as and as? for casting](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Syntax-Quirks#is-instead-of-instanceof-as-and-as-for-casting)

- [creating anonymous implementations for classes/interfaces](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Syntax-Quirks#creating-anonymous-implementations-for-classesinterfaces)

- [there is no condition ? true : false ternary operator](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Syntax-Quirks#there-is-no-condition--true--false-ternary-operator)

- [arrayOf and arrayOfNulls and listOf and mutableListOf and linkedMapOf](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Syntax-Quirks#arrayof-and-arrayofnulls-and-listof-and-mutablelistof-and-linkedmapof)

- [operator conventions (get() vs [], .equals() vs ==)](https://github.com/Zhuinden/guide-to-kotlin/wiki/1.\)-Syntax-Quirks#operator-conventions-get-vs--equals-vs-)

## Basic Kotlin Features

- [typed nullability, and null-safety operators (?., ?:)](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#typed-nullability-and-null-safety-operators--)

- [smart casting (and mutable vars gotcha)](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#smart-casting-and-mutable-vars-gotcha)

- [lateinit vars](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#lateinit-vars)

- [properties, backing fields](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#properties-backing-fields)

- [string interpolation and """multiline escaped ${strings}"""](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#string-interpolation-and-multiline-escaped-strings)

- [data classes](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#data-classes)

- [`when` keyword (and complex conditions, such as ranges)](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#when-keyword)

- [control statement as expression (assignment of `when`, `return`, ...)](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#control-statement-as-expression-assignment-of-when-return)

- [named arguments, default arguments](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#named-arguments-default-arguments)

- [vararg and the * spread operator](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#vararg-and-the--spread-operator)

- [interfaces and default implementation](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#interfaces-and-default-implementation)

- [generics (`<T: Blah>`, `in/out`, and star projection `<*>`)](https://github.com/Zhuinden/guide-to-kotlin/wiki/2.\)-Basic-Kotlin-Features#generics-t-blah-inout-and-star-projection-)

## The Cool Stuff

- [lambda types, trailing lambdas](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#lambda-types-trailing-lambdas)

- [method reference](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#method-reference)

- [`typealias`](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#typealias)

- [lambdas with receivers](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#lambdas-with-receivers)

- [extension functions, extension properties](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#extension-functions-extension-properties)

- [standard library functions - scoping functions: `apply`, `let`, `also`, `run`, `with`](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#standard-library-functions---scoping-functions-apply-let-also-run-with)

- [standard library functions - more utility functions: `takeIf`, `takeUnless`](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#standard-library-functions---more-utility-functions-takeif-takeunless)

- [`tailrec` keyword](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#tailrec-keyword)

- [`inline` functions (`crossinline`, `noinline`)](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#inline-functions-crossinline-noinline)

- *[a glance at the Collections API](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#a-glance-at-the-collections-api) ([see API here](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/index.html#functions))

- [`inline fun <reified T>`](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#inline-fun-reified-t)
  
- [`sealed` classes](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#sealed-classes)

- [`infix` keyword](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#infix-keyword)

- [tuples (`to`) and destructuring](https://github.com/Zhuinden/guide-to-kotlin/wiki/3.\)-The-Cool-Stuff#infix-keyword)

## The Tricky Stuff

- [*extension operators (`componentN`)](https://github.com/Zhuinden/guide-to-kotlin/wiki/4.\)-The-Tricky-Stuff#extension-operators-componentn)

- [*property delegates (and built-in ones: `lazy`, `observable`/`vetoable`, `by map` for configurations via `Map<String, Any?>`)](https://github.com/Zhuinden/guide-to-kotlin/wiki/4.\)-The-Tricky-Stuff#property-delegates-and-built-in-ones-lazy-observablevetoable-by-map-for-configurations-via-mapstring-any)

- [delegation by class](https://github.com/Zhuinden/guide-to-kotlin/wiki/4.\)-The-Tricky-Stuff#delegation-by-class)

- [*JVM annotations: `@JvmOverloads`, `@JvmField`, `@JvmSuppressWildcards`, `@get:` and `@set:` and `@field:`](https://github.com/Zhuinden/guide-to-kotlin/wiki/4.\)-The-Tricky-Stuff#jvm-annotations-jvmoverloads-jvmfield-jvmstatic-jvmsuppresswildcards-get-and-set-and-field)

## Android-Specific Stuff

- [synthetic view accessors with kotlin android extensions](https://github.com/Zhuinden/guide-to-kotlin/wiki/5.\)-Android-Specific-Stuff#synthetic-view-accessors-with-kotlin-android-extensions)

- [`@Parcelize data class` with experimental kotlin android extensions](https://github.com/Zhuinden/guide-to-kotlin/wiki/5.\)-Android-Specific-Stuff#parcelize-data-class-with-experimental-kotlin-android-extensions)

## Stuff that needs to be added or more fleshed out in this tutorial

- coroutines?

- channels?

- @DslMarker?

- multi-platform things: `expect` and `actual`?

# Feel like donating?

If you feel like this project helped you *so much* that you would have wanted to pay for it or something, I won't get in your way, and appreciate your support.

## PayPal 

* **[Donate €5](https://www.paypal.me/Zhuinden/5)**

# License

    Copyright 2018 Gabor Varadi

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
