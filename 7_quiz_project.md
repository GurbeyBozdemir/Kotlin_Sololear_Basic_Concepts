```Kotlin
/**
 * 7-Quiz + Code Project: Water Consumption
*/
var x = readline()!!:toInt()
var y = readLine()!!.toInt()
println(x*y)

//aşağıdaki kodun çıktısı nedir?
var x = 4
x *= 2
x -= 3
x++
println(x) //6

//Water Consumption
//Bir aile her gün 15 litre su tüketiyor. Girilen yıl sayısı boyunca ailenin tüketeceği su miktarını
//hesaplayan bir program yazınız. Örnek girdi: 5, örnek çıktı: 27375 (5 * 365 * 15 = 27375)

fun main (args: Array<String>) {
    var years = readline()!!.toInt()
    var total = years*365*15
    println(total)
}
```
