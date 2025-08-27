# Kartezyen Koordinat Sistemleri
## Diferansiyel Uzunluk Elemanı
Diferansiyel uzunluk elemanı, bir koordinat sisteminde çok küçük bir mesafe değişimini ifade eder. Kartezyan koordinat sisteminde, diferansiyel uzunluk elemanı $dl$ şu şekilde ifade edilir:
$$ dl = \sqrt{(dx)^2 + (dy)^2 + (dz)^2} $$
Burada $dx$, $dy$ ve $dz$, sırasıyla x, y ve z eksenlerindeki küçük değişiklikleri temsil eder.

---

$$

Bir uzayda bir noktadan diğerine hareket ederken, diferansiyel uzunluk vektörü $d\vec{l}$ Kartezyan koordinatlarda aşağıdaki gibi tanımlanır:

$$
d\vec{l} = dx\, \mathbf{a}_x + dy\, \mathbf{a}_y + dz\, \mathbf{a}_z
$$

**Problem:**
Bir parçacık, $(1,2,3)$ noktasından $(4,6,5)$ noktasına doğru doğrusal bir yol izlemektedir.  
a) Parçacığın izlediği yol boyunca diferansiyel uzunluk vektörünü yazınız.  
b) Parçacığın toplam yol uzunluğunu hesaplayınız.  
c) Eğer yol boyunca bir vektör alanı $\vec{A} = x\mathbf{a}_x + y\mathbf{a}_y + z\mathbf{a}_z$ tanımlanmışsa, bu yol boyunca $\vec{A} \cdot d\vec{l}$ doğrultusunda bir çizgisel integrali kurunuz.

---

$$

a) Parçacığın izlediği yol boyunca diferansiyel uzunluk vektörü

Parçacık doğrusal bir yol izlediği için, yolun parametrelenmesi:
$$(x, y, z) = (1, 2, 3) + t\, (4-1, 6-2, 5-3) = (1 + 3t,\, 2 + 4t,\, 3 + 2t)$$
$$

Diferansiyel uzunluk vektörü:
$$
d\vec{l} = dx\, \mathbf{a}_x + dy\, \mathbf{a}_y + dz\, \mathbf{a}_z
$$
Parametreye göre türev alınırsa:
$$
dx = 3\,dt,\quad dy = 4\,dt,\quad dz = 2\,dt
$$
Dolayısıyla:
$$
d\vec{l} = 3\,dt\, \mathbf{a}_x + 4\,dt\, \mathbf{a}_y + 2\,dt\, \mathbf{a}_z
$$

---

$$

Toplam yol uzunluğu iki nokta arasındaki mesafenin büyüklüğüdür:
$$
L = \sqrt{(4-1)^2 + (6-2)^2 + (5-3)^2} = \sqrt{9 + 16 + 4} = \sqrt{29}
$$

---

c) Çizgisel integralin kurulması

Vektör alanı:
$$
\vec{A} = x\, \mathbf{a}_x + y\, \mathbf{a}_y + z\, \mathbf{a}_z
$$
Çizgisel integral:
$$
\int_C \vec{A} \cdot d\vec{l}
$$
Parametrelenmiş yol için:
$$
\vec{A}(t) = (1 + 3t)\, \mathbf{a}_x + (2 + 4t)\, \mathbf{a}_y + (3 + 2t)\, \mathbf{a}_z
$$
$$
d\vec{l} = 3\,dt\,\mathbf{a}_x + 4\,dt\,\mathbf{a}_y + 2\,dt\,\mathbf{a}_z
$$
Skaler çarpım:
$$
\vec{A}(t) \cdot d\vec{l} = (1 + 3t) \cdot 3\,dt + (2 + 4t) \cdot 4\,dt + (3 + 2t) \cdot 2\,dt
$$
$$
= [3(1 + 3t) + 4(2 + 4t) + 2(3 + 2t)]\,dt
$$
$$
= [3 + 9t + 8 + 16t + 6 + 4t]\,dt
$$
$$
= (3 + 8 + 6) + (9t + 16t + 4t)\,dt
$$
$$
= 17 + 29t\,dt
$$
Çizgisel integral:
$$
\int_{t=0}^{1} (17 + 29t)\,dt = \left[17t + \frac{29}{2}t^2\right]_{0}^{1} = 17 + \frac{29}{2}
$$
$$
= \frac{34 + 29}{2} = \frac{63}{2}
$$

---

**Sonuçlar:**
- a) $d\vec{l} = 3\,dt\,\mathbf{a}_x + 4\,dt\,\mathbf{a}_y + 2\,dt\,\mathbf{a}_z$
- b) Toplam yol uzunluğu: $\sqrt{29}$
- c) Çizgisel integral sonucu: $\frac{63}{2}$

---