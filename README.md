# Проектная работа: "Путешествие по России".

## Создана в рамках учебы в [Яндекс.Практикум](https://praktikum.yandex.ru/) на курсе ["Веб-разработчик"](https://praktikum.yandex.ru/web/).


## Описание:

Проект о путешествии по России. Проект полностью адаптивный и подстраивается под любое разрешение экрана устройства.
Все изоброжения оптимизированны на [сайте доброй панды](https://tinypng.com).

[Посмотреть на GitHub Pages](https://sevamarkov88.github.io/russian-travel/)

## Технологии:
![HTML](https://img.shields.io/badge/-HTML-05122A?style=flat&logo=HTML5)&nbsp;
![CSS](https://img.shields.io/badge/-CSS-05122A?style=flat&logo=CSS3&logoColor=1572B6)&nbsp;
![Git](https://img.shields.io/badge/-Git-05122A?style=flat&logo=git)&nbsp;
![GitHub](https://img.shields.io/badge/-GitHub-05122A?style=flat&logo=github)&nbsp;
![Visual Studio Code](https://img.shields.io/badge/-Visual%20Studio%20Code-05122A?style=flat&logo=visual-studio-code&logoColor=007ACC)&nbsp;

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
## Инструкция по установке:

Клонировать репозиторий:

`
git clone https://github.com/SevaMarkov88/russian-travel.git
`
