* Для вершини 3 порядок обходу:  3 0 1 2 4 5 6 7

![image](https://user-images.githubusercontent.com/69114727/117046002-d50ab080-ad18-11eb-9506-0ac7b1b5cac7.png)

iv.	Чи будуть однаковими топології дерев побудованих з різних кореневих вершин? Чому?
* Ні, тому що у першому графі тільки 3 вершина веде до вершини 2, а в другому графі тільки 1 вершина веде до вершини 2.

#### 2.	За допомогою лабораторного макету побудувати випадковий орієнтований граф G={6,10}:

![image](https://user-images.githubusercontent.com/69114727/117190012-8b3ccb80-ade7-11eb-8975-650d799816c1.png)

i.	Побудувати дерево за алгоритмом обходу в ширину (BFS);
* Порядок обходу: 0 1 3 2 4 5

![image](https://user-images.githubusercontent.com/69114727/117190080-a14a8c00-ade7-11eb-878b-1bce3361cedb.png)

ii.	Яка вершина (вершини) буде знайдена останньою?
* Вершина 5

iii.	Визначити чи існують цикли. Вказати послідовність ребер і їх довжину.
* Цикли: 0-1-2-5-0 (довжина 4), 1-2-3-4-1 (довжина 4), 2-3-5-0-1-2 (довжина 5),   
* 2-3-4-5-0-1-2 (довжина 6), 5-0-1-2-5 (довжина 4), 4-1-2-3-4 (довжина 4).   

iv.	Визначити кількість хвиль, які пройдуть по ребрах доки буде виявлена остання вершина.
* Кількість хвиль становить 5.

v.	Побудувати дерево за алгоритмом обходу в глибину (DFS);
* Порядок обходу: 0 1 2 3 4 5

![image](https://user-images.githubusercontent.com/69114727/117194759-25534280-aded-11eb-8005-06725800485b.png)

#### 3.	Побудувати дерево шляхів рангом r=4 для випадкового графа G={6,9}.

![image](https://user-images.githubusercontent.com/69114727/117195682-3d779180-adee-11eb-98b3-9dee47918c56.png)

![image](https://user-images.githubusercontent.com/69114727/117200295-01dfc600-adf4-11eb-9aa4-2e574f843320.png)

#### 4.	Побудувати мінімальне зв’язне дерево для графа G. Вказати його вагу.

![image](https://user-images.githubusercontent.com/79188624/115473041-a6cea080-a243-11eb-882d-238ee4f1cdc4.png)


![image](https://user-images.githubusercontent.com/69114727/117201003-d01b2f00-adf4-11eb-827e-e347ab99194a.png)

* Вага: 5+7+9+3+5=29