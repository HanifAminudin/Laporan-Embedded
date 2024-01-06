<h1 align="center">LAPORAN PRAKTIKUM SISTEM EMBEDDED</h1>
<h2 align="center"> TRANSMISI DATA MENGGUNAKAN PROTOKOL HTTP DAN MQTT </h2>
<br>
<p align="center">
  <img src="https://en.polines.ac.id/images/logo_bw.jpg" width="200" height="200">
<br>
<br>HANIF AMINUDIN
<br>TE-3A
<br>4.31.21.0.14</p>
<br>
<b><p align="center">PROGRAM STUDI D4 TEKNIK TELEKOMUNIKASI</p>
<p style="font-family:courier;" align="center">POLITEKNIK NEGERI SEMARANG</p>
<p style="font-family:courier;" align="center">2023</p></b> 

#### A. ABSTRAK
<p align="justify">
Transfer Protocol (HTTP) adalah sebuah protokol jaringan lapisan
aplikasi yang digunakan untuk sistem informasi terdistribusi, kolaboratif, dan
menggunakan hypermedia. Protokol tersebut sering diimplementasikan untuk
melayani permintaan data dari user dan untuk manajemen website. Sementara itu,
Message Queuing Telemetry Trasnsport (MQTT) adalah protokol komunikasi
yang berjalan di atas stack TCP/IP, didesain untuk komunikasi Machine-to-
Machine (M2M), bersifat open sources dan lightweight, mempunyai protocol
overhead yang rendah (minimum 2 bytes) sehingga berefek pada konsumsi daya
yang kecil dan mampu bekerja pada latency yang tinggi serta bandwidth yang
kecil, sehingga protokol ini sering dimanfaatkan untuk transmisi data dari Node
Sensor menuju Server. </p>
<p align="justify">Jobsheet ini bertujuan untuk memahami cara kerja protokol HTTP dan MQTT untuk
transmisi data (akuisisi data dan kendali) pada Platform IoT Node-Red serta merancang dan melakukan konfigurasi pada perangkat
Internet of Things (IoT) menggunakan protokol HTTP dan MQTT untuk
monitoring dan kendali melalui Platform IoT Node-Red.</p>

**Sub-job** pada jobsheet ini, antara lain:
1. Setting SSID dan Password Wi-Fi ESP32 melalui Web Server
2. Transmisi Data Menggunakan Protokol HTTP
3. Transmisi Data Menggunakan Protokol MQTT
4. Akuisi Data dan Kendali Perangkat IoT Menggunakan Protokol MQTT

## Alat dan Bahan
**Alat dan Bahan** yang digunakan dalam praktikum ini, antara lain:
1. ESP32 dan Server Node-Red
2. Breadboard
3. Kabel jumper
4. Sensor DHT 11
5. LED (5)
6. Resistor 330, 1K, 10K Ohm (3)
