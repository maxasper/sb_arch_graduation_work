# Концептуальная архитектура

Наше новое приложение будет состоять из:

1. пользовательского приложения, которое будет получать информацию из таких компонентов, как социальная сеть и ассистент
   тренировок.
2. Компонент "Социальная сеть" будет предоставлять возможности пользователям вступать в группы, участвовать в
   соревнованиях, общаться, добавлять друзей, подписываться на людей итд. Внутри социальной сети можно выделить
   компонент "Пользователь" - как главную составляющую социальной сети и компонент, отвечающий за социальные
   взаимодействия.
3. Ассистент тренировок - компонент, отвечающий за тренировки пользователя. Ведет статистику тренировок, помогает
   составлять программу. По каждой программе хранит список необходимого инвентаря и одежды, место тренеровок итд
4. IoT - компонент, отвечающий за получение данных сторонних датчиков о показателях тела а также фитнес-данные и jps с
   телефона.

Все бэк-компоненты будут иметь возможность взаимодействовать с существующими сервисам. Как забрать, какие-то данные,
например информацию о тренировках из специализированных спортивных приложений, так и предоставлять данные о
пользователях другим сервисам, например профили пользователей и профили программ тренировок.
