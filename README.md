## Ubuntu testing using the official docker image

### Nginx image customization
#### Run nginx in the background on the port 8080
```
docker run -d -p 8080:80 nginx
```

#### Run a custom html instead of the default nginx greeter
```
docker run -d -p 8080:80 -v $PWD/:/usr/share/nginx/html nginx
```

### Packages
- zsh
- git
- python3
- neofetch (maybe)