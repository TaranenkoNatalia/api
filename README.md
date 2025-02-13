# ✉️ Тестирование REST и SOAP API через Postman

## **Тестирование REST API**  

Я протестировала все API запросы для интернет-магазина "DemoShopping", используя документацию <a href="https://qa.demoshopping.ru/api-docs/">Swagger</a>. Для некоторых запросов создала скрипты, которые проверяют статус-код, время ответа, соответствие окружения, тип данных и ключи в теле ответа.

 <ul>
<li>  <a href="https://www.postman.com/altimetry-specialist-32125376/workspace/demoshopping/collection/39719611-e745646a-0f39-4664-9435-1aa0195358c1?action=share&creator=39719611&active-environment=39719611-0fe1a957-1207-4a48-84eb-82c02d6226d8">Postman коллекция</a> модуля "Products", "Users", "Cart", "Order". </li>  

Для каждого запроса разработала **тест-кейсы**, в которых описала входные данные, шаги выполнения, ожидаемый результат. После этого провела **тест-ран** в **QASE**, проверяя корректность работы API.

<li>  <a href="https://github.com/TaranenkoNatalia/api/blob/main/%D0%A2%D0%B5%D1%81%D1%82-%D0%BA%D0%B5%D0%B9%D1%81%D1%8B%20%D0%B4%D0%BB%D1%8F%20Postman.pdf">Тест-кейсы</a> для Postman. </li> 

<li>  <a href="https://github.com/TaranenkoNatalia/api/blob/main/%D0%A0%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82%D1%8B%20%D1%82%D0%B5%D1%81%D1%82%D0%BE%D0%B2%D0%BE%D0%B3%D0%BE%20%D0%BF%D1%80%D0%BE%D0%B3%D0%BE%D0%BD%D0%B0%20postman.json">Результаты тестового прогона тест-кейсов</a> для Postman. </li>

## **Тестирование SOAP API**  
Также протестировала **SOAP-сервис** с помощью <a href="http://webservices.oorsprong.org/websamples.countryinfo/CountryInfoService.wso?WSDL">WSDL</a> </li>, который предоставляет информацию о странах. В Postman-коллекцию включены запросы для:  
Получения **списка всех стран**,  
Получения **детальной информации о стране** (столица, валюта, флаг и т. д.).

<li>  <a href="https://www.postman.com/altimetry-specialist-32125376/workspace/demoshopping/collection/39719611-362a6cd0-e675-444e-9613-8ca30affe12f?action=share&creator=39719611&active-environment=39719611-0fe1a957-1207-4a48-84eb-82c02d6226d8">Postman-коллекция для SOAP API</a>
</ul>


# ✉️ Тестирование REST и SOAP API через Postman  

## **Тестирование REST API**  
Я протестировала все API-запросы для интернет-магазина *DemoShopping*, используя документацию [Swagger](https://qa.demoshopping.ru/api-docs/). Для некоторых запросов создала скрипты, которые проверяют статус-код, время ответа, соответствие окружения, тип данных и ключи в теле ответа.  

- [Postman коллекция](https://www.postman.com/altimetry-specialist-32125376/workspace/demoshopping/collection/39719611-e745646a-0f39-4664-9435-1aa0195358c1?action=share&creator=39719611&active-environment=39719611-0fe1a957-1207-4a48-84eb-82c02d6226d8) модуля "Products", "Users", "Cart", "Order".  

Для каждого запроса разработала **тест-кейсы**, в которых описала входные данные, шаги выполнения, ожидаемый результат. После этого провела **тест-ран** в **QASE**, проверяя корректность работы API.  

- [Тест-кейсы](https://github.com/TaranenkoNatalia/api/blob/main/%D0%A2%D0%B5%D1%81%D1%82-%D0%BA%D0%B5%D0%B9%D1%81%D1%8B%20%D0%B4%D0%BB%D1%8F%20Postman.pdf) для Postman.  
- [Результаты тестового прогона тест-кейсов](https://github.com/TaranenkoNatalia/api/blob/main/%D0%A0%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82%D1%8B%20%D1%82%D0%B5%D1%81%D1%82%D0%BE%D0%B2%D0%BE%D0%B3%D0%BE%20%D0%BF%D1%80%D0%BE%D0%B3%D0%BE%D0%BD%D0%B0%20postman.json) для Postman.  

## **Тестирование SOAP API**  
Также протестировала **SOAP-сервис** с помощью [WSDL](ссылка_на_wsdl), который предоставляет информацию о странах. В Postman-коллекцию включены запросы для:  
Получения **списка всех стран**,  
Получения **детальной информации о стране** (столица, валюта, флаг).  

- [Postman-коллекция для SOAP API](https://www.postman.com/altimetry-specialist-32125376/workspace/demoshopping/collection/39719611-362a6cd0-e675-444e-9613-8ca30affe12f?action=share&creator=39719611&active-environment=39719611-0fe1a957-1207-4a48-84eb-82c02d6226d8)  






