# Vivarium-Hovercraft
<img src="logo.png" height=200 width=200/>
Рік випуску: 2018<br/>
Версія: 1.0.0<br/>
Розробник: Vivarium<br/>
<br/>

## Апаратне забезпечення
<ul>
  <li>плата Arduino Uno (1)</li>
  <li>Мотор A2212 930 KV 3.17 мм (2)</li>
  <li>пропелер вертикальної тяги (1)</li>
  <li>пропелер горизонтальної тяги (1)</li>
  <li>Wi-Fi модуль ESP8266 (1)</li>
  <li>Аккумулятор ZIPPY Compact 1300 мАч 3S1P 25С (1)</li>
  <li>сервомотор (1)</li>
</ul>

## Підключення компонентів
<ol>
  <li>Підключити ESP сервер до плати за схемою<br/><img src="server.png"/></li>
  <li>Підключити сервомотор та двигуни<br/><img src="motor.png"/></li>
  <li>Підключити двигуни до батареї<br/></li>
</ol>

## Завантаження коду на плату Arduino Uno
Для завантаження коду на плату необхідно завантажити та встановити Arduino IDE<br/>
Підключіть плату Arduino Uno до комп'ютера та загрузіть на нього код клієнтської частини<br/>
Підключіть ESP модуль до комп'ютера та загрузіть на нього код серверної частини<br/>

## Інструкція з використання
Приєднайтеся до Wi-Fi ESP сервера на будь-якому приладі<br/>
Відкрийте браузер та перейдіть за посиланням 192.168.4.<br/>
Використовуйте сторінку для керування СПП<br/>
<img src="manual.jpg"/>
