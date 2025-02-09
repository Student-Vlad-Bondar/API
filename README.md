# Документація

Детальна документація API доступна за посиланням:
[Postman Documentation](https://documenter.getpostman.com/view/41955505/2sAYX9mKdg)

---

## Опис запуску

1. **Виконайте клонування репозиторію**
   ```sh
   git clone https://github.com/oleksandr-kipz/symfony-test
   ```

2. **Встановіть Composer**  
   Завантажте та встановіть Composer відповідно до інструкцій на офіційному сайті:  
   [https://getcomposer.org/download/](https://getcomposer.org/download/)

3. **Встановіть залежності PHP**
   ```sh
   composer install
   ```

4. **Встановіть пакет для аутентифікації через JWT**
   ```sh
   composer require lexik/jwt-authentication-bundle
   ```

5. **Генеруйте ключі для JWT**
   ```sh
   php bin/console lexik:jwt:generate-keypair
   ```

6. **Можете запускати сервер**
   ```sh
   symfony server:start
   ```
