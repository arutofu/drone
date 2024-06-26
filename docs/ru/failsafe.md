# Настройка Failsafe

Во вкладке *Safety* настраиваются реакции дрона на различные нештатные ситуации. Рекомендуется включить как минимум реакцию на потерю связи с пультом управления:

1. В программе QGroundControl перейдите в панель *Vehicle Setup* и выберите меню *Safety*.
2. В блоке *RC Loss Failsafe Trigger* выберите один из рекомендуемых вариантов реакции на потерю связи с пультом:
   * *Land mode* – переход в режим посадки;
   * *Terminate* – аварийное отключение моторов.
3. В поле *RC Loss Timeout* выберите значение таймаута, по истечении которого связь с пультом считается потерянной. Рекомендуемое значение – 2 s.

<img src="../assets/qgc-failsafe.png" alt="QGroundControl failsafe" class="zoom">
