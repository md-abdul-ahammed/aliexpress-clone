# AliExpress Clone / (aliexpress-clone)

## App Setup (localhost)

```
git clone https://github.com/md-abdul-ahammed/aliexpress-clone.git

cp .env.example .env

npm i

npx prisma generate

npm run dev
```

You'll have to setup a Supabase account & Stripe account, then add all of the details in to your .env file.

Once you've connected your application to Supabase. You'll also need to setup the Auth Providers:
Google [Google](https://cloud.google.com)
Github [Github](https://github.com/settings/developers)

    https://supabase.com/docs/guides/auth/social-login/auth-google
    https://supabase.com/docs/guides/auth/social-login/auth-github

Now run the command to migrate your database tables and run your seed file.

```
npx prisma migrate dev --name init
```

You should be good to go! If you need any more help, take a look at the tutorial video by clicking the image above.

# Application Images

<img width="1439" src="https://i.ibb.co/2Sq0vGc/1.png">
<img width="1439" src="https://i.ibb.co/2Sq0vGc/2.png">
<img width="1439" src="https://i.ibb.co/2Sq0vGc/3.png">
<img width="1439" src="https://i.ibb.co/2Sq0vGc/4.png">
<img width="1439" src="https://i.ibb.co/2Sq0vGc/5.png">
<img width="1439" src="https://i.ibb.co/2Sq0vGc/6.png">
