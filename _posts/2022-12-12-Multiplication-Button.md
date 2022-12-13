--- 

description: Multiplication Button
title: Multiplication Button
toc: false
comments: true
permalink: /markdown/multiply
categories: [week 16]
layout: post

---
<button id="enter" onclick="print(a,b)">MULTIPLY</button>
<p id="result"></p>
<script>
    function print(a,b) {
        document.getElementById("result").innerHTML = a * b
    }
    var a = 5
    var b = 5
</script>

```html
<!-- function is called here -->
<button id="enter" onclick="print(a,b)">MULTIPLY</button> 
<p id="result"></p>
<!-- javascript -->
<script>
    function print(a,b) {
        document.getElementById("result").innerHTML = a * b // math
    }
    // variables are defined
    var a = 5
    var b = 5

</script>
```

