# Invitation
Downloading the file from the <a href="https://storage.googleapis.com/gctf-2019-attachments/00c2a73eec8abb4afb9c3ef3a161b64b451446910535bfc0cc81c2b04aa132ed">link</a>
![The Roadmap](https://github.com/CodingJackson/GoogleCTF-Beginner/blob/master/Invitation/Screenshot%20from%202020-03-01%2001-00-33.png)
## Identifying the download

![](https://github.com/CodingJackson/GoogleCTF-Beginner/blob/master/Invitation/Screenshot%20from%202020-03-01%2001-33-21.png)

```file 00c2a73eec8abb4afb9c3ef3a161b64b451446910535bfc0cc81c2b04aa132ed```

## Converting the file & extracting it...

```mv 00c2a73eec8abb4afb9c3ef3a161b64b451446910535bfc0cc81c2b04aa132ed 00c2a73eec8abb4afb9c3ef3a161b64b451446910535bfc0cc81c2b04aa132ed.zip```


## Searching the files...

![](https://github.com/CodingJackson/GoogleCTF-Beginner/blob/master/Invitation/Screenshot%20from%202020-03-01%2001-23-34.png)


```cat log.txt```
```cat rand2```
```strings rand2```

**Here we have a lot of mess lets _grep it out_**

``` strings rand2 | grep flag```

![](https://github.com/CodingJackson/GoogleCTF-Beginner/blob/master/Invitation/Screenshot%20from%202020-03-01%2001-17-26.png)

Now we got our flag... 
__CTF{welcome_to_googlectf}__

