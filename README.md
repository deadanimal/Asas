# Asas 

This is basic template for any Laravel app that any Piper need to use.

## Step to get basic template

please ensure that you rm -rf .git and later re set the git by init, add, commit, add remote, and push as usal.

1. composer install
2. npm install && npm run dev
3. cp .env.example .env
4. php artisan key:generate
5. setup MySQL for localhost
6. update .env
7. php artisan migrate
8. CODE!

## HTML base template available

1. SoftUI BS5
2. Hyper BS5

## Other components also install

1. Breeze 
2. Guzzle 
3. Sanctum

## Concepts implemented

1. Resource CRUD controller
2. Blade extend
3. Send email
4. File upload/storage
5. Task schedule
6. Role authorization(according to group)
7. Encryption

Things not implemented

1. Queue


