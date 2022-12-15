# Задание 6. Предсказание и парное выравнивание структур белков

Последовательность: 

MSTLTSVSGFPRIGQNRELKKIIEGYWKGANDLAAVKATAAELRAKHWRLQQAAGIDLIASNDFSYYDQMLDTAILLNVIPQRYQRLAFDDQEDTLFAMA

Программы-предсказатели: 
- ESMFold
- AlphaFold2

Инструмент парного выравнивания: [TMAlign](https://zhanggroup.org/TM-align/)

Полученные notebooks: 
- [ESMFold.ipynb](./ESMFold.ipynb)
- [AlphaFold2.ipynb](./AlphaFold2.ipynb)

Результаты предсказаний: 
- ESMFold
- AlphaFold2

Предсказания, которые использовались для выравнивания: 
- [EMSFold/ptm0.596_r3_default.pdb](./EMSFold/ptm0.596_r3_default.pdb)
- [AlphaFold2/test_3b0d9_unrelaxed_rank_3_model_1.pdb](./AlphaFold2/test_3b0d9_unrelaxed_rank_3_model_1.pdb) 

В качестве результата прогонки файлов через TMAlign (веб-версия) были на веб-страницы с последовательностями атомов и их координат.  Результат парного выравнивания: TMAlign

![image](https://user-images.githubusercontent.com/60536840/207837874-f32d8420-e160-403c-a344-66e5f529fda8.png)

![image](https://user-images.githubusercontent.com/60536840/207834038-19d12959-7710-471f-a861-11bf23547d23.png)

Использовала YASARA для визуализации:
![image](https://user-images.githubusercontent.com/60536840/207844324-a4f40cf5-c13b-4644-a4cb-608fc8000108.png)
![image](https://user-images.githubusercontent.com/60536840/207844412-55588c6c-69e4-48a9-a830-821bbbabc029.png)
![image](https://user-images.githubusercontent.com/60536840/207844468-05eaccb1-b57c-4f99-99a3-e01f40ecf669.png)

## Выводы

С помощью полученного выравнивания мы можем видеть, что предсказания похожи, но всё таки кое-где смещены. 
