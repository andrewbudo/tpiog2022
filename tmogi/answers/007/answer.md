**7. Априорные методы обнаружения грубых ошибок.**  

В процессе обработки данных следует исключать грубые ошибки ряда. Появление этих ошибок вполне вероятно, а наличие их ощутимо влияет на результат измерений. Однако необходимо убедится, что это действительно грубая ошибка, а не отклонение вследствие статистического разброса. Известно несколько методов определения грубых ошибок:

1. ***Способ доверительных интервалов.*** Доверительным называется интервал, в который попадают измеренные значения, соответствующие доверительной вероятности.
2. ***Правило «трех сигм» или правило Райта.*** Если случайная величина распределена нормально, то абсолютная величина ее отклонения от математического ожидания не превосходит утроенного среднего квадратического отклонения.
3. ***Критерий Хэмпэла.*** Согласно критерию грубым измерением считается измерение, лежащее вне инетервала  

<img src="https://latex.codecogs.com/gif.image?\dpi{110}AMO\,&space;low\leqslant&space;h\leqslant&space;AMO\,&space;high" title="https://latex.codecogs.com/gif.image?\dpi{110}AMO\, low\leqslant h\leqslant AMO\, high" />

где *med(h)* - медиана, вычисляемая из вариационного ряда измерений h;  
  AMO - абсолютное медианное отклонение:
  
<img src="https://latex.codecogs.com/gif.image?\dpi{110}AMO=med\left&space;(&space;\left|&space;h_{i}-med(h)\right|&space;\right&space;)" title="https://latex.codecogs.com/gif.image?\dpi{110}AMO=med\left ( \left| h_{i}-med(h)\right| \right )" />
  
  Нижняя граница: <img src="https://latex.codecogs.com/gif.image?\dpi{110}AMO\,&space;low=med(h)-5,2\,&space;AMO" title="https://latex.codecogs.com/gif.image?\dpi{110}AMO\, low=med(h)-5,2\, AMO" />  
  Верхняя граница:  <img src="https://latex.codecogs.com/gif.image?\dpi{110}AMO\,&space;high=med(h)&plus;5,2\,&space;AMO" title="https://latex.codecogs.com/gif.image?\dpi{110}AMO\, high=med(h)+5,2\, AMO" />
  
  
 
