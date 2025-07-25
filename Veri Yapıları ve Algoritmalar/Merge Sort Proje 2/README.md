# Merge Sort Projesi

## Veri Seti
`[16, 21, 11, 8, 12, 22]`

### Aşamalar:
1. Başlangıç: [16, 21, 11, 8, 12, 22]
2. Bölme: [16, 21, 11] ve [8, 12, 22]
3. Alt bölme: [16], [21], [11], [8], [12], [22]
4. Birleştirme:
   - [16, 21] → [11, 16, 21]
   - [8, 12] → [8, 12, 22]
5. Final: [11, 16, 21] + [8, 12, 22] = **[8, 11, 12, 16, 21, 22]**

## Big-O Gösterimi
- Best Case: O(n log n)
- Average Case: O(n log n)
- Worst Case: O(n log n)
