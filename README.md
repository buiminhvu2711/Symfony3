# Symfony3
https://www.codereviewvideos.com/course/symfony-3-for-beginners/video/creating-the-login-form

# Change Image infinite time after 1s (1000)

<script>
function myFunction() {
    document.getElementById("myImg").src = "hackanm.gif";
    setTimeout(myFunction2,1000);
} 
function myFunction2(){ 
  document.getElementById("myImg").src = "compman.gif";
  setTimeout(myFunction,1000);
  
}
</script>

# Auto run function

window.onload = function(){
  // your code here
};
# Mouse Enter and Mouse Out (JavaScript and JQuery)
1.JavaScript
<div onmousemove="myFunction()" onmouseout="clearCoor()"></div>
2. JQuery
$(document).ready(function(){
    $("p").mouseenter(function(){
        $("p").css("background-color", "yellow");
    });
    $("p").mouseleave(function(){
        $("p").css("background-color", "lightgray");
    });
});
