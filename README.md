# Merge Sort Patika
[Patika.dev](https://www.patika.dev/tr) Veri yapıları ve algoritmalar dersinin Merge sort projesi çözümleri

## Soru
1. [16,21,11,8,12,22] -> Merge Sort

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yazınız.

## Cevaplar
1. * -> [16,21,11] - [8,12,22]\
        -> [16] - [21,11] - [8] - [12,22]\
        -> [16] - [21] - [11] - [8] - [12] - [22]\
        -> [16] - [11, 21] - [8] - [12, 22]\
        -> [11, 16, 21] - [8, 12, 22]\
        -> [8, 11, 12, 16, 21, 22]

    * Big O(n*log(n))
