# Лабораторная работа. Просмотр таблицы MAC-aдресов коммутатора 

##  Топология

![alt text](NetScheme.png)

##  Таблица адресации

<table>
  <tr>
    <th style="text-align: center;">Устройство</th>
    <th style="text-align: center;">Интерфейс</th>
    <th style="text-align: center;">IP-адрес</th>
    <th style="text-align: center;">Маска подсети</th>
  </tr>
  <tr>
    <td style="text-align: center">Switch1</td>
    <td style="text-align: center">Vlan1</td>
    <td style="text-align: center">192.168.1.11</td>
    <td style="text-align: center">255.255.255.0</td>
  </tr>
  <tr>
    <td style="text-align: center">Switch 2</td>
    <td style="text-align: center">Vlan1</td>
    <td style="text-align: center">192.168.1.12</td>
    <td style="text-align: center">255.255.255.0</td>
  </tr>
  <tr>
    <td style="text-align: center">PC-A</td>
    <td style="text-align: center">NIC</td>
    <td style="text-align: center">192.168.1.1</td>
    <td style="text-align: center">255.255.255.0</td>
  </tr>
  <tr>
    <td style="text-align: center">PC-B</td>
    <td style="text-align: center">NIC</td>
    <td style="text-align: center">192.168.1.2</td>
    <td style="text-align: center">255.255.255.0</td>
</table>

## Выполнение работы

### Часть 1 Создаем и настройка сети

#### Шаг 1-4 
1. Собираем схему согласно топологии 
2. Делаем настройку PC-A и PC-B в соответствии с таблицей адрессации
3. Делаем настройку коммутатор в соответсвии с заданием и таблицей адресации

