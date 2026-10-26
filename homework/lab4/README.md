# Лабораторная работа. Настройка IPv6-адресов на сетевых устройствах 

##  Топология

![alt text](Topology.png)

##  Таблица адресации

<table><thead>
    <th style="text-align: center;">Устройство</th>
    <th style="text-align: center;">Интерфейс</th>
    <th style="text-align: center;">IPv6-адрес</th>
    <th style="text-align: center;">Link local IPv6-адрес</th>
    <th style="text-align: center;">Длина префикса</th>
    <th style="text-align: center;">Шлюз по умолчанию</th>
</thead>
<tbody>
  <tr>
    <th rowspan="2" style="text-align: center;">R1 </th>
    <th style="text-align: center;">G0/0/0</th>
    <th style="text-align: center;">2001:db8:acad:a::1</th>
    <th style="text-align: center;">fe80::1</th>
    <th style="text-align: center;">64</th>
    <th style="text-align: center;">-</th>
  </tr>
  <tr>
    <td style="text-align: center">G0/0/1</td>
    <td style="text-align: center">2001:db8:acad:1::1 </td>
    <td style="text-align: center">fe80::1</td>
    <th style="text-align: center;">64</th>
    <th style="text-align: center;">-</th>
  </tr>
  <tr>
    <td style="text-align: center">S1</td>
    <td style="text-align: center">Vlan1</td>
    <td style="text-align: center">2001:db8:acad:1::b</td>
    <td style="text-align: center">fe80::b</td>
    <th style="text-align: center;">64</th>
    <th style="text-align: center;">-</th>
  </tr>
  <tr>
    <td style="text-align: center">PC-A</td>
    <td style="text-align: center">NIC</td>
    <td style="text-align: center">2001:db8:acad:1::3</td>
    <td style="text-align: center">SLACC</td>
    <th style="text-align: center;">64</th>
    <th style="text-align: center;">fe80::1</th>
  </tr>
  <tr>
    <td style="text-align: center">PC-B</td>
    <td style="text-align: center">NIC</td>
    <td style="text-align: center">2001:db8:acad:a::3</td>
    <td style="text-align: center">SLACC</td>
    <th style="text-align: center;">64</th>
    <th style="text-align: center;">fe80::1</th>
</tbody>
</table>

## Задачи

Часть 1. Настройка топологии и конфигурация основных парамтеров маршрутизатора и коммутатора\
Часть 2. Ручная настройка IPv6-адресов\
Часть 3. Проверка сквозного соединения

## Выполнение работы

### Часть 1. Настройка топологии и конфигурация основных параметров маршрутизатора и коммутатора

#### Шаг 1 Настройка маршрутизатора

#### Шаг 2 Настройка коммутатора


### Часть 2. Ручная настройка IPv6-адресов

#### Шаг 1 Назначение IPv6-адреса интерфейсам Ethernet на R1

#### Шаг 2 Активация IPv6-маршрутизацию на R1

#### Шаг  3. Назначение IPv6-адресов интерфейсу управления (SVI) на S1

#### Шаг 4. Назначение компьютерам статических IPv6-адресов

### Часть 3 проверка сквозного подключения

## Вопросы для повторения 

1. Почему обоим интерфейсам Ethernet на R1 можно назначить один и тот же локальный адрес канала — FE80::1?\
**Ответ**: 
2. Какой идентификатор подсети в индивидуальном IPv6-адресе 2001:db8:acad::aaaa:1234/64?\
**Ответ**: