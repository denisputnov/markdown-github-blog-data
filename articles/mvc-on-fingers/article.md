Приветики-пистолетики. Вот так вот интересно зайду сегодня, могу себе позволить. 
В этом посте хочу поговорить о такой прекрасной штуке, как _MVC_ в применении к веб-разработке. Крайне популярная тема для всей Front-End движухи в принципе, которую требуют знать практически у каждого джуна. Поэтому сегодня об этом.

_MVC_ — это паттерн проектирования. Аббревиатура от слов *Model, View, Controller*. И, несмотря на такую большую распространненность и важность в целом, всё максимально просто. Суть заключается в том, что приложение разбивается на 3 блока, каждый из которых имеет свои функции. Три этих блока, соответственно, — модель, представление и контроллер. 

Рассмотрим каждый из блоков отдельно: 
- Модель — это блок, который отвечает за данные нашего приложения, и, по сути, во многом определяет его. Этот блок кода определяет данные и способы взаимодействия с ними.
- Представление — блок, который отвечает исключительно за представление наших данных. Этот блок кода отвечает только за то как будет выглядеть наше приложение и не несет в себе никакой бизнес-логики.
- Контроллер — блок, который организовывает взаимодействие модели и представления. В контроллере мы вешаем прослушку событий, взаимодействуем с данными и в целом организуем в этом блоке всю бизнес-логику нашего приложения.

**На примере:**
Ноутбук:  монитор (представление), память (модель), и процессор (контроллер)
Ресторан: вкусный кофе (представление), официант (контроллер), и повар (модель)

Кофе - представление, тут вопросов быть не должно.
Повар - модель, потому что именно он знает как сварить великолепный кофе.
Официант - связующее звено. Он никак не влияет на данные, никак не влияет на сам кофе. Просто перемещает его.

На таких тривиальных примерах можно уйти гораздо дальше, и я надеюсь, что каждому хватит интереса на это. 

Спасибо за прочтение, это важно ❤️