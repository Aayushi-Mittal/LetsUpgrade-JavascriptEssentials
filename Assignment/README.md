## Question 1
By how many ways we can access elements in the DOM and write about them in brief?
### Solution
```
we can access elements in DOM using their tag name, id name and class name.
For eg:
    - document.querySelector(p) //selector for tags
    - document.querySelector(.class) //selector for class
    - document.querySelector(#id) //selector for id
```

## Question 2
Write a javascript program that will take 2 numbers from the HTML page and display them on the
HTML page after the addition of those 2 numbers.
### Solution

📁 index.html
```
<html>
<head>
<title>Add two numbers!</title>
</head>
<body>
  <p></p><input type="number" id="num1">
  <p></p><input type="number" id="num2">
  <button onclick="add()">Add</button><input id="ans">
  
  <script>
    var num1=document.querySelector(#num1).value;
    var num2=document.querySelector(#num2).value;
    add(num1, num2)
    {
      var sum=num1+num2;
      document.getElementById("ans").value= sum;
    }
  </script>
</body>
</html>
```
