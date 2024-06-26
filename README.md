# Проект "Feature importance для моделей логистической регресии и градиентного бустинга"

## 🎯 Цели проекта:
1. **Отбор признаков для обучения моделей логистической регрессии и градиентного бустинга:**
    - Применены разнообразные методы, включая фильтрующий метод (на основе Information Value и Gain importance для градиентного бустинга) и оберточные методы (RFE, алгоритм Boruta).
    - Реализован алгоритм Stepwise для оптимизации отбора признаков.

2. **Линеаризация признаков для обучения логистической регрессии:**
    - Проведена линеаризация признаков по Woe.
    - Построены графики, демонстрирующие линейность полученных признаков.

3. **Анализ стабильности признаков по времени:**
    - Построены графики, отображающие стабильность признаков во времени.

4. **Подбор оптимальных параметров для градиентного бустинга:**
    - Использована библиотека optuna для подбора оптимальных гиперпараметров.

## 🛠 Используемые библиотеки:
- Pandas
- NumPy
- scikit-learn
- Optuna
- LightGBM
- Matplotlib
- Seaborn
- Boruta
- Plotly
- SciPy

## 📈 Результаты и выводы:
- Реализация алгоритма Stepwise, вместе с другими методами, позволила сократить количество признаков для логистической регрессии с 87 до 17 без ущерба качеству.
- Для градиентного бустинга, благодаря грамотному подбору гиперпараметров и использованию отбора по IV, RFE и Boruta, количество признаков уменьшилось с 230 до 53 без ухудшения качества модели.

Этот проект подчеркивает важность правильного отбора признаков и их линеаризации для успешного построения моделей машинного обучения.
