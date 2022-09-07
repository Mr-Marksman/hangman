# Виселица

Небольшая игра на отгадывание слов по буквам.

Правила: Игроку дается случайное слово, буквы которого закрыты. 
Игрок должен предлагать по одной букве русского алфавита, чтобы отгадать слово (Е - Ё и И - Й считаются одинаковыми буквами)
Если загаданная игроком буква присутствует в слове, то она открывается везде, где присутствует.
Если же буквы нет в слове, то игроку засчитывается ошибка - всего можно совершить 7 ошибок, после чего игра прекращается, игрок проигрывает.
Если же игроку удалось открыть все слово целиком, при этом не превысив лимит ошибок, то игрок считается победителем.

Программа использует гем `bundler` для работы. Чтобы установить все необходимые библиотеки введите в консоли:
```
gem bundler install
bundle install
```
Чтобы запустить игру:
```
bundle exec ruby main.rb 
```

Так же у Вас есть возможность добавить свои слова. Для этого откройте файл `data/words.txt` и допишите слово в пустой строке заглавными буквами
Внимание! Слово должно быть именем существительным, нарицательным в именительном падеже единственного числа, либо множественного числа при отсутствии у слова формы единственного числа.

Подробнее об игре "Виселица": https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0_(%D0%B8%D0%B3%D1%80%D0%B0)
