[ROS](https://www.ros.org)-based framework, providing user-friendly tools to control [PX4](https://px4.io)-powered drones. Clover is available as a ROS package, but is shipped mainly as a preconfigured image for Raspberry Pi. Once you've installed Raspberry Pi on your drone and flashed the image to its microSD card, taking the drone up in the air is a matter of minutes.

## Preconfigured image for Raspberry Pi.

🟡 - просмотрно/требует изменений
🔴 - убрать
🟢 - готово

## Ссылки

Техническая поддержка

## Содержание

* 🟡[Введение](docs/ru/README.md)
* 🟡[Глоссарий](docs/ru/glossary.md)
* 🟢[Безопасность](docs/ru/safety.md)
* 🟡[Сборка](docs/ru/assembly.md)
  * 🔴[Клевер 4.2 Pro](docs/ru/assemble_4_2_pro.md)
  * 🔴[Клевер 4.2](docs/ru/assemble_4_2.md)
  * 🔴[Клевер 4.2 WorldSkills](docs/ru/assemble_4_2_ws.md)
  * 🔴[Клевер 4.1](docs/ru/assemble_4_1.md)
  * 🔴[Клевер 4](docs/ru/assemble_4.md)
  * 🔴[Клевер 3](docs/ru/assemble_3.md)
  * 🔴[Клевер 2](docs/ru/assemble_2.md)
  * 🟡[Дрон 1](docs/ru/assemble_drone1)
  * 🟡[Дрон 2](docs/ru/assemble_drone2)
  * 🟡[Дрон 3](docs/ru/assemble_drone3)
* 🟡[Настройка](docs/ru/setup.md)
  * 🟡[Калибровка датчиков](docs/ru/calibration.md)
  * 🟢[Настройка пульта](docs/ru/radio.md)
    * 🟡[Работа с FS-A8S](docs/ru/rc_flysky_a8s.md)
  * 🟢[Полетные режимы](docs/ru/modes.md)
  * 🟡[Настройка питания](docs/ru/power.md)
  * 🟢[Настройка Failsafe](docs/ru/failsafe.md)
* 🟡[Ручной полет](docs/ru/flight.md)
  * 🟢[Упражнения](docs/ru/flight_exercises.md)
* 🟢[Работа с Raspberry Pi](docs/ru/raspberry.md)
  * 🟡[Образ для RPi](docs/ru/image.md)
  * 🟡[Подключение по Wi-Fi](docs/ru/wifi.md)
  * 🟡[Подключение к Pixracer](docs/ru/connection.md)
  * 🟡[QGroundControl по Wi-Fi](docs/ru/gcs_bridge.md)
  * 🟢[SSH-доступ](docs/ru/ssh.md)
  * 🟡[Командная строка](docs/ru/cli.md)
  * 🟡[Автоматическая проверка](docs/ru/selfcheck.md)
  * 🟢[Просмотр видеострима с камер](docs/ru/web_video_server.md)
* 🟢[Программирование](docs/ru/programming.md)
  * 🟢[Настройка камеры](docs/ru/camera_setup.md)
  * 🟢[Визуальные маркеры (ArUco)](docs/ru/aruco.md)
    * 🟢[Распознавание маркеров](docs/ru/aruco_marker.md)
    * 🟢[Навигация по карте маркеров](docs/ru/aruco_map.md)
  * 🟢[Навигация по Optical Flow](docs/ru/optical_flow.md)
  * 🟢[Автономный полет (OFFBOARD)](docs/ru/simple_offboard.md)
  * 🟢[Системы координат](docs/ru/frames.md)
  * 🟢[Примеры кода](docs/ru/snippets.md)
  * 🟡[Лазерный дальномер](docs/ru/laser.md)
  * 🟢[Светодиодная лента](docs/ru/leds.md)
  * 🟢[Работа с GPIO](docs/ru/gpio.md)
  * 🟢[Ультразвуковой дальномер](docs/ru/sonar.md)
  * 🟢[Компьютерное зрение](docs/ru/camera.md)
  * 🔴[Визуализация с помощью rviz и rqt](docs/ru/rviz.md)
  * 🟢[Автозапуск ПО](docs/ru/autolaunch.md)
  * 🟢[Использование JavaScript](docs/ru/javascript.md)
  * 🟢[Блочное программирование](docs/ru/blocks.md)
  * 🔴[Симулятор](docs/ru/simulation.md)
    * 🔴[Сборка на собственной машине](docs/ru/simulation_native.md)
    * 🔴[Установка виртуальной машины](docs/ru/simulation_vm.md)
    * 🔴[Использование симулятора](docs/ru/simulation_usage.md)
    * 🔴[Установка на компьютеры c M1](docs/ru/simulation_m1.md)
  * 🟢[ROS](docs/ru/ros.md)
  * 🟢[MAVROS](docs/ru/mavros.md)
* 🟢[Дополнительные материалы](docs/ru/supplementary.md)
  * 🟢[COEX Pix](docs/ru/coex_pix.md)
  * 🟢[COEX PDB](docs/ru/coex_pdb.md)
  * 🟢[COEX GPS](docs/ru/coex_gps.md)
  * 🟢[Радио-телеметрия](docs/ru/radio_telemetry.md)
  * 🟡[Камера Hawk Eye](docs/ru/hawk_eye.md)
  * 🟢[Гид по автономному полету](docs/ru/auto_setup.md)
  * 🟢[Имя хоста](docs/ru/hostname.md)
  * 🔴[Симулятор](docs/ru/sitl.md)
  * 🟢[Настройка PID](docs/ru/pid_tuning.md)
  * 🟡[Навигация по настенным маркерам](docs/ru/wall_aruco.md)
  * 🟡[CAD-модели](docs/ru/models.md)
  * 🔴[Docker-контейнер с симулятором](docs/ru/sitl_docker.md)
  * 🔴[Установка ROS Melodic](docs/ru/ros-install.md)
  * 🟢[Калибровка камеры](docs/ru/camera_calibration.md)
  * 🟢[Подключение к VPN ZeroTier](docs/ru/zerotier_vpn.md)
  * 🟢[Подключение к VPN Hamachi](docs/ru/hamachi_vpn.md)
  * 🟢[Управление мультикоптером при помощи 4G связи](docs/ru/4g.md)
  * 🟢[Jetson Nano](docs/ru/jetson_nano.md)
  * 🔴[Пилотирование со смартфона](docs/ru/rc.md)
  * 🟢[Настройка сети RPi](docs/ru/network.md)
  * 🟢[Интерфейс UART](docs/ru/uart.md)
  * 🟢[Параметры PX4](docs/ru/parameters.md)
  * [Работа с логами PX4](docs/ru/flight_logs.md)
  * [Прошивка PX4](docs/ru/firmware.md)
  * [Протокол MAVLink](docs/ru/mavlink.md)
  * [Использование мультиметра](docs/ru/test_connection.md)
  * [Неисправности радиоаппаратуры](docs/ru/radioerrors.md)
  * 🟢[Прошивка ESC контроллеров](docs/ru/esc_firmware.md)
  * [Взаимодействие с Arduino](docs/ru/arduino.md)
  * [Подключение GPS](docs/ru/gps.md)
  * [Работа с ИК датчиками](docs/ru/ir_sensors.md)
  * 🔴[Установка FPV](docs/ru/fpv_clover_4_2.md)
  * 🔴[Установка FPV (Клевер 3)](docs/ru/fpv.md)
  * [Магнитный захват](docs/ru/magnetic_grip.md)
  * [Механический захват](docs/ru/mechanical_grip.md)
  * [Груз для магнитного захвата](docs/ru/magnetic_grip_load.md)
  * [Сборка шаровой защиты](docs/ru/sphere_guard.md)
  * [Управление в режиме тренера](docs/ru/trainer_mode.md)
  * [Техника лужения](docs/ru/tinning.md)
  * [Подключение PX4FLOW](docs/ru/px4flow.md)
  * [Типы силовых разъемов](docs/ru/connectortypes.md)
  * [Модуль ESP8266](docs/ru/esp8266_bridge.md)
  * 🔴[Сборка и модификация образа Клевера](docs/ru/image_building.md)
  * [Подключение регулятора 4 в 1](docs/ru/4in1.md)
  * [Светодиодная лента (legacy)](docs/ru/leds_old.md)
  * 🔴[Вклад в Клевер](docs/ru/contributing.md)
  * [Репозиторий пакетов COEX](docs/ru/packages.md)
  * [Тестирование Клевера](docs/ru/testing.md)
  * 🔴[Переход на версию 0.20](docs/ru/migrate20.md)
  * 🔴[Переход на версию 0.22](docs/ru/migrate22.md)
  * [COEX DuoCam](docs/ru/duocam.md)
    * [Виртуальная MAVLink-камера](docs/ru/duocam_mavlink.md)
    * [Настройка DuoCam](docs/ru/duocam_setup.md)
* 🔴[Мероприятия](docs/ru/events.md)
  * 🔴[CopterHack-2023](docs/ru/copterhack2023.md)
  * 🔴[CopterHack-2022](docs/ru/copterhack2022.md)
  * 🔴[CopterHack-2021](docs/ru/copterhack2021.md)
  * 🔴[CopterHack-2019](docs/ru/copterhack2019.md)
  * 🔴[Олимпиада НТИ 2019](docs/ru/nti2019.md)
  * 🔴[Робокросс-2019](docs/ru/robocross2019.md)
  * 🔴[CopterHack-2018](docs/ru/copterhack2018.md)
  * 🔴[CopterHack-2017](docs/ru/copterhack2017.md)
  * 🔴[Конкурс видео](docs/ru/video_contest.md)
  * 🔴[Образовательные конкурсы](docs/ru/educational_contests.md)
* 🔴[Проекты на базе Клевера](docs/ru/projects.md)
  * 🔴[Система радионавигации](docs/ru/nav-beacon.md)
  * 🔴[Advanced Clover Simulator](docs/ru/advanced_clover_simulator.md)
  * 🔴[Copter For Space](docs/ru/c4s.md)
  * 🔴[CopterCat CM4](docs/ru/copter_cat.md)
  * 🔴[Система мониторинга воздуха](docs/ru/air_monitor.md)
  * 🔴[Контроль соблюдения ПДД на выделенной полосе с дроном](docs/ru/lane_control.md)
  * 🔴[Система автоматической посадки (AMLS)](docs/ru/amls.md)
  * 🔴[Разработка системы для управления БПЛА с помощью шлема виртуальной реальности](docs/ru/remote-control-with-oculusvr.md)
  * 🔴[Шоу коптеров](docs/ru/clever-show.md)
  * 🔴[Innopolis Open 2020 (L22_ÆRO)](docs/ru/innopolis_open_L22_AERO.md)
  * 🔴[Олимпиада НТИ 2020 (P4DF2)](docs/ru/nti2020_p4df2.md)
  * 🔴[Генератор ArUco карт](docs/ru/arucogenmap.md)
  * 🔴[Модель аэротакси в городе](docs/ru/bigchallenges.md)
  * 🔴[Шаровая защита коптера](docs/ru/shield.md)
  * 🔴[Система засечки для дронов](docs/ru/race_timing_sys_copterhack.md)
  * 🔴[Дрон для 3D-сканирования человека](docs/ru/3dscan.md)
  * 🔴[Распознавание лиц](docs/ru/face_recognition.md)
  * 🔴[Управление дроном силой мысли](docs/ru/control_emotions.md)
  * 🔴[Подсчет количества объектов c камеры](docs/ru/object_counting.md)
  * 🔴[Пульт на Андроид](docs/ru/android.md)
  * 🔴[Блочный конструктор полета](docs/ru/clever_blocks.md)
  * 🔴[Калибровка камеры (legacy)](docs/ru/camera_calib.md)
  * 🔴[Управление дроном для оценки позы человека](docs/ru/human_pose_estimation_drone_control.md)
  * 🔴[Распознавание видов агрокультур](docs/ru/agriculture.md)
  * 🔴[AdvancedClover](docs/ru/advanced_clover.md)
  * 🔴[Дрон для высаживания семян](docs/ru/seeding_drone.md)
  * 🔴[Граффити коптер D-drone](docs/ru/ddrone.md)
  * 🔴[Программируемый летающий автомобиль](docs/ru/zaural_viking.md)
  * 🔴[Дрон-Агроном](docs/ru/drone-agronom.md)
  * 🔴[Easy To Fly](docs/ru/easytofly.md)
  * 🔴[Хардатон Квиддич](docs/ru/hardaton_quidditch.md)
  * 🔴[Октокоптер со специфичным расположением пропеллеров](docs/ru/oktazodg.md)

## Учебник

* [Теория и видеоуроки](lessons.md)
* [Учебно-методическое пособие](metod.md)
* [Контрольные материалы](tests.md)
