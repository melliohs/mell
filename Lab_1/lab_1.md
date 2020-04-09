<div align="center">
  <br>
  <img src="https://i.ibb.co/DkYw4wF/logo.png" alt="logo" border="0"><br><br>
  МИНОБРНАУКИ РОССИИ<br>
  Федеральное государственное бюджетное<br>
  образовательное учреждение высшего образования
  
#### **«МИРЭА – Российский технологический униврситет»**
  
  Лабораторная работа по дисциплине:<br>
  «Программные средства оперативно-аналитического поиска»
</div>
<br><br><br><br><br>
<div align="right">
  <br>
  Выполнил:<br>
  Студент 4 курса<br>
  Специальности 10.05.05<br>
  Группа ББСО-02-16<br>
  Поляков Д.А.<br>
  Проверил:<br>
  Захарчук И.И.<br>
</div>
<br><br><br><br><br><br><br>

<p align="center">
  Москва 2020
</p>
<br><br><br>

<div align="center">

#### **Лабораторная работа № 1**

</div>

<p>

#### **Цель работы**

Используя специализированные утилиты и сервисы произвести сбор информации по каждой цели (сайты)
</p>

<p>

#### **Исходные данные**


|    Наименование устройства     |  Программа виртуализации  | Операционная система  |
| ------------------------------ | ------------------------- | --------------------- |
|  Apple Macbook Pro Early 2015  |    VMware Fusion Pro 15   |   Kali linux 2020.1   |

</p>

<p>

#### **Наименования компаний**

1. [Analog Devices Inc.](www.analog.com)<br>
2. [Allstate Corporation](www.allstate.com)<br>
3. [SunTrust Banks Inc.](www.suntrust.com)<br>
4. [Sherwin-Williams Company](www.sherwin-williams.com)<br>
5. [Baxter International Inc.](www.baxter.com)<br>
</p>

<p>

#### **Используемые ресурсы и утилиты**

1. Утилиты Dig, nslookup, whois, nmap<br>
2. Сайты:
    * [Shodan](shodan.io)
    * [Censys](censys.io)
    * [Maxmind](maxmind.com)
3. Расширение для брузера - [Wappalyzer](wappalayzer.com)
</p>


#### **Процесс выполнения работы**

<p>

* **Analog Devices Inc.**

| Признак                    | Значение                                                                |
|----------------------------|-------------------------------------------------------------------------|
| Компания                   | Analog Devices Inc.                                                     |
| Сайт                       | www.analog.com                                                          |
| IP netblock                | 137.71.173.128                                                          |
| Местоположение             | Norwood, One Technology Way, MA 02062-9106                              |
| Телефон                    | +1-781-461-3019                                                         |
| E-mail                     | dns_admin@analog.com                                                    |
| Информация об оборудовании | 80,443,113                                                              |
| Хостинг                    | Analog Devices                                                          |
| WEB-технологии             | JS фреймворк - Handlebars 1.3.0, React 16.10.2                          |
|                            | Веб сервер - IIS10.0                                                    |
|                            | Операционная система - Windows Server                                   |
|                            | CDN - Akamai                                                            |
|                            | JavaScript Libraries - Modernizr 2.6.1, Moment.js 2.20.1, jQuery 1.12.4 |
|                            | UI Frameworks Bootstrap 3.3.5                                           |

</p>


<p>

* **Allstate Corporation**

| Признак                    | Значение                                                                                  |
|----------------------------|-------------------------------------------------------------------------------------------|
| Компания                   | Allstate Corporation                                                                      |
| Сайт                       | www.allstate.com                                                                          |      
| IP netblock                | 167.127.208.24                                                                            |
| Местоположение             | US, Northbrook, 3075 Sanders Road                                                         |
| Телефон                    | +1-847-402-5000                                                                           |
| E-mail                     | dnsadmin@allstate.com                                                                     |
| Информация об оборудовании | 26,80,163,443,1074,1145,1433,2007,3128,3801,5911,9593,10621,15003,33354,49155,49400,52869 |
| Хостинг                    | Allstate Insurance Company                                                                |
| WEB-технологии             | CDN - Akamai                                                                              |
|                            | Веб сервер - IIS                                                                          |
|                            | Операционная система - Windows Server                                                     |
|                            | Веб фреймворк - Microsoft ASP.NET                                                         |
|                            | JavaScript Libraries - Polyfill, jQuery 3.4.1                                             |
|                            | UI Frameworks - Bootstrap 3.3.7                                                           |

</p>

<p>

* **SunTrust Banks Inc.**

| Признак                    | Значение                                                                     |
|----------------------------|------------------------------------------------------------------------------|
| Компания                   | SunTrust Banks Inc.                                                          |       
| Сайт                       | www.suntrust.com                                                             |
| IP netblock                | 143.204.55.119                                                               |
|                            | 143.204.55.23                                                                |
|                            | 143.204.55.51                                                                |
|                            | 143.204.55.62                                                                |
|                            | 2600:9000:20a5:800:5:842a:2dc0:93a1                                          |
|                            | 2600:9000:20a5:c600:5:842a:2dc0:93a1                                         |
|                            | 2600:9000:20a5:4e00:5:842a:2dc0:93a1                                         |
|                            | 2600:9000:20a5:be00:5:842a:2dc0:93a1                                         |
|                            | 2600:9000:20a5:1c00:5:842a:2dc0:93a1                                         |
|                            | 2600:9000:20a5:1400:5:842a:2dc0:93a1                                         |
|                            | 2600:9000:20a5:4400:5:842a:2dc0:93a1                                         |
|                            | 2600:9000:20a5:e400:5:842a:2dc0:93a1                                         |
| Местоположение             | US, GA , Atlanta                                                             |
| Телефон                    | +1-404-813-7522                                                              |
| E-mail                     | digitalgovernance@suntrust.com                                               |
| Информация об оборудовании | -                                                                            |
| Хостинг                    | Amazon CloudFront                                                            |
| WEB-технологии             | CMS - Adobe Experience Manager                                               |
|                            | JavaScript Libraries - jQuery 1.11.3, Select2, Modernizr 2.6.2, Lodash 2.4.1 |
|                            | Язык программирования - Java                                                 |
|                            | Веб сервер - Apache                                                          |
|                            | PaaS - Amazon Web Services                                                   |
|                            | JS фреймворк - GSAP                                                          |
|                            | CDN - Amazon Cloudfront                                                      |
|                            | UI Framework - Bootstrap 3.3.7                                               |

</p>

<p>

* **Sherwin-Williams Company**

| Признак                    | Значение                                                                         |
|----------------------------|----------------------------------------------------------------------------------| 
| Компания                   | Sherwin-Williams Company                                                         |
| Сайт                       | www.sherwin-williams.com                                                         |
| IP netblock                | 196.44.56.48                                                                     |
| Местоположение             | US, Ohio, Cloveland, 101 Prospect Avenue NW                                      |
| Телефон                    | +1-216-566-2000                                                                  |
| E-mail                     | hostmaster@sherwin.com                                                           |
| Информация об оборудовании | 19,80,443                                                                        |
| Хостинг                    | SoftLayer Technologies                                                           |
| WEB-технологии             | Язык программирования - Java                                                     |
|                            | JS фреймворк - AngularJS 1.5.7, Handlebars 4.0.5                                 |
|                            | JavaScript Libraries - Dojo, jQuery 2.1.3, jQuery UI 1.11.4, Underscore.js 1.9.1 |
|                            | UI Frameworks - Bootstrap                                                        |

</p>

<p>

* **Baxter International Inc.**

| Признак                    | Значение                                                   |
|----------------------------|------------------------------------------------------------| 
| Компания                   | Baxter International Inc.                                  |
| Сайт                       | www.baxter.com                                             |
| IP netblock                | 198.89.204.46                                              |
| Местоположение             | US, IL, Deerfield                                          |
| Телефон                    | +1-224-948-2000                                            |
| E-mail                     | hostmaster@baxter.com                                      |
| Информация об оборудовании | 80,443,5226                                                |
| Хостинг                    | Telia Finland                                              |
| WEB-технологии             | CMS - Drupal 8                                             |
|                            | CDN - CloudFlare                                           |
|                            | База данных - Percona                                      |
|                            | PaaS - Acquia Cloud, Amazon Web Services                   |
|                            | Кеширование - Varnish                                      |
|                            | Веб сервер - Apache, Amazon EC2                            |
|                            | Язык программирования - PHP                                |
|                            | JavaScript Libraries - jQuery 3.2.1, jQuery Migrate 3.1.0  |                            
</p>

#### **Вывод**

<p>
В данной лабораторной работе я потворил основы предварительного сбора информации о жертве, применяя различные утилиты и сервисы
</p>

