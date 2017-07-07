## What is this?

Just you wait folks!

## Sample Datao

To load sample data, run the following command in your terminal:

```bash
npm run sample
```

If you have previously loaded in this data, you can wipe your database 100% clean with:

```bash
npm run blowitallaway
```

That will populate 16 stores with 3 authors and 41 reviews. The logins for the authors are as follows:

|Name|Email (login)|Password|
|---|---|---|
|Wes Bos|wes@example.com|wes|
|Debbie Downer|debbie@example.com|debbie|
|Beau|beau@example.com|beau|

#### Installed Extensions
    Pug Snippet
    Pug to HTML
    Babel Highlighting

#### MongoDB/mLab Setup, Configuration and Deployment
    1. Go to mLab to choose and create cloud provider hosting for deployment
        - select Amazon Web Services
        - Sandax, shared, .5gb, free
        - Select MongoDB version
        - Enter Database Name (dang-thats-delicious)
    2. Go to App Folder, select variables.env.sample and rename to variables.env
    3. Go to mLab then copy the connection string and paste into variables.env with DATABASE=
    4. Go to mLab, Select Users, Add new database user
        - Enter Database Name, Database Password, Confirm and click create(dang-thats-delicious, dang, dang)
    4. Go to App Folder, select variables.env, at DATABASE line replace the syntax and enter the database name and password that was entered in the mLab Users .
    5. Go to MongoDB Website and Donwload the MongoDB Compass for localhost database manipulation.
        - Open CMD then prompt to MongodDB Compass installation folder and type > mongod.
            - An error will occur, to solve, create a path C:\Data\db

    


        