1. **Работа c HTTP через telnet.**
      
    ![network-1_1](img/network-1_1.png)
    
    Возвращает код 403 - страница не найдена
      
2. **Повторите задание 1 в браузере, используя консоль разработчика F12**

    Первый ответ HTTP-сервера показывает, что происходит редирект с http на https:

   ![network-1_2-1](img/network-1_2-1.png)
   
   Дольше всего обрабатывается запрос загрузки скрипта:
   
   ![network-1_2-2](img/network-1_2-2.png)
   
3. **Какой IP-адрес у вас в интернете?**

   164.138.94.233
   
4. **Какому провайдеру принадлежит ваш IP-адрес? Какой автономной системе AS? Воспользуйтесь утилитой whois.**

  ![network-1_4](img/network-1_4.png)
  
  Провайдер - Redcom, AS8749.
  
5. **Через какие сети проходит пакет, отправленный с вашего компьютера на адрес 8.8.8.8? Через какие AS? Воспользуйтесь утилитой traceroute.**

   ![network-1_5](img/network-1_5.png)
   
6. **Повторите задание 5 в утилите mtr. На каком участке наибольшая задержка — delay?**

    Наибольшая задержка на 7 хопе:
    
    ![network-1_6](img/network-1_6.png)
    
7. **Какие DNS-сервера отвечают за доменное имя dns.google? Какие A-записи? Воспользуйтесь утилитой dig.**

    ![network-1_7](img/network-1_7.png)
    
8. **Проверьте PTR записи для IP-адресов из задания 7. Какое доменное имя привязано к IP? Воспользуйтесь утилитой dig.**

    ![network-1_8](img/network-1_8-1.png)
    
    ![network-1_8](img/network-1_8-2.png)
