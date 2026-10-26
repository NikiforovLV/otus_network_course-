# Лабораторная работа. Внедрение маршрутизации между виртуальными локальными сетями

##  Топология

![alt text](Topology.png)

##  Таблица адресации

<table><thead>
    <th style="text-align: center;">Устройство</th>
    <th style="text-align: center;">Интерфейс</th>
    <th style="text-align: center;">IP-адрес</th>
    <th style="text-align: center;">Маска подсети</th>
    <th style="text-align: center;">Шлюз по умолчанию</th>
</thead>
<tbody>
  <tr>
    <th rowspan="4" style="text-align: center;">R1 </th>
    <th style="text-align: center;">G0/0/1.10</th>
    <th style="text-align: center;">192.168.10.1</th>
    <th style="text-align: center;">255.255.255.0</th>
    <th rowspan="4" style="text-align: center;">-</th>
  </tr>
  <tr>
    <td style="text-align: center">G0/0/1.20</td>
    <td style="text-align: center">192.168.20.1</td>
    <td style="text-align: center;">255.255.255.0</td>
  </tr>
  <tr>
    <td style="text-align: center">G0/0/1.30</td>
    <td style="text-align: center">192.168.30.1</td>
    <td style="text-align: center">255.255.255.0</td>
  </tr>
  <tr>
    <td style="text-align: center">G0/0/1.1000</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
  </tr>
   <tr>
    <td style="text-align: center;">S1</td>
    <td style="text-align: center">VLAN 10</td>
    <td style="text-align: center">192.168.10.11</td>
    <td style="text-align: center">255.255.255.0</td>
    <td style="text-align: center;">192.168.10.1</td>
  </tr>
   <tr>
    <td style="text-align: center;">S2 </td>
    <td style="text-align: center">VLAN 10</td>
    <td style="text-align: center">192.168.10.12</td>
    <td style="text-align: center">255.255.255.0</td>
    <td style="text-align: center;">192.168.10.1</td>
  </tr>
   <tr>
    <td style="text-align: center;">PC-A</td>
    <td style="text-align: center">NIC</td>
    <td style="text-align: center">192.168.20.3</td>
    <td style="text-align: center">255.255.255.0</td>
    <td style="text-align: center;">192.168.20.1</td>
  </tr>
   <tr>
    <td style="text-align: center;">PC-B</td>
    <td style="text-align: center">NIC</td>
    <td style="text-align: center">192.168.30.3</td>
    <td style="text-align: center">255.255.255.0</td>
    <td style="text-align: center;">192.168.30.1</td>
  </tr>
</tbody>
</table>

##  Таблица VLAN

<table><thead>
    <th style="text-align: center;">VLAN</th>
    <th style="text-align: center;">Имя</th>
    <th style="text-align: center;">Назначенный интерфейс</th>
</thead>
<tbody>
  <tr>
    <th style="text-align: center;">10</th>
    <th style="text-align: center;">Управление</th>
    <th style="text-align: center;">S1: VLAN 10

 S2: VLAN 10</th>
  </tr>
  <tr>
    <td style="text-align: center">20</td>
    <td style="text-align: center">Sales</td>
    <td style="text-align: center;">S1: F0/6</td>
  </tr>
  <tr>
    <td style="text-align: center">30</td>
    <td style="text-align: center">Operations</td>
    <td style="text-align: center">S2: F0/18</td>
  </tr>
  <tr>
    <td style="text-align: center">999</td>
    <td style="text-align: center">Parking_Lot</td>
    <td style="text-align: center">C1: F0/2-4, F0/7-24, G0/1-2

C2: F0/2-17, F0/19-24, G0/1-2
</td>
  </tr>
   <tr>
    <td style="text-align: center">1000</td>
    <td style="text-align: center">Собственная</td>
    <td style="text-align: center">-</td>
  </tr>
</tbody>
</table>

## Задачи

Часть 1. Создание сети и настройка основных параметров устройства\
Часть 2. Создание сетей VLAN и назначение портов коммутатора\
Часть 3. Настройка транка 802.1Q между коммутаторами\
Часть 4. Настройка маршрутизации между сетями VLAN\
Часть 5. Проверка, что маршрутизация между VLAN работает

## Выполнение работы

### Часть 1. Создание сети и настройка основных параметров устройства

#### Шаг 1 Создаем топологию сети

#### Шаг 2 Настройка маршрутизатора

#### Шаг 3 Настройка коммутаторов

#### Шаг 4 Настройка ПК

### Часть 2. Создание сетей VLAN и назначение портов коммутатора

#### Шаг 1 Создание сетей VLAN на коммутаторах

#### Шаг 2 Назначение сетей VLAN на соответствующие интерфейсы коммутатора

### Часть 3 Настройка транка 802.1Q между коммутаторами

#### Шаг 1 Настройка магистрального интерфейса F0/1 на коммутаторах S1 и S2

#### Шаг 2 Настройка магистрального интерфейс F0/5 на коммутаторе S1

### Часть 4. Настройка маршрутизации между сетями VLAN

#### Шаг 1 Настройка маршрутизатора

### Часть 5.  Проверка, что маршрутизация между VLAN работает

#### Шаг 1 Выполнение тестов c PC-A

#### Шаг 2 Выполнение тестов с PC-B