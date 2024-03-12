## Порівняння методів обчислення визначеного інтегралу: Метод Монте-Карло та `scipy.integrate.quad`

### Результати обчислень

- **Метод `scipy.integrate.quad`**: Визначений інтеграл функції \(y = \log(x)\) на інтервалі від 20 до 80 дорівнює приблизно 230.6475 з оцінкою помилки \(2.6 \times 10^{-11}\).
- **Метод Монте-Карло**: Визначений інтеграл тієї ж функції дорівнює приблизно 230.6687, використовуючи 15000 випадкових точок та 100 експериментів для обчислень.

### Висновок

Обидва методи, `scipy.integrate.quad` і метод Монте-Карло, демонструють високу точність у обчисленні визначеного інтегралу функції \(y = \log(x)\) на заданому інтервалі. Результати, які вони надають, є порівнянно близькими.

- **`Scipy.integrate.quad`** є детермінованим методом для обчислення інтегралів, а також надає оцінку помилки.
- **Метод Монте-Карло**, будучи статистичним методом, менш точний при малих обсягах даних, але його точність висока за достатньо великої кількості випадкових точок та експериментів, що доводить даний приклад.
