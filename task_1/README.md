Аналіз швидкості роботи алгоритмів сортування:
- злиттям, 
- вставками
- вбудованого алгоритму Timsort
на різних наборах даних.

Array Length: 10
Merge Sort Time: 0.000015 seconds
Insertion Sort Time: 0.000006 seconds
Timsort Time: 0.000002 seconds

Array Length: 100
Merge Sort Time: 0.000062 seconds
Insertion Sort Time: 0.000083 seconds
Timsort Time: 0.000006 seconds

Array Length: 1000
Merge Sort Time: 0.000862 seconds
Insertion Sort Time: 0.010385 seconds
Timsort Time: 0.000067 seconds

Array Length: 10000
Merge Sort Time: 0.011432 seconds
Insertion Sort Time: 1.104822 seconds
Timsort Time: 0.000827 seconds

Array Length: 100000
Merge Sort Time: 0.143263 seconds
Insertion Sort Time: 113.473816 seconds
Timsort Time: 0.012183 seconds

Висновок: 
1) на маленьких виборках алгоритми працюють практично з однаковою швидкістю
2) і збільшенням кількості даних, алгоритм сортування вставкою починає значно відставати по швидкості від алгоритму злиттям. 
3) Максимальну ефективність на великих вибірках показує вбудований алгоритм Timsort через свою максимальну оптимізацію.