# Проект: Путешествие по России

### Обзор
* Интро
* Технологии

**Интро**

Здесь будет проект о путешествии по России и не простой а адаптивный.
Все изоброжения оптимизированны на [сайте доброй панды](https://tinypng.com).


**Технологии**

1. Grid Layout
```css
.photo-grid {
  max-width: 1184px;
  margin: 92px auto 0;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(284px, 1fr));
  gap: 16px;
}
```
2. Медиазапросы
```css
@media (max-width: 1024px) {
  .photo-grid {
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 14px;
    margin-left: 48px;
  }

  .cover__title {
    margin-top: 195px;
  }

  .cover__subtitle {
    margin-bottom: 195px;
  }

  .footer {
    margin-left: 48px;
    margin-right: 48px;
  }
}
```
