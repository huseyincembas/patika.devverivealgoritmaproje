# INSERTION SORT PROJESİ [patika.dev](www.patika.dev)

## [22,27,16,2,18,6] -> Insertion Sort

1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2) Big-O gösterimini yazınız.
3) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

---

### 1. Verilen dizinin insertion sorta göre aşamaları

```text
[22, 27, 16, 2, 18, 6]
[2, 27, 16, 22, 18, 6]
[2, 6, 16, 22, 18, 27]
[2, 6, 16, 18, 22, 27]
```

---

### 2. Big-O Gösterimi

```text
Worst Case: O(n²)  
Average Case: O(n²)  
Best Case: O(n)
```

---

### 3. Time Complexity

```text
Worst Case: [27, 22, 18, 16, 6, 2]
```

```text
Average Case: [27, 2, 18, 16, 22, 6]
```

```text
Best Case: [2, 6, 16, 18, 22, 27]
```

---

### 4. Sıralı dizide 18 sayısı hangi case kapsamına girer?

```text
Sıralamaın ortasında bulunuduğu için average case kapsamına girer.
```

---

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı

```text
[2, 3, 5, 8, 7, 9, 4, 15, 6]
[2, 3, 4, 8, 7, 9, 5, 15, 6]
[2, 3, 4, 5, 7, 9, 8, 15, 6]
[2, 3, 4, 5, 6, 9, 8, 15, 7]
```
