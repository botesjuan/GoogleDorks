# GoogleDorks  

>Google Dork Sample Search Filters  

## Sensitive Information Searching

>Searching for sensitive data, or files containing information containing the `target` domain with following sample search syntax.  
>Below sample search queries are for Amazon S3, jfrog, pastebin, dropbox, azure, etc.   

```
site:pastebin.com *@gmail.com* intext:spotify intext:premium
```

```
site:pastebin.com "target.abc"
```

```
site:docs.google.com inurl:"/d/" "target.abc"
```

```
site:onedrive.live.com "target.abc"
```

```
site:dropbox.com/s "target.abc"
```

```
site:box.com/s "target.abc"
```

```
site:dev.azure.com "target.abc"
```

```
site:http://sharepoint.com "target.abc"
```

```
site:digitaloceanspaces.com "target.abc"
```

```
site:firebaseio.com "target.abc"
```

```
site:jfrog.io "target.abc"
```

```
site:http://s3-external-1.amazonaws.com "target.abc"
site:http://s3.dualstack.us-east-1.amazonaws.com "target.abc"
```
