# Real Estate Site 
### Made By [***DannyGlade***](https://github.com/DannyGlade)
This is a Real E-state Site Project Made with Laravel, Bootstarp, JQuery, DataTables, FacyApp.
I only made it for my College Project, but if you are here that means I might have posted it online somewhere and you are here to steal it or see as refrence, but it's okay.
> Please Note!
> Beacause I am not good of a designer I have only used bootstrap, and nothing else, yet. So if you are looking for fancy site this might not be it. otherwise it looks decent enogh and funtionalities are also working... (obviously there will be some bugs)

## Dependencies
- [Composer v2.2.3^](https://getcomposer.org/download/)
- [Laravel v8.x](https://laravel.com/docs/8.x)
- [Bootstap v5.1.3](https://getbootstrap.com/docs/5.1/getting-started/introduction/)
- [Bootstrap v5.1 Examples](https://getbootstrap.com/docs/5.1/examples/) (Used Some of these as boiler plate)
- [JQuery v3.6.0](https://releases.jquery.com/)
- [DataTables v1.11.4](https://datatables.net/manual/) with [DataTables v1.11.4 Bootstap 5](https://datatables.net/examples/styling/bootstrap5.html)
- [FancyApps](https://fancyapps.com/docs/ui/installation)
  - [FancyBox](https://fancyapps.com/docs/ui/fancybox)
  - [Carousal](https://fancyapps.com/docs/ui/carousel)
- And Familiarity with Laravel, Can't remember anything else...

## What needs to be installed...
- [Composer v2.2.3^](https://getcomposer.org/download/)
- [Git](https://git-scm.com/downloads)
- [Laravel v8.x](https://laravel.com/docs/8.x)
- [Wamp](https://www.wampserver.com/en/) (I used Wamp you can use Similar ones)
- Can't remember anything else...

## Steps to Install
### Clone The GitHub Repo first
1. Open Cmd in folder you want to install project in...
2. Type Command `git clone https://github.com/DannyGlade/Real_Estate_Site.git` and hit enter...
3. Then cd into folder using `cd Real_Estate_Site`
> Note from here On, You can also use Terminal from VS Code or Your IDE...

### Install All Composer Dependencies
1. Use `composer install` to install all dependencies then wait till all process is complete...

### Create a .env file
1. Duplicate *.env.example* as *.env* file
2. Fill information of your DB **username** and **password** & other info if needed...

### Create DataBase
1. Create DataBase by PhpMyadmin (provided bt [Wamp](https://www.wampserver.com/en/)) or Any Other DB you use...
> Note DataBase name should be same as typed in *.env* file
### DataBase Structure
> I recommend to import DB structure Using `php artisan` method but you can use *.sql* file to import if you want.
1. Use Command `php artisan migrate` and wait till all migrations complete...

### Serve Project
1. Use Command `php artisan serve`( [Wamp](https://www.wampserver.com/en/)/Other Should be Runnig ) to run project...
> if some *key* related error appears then use command `php artisan key:generate` to generate AppKey.

## That's it...
Go to the Link that `php artisan serve` command gives you and Hopefully it should be working, I hope you are capable of any troubleshooting if any error occurs.

- Admin Email -> `admin@admin.com`
- Admin Password -> `admin123`

I am writing this documentaion while this project is still in making, because I was bored...

I will add more soon, If my mind says, lol...

If You are still reading, then thanks and Welcome...

Hope My project helps you any ways...

