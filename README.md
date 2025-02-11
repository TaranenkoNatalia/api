# ✉️ Тестирование REST и SOAP API через Postman

Я протестировала все запросы для интернет-магазина "DemoShopping", используя документацию <a href="https://qa.demoshopping.ru/api-docs/">Swagger</a>. Для некоторых запросов создала автотесты, которые проверяют статус-код после отправки запроса, время ответа, проверки для тела (тип данных в значениях, изменение ключа). 

 <ul>
<li>  <a href="https://www.postman.com/altimetry-specialist-32125376/workspace/demoshopping/collection/39719611-e745646a-0f39-4664-9435-1aa0195358c1?action=share&creator=39719611&active-environment=39719611-0fe1a957-1207-4a48-84eb-82c02d6226d8">Postman коллекция</a> модуля "Products", "Users", "Cart", "Order". </li> 

<li>  <a href="https://github.com/TaranenkoNatalia/api/blob/main/%D0%A2%D0%B5%D1%81%D1%82-%D0%BA%D0%B5%D0%B9%D1%81%D1%8B%20%D0%B4%D0%BB%D1%8F%20Postman.pdf">Тест-кейсы</a> для Postman. </li> 

<li>  <a href="https://github.com/TaranenkoNatalia/api/blob/main/%D0%A0%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82%D1%8B%20%D1%82%D0%B5%D1%81%D1%82%D0%BE%D0%B2%D0%BE%D0%B3%D0%BE%20%D0%BF%D1%80%D0%BE%D0%B3%D0%BE%D0%BD%D0%B0%20postman.json">Результаты тестового прогона тест-кейсов</a> для Postman. </li>


<li>  <a href="https://www.postman.com/altimetry-specialist-32125376/workspace/demoshopping/collection/39719611-362a6cd0-e675-444e-9613-8ca30affe12f?action=share&creator=39719611&active-environment=39719611-0fe1a957-1207-4a48-84eb-82c02d6226d8">Postman коллекция</a> для тестирования SOAP-сервиса с помощью <a href="http://webservices.oorsprong.org/websamples.countryinfo/CountryInfoService.wso?WSDL">WSDL</a> , который предоставляет информацию о странах (получение списка всех стран, получение
деталей о конкретной стране - столица, валюта, флаг и т.д.). </li>
</ul>
