```Kotlin
/**
 * 6-Input
 * Kullanıcı inputu readline() fonksiyonu kullanılarak alınır.
 */
var age = readline()
println("You entered " + age) 

var name = readline()
println(name)

//readline() fonksiyonu, inputu string olarak alır.
//Örneğin inputu int olarak almak için toInt() fonksiyonu kullanılır.
//aşağıdaki ifade 2 adet int alır ve toplamlarının çıktısını verir.
var a = readline()!!.toInt()
var b = readline()!!.toInt()
println(a+b)

//toInt() fonksiyonunun doğru çalışması için !! ifadesi kullanılır.
//bu ifade solundakinin null olmadığını, geçerli bir değer almak zorunda olduğunu ifade eder.
var height = readline()!!.toDouble()
```
