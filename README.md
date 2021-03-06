# bookstore-uml
UML Class Diagram of academic project with given description

1. Интернет-магазин должен иметь веб-интерфейс, но он должен иметь возможность подключения через другие интерфейсы (веб-сервисы и т.п.)
2. Интернет-магазин предназначен для продажи книг, с оплатой заказов через интернет.
3. Пользователь должен иметь возможность добавить книги в онлайн корзину, после чего произвести оплату.
4. Пользователь может убрать предметы из корзины.
5. Пользователь должен иметь возможность вести списки желаемых покупок, т.е. книг, которые он хочет купить позже.
6. Пользователь должен иметь возможность отменить заказ до того, как он отправлен по почте.
7. Пользователь должен иметь возможность оплатить заказ кредитной картой или по счету на оплату.
8. Должна быть возможность вернуть книги.
9. Интернет-магазин должен встраиваться на сайты партнеров в виде мини-каталога, который составляется по основному каталогу, хранящемуся в центральной базе данных.
10. Мини-каталог должен быть построен на основе XML для того, чтобы была возможность передавать его между системами.
11. Пользователь должен иметь возможность создать учетную запись клиента, чтобы система запоминала данные пользователя (имя, адрес, данные банковской карты и т.д.) и восстанавливала их при входе.
12. Система должна вести основной список учетных записей в центральной базе данных.
13. При входе пользователя его пароль должен сверяться с паролем в основном списке паролей, сохраненным в базе данных.
14. Пользователь должен иметь возможность искать книги различными способами поиска – по заголовку, по автору, ключевому слову или категории и после поиска просматривать детальное описание книги.
15. Пользователь должен иметь возможность оставлять отзывы на понравившиеся книги. Оставленные отзывы  должны появляться в детальном описании книги. Отзыв должен включать выставленный клиентом рейтинг (1-5), который должен показываться вместе с заголовком книги в списке книг.
16. Отзывы на книгу должны модерироваться, т.е. им должен присваиваться статус Ok кем-то из администраторов прежде, чем они появятся на сайте.
17. Длинные отзывы должны обрезаться при выводе детального описания книги. Клиент может щелкнуть по отзыву, чтобы просмотреть  полный отзыв на отдельной странице.
18. Должна быть возможность размещения администраторами редакторских отзывов. Они также должны появляться на странице с детальным описанием книги.
19. Интернет-магазин должен позволять сторонним продавцам (например, магазинам подержанных книг) добавлять свои каталоги книг в основной каталог книг, так чтобы книги этих продавцов присутствовали в результатах поиска.
20. Интернет-магазин должен быть масштабируем со следующими требованиями:
* Должна быть возможность управлять до 100 тыс. учетных записей пользователей за первые 6 месяцев работы и затем до 1 млн. пользователей.
* Должна быть возможность обслуживать одновременно 1000 посетителей (до 10000 тысяч после 6 месяцев)
* Система должна обслуживать 100 поисковых запросов в минуту (1 тыс./мин. после 6 месяцев)
* Система должна обслуживать 100 покупок в час (1 тыс./час после 6 мес.)

