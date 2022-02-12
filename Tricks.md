### Pair trick
So Pair is a class in java that contains key and value, so the class is
## import javafx.util.Pair;
we can use pair as - Pair < key, value > name
here name is a variable.
example = Pair < Integer, Integer > ans
there are two function to get key and value
1. getValue()
2. getKey()
Application:
swapping of two values -
## code
Pair < Integer, Integer> result = new Pair(value2.getValue(), value1.getKey());
return result;

### what is floor in java?
floor is used to round off kind, it is easy but not easy to explain I will give you example:
int x = 39.34
if we do floor using - Math.floor(x)
then it return 40.0.
if typecasting to int the above result will be - 40 onlys
Instead for Math.floor() we can typecast to Int...result will be same if we don't need decimal part.

### function for rounding off the decimal
Math.round()
example - x = 67.89
if we use round function Math.round(x) - this will give us 67 only.

### instead of finding even number till n
What we can do is in for loop we can increment the variable by 2
example - for (i=0; i<n; i+=2){
}
so now the variable will point to only even number
