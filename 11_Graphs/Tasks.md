## Практикум 11
### Задачи
### Графи

<b>Задача 1.</b>  
  Нека имаме ориентиран граф от символи g и двоично дърво от символи t. Множеството от елементите на двете структури е едно и също, като
  в рамките на всяка една от структурите символите са уникални.
  Напишете функция, която проверява дали съществува път от корена на дървото до листо, който да отговаря на път в графа, и ако има такъв, да го извежда
  (ЗАБ.: достатъчно е да изведете само един път, който да отговаря на условието).  
  <br>
  <b>Example 1:</b>
  
![](https://github.com/karinag99/Data_Structures_and_algorithms_FMI/blob/main/11_Graphs/images/task_01.png)
```
Output: a-f-c-h
```

<br><b>Задача 2.</b>  
Нека има общо numCourses на брой курсове, които трябва да вземете, обозначени от 0 до numCourses-1.
Някои курсове могат да имат предпоставки, например, за да вземете курс 0, първо трябва да вземете курс 1, което се изразява като наредена двойка: [0,1].
Предвид общия брой курсове и списък от двойки с предварителни условия, възможно ли е да завършите всички курсове?

<b>Example 1:</b>
```
Input: numCourses = 2, prerequisites = [[1,0]]
Output: true
Explanation: There are a total of 2 courses to take. 
             To take course 1 you should have finished course 0. So it is possible.
```
<b>Example 2:</b>
```
Input: numCourses = 2, prerequisites = [[1,0],[0,1]]
Output: false
Explanation: There are a total of 2 courses to take. 
             To take course 1 you should have finished course 0, and to take course 0 you should
             also have finished course 1. So it is impossible.  
```


<br><br><b>Задача 3.</b>
Нека имаме масив от уравнения на двойки променливи и масив от стойности на реални числа, където уравненията [i] = [Ai, Bi] и стойностите [i] представляват уравнението Ai / Bi = стойност [i]. Всеки Ai или Bi са символи,
които представляват две променливи.
Нека имаме и няколко заявки, като заявката [j] = [Cj, Dj] представлява j-тата заявка, която означава, че трябва да намерите стойноста на Cj/Dj.
Върнете отговорите на всички запитвания като масив. Ако даден отговор не може да бъде пресметнат, върнете -1.0.

Забележка: Въведените стойности са винаги валидни. Може да предположите, че оценяването на заявките няма да доведе до разделяне на нула и че няма противоречие.

<b>Example 1</b>
```
Input: equations = [["a","b"],["b","c"]], values = [2.0,3.0], queries = [["a","c"],["b","a"],["a","e"],["a","a"],["x","x"]]
Output: [6.00000,0.50000,-1.00000,1.00000,-1.00000]
Explanation: 
Given: a / b = 2.0, b / c = 3.0
queries are: a / c = ?, b / a = ?, a / e = ?, a / a = ?, x / x = ?
return: [6.0, 0.5, -1.0, 1.0, -1.0 ]
```
<b>Example 2</b>
```
Input: equations = [["a","b"]], values = [0.5], queries = [["a","b"],["b","a"],["a","c"],["x","y"]]
Output: [0.50000,2.00000,-1.00000,-1.00000]
```
