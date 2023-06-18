# Kucoin futures crypto trading bot (USDTM)

### IMPORTANT 
Create a file called " config.env "

# 1.
Sign up to Kucoin - third party api for futures trading.
```
https://www.kucoin.com
```
Click on profile -> API management -> Create Api
Fill out the config.env.
```
KUCOIN_API_KEY=api_key
KUCOIN_API_SECRET=api_secret
KUCOIN_API_PASSPHRASE=api_passphrase
```

# 2.
Sign up to MongoDB - database for storing our data.
```
https://www.mongodb.com
```
Create a new cluster -> connect -> drivers -> copy "mongodb+srv...majority"
Fill out the config.env.
```
NODE_ENV=development
DATABASE=mongodb+srv://<username>:<password>@cluster0.safaff.mongodb.net/?retryWrites=true&w=majority
DATABASE_PASSWORD=password
```