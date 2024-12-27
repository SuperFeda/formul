<details>
<summary>Константы</summary>

$e = 2.71828...$</br>
$\pi = 3.14159...$<br>
  
</details>

---

<details>
<summary>Формулы сокращенного умножения</summary>

$a^{2} - b^{2} = (a-b)(a+b)$</br>
$(a+b)^{2} = a^{2} + 2ab + b^{2}$</br>
$(a-b)^{2} = a^{2} - 2ab + b^{2}$</br>
$a^{3} + b^{3} = (a+b)(a^{2} - ab + b^{2})$</br>
$a^{3} - b^{3} = (a-b)(a^{2} + ab + b^{2})$</br>
$(a + b)^{3} = a^{3} + 3a^{2}b + 3ab^{2} + b^{3}$</br>
$(a - b)^{3} = a^{3} - 3a^{2}b + 3ab^{2} - b^{3}$</br>
  
</details>

---

<details>
<summary>Свойства степеней</summary>

$a^{0} = 1$<br>
$a^{m} \times a^{b} = a^{m+n}$<br>
$a^{m} \div a^{b} = a^{m-n}$<br>
$(a^{m})^{n} = a^{m \times n}$<br>
$(a \times b)^{n} = a^{n} \times b^{n}$<br>

$\Big(\frac{a}{b}\Big)^n = \frac{a^{n}}{b^{n}}$<br>

$a^{-n} = \frac{1}{a^{n}}$
  
</details>

---

<details>
<summary>Алгебра логики (алгебра высказываний)</summary>

1) Конъюнкция (и) (& ∧)</br>Истино только тогда, когда истины все входящие в него простые высказывания.
2) Дизъюнкция (или) (∨ +)</br>Является истиной только тогда, когда хотябы одно высказывание истино.
3) Отрицание (не) (¬ $\overline{A}$ !)</br>Делает ложным истинное высказывание, и наоборот.
4) Импликация (если ... то ...) (⇒ → ⊃)</br>Ложно только тогда, когда первое высказывание истино, во всех остальных случаях - истина.
5) Эквивалентность (⇔ ≡ ↔)</br>Истино только тогда, когда оба высказывания истины или ложны.

|A|B|!A|!B|A & B|A ∨ B|A → B|A ↔ B|
|--|--|--|--|--|--|--|--|
|0|0|1|1|0|0|1|1|
|0|1|1|0|0|1|1|0|
|1|0|0|1|0|1|0|0|
|1|1|0|0|1|1|1|1|

### Законы:

A ∨ B = B ∨ A</br>
A & B = B & A

A ∨ (B ∨ C) = (A ∨ B) ∨ C<br>
A & (B & C) = (A & B) & C

A ∨ (B & C) = (A ∨ B) & (A ∨ C)</br>
A & (B ∨ C) = (A & B) ∨ (A & C)

$\overline{A}$ $\overline{∨}$ $\overline{B}$ = $\overline{A}$ ∧ $\overline{B}$</br>
$\overline{A}$ $\overline{∧}$ $\overline{B}$ = $\overline{A}$ ∨ $\overline{B}$

A ∨ (A & B) = A<br>
A & (A ∨ B) = A

A → B = $\overline{A}$ ∨ B

A ↔ B = (A → B) & (B → A)<br>
A ↔ B = ($\overline{A}$ → B) & ($\overline{B}$ → A)

</details>

---

<details>
<summary>Log</summary>
  
$log_{a} b = x \implies a^{x} = b$</br>
$b>0$; $a>0$; $a\neq1$

$lg(b)$ это $log_{10}b$</br>
$ln(b)$ это $log_{e}b$

### Основное log тождество:</br>
$a^{log_{a}b} = b$

### Свойства:</br>
$log_{a}1 = 0$</br>
$log_{a}a = 1$</br>
$log_{a}\frac{1}{a} = -1$</br>
$log_{a}a^{b} = b$</br>
$log_{a}b^{p} = p \times log_{a}b$</br>
$log_{a^{p}}b = \frac{1}{p} \times log_{a}{b}$</br>
$log_{a}b + log_{a}c = log_{a}(a \times b)$</br>
$log_{a}b - log_{a}c = log_{a}\frac{b}{c}$</br>

### Формула перехода к новому основанию:

$log_{a}b = \frac{log_{c}b}{log_{c}a}$</br>
$c>0; c\neq1$

</details>

---

<details>
<summary>Арифметический корень</summary>

$\sqrt[n]{a} = b \implies b^{n} = a$</br>
$a\geq0$; $b\geq0$; $n \in N$; $n \geq 2$

### Свойства:</br>

$\sqrt[n]{a^{m}} = a^{\frac{m}{n}}$</br>

$\sqrt[n]{a \times b} = \sqrt[n]{a} \times \sqrt[n]{b}$

$\sqrt[n]{\frac{a}{b}} = \frac{\sqrt[n]{a}}{\sqrt[n]{b}}$; $(b\neq0)$

$\sqrt[n]{\sqrt[m]{a}} = \sqrt[m \times n]{a}$

$\sqrt[n \times m]{a^{2m}} = \sqrt[n]{a^{2}}$

$(\sqrt[n]{a})^{n} = a$

$\sqrt[2n]{a^{2n}} = |a|$

</details>

---

<details>
<summary>Тригонометрия</summary>

| $\alpha$ | $0\degree$ | $\frac{\pi}{6} \ (30\degree)$ | $\frac{\pi}{4} \ (45\degree)$ | $\frac{\pi}{3} \ (60\degree)$ | $\frac{\pi}{2} \ (90\degree)$ | $\pi \ (180\degree)$ | $\frac{3\pi}{2} \ (270\degree)$ | $2\pi \ (360\degree)$ 
| -- | -- | -- | -- | -- | -- | -- | -- | -- |
| $sin(\alpha)$ | 0 | $\frac{1}{2}$ | $\frac{\sqrt[]{2}}{2}$ | $\frac{\sqrt[]{3}}{2}$ | $1$ | $0$ | $-1$ | $0$ |
| $cos(\alpha)$ | 1 | $\frac{\sqrt[]{3}}{2}$ | $\frac{\sqrt[]{2}}{2}$ | $\frac{1}{2}$ | $0$ | $-1$ | $0$ | $1$ |
| $tg(\alpha)$ | 0 | $\frac{\sqrt[]{3}}{3}$ | $1$ | $\sqrt[]{3}$ | $-$ | $0$ | $-$ | $0$ |
| $ctg(\alpha)$ | - | $\frac{3}{\sqrt[]{3}}$ | $1$ | $\frac{\sqrt[]{3}}{3}$ | $0$ | $-$ | $0$ | $-$ |

![](https://github.com/SuperFeda/formul/blob/main/snaki-4160711157.jpg)

### Основные тригонометрические тождества</br>
$sin^{2}(a) + cos^{2}(a) = 1$</br>

$tg(a) = \frac{sin(a)}{cos(a)}$</br>

$ctg(a) = \frac{cos(a)}{sin(a)}$</br>

$tg(a) \times ctg(a) = 1$</br>

$1 + tg^{2}(a) = \frac{1}{cos^{2}a}$</br>

$1 + ctg^{2}(a) = \frac{1}{sin^{2}a}$</br>

### Четность / нечетность</br>
$sin(-a) = -sin(a)$</br>
$cos(-a) = cos(a)$</br>
$tg(-a) = -tg(a)$</br>
$ctg(-a) = -ctg(a)$</br>

### Формулы сложения/вычитания</br>
$sin(a+b) = sin(a) \times cos(b) + cos(a) \times sin(b)$</br>
$sin(a-b) = sin(a) \times cos(b) - cos(a) \times sin(b)$</br>
$cos(a+b) = cos(a) \times cos(b) - sin(a) \times sin(b)$</br>
$cos(a-b) = cos(a) \times cos(b) + sin(a) \times sin(b)$</br>

$tg(a+b) = \frac{tg(a)+tg(b)}{1 - tg(a) \times tg(b)}$

$tg(a-b) = \frac{tg(a)-tg(b)}{1 + tg(a) \times tg(b)}$

$ctg(a+b) = \frac{-1 + ctg(a) \times ctg(b)}{ctg(a)+ctg(b)}$

$ctg(a-b) = \frac{-1 - ctg(a) \times ctg(b)}{ctg(a)-ctg(b)}$

### Формулы двойного угла</br>
$sin(2a) = 2sin(a) \times cos(a)$</br>
$cos(2a) = cos^{2}a - sin^{2}a$<br>
$cos(2a) = 1-2sin^{2}a = 2cos^{2}a-1$<br>

$tg(2a) = \frac{2tg(a)}{1-tg^{2}a}$<br>

### Свойства обратных тригонометрических функций<br>
$arcsin(-a) = -arcsin(a)$<br>
$arccos(-a) = \pi - arccos(a)$<br>
$arctg(-a) = -arctg(a)$<br>
$arcctg(-a) = -arcctg(a)$<br>

### Формулы корней тригонометрических функций
$sin(t) = a; t = (-1)^{k} \times arcsin(a) + \pi k, k \in Z$<br>
$cos(t) = a; t = \pm arccos(a) + 2 \pi k, k \in Z$<br>
$tg(t) = a; t = arctg(a) + \pi k, k \in Z$<br>
$ctg(t) = a; t = arcctg(a) + \pi k, k \in Z$<br>

</details>


