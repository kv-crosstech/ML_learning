# TODO list

Здесь будет TODO-список, обычно будет выполняться один пункт в день. Если вдруг пропустил какой то день и не запостил - можно с вероятностью в 50% на следующий день или в течение недели ждать две публикации подряд. Список постоянно пополняется по мере обсуждения планов с госпожой музой, а сроки выпуска статей могут корректироваться по мере тушения или воспламенения заднепроходной части тела.

### THE list
* полезные функции и комментарии с описанием работы в папке useful_stuff
* мемы - картинки и прочее в папке memes
* статьи в папке articles - markdown файлы и ссылки на них в README

## Articles
Порядок не особо важен, но я стараюсь учитывать его при составлении списка.

Рассчитываю, что у читателя перед прочтением есть некоторый базис общения с компьютером путём передачи ему команд посредством программного кода на языке Python. В статьях не будет слишком много кода, но все же настоятельно рекомендуется ознакомиться с основами программирования. Изучать Python можно по мере чтения.

Хорошим дополнением будет знание базовых терминов о машинном обучении, впрочем я постараюсь их раскрыть максимально подробно и наименее больно для читателя в первых двух-трёх статьях. Эта задача близка к невозможной, так что где-то придётся пожертвовать подробностью, а где-то читателям придётся испытать душевные и умственные страдания.

Статьи постараюсь заранее промечать по обилию кода, используемого в статье:
- ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) High code
- ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Medium code
- ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Low code
- _ No (or very little) code


### Собственно список статей связанных с машинным обучением, планирующихся к выпуску:
* _ Эпос о машинном обучении
* _/![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Рассказ о человеке с наставником, самоучке и о их друге, который просто любит подкрепиться
* ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Регрессия, классификация и другие смешные слова и не менее непонятные картинки
* ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) SQL, форматы хранения данных, Pandas. Часть 1: основы работы с табличными данными и некоторые методы ускорения/сжатия.
* ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Пособие для ленивых, или лёгкий старт на пути становления машинным специалистом
* ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Пособие для чуть более трудолюбивых, чем лентяи, или продолжение статьи про AutoML
* ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Learning the hard way. Scikit-Learn, Tensorflow. И другие английские (и не очень) термины.
* ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) ~~Трансгрессия~~ Регрессия
* ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Классификация и почему она лучше регрессии. Или не лучше. А может даже хуже. Хотя нет, всё таки лучше. Короче, всё ситуативно.
* ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Кластеризация - самое полезное из понятного и самое непонятое из непонятного
* ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Обучение с подкреплением. Часть 1: Чуть больше про openai, google и как игры помогают в решении практических задач.
* ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Обучение с подкреплением. Часть 2: Окружение, функция обратной связи, базовые примеры из библиотеки [openai/gym](https://github.com/openai/gym) и причём тут вообще качалка.
* ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Обучение с подкреплением. Часть 3: Делаем своё окружение и применяем AutoML для ультимативного решения поставленной задачи.
* ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) SQL, форматы хранения данных, Pandas. Часть 2: Работа с большими датасетами. Modin, dask, и плюсы наличия нескольких ядер центрального процессора в системе
* ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Пособие для чуть более богатых, но трудолюбивых лентяев, или как обучать модели сразу на нескольких вычислительных единицах. Часть 1. Optuna.
* ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Майнерам не заходить. Машинное обучение на графических процессорах: основы, преимущества и различия с классическим обучением.

## useful_stuff - плюшки для работы с питоном, обработкой данных и полезные библиотеки

* Полезные функции для обработки данных (строки, массивы, анализ SQL запросов)
* Полезные штуки для работы с Python. Краткие (и не очень) статьи про них
  * ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Как устанавливать разные проекты легко и непринуждённо: Менеджеры окружений. venv, conda, poetry
  * ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Интерактивное выполнение кода через IPython. Прелести и неудобства.
  * ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Работа с классами и зачем она нужна в python. Простые примеры структурирования проекта.
  * ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Глобальные/локальные переменные. Почему в проекте может возникнуть циклический импорт, перезаписаться переменные и прочее.
  * ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Аргументы командной строки, конфигурационные файлы. Зачем их едят и с чем они нужны.


