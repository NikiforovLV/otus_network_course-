# Лабораторная работа - Расчет подсетей IPv4

 
##  Задачи

Часть 1. Опредление подсетей по IPv4-адресу

Часть 2. Расчет подсетей по IPv4

## Общие сведения/сценарий 

Умение работать с IPv4-подсетями и определять информацию о сетях и узлах на основе известного IP-адреса и маски подсети необходимо для понимания принципов работы IPv4-сетей. Цель первой части — закрепить знания о том, как рассчитывать IP-адрес сети на основе известного IP-адреса и маски подсети. Зная IP-адрес и маску подсети, вы всегда сможете получить другие данные об этой подсети.

##  Решение

### Проблема 1

<table><thead>
  <tr>
    <th colspan="2" style="text-align: center;">Дано: </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="text-align: left;"> IP-адрес узла:  </td>
    <td style="text-align: left;"> 192.168.200.139 </td>
  </tr>
  <tr>
    <td style="text-align: left;"> Исходная маска подсети: </td>
    <td style="text-align: left;"> 255.255.255.0 </td>
  </tr>
  <tr>
    <td style="text-align: left;"> Новая маска подсети:</td>
    <td style="text-align: left;"> 255.255.255.224</td>
  </tr>
</tbody>
</table>

<table><thead>
  <tr>
    <th colspan="2" style="text-align: center;">Найти: </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="text-align: left;"> Количество бит подсети  </td>
    <td style="text-align: left;">27</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Количество созданных подсетей </td>
    <td style="text-align: left;">8</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Количество бит узлов в подсети</td>
    <td style="text-align: left;">5</td>
  </tr>
   <tr>
    <td style="text-align: left;">Количество узлов в подсети</td>
    <td style="text-align: left;">30</td>
  </tr> <tr>
    <td style="text-align: left;"> Сетевой адрес этой подсети</td>
    <td style="text-align: left;">192.168.200.128</td>
  </tr> <tr>
    <td style="text-align: left;"> IPv4-адрес первого узлоа в этой подсети</td>
    <td style="text-align: left;">192.168.200.129</td>
  </tr> <tr>
    <td style="text-align: left;"> IPv4-адрес последнего узла в этой подсети</td>
    <td style="text-align: left;">192.168.200.158</td>
  </tr>
  </tr> <tr>
    <td style="text-align: left;">Широковещательный IPv4-адрес в этой подсети</td>
    <td style="text-align: left;">192.168.200.159</td>
  </tr>
</tbody>
</table>

### Проблема 2

<table><thead>
  <tr>
    <th colspan="2" style="text-align: center;">Дано: </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="text-align: left;"> IP-адрес узла:  </td>
    <td style="text-align: left;">10.101.99.228</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Исходная маска подсети: </td>
    <td style="text-align: left;"> 255.0.0.0</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Новая маска подсети:</td>
    <td style="text-align: left;">255.255.128.0</td>
  </tr>
</tbody>
</table>

<table><thead>
  <tr>
    <th colspan="2" style="text-align: center;">Найти: </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="text-align: left;"> Количество бит подсети  </td>
    <td style="text-align: left;">17</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Количество созданных подсетей </td>
    <td style="text-align: left;">512</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Количество бит узлов в подсети</td>
    <td style="text-align: left;">9</td>
  </tr>
   <tr>
    <td style="text-align: left;">Количество узлов в подсети</td>
    <td style="text-align: left;">32766</td>
  </tr> <tr>
    <td style="text-align: left;"> Сетевой адрес этой подсети</td>
    <td style="text-align: left;">10.101.0.0</td>
  </tr> <tr>
    <td style="text-align: left;"> IPv4-адрес первого узлоа в этой подсети</td>
    <td style="text-align: left;">10.101.0.1</td>
  </tr> <tr>
    <td style="text-align: left;"> IPv4-адрес последнего узла в этой подсети</td>
    <td style="text-align: left;">10.101.127.254</td>
  </tr>
  </tr> <tr>
    <td style="text-align: left;">Широковещательный IPv4-адрес в этой подсети</td>
    <td style="text-align: left;">10.101.127.255</td>
  </tr>
</tbody>
</table>

### Проблема 3

<table><thead>
  <tr>
    <th colspan="2" style="text-align: center;">Дано: </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="text-align: left;"> IP-адрес узла:  </td>
    <td style="text-align: left;">172.22.32.12</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Исходная маска подсети: </td>
    <td style="text-align: left;"> 255.255.0.0 </td>
  </tr>
  <tr>
    <td style="text-align: left;"> Новая маска подсети:</td>
    <td style="text-align: left;"> 255.255.224.0</td>
  </tr>
</tbody>
</table>

<table><thead>
  <tr>
    <th colspan="2" style="text-align: center;">Найти: </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="text-align: left;"> Количество бит подсети  </td>
    <td style="text-align: left;">19</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Количество созданных подсетей </td>
    <td style="text-align: left;">8</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Количество бит узлов в подсети</td>
    <td style="text-align: left;">13</td>
  </tr>
   <tr>
    <td style="text-align: left;"> Количество узлов в подсети</td>
    <td style="text-align: left;">8190</td>
  </tr> <tr>
    <td style="text-align: left;"> Сетевой адрес этой подсети</td>
    <td style="text-align: left;">172.22.32.0</td>
  </tr> <tr>
    <td style="text-align: left;"> IPv4-адрес первого узлоа в этой подсети</td>
    <td style="text-align: left;">172.22.32.1</td>
  </tr> <tr>
    <td style="text-align: left;"> IPv4-адрес последнего узла в этой подсети</td>
    <td style="text-align: left;">172.22.63.254</td>
  </tr>
  </tr> <tr>
    <td style="text-align: left;">Широковещательный IPv4-адрес в этой подсети</td>
    <td style="text-align: left;">172.22.63.255</td>
  </tr>
</tbody>
</table>

### Проблема 4

<table><thead>
  <tr>
    <th colspan="2" style="text-align: center;">Дано: </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="text-align: left;"> IP-адрес узла:  </td>
    <td style="text-align: left;">192.168.1.245</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Исходная маска подсети: </td>
    <td style="text-align: left;">255.255.255.0</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Новая маска подсети:</td>
    <td style="text-align: left;">255.255.255.252</td>
  </tr>
</tbody>
</table>

<table><thead>
  <tr>
    <th colspan="2" style="text-align: center;">Найти: </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="text-align: left;"> Количество бит подсети  </td>
    <td style="text-align: left;">30</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Количество созданных подсетей </td>
    <td style="text-align: left;">64</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Количество бит узлов в подсети</td>
    <td style="text-align: left;">2</td>
  </tr>
   <tr>
    <td style="text-align: left;"> Количество узлов в подсети</td>
    <td style="text-align: left;">2</td>
  </tr> <tr>
    <td style="text-align: left;"> Сетевой адрес этой подсети</td>
    <td style="text-align: left;">192.168.1.244</td>
  </tr> <tr>
    <td style="text-align: left;"> IPv4-адрес первого узлоа в этой подсети</td>
    <td style="text-align: left;">192.168.1.245</td>
  </tr> <tr>
    <td style="text-align: left;"> IPv4-адрес последнего узла в этой подсети</td>
    <td style="text-align: left;">192.168.1.246</td>
  </tr>
  </tr> <tr>
    <td style="text-align: left;">Широковещательный IPv4-адрес в этой подсети</td>
    <td style="text-align: left;">192.168.1.247</td>
  </tr>
</tbody>
</table>

### Проблема 5

<table><thead>
  <tr>
    <th colspan="2" style="text-align: center;">Дано: </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="text-align: left;"> IP-адрес узла:  </td>
    <td style="text-align: left;">128.107.0.55</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Исходная маска подсети: </td>
    <td style="text-align: left;">255.255.0.0</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Новая маска подсети:</td>
    <td style="text-align: left;">255.255.255.0</td>
  </tr>
</tbody>
</table>

<table><thead>
  <tr>
    <th colspan="2" style="text-align: center;">Найти: </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="text-align: left;"> Количество бит подсети  </td>
    <td style="text-align: left;">24</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Количество созданных подсетей </td>
    <td style="text-align: left;">256</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Количество бит узлов в подсети</td>
    <td style="text-align: left;">8</td>
  </tr>
   <tr>
    <td style="text-align: left;"> Количество узлов в подсети</td>
    <td style="text-align: left;">254</td>
  </tr> <tr>
    <td style="text-align: left;"> Сетевой адрес этой подсети</td>
    <td style="text-align: left;">128.107.0.0</td>
  </tr> <tr>
    <td style="text-align: left;"> IPv4-адрес первого узлоа в этой подсети</td>
    <td style="text-align: left;">128.107.0.1</td>
  </tr> <tr>
    <td style="text-align: left;"> IPv4-адрес последнего узла в этой подсети</td>
    <td style="text-align: left;">128.107.0.254</td>
  </tr>
  </tr> <tr>
    <td style="text-align: left;">Широковещательный IPv4-адрес в этой подсети</td>
    <td style="text-align: left;">128.107.0.255</td>
  </tr>
</tbody>
</table>

### Проблема 6

<table><thead>
  <tr>
    <th colspan="2" style="text-align: center;">Дано: </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="text-align: left;"> IP-адрес узла:  </td>
    <td style="text-align: left;">192.135.250.180</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Исходная маска подсети: </td>
    <td style="text-align: left;">255.255.255.0</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Новая маска подсети:</td>
    <td style="text-align: left;">255.255.255.248</td>
  </tr>
</tbody>
</table>

<table><thead>
  <tr>
    <th colspan="2" style="text-align: center;">Найти: </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="text-align: left;"> Количество бит подсети  </td>
    <td style="text-align: left;">29</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Количество созданных подсетей </td>
    <td style="text-align: left;">32</td>
  </tr>
  <tr>
    <td style="text-align: left;"> Количество бит узлов в подсети</td>
    <td style="text-align: left;">3</td>
  </tr>
   <tr>
    <td style="text-align: left;"> Количество узлов в подсети</td>
    <td style="text-align: left;">6</td>
  </tr> <tr>
    <td style="text-align: left;"> Сетевой адрес этой подсети</td>
    <td style="text-align: left;">192.135.250.176</td>
  </tr> <tr>
    <td style="text-align: left;"> IPv4-адрес первого узлоа в этой подсети</td>
    <td style="text-align: left;">192.135.250.177</td>
  </tr> <tr>
    <td style="text-align: left;"> IPv4-адрес последнего узла в этой подсети</td>
    <td style="text-align: left;">192.135.250.182</td>
  </tr>
  </tr> <tr>
    <td style="text-align: left;">Широковещательный IPv4-адрес в этой подсети</td>
    <td style="text-align: left;">192.135.250.183</td>
  </tr>
</tbody>
</table>

## Вопрос для повторения

Вопрос: почему маска подсети так важна при анализе IPv4-адреса?

Ответ: она ограничевает простанство адресов внутри подсети