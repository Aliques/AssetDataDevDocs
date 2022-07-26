##  Создание проекта в Facebook

1. Перейти по ссылке https://developers.facebook.com
2. Перейти по ссылке “Начать работу” или ”MyApps” (в зависимости от локализации)

![fimage9](./img/fimage9.png)

![fimage5](./img/fimage5.png)

4. В окне приложений создайте приложение нажав на соответствующую кнопку

![fimage2](./img/fimage2.png)

5. Выберите тип приложения “Consumer”/”Потребительское”  (в зависимости от локализации).

![fimage3](./img/fimage3.png)

6. Введите название приложения (остальные поля по желанию) и создайте приложение (зеленая кнопка)

![fimage1](./img/fimage1.png)

7. После создания приложения, сайт перенаправит на страницу с добавления продуктов. Выберите “Set up”/”Настроить” для “Facebook login”/”Вход через facebook”

![fimage7](./img/fimage7.png)

8. В следующем окне перейдите во вкладку “Настроек”

![fimage4](./img/fimage4.png)

9. В поле “Действительные URI перенаправления для OAuth”/”Valid OAuth redirect URLs” ввести “https://test.service.assetdata.market/signin-facebook” и “https://test.service.assetdata.market/api/identity/externalAuth/auth-client-redirect”  (без кавычек). Сохраните изменения.

![fimage6](./img/fimage6.png)

10. Во вкладке Настройки(“Settings”) -> Основные(“Basics”). Значения полей AppId(id приложения) и App secret (секрет приложения) определить в настройках web(server-side) приложения.

![fimage8](./img/fimage8.png)

11. Возможно потребуется заполнить такие поля как: URL-адрес политики конфиденциальности и url удаления данных пользователей

![fimage8](./img/fimage10.png)
