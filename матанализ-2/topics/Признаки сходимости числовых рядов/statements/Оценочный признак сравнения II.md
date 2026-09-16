#statement 

---

**Теорема**. Пусть $\displaystyle \sum_{n=1}^\infty a_n$  и $\displaystyle \sum_{n=1}^\infty b_n$ — два [[Числовые ряды|ряда]] с [[Абсолютная и условная сходимость#^4b51f5|положительными]] членами и $\displaystyle \frac{a_{n+1}}{a_n} \le \frac{b_{n+1}}{b_n}$ ([[Критерий сходимости числовых рядов через остатки#^9c927f|начиная]] с некоторого $N$). Тогда
1. из сходимости $\displaystyle \sum_{n=1}^\infty b_n$ следует сходимость $\displaystyle \sum_{n=1}^\infty a_n$ 
2. из расходимости $\displaystyle \sum_{n=1}^\infty a_n$ следует расходимость $\displaystyle \sum_{n=1}^\infty b_n$ 

---

## Доказательство
#proof 

Отбросим первые $N$ слагаемых рядов.
Распишем неравенства $\displaystyle \frac{a_{i+1}}{a_i} \le \frac{b_{i+1}}{b_i}$ для всех $i = 1, \dots n$ и перемножим, получим
$$
\frac{a_{n+1}}{a_1} \le \frac{b_{n+1}}{b_1} \iff a_{n+1} \le \frac{a_1}{b_1} \cdot b_{n+1}.
$$
И дальше утверждение теоремы вытекает из [[Оценочный признак сравнения|оценочного признака сравнения]].

$$ \begin{flalign*} && \blacksquare \end{flalign*} $$