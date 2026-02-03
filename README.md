[index2.html](https://github.com/user-attachments/files/25044135/index2.html)
<!DOCTYPE html>
<html>
<head>
                <style>.lw { font-size: 60px; font-family: Arial, Helvetica, sans-serif; }</style>
            </head>
            <body>
                

    <meta charset="UTF-8">
<title>My 1st Mini Test 第一個小測試網站</title>


    <h3>翻譯小測試</h3>
    Q1. Apple = ? <br>
    <input type="radio" name="q1" id="ans1">梨子
    <input type="radio" name="q1" id="ans2">蘋果
    <input type="radio" name="q1" id="ans3">榴槤
    <button onclick="question1()">Submit</button>
    <p id="results1"></p>

Q2. Peer = ? <br>
    <input type="radio" name="q2" id="ans4">梨子
    <input type="radio" name="q2" id="ans5">蘋果
    <input type="radio" name="q2" id="ans6">榴槤
    <button onclick="question2()">Submit</button>
    <p id="results2"></p>

Q3. 誰是韓國首位在選秀節目中獲得第一名的中國人 = ? <br>
    <input type="radio" name="q3" id="ans7">章昊
    <input type="radio" name="q3" id="ans8">周安信
    <input type="radio" name="q3" id="ans9">ricky
    <button onclick="question3()">Submit</button>
    <p id="results3">Correct!好棒</p>


                <script>function question1(){
    var ans1 = document.getElementById("ans1");
    var ans2 = document.getElementById("ans2");
    var ans3 = document.getElementById("ans3");

    if(ans2.checked){
        document.getElementById("results1").
        innerText = "Correct!好棒";
         }else if(ans1.checked || ans3.checked){
            document.getElementById("results1").
            innerHTML = "Oppps!錯了～ <img src='https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR5y8Nd-KM9P8T3jgxloJukf-mGeDOX6-MouA&s'  width='20%'>;"
         }
}       
         function question2(){
    var ans4 = document.getElementById("ans4");
    var ans5 = document.getElementById("ans5");
    var ans6 = document.getElementById("ans6");

    if(ans4.checked){
        document.getElementById("results2").
        innerText = "Correct!好棒";
         }else if(ans5.checked || ans6.checked){
            document.getElementById("results2").
            innerHTML = "Oppps!錯了～ <img src='https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR5y8Nd-KM9P8T3jgxloJukf-mGeDOX6-MouA&s'  width='20%'>;"
         }
}
function question3(){
    var ans7 = document.getElementById("ans7");
    var ans8 = document.getElementById("ans8");
    var ans9 = document.getElementById("ans9");

    if(ans7.checked){
        document.getElementById("results3").
        innerText = "Correct!好棒";
         }else if(ans8.checked || ans9.checked){
            document.getElementById("results3").
            innerHTML = "Oppps!錯了～ <img src='https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR5y8Nd-KM9P8T3jgxloJukf-mGeDOX6-MouA&s'  width='20%'>;"
         }
}</script>
            
        
    </body>
