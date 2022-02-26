## Proje 1
## [22,27,16,2,18,6]

# 1 - Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız. "Insertion Sort"

[22,27,16,2,18,6] -> Insertion Sort

- `[22,27,16,2,18,6]` Değişim olmaz    22 < 27
- `[16,22,27,2,18,6]` Değişim olur     16 < 22 < 27
- `[2,16,22,27,18,6]` Değişim olur     2  < 16 < 22 < 27
- `[2,16,18,22,27,6]` Değişim olur     2  < 16 < 18 < 22 < 27
- `[2,6,16,18,22,27]` Değişim olur     2  < 6  < 16 < 18 < 22 < 27

# 2 - Big-O gösterimini yazınız.

- Big-O Notation : `O(n^2)`

- Time Complexity : `(n^2+n)/2`

- Average case: `O(n^2)`

- Worst case: `O(n^2)`

- Best case: `O(n)`

# 3 - Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
`Average case`

# 4 - [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
[7,3,5,8,2,9,4,15,6] -> Insertion Sort

- `Adım 1 - [3,7,5,8,2,9,4,15,6]` Değişim olur  3 < 7
- `Adım 2 - [3,5,7,8,2,9,4,15,6]` Değişim olur  3 < 5 < 7
- `Adım 3 - [3,5,7,8,2,9,4,15,6]` Değişim olmaz 3 < 5 < 7 < 8
- `Adım 4 - [2,3,5,7,8,9,4,15,6]` Değişim olur  2 < 3 < 5 < 7 < 8
