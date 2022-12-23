Функционал конструктора:

С левой панели конструктора открываются настройки страницы (правая панель) в которых можно задать такие настройки как:

-	Название страницы и значения мета тегов таких как описание страницы и ключевые слова для поисковика, эти теги для SEO.
-	Ширину контейнера содержащего контент сайта, можно задать на всю ширину экрана либо размер в пикселях.
-	Задний фон контейнера, можно задать один цвет, градиент из двух цветов с настраиваемым углом, и там и там также настраиваются прозрачность заднего фона. Также можно поставить любое видео с ютуба на задний фон, вставив ссылку, здесь можно настроить со звуком видео или без и зациклить видео (будет начинаться с начала когда закончится). Видео будет на всю ширину экрана, не контейнера.

На левой панели конструктора располагаются модули которые можно перетягивать мышкой, первый модуль это главный блок, только в него можно вставлять все остальные кроме него самого, главный модуль вставляется только в контейнер, а в контейнер вставляются только главные блоки. Их четыре разновидности на левой панели с одной, 2, 3 и 4-мя секциями, количество секций меняется непосредственно в настройке блока + и -(всплывают при наведении курсора на блок в правом верхнем углу), максимальное количество 12 (по сетке бутстрапа), сам блок и каждая секция соответствуют определенному классу bootstrap для адаптивности под разные устройства, секции переносятся вниз на определённых точках ширины экрана в пикселях, на мобильном устройстве например каждая секция будет на новой строке. Ширину и высоту блока и ширину каждой секции можно регулировать, двигая границу блока мышкой (как окно на компьютере). При наведении курсора на блок в правом верхнем углу всплывает панель управления блоком, на которой есть кнопки удалить элемент (крестик), скопировать элемент со всеми его настройками (значок копирования), добавить/удалить одну секцию (+/-), открыть меню настройки главного блока в правой панели (шестерёнка).

В настройках главного блока (правой панели) можно задать (при помощи текстовых, числовых полей, полей для цвета): такие настройки как:

-	Внешние и внутренние отступы главного блока сверху/справа/снизу и слева.
-	Задний фон главного блока, можно задать один цвет, градиент из двух цветов с настраиваемым углом, и там и там также настраиваются прозрачность заднего фона блока. Также можно поставить любое видео с ютуба на задний фон, вставив ссылку, здесь можно настроить со звуком видео или без и зациклить видео (будет начинаться с начала когда закончится). Видео будет на всю ширину главного блока.
-	Толщину, стиль (сплошная, штрих-пунктирная, двойная..), цвет, закругление углов по радиусу всех границ главного блока или каждой по отдельности.
-	Настройку тени к блоку, сделать её внутренней или внешней, задать вертикальное, горизонтальное смещения, размытие, размах тени, цвет тени и её прозрачность.
-	Анимация блока, можно выбрать любую понравившуюся анимацию из выпадающего списка, задать ей задержку и длительность. Все анимации из библиотеки animate.css. Анимация будет видна только на странице предпросмотра (ссылка в левом верхнем углу на странице конструктора), на странице конструктора библиотека не подключена.
-	Скрытие блока – установка часов, минут и секунд от настоящего времени через которые блок появится на странице, работает на странице предпросмотра.

Второй модуль это контентный блок, он абсолютно идентичен главному блоку и у него все те же настройки что и у главного, за исключением видео на заднем фоне. Разница между ними в том что главный блок вставляется непосредственно и только в контейнер, а контентный блок только в секции главного блока которых может быть от 1 до 12 и в каждой секции может быть неограниченное количество контентных блоков.

Далее контентные модули –линия, список, форма, форма подписки, текст, картинка, видео и кнопка. Общее у них то что любые модули можно вставить в любую секцию как главного так и контентного блока в неограниченном количестве, ширина высота любого модуля регулируются мышкой (как окно на компьютере). При наведении курсора на модуль в правом верхнем углу всплывает панель управлени, на которой есть кнопки удалить элемент (крестик), скопировать элемент со всеми его настройками (значок копирования), прижать элемент к правой/левой границе (значки вправо/влево), расположить элемент по центру горизонтали секции (значок выравнивания текста), открыть меню настройки главного блока в правой панели (шестерёнка).Любой модуль можно настроить открыв его настройки в правой панели, общие настройки (присутствуют в любом модуле):

-	Внешние и внутренние отступы элемента сверху/справа/снизу и слева, выравнивание по вертикали – расположить элемент по центру либо прижать его к верху/низу секции.
-	Анимация элемента, можно выбрать любую понравившуюся анимацию из выпадающего списка, задать ей задержку и длительность. Все анимации из библиотеки animate.css. Анимация будет видна только на странице предпросмотра (ссылка в левом верхнем углу на странице конструктора), на странице конструктора библиотека не подключена.
-	Скрытие блока – установка часов, минут и секунд от настоящего времени через которые элемент появится на странице, работает на странице предпросмотра.

Также есть уникальные настройки для конкретного модуля. В модуле списка помимо общих настроек также есть:

-	Выбор иконки для строк списка, представлено 4 варианта.
-	Возможность добавления/удаления и редактирования содержимого строки списка
-	Настройка расстояния между строками списка
-	Настройки шрифта – выбор шрифта, его размер и цвет, межстрочный интервал. Также настройка тени шрифта, её горизонтальное, вертикальное смещение, размытие и прозрачность

В модуле линии:

-	Настройки толщины линии, её цвет и стиль (сплошная, двойная, штрих-пунктирная..)
-	Выбор линии, обычная html линия или картинка линии, представлено 5 вариантов.

В форме подписки:

-	Можно вставить код рассылки для формы подписки, конструктор сам определяет количество полей в форме и делает возможным их настройку (placeholder в каждом поле, обязательное/необязательное поле, имя поля).
-	Настройка самой формы – метод get/post, url где форма будет обрабатываться.
-	Настройка полей формы - placeholder, обязательное/необязательное поле, имя поля
-	По отдельности настраиваются кнопка отправки и поля формы. На кнопке отправки можно отредактировать текст, в стандартном варианте текст на кнопке - «Подписаться», 
-	Настройки шрифта на кнопке– выбор шрифта, его размер и цвет, межстрочный интервал. Также настройка тени шрифта, её горизонтальное, вертикальное смещение, размытие и прозрачность
-	Устанавливается цвет, размер кнопки и границы кнопки - толщину, стиль (сплошная, штрих-пунктирная, двойная..), цвет, закругление углов по радиусу всех границ или каждой по отдельности.
-	В полях формы можно настроить расстояние между полями, цвет полей - можно задать один цвет, градиент из двух цветов с настраиваемым углом, и там и там также настраиваются прозрачность заднего фона.
-	Границы полей формы подписки - толщину, стиль (сплошная, штрих-пунктирная, двойная..), закругление углов по радиусу всех границ или каждой по отдельности.
-	Настройка тени к форме подписки, можно сделать её внутренней или внешней, задать вертикальное, горизонтальное смещения, размытие, размах тени, цвет тени и её прозрачность.

Модуль формы идентичен форме подписки, за исключением возможности вставить код рассылки.

В модуле текста:

-	При клике по самому модулю появляется редактор текста прямо над текстом, в котором можно отредактировать основные параметры текста как в ворде, такие как жирный текст, курсив, подчеркнутый, зачеркнутый, выровнять текст по левому/правому краям, по центру и по ширине. Также можно вставить ссылку на какой-либо ресурс.
-	В настройках текста (в правой панели) задается простой это будет текст или один из 6-и заголовков (h1 – h6)
-	Настройки шрифта текста – выбор шрифта (), его размер и цвет, межстрочный интервал. Также настройка тени шрифта, её горизонтальное, вертикальное смещение, размытие и прозрачность.
-	Реализована возможность заливки текста любым цветом.

В модуле картинки:

-	Заливка изображений на сервер не доделана со стороны бэкенда, нет возможности закачивать изображения на сервер и выводить их списком. Со стороны фронтенда реализована возможность выбора картинки (представленно 6 штук).
-	Есть возможность переключать пропорциональность картинки (если нужно например растянуть её на весь блок не оставляя пустого пространства)
-	Настройка границы  картинки - толщина, стиль (сплошная, штрих-пунктирная, двойная..), цвет, закругление углов по радиусу всех границ или каждой по отдельности.
-	Настройку тени к картинке, сделать её внутренней или внешней, задать вертикальное, горизонтальное смещения, размытие, размах тени, цвет тени и её прозрачность.

В модуле видео (само видео подключается только на странице предпросмотра):

-	Реализована возможность вставки видео с ютуба, вимео и есть возможность добавить код любого понравившегося плеера.
-	Для ютуба и вимео можно включать/отключать автовоспроизведение, скрыть/показать панель управления видео.
-	Настройка границы  видео - толщина, стиль (сплошная, штрих-пунктирная, двойная..), цвет, закругление углов по радиусу всех границ или каждой по отдельности.
-	Настройка тени к видео, сделать её внутренней или внешней, задать вертикальное, горизонтальное смещения, размытие, размах тени, цвет тени и её прозрачность.

В модуле кнопки:

-	На кнопке можно отредактировать текст, в стандартном варианте текст на кнопке - «Кликните чтобы продолжить» 
-	Настройки шрифта на кнопке– выбор шрифта, его размер и цвет, межстрочный интервал. 
-	Устанавливается задний фон кнопки цвет/градиент из двух цветов с настраиваемым углом, и там и там также настраиваются прозрачность заднего фона.
-	Настройка размера границы кнопки - толщину, стиль (сплошная, штрих-пунктирная, двойная..), цвет, закругление углов по радиусу всех границ или каждой по отдельности.
-	Настройка тени к кнопке, сделать её внутренней или внешней, задать вертикальное, горизонтальное смещения, размытие, размах тени, цвет тени и её прозрачность.
-	Также реализована возможность превратить кнопку в ссылку на любой ресурс.

При переходе по ссылке «Предпросмотр» в левом верхнем углу открывается страница предпросмотра – как будет выглядеть сайт в окончательном варианте, с видео, анимацией, скрытием блоков. 
