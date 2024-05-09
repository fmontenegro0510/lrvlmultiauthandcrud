`# Laravel 10 Login Register with Multi User Authentication and CRUD Admin Page`

`Este repositorio contiene un proyecto de Laravel 10 que implementa un sistema de autenticación de múltiples usuarios con páginas de inicio de sesión y registro, así como una página de administración CRUD.`

`## Requisitos`

`- PHP >= 8.0`
`- Composer`
`- Laravel 10`

`## Instalación`

`1. Clona el repositorio:`
```
git clone https://github.com/tu-usuario/laravel10-multi-auth.git
```
`2. Instala las dependencias con Composer:`
```
composer install
```
`3. Copia el archivo .env.example y renómbralo a .env:`
```bash
cp .env.example .env
```
`4. Genera una nueva clave de aplicación:`
```css
php artisan key:generate
```
`5. Configura la base de datos en el archivo .env y ejecuta las migraciones:`
```css
php artisan migrate
```
`6. Instala las dependencias de npm y compila los assets:`
```
npm install
npm run dev
```
`## Uso`

`Accede al proyecto en tu navegador en la dirección `http://localhost:8000` y podrás ver la página de inicio de sesión y registro. Una vez registrado e iniciado sesión, los usuarios pueden acceder a su perfil y editar su información. Los usuarios administradores también pueden acceder a la página CRUD de administración para gestionar los usuarios y su información.`

`## Contribuciones`

`Las contribuciones son bienvenidas. Si encuentras un error o quieres añadir alguna funcionalidad, por favor abre un issue o envía un pull request.`

`## Licencia`

`Este proyecto está licenciado bajo la licencia MIT.`