# Wordpress Curated helm deployment

# tl;dr
`helm install  .\wordpress-curated\ --set hostname=yourdomain.example.com`

You'll be greeted with a language selection and skip to define your user credentais as the database credentials are pregenerated. 


# TODO 

- Use https://vitess.io/ in place of mariadb deployment
- Enable HTTPS along with cert manager for automatic  LetsEncrypt assignment
- Make alternate: Cloudflared deployment
- Configure premade user/pass via secret using an initi container with image wordpress:cli
- More dynamics/config options/overrides
- More cluster manifests / documentation on requirements, such as nginx ingress controller
- Additional documentation
- Preconfigure admin users using an init container 
