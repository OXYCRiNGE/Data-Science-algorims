# ОЦЕНКА МОДЕЛИ
## Построить простую модель энергопотребления здания по среднему значению, оценить эффективность модели через метрику
```math
RMSLE = \sqrt{\frac{\sum_{i=1}^{n}(\log(p_{i}+1)-(\log(a_{i}+1)^{2}}{n}},
```
где $n$ - число наблюдений;<br/>
$log$ - натуральный логорифм;<br/>
$p_{i}$ - вычисленное значение метрики;<br/>
$a_{i}$ - заданное значение метрики.<br/>
Данные: http://video.ittensive.com/machine-learning/ashrae/train.0.0.csv.gz
