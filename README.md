

*Изглед:*

След стартиране на проекта и писане на localhost:8080 би трябвало да видим Login страницата по този начин:
![](readmeimg/Aspose.Words.d130e470-a409-49f3-b68b-2e39241515e7.003.png)



А след правилно изписване на потребителско име и парола се вижда списъка с клиенти:
![](readmeimg/Aspose.Words.d130e470-a409-49f3-b68b-2e39241515e7.004.png)

Използваме H2 база данни:

![](readmeimg/Aspose.Words.d130e470-a409-49f3-b68b-2e39241515e7.005.png)


Добавяме нов запис:


![](readmeimg/Aspose.Words.d130e470-a409-49f3-b68b-2e39241515e7.006.png)

Изтриваме новия запис: 
![](Aspose.Words.d130e470-a409-49f3-b68b-2e39241515e7.007.png)






![](readmeimg/Aspose.Words.d130e470-a409-49f3-b68b-2e39241515e7.005.png)
![](Aspose.Words.d130e470-a409-49f3-b68b-2e39241515e7.008.png)


Има и възможността да филтрира клиентите по фамилия:
![](readmeimg/Aspose.Words.d130e470-a409-49f3-b68b-2e39241515e7.009.png)






*Кодова част:*


Създаваме модела за клиентите в Customer.java:

![](readmeimg/Aspose.Words.d130e470-a409-49f3-b68b-2e39241515e7.010.png)

Дефинираме Customer repository в CustomerRepository.java:

![](readmeimg/Aspose.Words.d130e470-a409-49f3-b68b-2e39241515e7.011.png)


Класa JavauniApplication го използваме за добавяне на обекти:

![](readmeimg/Aspose.Words.d130e470-a409-49f3-b68b-2e39241515e7.012.png)



Добавяме в pom.xml Vaadin Dependencies: 


![](readmeimg/Aspose.Words.d130e470-a409-49f3-b68b-2e39241515e7.013.png)


В MainView класа си създаваме изгледа на сайта:

![](readmeimg/Aspose.Words.d130e470-a409-49f3-b68b-2e39241515e7.014.png)


Функционалстта на бутоните е в CustomerEditor:

![](readmeimg/Aspose.Words.d130e470-a409-49f3-b68b-2e39241515e7.015.png)


Правим и Login view:

![](readmeimg/Aspose.Words.d130e470-a409-49f3-b68b-2e39241515e7.016.png)


И настройваме нещата в SecurityConfig:


![](readmeimg/Aspose.Words.d130e470-a409-49f3-b68b-2e39241515e7.017.png)

