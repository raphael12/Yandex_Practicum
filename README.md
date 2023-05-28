# Yandex_Practicum

Здесь представлены учебные проекты от Яндекс Практикума, которые я решал в процесссе моего обучения. 

## Определение наиболее выгодного региона нефтедобычи  
**Навыки и инструменты:** Pandas, Scikit-learn, бутстреп  
**Задача:** На основе данных геологи разведки выбрать район добычи нефти  
**Описание:** По предоставленным пробам нефти в трёх регионах постройте модель для определения региона с наибольшей прибылью.   
**Результат:** Использована и обучена модель линейной регрессии. Уже на стадии модели видно, что второй регион сильно выделяется на фоне других. Он имеет наименьшую вероятность убытков (около 1%) и наибольшее среднее значение прибыли (450млн руб).  

## Исследование технологического процесса очистки золота  
**Навыки и инструменты:** Matplotlib, NumPy, Pandas, Python, Scikit-learn, исследовательский анализ данных  
**Задача:** Спрогнозировать концентрацию золота при проведении процесса очистки золота  
**Описание:** Строитстся модель машинного обучения для промышленной компании, разрабатывающая решения для эффективной работы промышленных предприятий. Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды на основе данных с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.  
**Результат:** Лучше всего себя показала модель Gradient Boosting Regressor, с ошибкой метрики sMAPE = 8.67.  


## Определение температуры стали  
**Навыки и инструменты:** Matplotlib, NumPy, Pandas, CatBoost, Python, Scikit-learn, Pipeline, исследовательский анализ данных  
**Задача:** Необходимо построить модель, которая предскажет температуру стали для металлургического комбината  
**Описание:** Чтобы оптимизировать производственные расходы, металлургический комбинат ООО «Так закаляем сталь» решил уменьшить потребление электроэнергии на этапе обработки стали. Вам предстоит построить модель, которая предскажет температуру стали.  
**Результат:** Лучший результат на кросс-валидации показала модель CatBoost со значение метрики MAE = 6.213 на тестовой выборки.  

