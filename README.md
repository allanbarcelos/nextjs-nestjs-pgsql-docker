# 

## 

- Api: `http://__DOMAIN__/api`
- WebApp: `http://__DOMAIN__/`
- WebAdmin: `http://__DOMAIN__/webadmin/`


## Commands

### Docker

```shell
# default: 
# USER -> admin PASS -> admin
# htpassword: generate new when go to production
docker run --rm httpd:2.4 htpasswd -Bbn admin sua_senha > .htpasswd
```