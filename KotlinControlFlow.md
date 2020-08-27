# Kontlin-Control-Flow

# Enumeration

    fun main (){
    val color : Color = Color.RED
    }
    enum class Color{
        RED,GREEN, BLUE
    }

# When Expressions
    fun main (){
    val value = 7

    when (value){
        6 -> println("value is 6")
        7 -> println("value is 7")
        8 -> println("value is 8")
    }
    }
    
# Expressions and Statment
    fun main (){
    val value1 = 10
    val value2 = 10
    sum(value1, value2)
    }
    fun sum(value1: Int, value2: Int) = value1 + value2
    
# While and Do While
    fun main(){
    var counter = 1
    while ( counter <= 7) {
        println("Amalia Bahari")
        counter++
    }
    }
    
# Range
    fun main(){
    val rangeInt = 1..10
    print(rangeInt.step)
    }
    
# Foor Loop
    fun main  (){
    val ranges = 1..5
    for ( i in ranges){
        println("value is $i!")
    }
    }
    
# Break and Continue
    fun main (){
    val listOfInt = listOf(1,2,3, null,5, null, 7)
    for ( i in listOfInt){
        if (i == null) continue
        print (i)
    }
    }

