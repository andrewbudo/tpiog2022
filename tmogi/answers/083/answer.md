Точные критерии исследования ряда случайных величин на соответствие нормальному закону распределения  

``К точным критетриям исследования относят критерии Колмогорова и Пирсона. Критерий согласия Колмогорова предназначен для проверки гипотезы о принадлежности
выборки некотору закону распределения, то есть проверки того, что эмпирическое распределение соответствует предполагаемой модели. 
  Для оценки по критерию Пирсона следует вычислить величину:
<img src="https://latex.codecogs.com/gif.image?\dpi{110}\chi^{2}&space;=&space;\sum_{i=1}^{N}\frac{\left&space;(&space;N_{i}-N\cdot&space;p_{i}&space;\right&space;)^{2}}{N\cdot&space;p_{i}" title="https://latex.codecogs.com/gif.image?\dpi{110}\chi^{2} = \sum_{i=1}^{N}\frac{\left ( N_{i}-N\cdot p_{i} \right )^{2}}{N\cdot p_{i}" />  
  Здесь <img src="https://latex.codecogs.com/gif.image?\dpi{110}p_{i}" title="https://latex.codecogs.com/gif.image?\dpi{110}p_{i}" /> - теоретическая вероятность
  попадания случайной величины в соответсвующий интервал. Данная величина вычисляется по значениям интеграла вероятности <img src="https://latex.codecogs.com/gif.image?\dpi{110}\Phi&space;(t_{i})" title="https://latex.codecogs.com/gif.image?\dpi{110}\Phi (t_{i})" />
  , которые выбираются из статистических таблиц по величинам границ интегралов <img src="https://latex.codecogs.com/gif.image?\dpi{110}t_{i}" title="https://latex.codecogs.com/gif.image?\dpi{110}t_{i}" />  
  <img src="https://latex.codecogs.com/gif.image?\dpi{110}p_{i}=&space;\frac{1}{2}&space;\cdot&space;(\Phi&space;(t_{i&plus;1})-\Phi&space;(t_{i}))" title="https://latex.codecogs.com/gif.image?\dpi{110}p_{i}= \frac{1}{2} \cdot (\Phi (t_{i+1})-\Phi (t_{i}))" />  
   и не деля на два, если используются таблицы нормированной функции Лапласа.  
