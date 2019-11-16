 # 1
let  a = 300;
let b = 100;
let x = a + b;
if(a <= b){
  alert ('x = +a + +b/2*4');
}else if(a = b){
  alert( 'x=400');
}else if( a > b){
 alert('x=a-b+2/b*4');
}else{
    alert(" невозможно!!!!")
}

let numberDay = prompt( "Введите номер дня недели ");
 if (numberDay == 1){
   alert("Понедельник")
 }else if(numberDay == 2){
   alert("Вторник")
 }else if(numberDay == 3){
   alert("Среда")
 }else if(numberDay == 4){
  alert("Четверг")
 }else if(numberDay == 5){
  alert("Пятница")
 }else if(numberDay == 6){
  alert("Суббота")
 }else if(numberDay == 7){
  alert("Воскресенье")
 }else{
   alert("Такого дня недели не существует!")
 }
 if (numberDay >= 1 && numberDay <= 5){
   alert("Рабочий день!")
 }else if(numberDay > 5 && numberDay <=7){
   alert("Выходной!!!")
 }else{
   alert(" It's not day")
 }

