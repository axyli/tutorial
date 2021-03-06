#### REST vs SOAP

* Пример реализации RESTful: JSON через HTTP
* Пример реализации SOAP: XML поверх SOAP через HTTP

На верхнем уровне **SOAP** ограничивает структуры ваших сообщений, тогда как **REST** — это архитектурный подход, ориентированный на использование HTTP в качестве транспортного протокола.

Специфика SOAP — это формат обмена данными. С SOAP это всегда SOAP-XML, который представляет собой XML, включающий:
* Envelope (конверт) – корневой элемент, который определяет сообщение и пространство имен, использованное в документе,
* Header (заголовок) – содержит атрибуты сообщения, например: информация о безопасности или о сетевой маршрутизации,
* Body (тело) – содержит сообщение, которым обмениваются приложения,
* Fault – необязательный элемент, который предоставляет информацию об ошибках, которые произошли при обработке сообщений. И запрос, и ответ должны соответствовать структуре SOAP.

Специфика REST — использование HTTP в качестве транспортного протокола. Он подразумевает наилучшее использование функций, предоставляемых HTTP — методы запросов, заголовки запросов, ответы, заголовки ответов и т. д.

**Формат обмена сообщениями**

* В SOAP вы используете формат SOAP XML для запросов и ответов.
* В REST такого фиксированного формата нет. Вы можете обмениваться сообщениями на основе XML, JSON или любого другого удобного формата. JSON является самым популярным среди используемых форматов.

**Определения услуг**

*  SOAP использует WSDL (Web Services Description Language) — язык описания веб-сервисов и доступа к ним, основанный на языке XML.
* REST не имеет стандартного языка определения сервиса. Несмотря на то, что WADL был одним из первых предложенных стандартов, он не очень популярен. Более популярно использование Swagger или Open API.

**Транспорт**

* SOAP не накладывает никаких ограничений на тип транспортного протокола. Вы можете использовать либо Web протокол HTTP, либо MQ.

* REST подразумевает наилучшее использование транспортного протокола HTTP

**Простота реализации**

* RESTFful веб-сервисы, как правило, гораздо проще реализовать, чем веб-сервисы на основе SOAP.

* REST обычно использует JSON, который легче анализировать и обрабатывать. В дополнение к этому, REST не требует наличия определения службы для предоставления веб-службы.
Однако в случае SOAP вам необходимо определить свой сервис с использованием WSDL, и при обработке и анализе сообщений SOAP-XML возникают большие накладные расходы.


Описание RPC по ссылке, если интересно  
https://coderlessons.com/tutorials/akademicheskii/osnovy-operatsionnykh-sistem/13-udalennyi-vyzov-protsedur-rpc


Интересная и хорошая статься по gRPC  
https://blog.maddevs.io/go-rest-%D0%B8%D0%BB%D0%B8-grpc-f5d52d7ffff6