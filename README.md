# Ejemplo de un API RESTFUL con autenticación usando SANCTUM

# Instalación

```bash
composer install
```
```bash
php artisan migrate
```
```bash
copy .env.example .env o cp .env.example .env
```
```bash
php artisan serve
```

# Endpoints
- api/auth/register **(POST)**
    - **Campos**: name, email, password

- api/auth/login **(POST)**
    - **Campos**: email, password
- api/auth/logout **(POST)**

- api/user **(GET)**
- api/posts **(GET/POST)**
    - **Campos**: title, body
- api/posts/{id} **(GET/PUT/DELETE)**
