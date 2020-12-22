1. С очередным релизом приложения были добавленны новые шаблоны писем с использованием Маутика. Шаблоны отправляют данные с именем клиента, стоимостью заказа и если заказ больше определенной суммы, то отправляют купон на следующий новый заказ для этого клиента. Опишите ваши действия, как вы будете проверять всю логику обновлений, какой результат проверки можно считать корректным и не требующим исправлений. 
2. При поступлении платежей через PayPal, служба поддержки продукта не видет их в административной панели. Что можно проверить и в какой последовательности, что бы понять причину этой ситуации.
3. При регистрации новых клиентов в web приложении, переодически поступают жалобы в службу поддержки о невозможности пройти полностью процесс регистрации. Какие автоматизированные средства проверки можно использовать что бы найти причины жалоб. 
4. Продукт имеет сложный подстчет стоимости. На финальную стоимость влияет срок реализации продукта, наличие скидочного купона, купоны могут иметь скидку на определенные части продукта. Сколько и какие варианты проверки стоимости вы считаете нужным сделать?
5. При проверке нового дизайна web приложения и писем на что нужно обращать внимание?
6. При сложении 5+2, может ли быть получен результат 52, и если да, то почему и может ли это не быть ошибкой? 
7. Какую ошибку содержит код представленный ниже:
```
<div class="form">
  <p>
    Enter your full name: <input type="text" name="fullname">
    <input type="submit" value="Send data">
  </p>
</form>
</div>
```
8. Автоматические тесты должны проверять только что сущность работает корректно на корректных данных?
9. В базе данных config в таблице gateway содержится 17М записей, каким запросом к этой таблице можно очень сильно нагрузить базу данных?
10. Предположим ситуацию: вместе с релизом в продакшен уходит очень большое количество правок, затрагивающих самые разные аспекты продукта (процесс регистрации, обновления онлайн чата, новый дизайн отдельных блоков, добавлены новые методы оплаты …) В какой последовательности стоит тестировать данный функционал, нужно ли проверять области которые не затрагивались (например авторизация, триггерные сообщения итд, расчет цены), в каком порядке выставить приоритеты, учитывая что на полное мануальное тестирование может уйти не один день.
11. Сегодня релиз продукта и тебя попросили сделать полную проверку, имея выбор - пойти с друзьями в поход на выходные или посидеть подольше и проверить все что можно, какой ты сделаешь выбор?
