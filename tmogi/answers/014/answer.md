**Коррелатный способ уравнивания. Условные уравнения**
Коррелатный способ основан на использовании функциональной связи между собой элементов геодезических построений Xi (i = 1, n). 
Эти уравнения связи называются условными уравнениями:
Φj (X1, X2,..., Xn )= 0
i = l,n;
j = l,k;

При коррелатном способе уравнивания вначале составляется система условных уравнений AV + W = 0,
где А – матрица коэффициентов системы условных уравнений;
V – вектор поправок в измеренные значения элементов сети;
W – вектор невязок условных уравнений.
При этом коэффициенты aij условных уравнений поправок определяются по формуле:
<img src="https://latex.codecogs.com/svg.image?a_{ij}=\frac{\delta&space;\phi&space;_{j}X_{i}}{\delta&space;X_{i}}" title="https://latex.codecogs.com/svg.image?a_{ij}=\frac{\delta&space;\phi&space;_{j}X_{i}}{\delta&space;X_{i}}" />

а невязки уравнений – по формуле:

<img src="https://latex.codecogs.com/svg.image?w_{j}=\phi&space;_{j}(x_{1},x_{2},...,&space;x_{n})" title="https://latex.codecogs.com/svg.image?w_{j}=\phi&space;_{j}(x_{1},x_{2},...,&space;x_{n})" />
где xi (i = 1, n) – измеренные значения элементов геодезических построений.

При известной весовой матрице Р вначале вычисляют обратную весовую матрицу Q = P^-1, а затем от системы условных уравнений переходят к системе нормальных уравнений:

<img src="https://latex.codecogs.com/svg.image?(AQA^{T})K&plus;W=0" title="https://latex.codecogs.com/svg.image?(AQA^{T})K&plus;W=0" />
Определив коррелаты 
<img src="https://latex.codecogs.com/svg.image?K=-(AQA^{T})^{-1}W" title="https://latex.codecogs.com/svg.image?K=-(AQA^{T})^{-1}W" />
вычисляют поправки
<img src="https://latex.codecogs.com/svg.image?V&space;=&space;QA^TK" title="https://latex.codecogs.com/svg.image?V&space;=&space;QA^TK" />
и уравненные значения измеренных элементов сети x* = x + v,

где х* – вектор уравненных значений;

х – вектор измеренных значений элементов геодезических построений.
