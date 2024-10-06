# Insertion Sort Aşamaları

## Verilen Dizi: [22,27,16,2,18,6]

### Adım Adım Sıralama:
1. [22,27,16,2,18,6] - Başlangıç
2. [22,27,16,2,18,6] - 22 < 27, değişiklik yok
3. [22,16,27,2,18,6] → [16,22,27,2,18,6] - 16 yerleştirildi
4. [16,22,2,27,18,6] → [2,16,22,27,18,6] - 2 yerleştirildi
5. [2,16,22,18,27,6] → [2,16,18,22,27,6] - 18 yerleştirildi
6. [2,16,18,22,6,27] → [2,6,16,18,22,27] - 6 yerleştirildi

### Big-O Gösterimi: 
- O(n²)

### Time Complexity
- Worst Case: O(n²)
- Average Case: O(n²)
- Best Case: O(n)

18 sayısı dizinin ortasında yer aldığından **Average case** kapsamına girer.

---

# Selection Sort İlk 4 Adım

## Verilen Dizi: [7,3,5,8,2,9,4,15,6]

1. [**2**,3,5,8,7,9,4,15,6] - En küçük 2, 7 ile yer değiştirir
2. [2,**3**,5,8,7,9,4,15,6] - 3 zaten doğru konumda
3. [2,3,**4**,8,7,9,5,15,6] - 4, 5 ile yer değiştirir
4. [2,3,4,**5**,7,9,8,15,6] - 5, 8 ile yer değiştirir