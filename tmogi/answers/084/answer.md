**Вычисление весов результатов измерений весов и функций от результатов измерений**

Для облегчения совместной обработки разнородных и неравноточных результатов измерений вводится понятие веса. 
Весом  называют степень доверия к результату, который вычисляется как величина, 
обратно пропорциональная к точности получения результата.

Для оценки точности результатов измерений вычисляют
- среднюю квадратическую ошибку единицы веса.
<img src="https://latex.codecogs.com/svg.image?\mu&space;=&space;\sqrt{\frac{[pv^2]}{r}}" title="https://latex.codecogs.com/svg.image?\mu = \sqrt{\frac{[pv^2]}{r}}" />
- обратный вес функции, определяемый в дополнительном столбце схемы решения нормальных уравнений,
вычисляется как сумма [πff] и произведений чисел элиминационных строк столбца F на вышестоящие числа того же столбца.
<img src="https://latex.codecogs.com/svg.image?\frac{1}{P_{f}}=&space;[\pi&space;ffr]=[\pi&space;ff]-\frac{[\pi&space;af]^2}{[\pi&space;aa]}-\frac{[\pi&space;bf1]^2}{[\pi&space;bb1]}-..\frac{[\pi&space;rf(r-1)]^2}{[\pi&space;rr(r-1)]}" title="https://latex.codecogs.com/svg.image?\frac{1}{P_{f}}= [\pi ffr]=[\pi ff]-\frac{[\pi af]^2}{[\pi aa]}-\frac{[\pi bf1]^2}{[\pi bb1]}-..\frac{[\pi rf(r-1)]^2}{[\pi rr(r-1)]}" />
- средняя квадратическая ошибка функции.
<img src="https://latex.codecogs.com/svg.image?m_{f}=\mu&space;\sqrt{\frac{1}{P_{f}}}" title="https://latex.codecogs.com/svg.image?m_{f}=\mu \sqrt{\frac{1}{P_{f}}}" />
