
<div>
<h6>Chapter 0002</h6>
<hr style="height:2px;border-width:0;color:#606D7E;background-color:#606D7E">
</div>
</br>
</br>
</br>

<div>
    <h1 border-bottom='1px' >Basic types</h1>
</div>

<p>
All languages need to have built in types.Types are used to represent values.
Some examples are number, Boolean,characters and String.

* numbers(Int, Long, Double, Float Short, Byte)
  - In numbers depends which your choose this determines the size(bits) of the number, min value and max value.
     - Int .- 32:bits, min:-2,147,483,648, max:2,147,483,647
     - Long .- 64:bits, min:-9,223,372,036,854,775,808, max:9,223,372,036,854,775,807
     - Short .- 16:bits, min:-32768, max:32767
     - Byte .- 8:bits, min:-128, max:127
    
* boolean(Boolean)
* characters(Char)
* string(String)

</p>

<div>
    <img align="left" height="13px"  src="../../assets/kotlin/kotlin.svg"/>
    <img align="right" height="30px"  src="../../assets/kotlin/mascot.svg"/>    
</div>


<br>

<p>
For declare this basic types we need to use val or var word. 
 
 - Val("value").- read-only you cannot modify the value
 - Var("variable").- read-write you can modify the value
</p>
<p>
This way allow create types. Without declare Int,Long...
</p>

<table bgcolor="#7B5FCD"><tr><td> <a color='#ffffff' href="https://play.kotlinlang.org/#eyJ2ZXJzaW9uIjoiMi4wLjAiLCJwbGF0Zm9ybSI6ImphdmEiLCJhcmdzIjoiIiwibm9uZU1hcmtlcnMiOnRydWUsInRoZW1lIjoiaWRlYSIsImNvZGUiOiJmdW4gbWFpbigpIHtcbiAgICBwcmludChcIkhlbGxvLCB3b3JsZCEhIVwiKVxufSJ9">
  <font color="white"><i>&#9654;</i> Run </font>
</a></td></tr><table>
<h6>VAL</h6>

```kt
fun main() {
    val a1 = 1
    a1 = 2
    print(a1)
}
```

```diff
- 'val' cannot be reassigned.
```
<h6>VAR</h6>

```kt
fun main() {
    var a1 = 1
    a1 = 2
    print(a1)
}
```

```
2
```
<h6>INTEGER</h6>

```kt
fun main() {
    val a1 = 1
    val a2:Int = 1
    print(a1)
    print(" is ")
    System.out.println(a1.javaClass.name)    
    print(a2)
    print(" is ")
    System.out.println(a2.javaClass.name)
}
```
```
1 is int
1 is int
```
<h6>LONG</h6>
This case the compiler interpret you don't need a number long and this assing the type Int.

```kt
fun main() {
    val a1 = 1
    val a2:Long = 1
    print(a1)
    print(" is ")
    System.out.println(a1.javaClass.name)    
    print(a2)
    print(" is ")
    System.out.println(a2.javaClass.name)
}
```

```
1 is int
1 is long
```


