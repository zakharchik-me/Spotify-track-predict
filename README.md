# Spotify-track-predict
Classic ML В качестве тестового предлагается предсказать популярность песни на Spotify по её характеристикам c помощью этого датасета.

Была выбрана модель - Decission Tree classifier

Дан датасет аудиозаписей из спотифай(исполнитель, название, ритм, длительность, и др) Требуется предсказать популярность

Анализирум дс, вычленяем целевую переменную, избавляемся от сильно сколлерированных (независимых) переменных, str->int ячейки Строим графики зависимости точности предсказания от глубины дерева (проверка на under/overfitting)
