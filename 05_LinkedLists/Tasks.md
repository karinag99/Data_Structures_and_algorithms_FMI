## Практикум 5
### Задачи
### Стек  

<b>Задача 1.</b>  
Дефинираме израз по следния начин:
( <операнд> <операция> <операнд> ), където операндите представляват малки латински букви, а операциите са елементи на следното множество {‘+’, ‘-’, ‘*’}.  

<b>а)</b> Напишете функция, която получава израз като символен низ и проверява дали той е валиден, като приемаме, че единствената грешка, която може да се открие в израза е в скобите(липса на скоби(отваряща и затваряща) около израз или повече от един чифт скоби около израз). Нека имаме следните правила: 
Всяка буква е валиден израз
Скоби има само около израз във вида <операнд> <операция> <операнд>   

  Примери:
```
(a+b) е валиден израз
a е валиден израз
(a+(a*c)) е валиден израз
(a) не е валиден израз
((b-c)) не е валиден израз
a+b не е валиден израз
```

  <b>б)</b> Напишете функция, която получава израз от същия вид и изкарва позициите на невалидните скоби, ако има такива  
  
  Примери:
  ```
  ((a+b)) -- позиции 0 и 6
  (а) -- позиции 0 и 2
  a+b -- няма невалидни скоби
  ```
  
  ### Свързан списък
      
<b>Задача 2.</b>  
Напишете функция, която получава указател към главата на свързан списък и естествено число n и връща стойността на елемента, който се намира на n позиции от опашката на списъка.
Пример:

    Вход:
    1->2->3->4->5->6->7
    3
    Изход : 5
  

<b>Задача 3.</b> [Линк към задачата](https://www.hackerrank.com/challenges/detect-whether-a-linked-list-contains-a-cycle/problem) 

<b>Задача 4.</b> [Линк към задачата](https://www.hackerrank.com/challenges/merge-two-sorted-linked-lists/problem)  

      
