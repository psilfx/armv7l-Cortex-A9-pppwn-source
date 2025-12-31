<h1>PPPwn под armv7l.</h1>

<p>file: ELF 32-bit LSB executable, ARM, EABI5 version 1 (SYSV), statically linked, with debug_info, not stripped</p>

<h2>Проверен и работает на Netgear r7000 Nighthawk.</h2>

<p>Собрано из https://github.com/xfangfang/PPPwn_cpp .</p>
<p>Бинарники Stage взяты с https://github.com/MODDEDWARFARE/PPPwn_WRT .</p>

<h3>Запуск:</h3>
<ul>
<li>1. Скопировать на роутер или ещё куда, стартануть например через ssh
./pppwn --interface br-lan --fw 1100 --stage1 "stage1_1100.bin" --stage2 "stage2_1100.bin" --timeout 10 --auto-retry </li>
<li>2. Взять флэшку записать в корень goldhen.bin и вставить в PS4</li>
<li>3. Запустить Сеть -> Установить соединение с интернетом -> Использовать Lan кабель -> Специальный -> PPPoE -> Login: PPP , Password: PPP -> Тестовое соединение</li>
<li>4. Дождаться успешной прошивки, если что то пойдёт не так приставка отрубится, а может и нет.</li>
</ul>
