# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

05.03.2021 - 05.03.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 0.5 часа

В результате тестирования выявлены следующие дефекты:
* [Не проходят проверку карты с числом знаков отличным от 16](https://github.com/DoroshenkoDenis/HomeWork2/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Домашнее задание 1 к лекции Введение в Java: JDK, JRE, JVM, IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* [Код программы](src/Main.java)



В качестве тестовых данных использовались данные [Credit Card Number Generator & Validator](https://www.freeformatter.com/credit-card-number-generator-validator.html):

**Номера карт с ожидаемым результатом:**

**VISA:**  
4916004933579713  :OK  
4916192193882065  :OK  
4485823257112943402  :OK  
4716231103944216928  :OK         

**MasterCard:**  
2221000499941960  :OK  
5290722420479344  :OK  
5581283974816694  :OK

**American Express (AMEX):**  
344907740223038  :OK  
345495517192023  :OK   
345930889020246  :OK

**Discover:**  
6011697904507834  :OK  
6011761157888257  :OK  
6011264866043149414  :OK  
6011646643185379243  :OK   

**JCB:**  
3530888997330759  :OK  
3533437534424043  :OK  
3533350390669341875  :OK  
3531964384810556657  :OK

**Diners Club - North America:**  
5575168986667383  :OK  
5576613096652410  :OK  
5454838926746861  :OK

**Diners Club - Carte Blanche:**  
30131743817675  :OK  
30183266891504  :OK  
30422272957952 :OK

**Diners Club - International:**  
36207843236273  :OK  
36479064544491  :OK  
36622803821718  :OK  

**Maestro:**  
5893575328669932  :OK  
0604948715698239  :OK  
6304782655286246  :OK

**Visa Electron:**  
4175009318713494  :OK  
4175005153181151  :OK  
4917913034019750  :OK

**InstaPayment:**   
6393117410526283  :OK  
6378679230381032  :OK  
6372481406112317  :OK




**Тестирование производилось в следующем окружении:**
* Windows 10 x64
* версия Java 11.0.10
* IntelliJ IDEA 2020.3.2 x64