--- 

description: Division Button
title: Division Button
toc: false
comments: true
permalink: /markdown/division
categories: [week 16]
layout: post

---

### SUBTRACTION

<button id="enter" onclick="print(c,d)">DIVISION</button>
<p id="result"></p>
<script>
    function print(c,d) {
        document.getElementById("result").innerHTML = c / d
    }
    var c = 5
    var d = 5
</script>

```html
<!-- function is called here -->
<button id="enter" onclick="print(c,d)">MULTIPLY</button> 
<p id="result"></p>
<!-- javascript -->
<script>
    function print(c,d) {
        document.getElementById("result").innerHTML = c / d // math
    }
    // variables are defined
    var c = 5
    var d = 5

</script>
```





