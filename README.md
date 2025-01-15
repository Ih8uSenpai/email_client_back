Для запуска требуется бд postgresql, в переменных среды указываются параметры бд и url фронта

Переменные среды(в IDEA можно указать прямо в конфигурации запуска, нужно нажать modify options и добавить Environment variables):
SPRING_DATASOURCE_URL=your_url;SPRING_DATASOURCE_USERNAME=your_username;SPRING_DATASOURCE_PASSWORD=your_password;FRONTEND_URL=http://localhost:3000/
