| Statements                                                                      | Branches                                                                    | Functions                                                                   | Lines                                                                 |
| ------------------------------------------------------------------------------- | --------------------------------------------------------------------------- | --------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| ![Statements](https://img.shields.io/badge/statements-99.02%25-brightgreen.svg) | ![Branches](https://img.shields.io/badge/branches-98.63%25-brightgreen.svg) | ![Functions](https://img.shields.io/badge/functions-100%25-brightgreen.svg) | ![Lines](https://img.shields.io/badge/lines-99.02%25-brightgreen.svg) |

# Игра «Жизнь»

### [Wiki - Игра "Жизнь"](https://ru.wikipedia.org/wiki/%D0%98%D0%B3%D1%80%D0%B0_%C2%AB%D0%96%D0%B8%D0%B7%D0%BD%D1%8C%C2%BB)

Домашнее задание по курсу Otus Js-basic-course

## Описание:

- Поле с настройками размера по вертикали и горизонтали, а так же скоростью игры.
- При нажатии на кнопку "Start game" - игра запускается.
- При нажатии на кнопку "Stop game" - останавливается.
- Чёрным цветом отображаются живые клетки.
- Синим - те что погибнут в следующем поколении.
- Белым - мёртвые клетки.

### Игра прекращается, если:

- на поле не останется ни одной «живой» клетки
- конфигурация на очередном шаге в точности (без сдвигов и поворотов) повторит себя же на одном из более ранних шагов
  (складывается периодическая конфигурация)
- при очередном шаге ни одна из клеток не меняет своего состояния
  (складывается стабильная конфигурация; предыдущее правило, вырожденное до одного шага назад)
