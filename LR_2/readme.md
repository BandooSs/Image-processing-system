#Лабораторная работа №2
## Фильтрация изображений

1. Считать цветное rgb изображение
2. Зашумить изображение аддитивным шумом с вероятностью p (по вариантам).
  *   Вход: изображение из пункта 1
  *   Вывод: зашумленное изображение
3. Написать функцию реализации ранговой фильтрации

> Функцию вида fun(Image, window, rank)  
Где window  - окно фильтрации (по вариантам)  
rank - опциональный параметр, значение ранга в ранговой фильтрации


4. Отфильтровать зашумленное изображение со всеми возможными рангами (кол-во рангов зависит от окна по вариантам).  
Подсчитать СКО для результата фильтрации с каждым рангом.
  *   Вход: изображение из пункта 2
  *   Вывод: Значения СКО для каждого ранга. Исходное (из пункта 1), зашумленное (из пункта 2) и отфильтрованные изображения для первого, последнего ранга, а так же для ранга с наименьшим СКО.
  *   СКО считать между отфильтрованным изображением и исходным (не зашумленным) из пункта 1
5. Написать функцию реализации свертки

> Функцию вида fun(mat1, mat2)  
Где mat1  - первый сигнал. В данном случае изображение  
mat2 - второй сигнал. В данном ядро КИХ фильтра

6. Отфильтровать изображение КИХ фильтром с ядром заданным по вариантам. Подсчитать СКО. Сравнить с результатами пункта 4.
  *   Вход: изображение из пункта 2
  *   Вывод: Значения СКО . Исходное (из пункта 1), зашумленное (из пункта 2) и отфильтрованное изображение.
  *   СКО считать между отфильтрованным изображением и исходным (не зашумленным) из пункта 1