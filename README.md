# Задание 6. Предсказание и парное выравнивание структур белков

Последовательность: 

MSTLTSVSGFPRIGQNRELKKIIEGYWKGANDLAAVKATAAELRAKHWRLQQAAGIDLIASNDFSYYDQMLDTAILLNVIPQRYQRLAFDDQEDTLFAMA

Программы-предсказатели: 
- ESMFold
- AlphaFold2

Инструмент парного выравнивания: [TMAlign](https://zhanggroup.org/TM-align/)

Полученные notebooks: 
- ESMFold.ipynb 
- AlphaFold2.ipynb

Результаты предсказаний: 
- ESMFold 
- AlphaFold2

Предсказания, которые использовались для выравнивания: 
- EMSFold/ptm0.596_r3_default.pdb  
- AlphaFold2/test_3b0d9_unrelaxed_rank_3_model_1.pdb 

В качестве результата прогонки файлов через TMAlign (веб-версия) были на веб-страницы с последовательностями атомов и их координат.  Результат парного выравнивания: TMAlign

![image](https://user-images.githubusercontent.com/60536840/207834038-19d12959-7710-471f-a861-11bf23547d23.png)

Использовала YASARA для визуализации:

## Выводы

С помощью полученного выравнивания мы можем видеть, что предсказания близки, но всё таки имеются некоторые отличия
