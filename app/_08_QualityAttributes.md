# Атрибуты качества

Наше приложение - это по большей части гибрид ассистента тренировок и социальной сети, поэтому, предполагается большое
количество пользователей. Соответственно, приложение должно быть интуитивно понятным, легким для освоения, при этом
предполагается, что пользователи будут во всех часовых поясах, поэтому оно должно быть высоко доступным. Т.к. мы храним
персональные данные пользователей, то оно должно быть еще и хорошо защищено. А чтобы выдерживать высокие нагрузки, мы
должны иметь возможность легко масштабироваться и дорабатываться в случае нахождения "бутылочных горлышек" в наших
сервисах.

Из приведенных выше доводов, можно получить следующие атрибуты качества:
**Пользовательское приложение** должно обладать следующими атрибутами:

1. Удобство работы
2. понятность
3. устойчивость к отказам

для **социальной части** нашего приложения и **тренера** важно:

1. Защищенность
2. Удобство изменений
3. способность к восстановлению
4. устойчивость к отказам

**Для IoT:**

1. Удобство изменений
2. устойчивость к отказам
3. способность к восстановлению
4. Эффективность использования ресурсов

IoT должен будет принимать множество данных в реальном времени и успевать их обрабатывать, при этом можно на уровне
самого IoT сделать данные обезличенными, что позволяет нам отказаться от защищенности в пользу более быстрой и
эффективной работы.


