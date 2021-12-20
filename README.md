object Hello{
    def main(args: Array[String]){
        val sen=scala.io.StdIn.readLine()
        var n=sen.length()
        if(n<4)
        println("in upper case "+sen.toUpperCase())
        else
        println("in upper case "+sen.takeRight(4).toUpperCase())
    }
}
