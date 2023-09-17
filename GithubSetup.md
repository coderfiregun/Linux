Key creation

```
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

Check if eval agent is there

```
 eval "$(ssh-agent -s)"
```

Add key

```
ssh-add ~/.ssh/id_rsa
```

Add pub key to Cloud Repository
```
cat id_rsa.pub
```


