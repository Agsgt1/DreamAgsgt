# DreamAgsgt
DreamAgsgt is a version of Dreamberd which is owned by the Agsgt Foundation, here are some scripts for the language, also this is fake so im trying to make the functions (demo only bcz idk how to make complex functions). <br>
The text marked with a "*" is a copy or a same script of the Dreamberd language<br>

## If
If is a function which if its input is true, the then output is true, if not, the script excecutes the scripts after the if script, or if it has a *else* counterpart, it runs it <br>
```java
if <score = 5> {
  var score = score - 5
}
```

## We
We is a statement randomness, it is complex and may have a table for it, here it is:

|A|B|Out|
|-|-|---|
|F|F|F  |
|F|T|F  |
|T|F|T  |
|T|T|T  |

And i cant froget about the example!
```java
print(We(True, False)) //True
```

## Lifetimes*
Lifetimes are a toggler that makes a duration for scripts, they can be positive by lines or seconds by the example below
```java
print<2l>("I last for 2 lines!") //I last for 2 lines!
print<10s>("I last for 10 seconds!") //I last for 10 seconds!
```
Or they can be negative
```java
var text = "I may last after my creation..."
print<-1l>(text) //I may last after my creation...
```

## We're
We're is a copy of **We**, with the difference that it is more advanced than We and has more inputs and outputs.

|A|B|C|Out|Qwery|
|-|-|-|---|-----|
|F|F|F|F  |F>T  |
|T|F|F|F  |F>T  |
|T|T|F|?  |F=T  |
|F|T|F|F  |F>T  |
|T|F|T|?  |F=T  |
|F|T|T|?  |F=T  |
|F|F|T|F  |F>T  |
|T|T|T|T  |F<T  |

```java
print(We're(T,T,T)) //[True, Qwery: False < True]
```

## Function*
Makes a function with every letter of the word function (only if they are in order)
```java
function (add(a,b)) {return a + b}
funti (sub(a,b)) {return a - b}
i (mult(a,b)) {return a * b}
funi (div(a,b,)) {return a / b}
```

## Rich text*
More complex text, used for links and stuff
<pre>
  print("<b>Wow!</b>") //<b>Wow!</b>
</pre>

## HTJS*
HTJS is a script that turns from JavaScript into HTML
```java
HTJS.run{
<h1>HTJS script</h1>
}
```
It has a lot of variants:
```java
print(HTJS.htmltotext(
<h2>What am i doing here?!?</h2>
)) //What am i doing here?!?

HTJS.functionHTJS <hn "size"=1-6> {
<HTJS.headersize (size)>
}
```

## Youtube
Uses youtube search query to play on a window
```java
Youtube.play(Youtube.search("Reaction Reaction"))
```
### Youtube: Extras
You can even use Youtube search query to search in your browser! Spoiler: it has another command comming up next!
```java
let searchYT = Youtube.search("@AngelThe4th")
Browser.search(searchYT)
```

## DreamlyBerd
An giant extension with most of DreamBerd commmands!<br>
Import:
```java
import ("DreamlyBerd")
```
Note: it has a premium version and you can buy it like this:
```java
DreamlyBerd.PremiumBuy()
```
it enables all of the DreamBerd commands!

##

## Comming soon....
Some new scripts are comming soon, make sure to watch this project! (2/7)
