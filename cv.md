# DENIS BORNEMAN

# 

## **City**: Tomsk
## **Contacts**
### [Email](mailto:chainsawfish@gmail.com)
### **Discord**: chainsawfish#5802

## **About me**
I want to learn as much languages as I like and can. I like my two bold cats and my wife. I teach kids for learn math.

## **Hard skills**
I know **java, swift, javascript** and some other languages as well.


## **Code examples**

[Codewars](https://www.codewars.com/kata/reviews/5264d41ce218b86cb90000df/groups/6298d041384c780001fb3fbd)
```
function revers(text){
    let reversStr = ""
    for (let i=text.length-1; i>=0; i-=1){
        reversStr += text[i]
    }
    return reversStr
}



function spinWords(string){
    let newArr = []
    let arrStr = string.split(" ")
    for (let i = 0; i<arrStr.length; i+=1){
        let word = arrStr[i]
        if (word.length > 4) {
            newArr.push(revers(word)) 
            
        }
        else {
            newArr.push(word)
        }
    }

    return newArr.join(" ")
}

 console.log(spinWords("Hello my name is"))
=======

## Contacts
### [Email](mailto:chainsawfish@gmail.com)
### **Discord**: chainsawfish#5802

## About me
I want to learn as much languages as I like and can. I like my two bold cats and my wife. I teach kids for learn math.

## Hard skills
I know **java, swift, javascript** and some other languages as well.


## Code examples

Самая сложная буква в наборе (Swift) (yandex task)
```
import Foundation

var n: Int = Int(readLine()!)!
var str: String = readLine()!
var hardness: String = readLine()!

//var n = 5
//var str = "aabbc"
//var hardness = "1 3 5 7 8"

var maxIndex : Int = 0
var maxLetter: String = ""

var hardnessArray = hardness.components(separatedBy: " ")
    .map{Int($0)!}

var strArray = Array(str).map{String($0)}


var speedArray = [String: Int]()

for i in 0..<strArray.count {
    if i != 0 {
        speedArray[strArray[i]] = hardnessArray[i]-hardnessArray[i-1]
        
    }
    else {
        speedArray[strArray[i]] = hardnessArray[i]

    }
    if speedArray[strArray[i]]! >= maxIndex {
        maxIndex = speedArray[strArray[i]]!
        maxLetter = strArray[i]
    }
    
}


print(maxLetter)

```




## **Education:**

**Tomsk State Pedagogical University**, ___faculty of computer Science and mathematics___, teacher of cs and math \ 2005-2011

**English:** Intermediate 
