<h2><a href='yandex.ru'>Ссылка на сайт с проектом (версия на React)</a></h2
<hr/>


<blockquote>
Расскажите, чем, на ваш взгляд, отличается хорошее клиентское приложение от
плохого с точки зрения
  <ul>
    <li>
      пользователя;
    </li>
    <li>
      менеджера проекта;
    </li>
    <li>
      дизайнера;
    </li>
    <li>
      верстальщика;
    </li>
    <li>
      серверного программиста.
    </li>
  </ul>
</blockquote>
Для пользователя - удобство использования, скорость работы,<br/>
для менеджера проекта - масштабируемость,<br/>
для дизайнера - хорошо выполненный и фнукциональный дизайн,<br/>
для верстальщика - возможность переиспользовать компоненты, единообразность подхода,<br/>
для программиста - продуманность логики<br/>

<blockquote>
   Опишите основные особенности разработки крупных многостраничных сайтов, функциональность которых может меняться в процессе    реализации и поддержки.
   Расскажите о своем опыте работы над подобными сайтами: какие подходы, инструменты и технологии вы применяли на практике, с    какими проблемами сталкивались и как их решали.
</blockquote>  

Мой опыт разработки крупных многостраничных сайтов невелик. Насколько могу судить, необходимо особенно тщетельно
продумывать структуру и механизмы изменений и доработок.

<blockquote>
При разработке интерфейсов с использованием компонентной архитектуры часто
используются термины Presentational Сomponents и Сontainer Сomponents. Что
означают данные термины? Зачем нужно такое разделение, какие у него есть
плюсы и минусы?
</blockquote>
Если я правильно понял - это аналог деления на "Умные" и "Глупые" компоненты.<br/>
"Умные" знают о состоянии приложения, хранят его в state или подключены к Redux.<br/>
"Глупые" - напротив, знают только то, что им передали в props.<br/>
Обычно "Умные" хранятся в папке containers, а "Глупые" в сomponents<br/>

Плюсы: Лучшее разделение в решении проблем.
Лучше повторное использование.<br/>

Минусы: Больше времени идет на анализ и организацию структуры компонентов<br/>

<blockquote>
Как устроено наследование в JS? Расскажите о своем опыте реализации JSнаследования
без использования фреймворков.
</blockquote>    
Наследование в JS прототипное. Если в свойстве {Объект1}._proto_ указать некоторый другой объект, то Объект1
становится наследником другого объекта, и получает возможность пользоваться его методами.


<blockquote>  
Какие библиотеки можно использовать для написания тестов end-to-end во
фронтенде? Расскажите о своем опыте тестирования веб-приложений.
</blockquote>    
Тестирование сейчас находится в процессе активного освоения. Думаю, очень скоро смогу ответить на этот вопрос)

<blockquote>  
Вам нужно реализовать форму для отправки данных на сервер, состоящую из
нескольких шагов. В вашем распоряжении дизайн формы и статичная верстка, в
которой не показано, как форма должна работать в динамике. Подробного
описания, как должны вести себя различные поля в зависимости от действий
пользователя, в требованиях к проекту нет. Ваши действия?
</blockquote>    
Постараюсь уточнить, каково поведение формы. Если уточнить не получается,
реализую базовый функционал (простейшие валидации и т.п.), возможно подойдет этот вариант.
Когда появится возможность уточнить, доработаю так, как надо.

<blockquote>  
Расскажите, какие инструменты помогают вам экономить время в процессе
написания, проверки и отладки кода.
</blockquote>    
Глубоко убежден, что лучший способ экономии времени - это тщательное продумывание структуры модели данных и поведения программы.

<blockquote>  
Какие ресурсы вы используете для развития в профессиональной сфере? Приведите
несколько конкретных примеров (сайты, блоги и так далее).
Какие ещё области знаний, кроме тех, что непосредственно относятся к работе,
вам интересны?
</blockquote>    
Tproger, Toster, habra, некоторые испаноязычные ресурсы, читаю книги по интересным мне технологиям.
Также увлекаюсь матэ, боксом, хорошей литературой, верховой ездой.

<blockquote>  
Расскажите нам немного о себе и предоставьте несколько ссылок на последние
работы, выполненные вами.
</blockquote>    

Меня зовут Вадим. Уже много лет живу в Аргентине. Окончил МГТУ им. Баумана в 2007 году.
Люблю животных. Много работаю, стараюсь это делать хорошо.
