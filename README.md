# laravel-7-simple-multi-auth
Free

1. composer install
2. php artisan migrate
3. default admin login -> ../admin/login
    admin@admin.com / password
4. for user can register
5. to add another admin can use 'php artisan tinker', example;
    $admin = new App\Admin;
    $admin->name = "Admin";
    $admin->email = "admin@admin.com";
    $admin->password = Hash::make("password");
    $admin->save();
