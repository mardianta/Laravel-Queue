# Laravel-Queue
Laravel Queue

How to see response time :

        $starttime = microtime(true);
        //code
        $endtime = microtime(true);
        $timediff = $endtime - $starttime;
        echo $timediff.'s';
Step 1. Create Queue

        php artisan queue:table
        
        php artisan migrate

# Reference
- Laravel Queues : https://laravel.com/docs/9.x/queues
- Laravel Queue Indonesia https://www.youtube.com/watch?v=U2g_mNL1yc8
