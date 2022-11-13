# Русификация LaTeX документов в Quarto с последующей компиляцией в pdf

1. Установите [Quarto](https://quarto.org/docs/download/) 

2. Загрузите в папку с проектом файл `template.tex` 

3. Подготовьте **Quarto**-документ по образцу `sample.qmd`, указав в преамбуле документа

```
lang: ru
...
pdf:
  template: template.tex
  ...
```

4. Отрендерите проект командой `quarto render sample.qmd --to pdf`

Возможно, необходимо установить `tlmgr install babel-russian`

Автор идеи русификации -- С.В. Бабёнышев ([@SBabenyshev](https://twitter.com/SBabenyshev))
