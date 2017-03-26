## Social Poll

Go programming for study

### Setting

#### Setting Env

```
export SP_TWITTER_KEY=
export SP_TWITTER_SECRET=
export SP_TWITTER_ACCESSTOKEN=
export SP_TWITTER_ACCESSSECRET=
```

#### Start MongoDB Deamon

```
$ mongod --config /usr/local/etc/mongod.conf
```

#### Start NSQ Lookup Deamon

```
$ nsqlookupd
```

#### Start NSQ Deamon

```
$ nsqd --lookupd-tcp-address=localhost:4160
```

#### Watch NSQ Message

```
nsq_tail --topic="votes" --lookupd-http-address=localhost:4161
```
