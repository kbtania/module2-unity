# Система променів. Raycast.
Raycast широко використовується у розробці ігор. Raycast дозволяє створити деякий промінь і показати, на які об'єкти він потрапляє. Одним з прикладів використання може бути
випадок, коли при наведенні на об'єкт необхідно, щоб він змінив колір, розмір і т.д. По замовчуванню промінь потрапляє на всі об'єкти, але є можливість відфільтрувати об'єкти,
з якими колізії створюватися не будуть. Так як Raycast є об'єктом, відповідно він має певні поля. Наприклад деякі з них:
- origin - відповідає за початкові координати, звідки з'являтимуться промені;
- direction - вказує напрямок променів;
- maxDistance - максимальна відстань потрапляння променів;
- layerMask - вказує на об'єкти, які варто ігнорувати при потраплянні променів.

Доволі часто використовується при створенні сцен зі стрільбою.
