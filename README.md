# Digispark (payload)
The ATTINY85 developer board is designed for device development with minimal peripheral requirements and the ability to automatically connect to a computer's USB interface for programming and debugging.  
![image](https://github.com/Petskovych/Digispark/assets/147243488/cd2f72f6-9f76-4887-b81d-f041d4d1452c)


# Characteristics:
Microcontroller: ATTINY85
Internal oscillator: 8 MHz
Built-in frequency multiplier: 8
Program memory: 8 KB (6 KB available)
Hardware interfaces: SPI, I2C
PWM: 3 channels
ADC: 4 channels
Indicators: power, status (Pin0) (можна впливати на роботу інндикаторів)

# Сonnection
Digispark працює з USB 1.1 і USB 2.0, проте слід мати на увазі, що в деяких випадках може знадобитися адаптер або кабель для забезпечення сумісності, якщо виникають проблеми зі з'єднанням. Цю особливість я виявив коли підєднував його до usb 3.0.  

# Payloads
Регулюйте затримку для коректної роботи програми, також після виконання програми світиться другий індикатор, при необхідності це можна забрати для оптимізації коду.
На мою думку це найлекше що можна писати на c++.
Майте на увазі що команда в Shell прописується приблизно 30 секунд. 
Згодом я розширю цей репозиторій, і додам ще корисного навантаження з коментаріями до коду.     
 
