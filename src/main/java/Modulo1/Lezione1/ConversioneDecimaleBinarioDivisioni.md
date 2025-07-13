# Conversione da Decimale a Binario  
## Metodo 1: Divisioni successive per 2

Il metodo delle divisioni successive per 2 è uno dei più semplici per convertire un numero decimale in binario.

### 🔢 Procedura passo passo

1. Dividi il numero decimale per 2.
2. Annota il **resto** (0 o 1).
3. Usa il **quoziente** per la divisione successiva.
4. Ripeti finché il quoziente è 0.
5. Leggi i resti **dal basso verso l’alto**: otterrai il numero in binario.

---

## ✅ Esempi svolti

### Esempio 1: Convertire 13 in binario

```
13 ÷ 2 = 6, resto 1  
 6 ÷ 2 = 3, resto 0  
 3 ÷ 2 = 1, resto 1  
 1 ÷ 2 = 0, resto 1  
```

**Binario = 1101** (leggendo i resti dal basso verso l'alto)

---

### Esempio 2: Convertire 22 in binario

```
22 ÷ 2 = 11, resto 0  
11 ÷ 2 = 5, resto 1  
 5 ÷ 2 = 2, resto 1  
 2 ÷ 2 = 1, resto 0  
 1 ÷ 2 = 0, resto 1  
```

**Binario = 10110**

---

## 📝 Esercizi

Converti i seguenti numeri decimali in binario usando il metodo delle divisioni successive per 2:

1. 7  
2. 18  
3. 25  
4. 31  
5. 36  

---

## 🧠 Soluzioni

### 1. 7 in binario
```
7 ÷ 2 = 3, resto 1  
3 ÷ 2 = 1, resto 1  
1 ÷ 2 = 0, resto 1  
→ Binario = 111
```

### 2. 18 in binario
```
18 ÷ 2 = 9, resto 0  
 9 ÷ 2 = 4, resto 1  
 4 ÷ 2 = 2, resto 0  
 2 ÷ 2 = 1, resto 0  
 1 ÷ 2 = 0, resto 1  
→ Binario = 10010
```

### 3. 25 in binario
```
25 ÷ 2 = 12, resto 1  
12 ÷ 2 = 6, resto 0  
 6 ÷ 2 = 3, resto 0  
 3 ÷ 2 = 1, resto 1  
 1 ÷ 2 = 0, resto 1  
→ Binario = 11001
```

### 4. 31 in binario
```
31 ÷ 2 = 15, resto 1  
15 ÷ 2 = 7, resto 1  
 7 ÷ 2 = 3, resto 1  
 3 ÷ 2 = 1, resto 1  
 1 ÷ 2 = 0, resto 1  
→ Binario = 11111
```

### 5. 36 in binario
```
36 ÷ 2 = 18, resto 0  
18 ÷ 2 = 9, resto 0  
 9 ÷ 2 = 4, resto 1  
 4 ÷ 2 = 2, resto 0  
 2 ÷ 2 = 1, resto 0  
 1 ÷ 2 = 0, resto 1  
→ Binario = 100100
```

---

## 📌 Suggerimento

Usa una tabella per tenere ordinati i passaggi:

| Divisione | Quoziente | Resto |
|-----------|-----------|-------|
| 36 ÷ 2    | 18        | 0     |
| 18 ÷ 2    | 9         | 0     |
| 9 ÷ 2     | 4         | 1     |
| 4 ÷ 2     | 2         | 0     |
| 2 ÷ 2     | 1         | 0     |
| 1 ÷ 2     | 0         | 1     |

Rileggi i resti **dal basso verso l’alto** → 100100
