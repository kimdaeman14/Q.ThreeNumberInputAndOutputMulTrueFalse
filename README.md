# Q.ThreeNumberInputAndOutputMulTrueFalse


## *세 수를 입력받아 세 수의 곱이 양수이면 true , 음수이면 false 반환하는 함수*

````
func inputThreeNubmer(fir :Double, sec:Double, thi : Double) -> Bool {
    var total = 0.0
    total = fir * sec * thi
    if(total>0){
        return true
    }else{
        return false
    }
}
inputThreeNubmer(fir: 1, sec: 2, thi: 3)
inputThreeNubmer(fir: -1, sec: 2, thi: 3)
inputThreeNubmer(fir: 1, sec: -2, thi: -3)
inputThreeNubmer(fir: 134.4, sec: 22.1, thi: 3)
inputThreeNubmer(fir: -1, sec: 223.1, thi: 3)
`````

````
func checkNegative(_ num1:Int,_ num2:Int,_ num3:Int)->Bool{
    var isTrue = true

    if (num1*num2*num3)>=0{
        isTrue=true
    }
    else{
        isTrue=false
    }
    return isTrue
}

checkNegative(15, -15, -15)
````

````
func mulFn(_ num:Int , _ num2:Int , _ num3:Int)->Bool{
    var sum = 0
    sum = num * num2 * num3
    return sum > 0 ? true : false
}
mulFn(1,2,1)
````
