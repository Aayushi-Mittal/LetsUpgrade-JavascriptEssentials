## Question 1
What is the value of clothes[0] and why?
const clothes = ['jacket', 't-shirt'];
clothes.length = 0;
console.log(clothes[0]);

### Solution
```
undefined
```

## Question 2
Write a Javascript program to find the sum of all elements of a given array?

### Solution
```
var arr=[1,2,3,4,5,6,7,8,9,0], sum=0;
for(var i=0; i<arr.length; i++)
{
  sum+=arr[i];
}
console.log(sum);
```
