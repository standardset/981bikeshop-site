# 981bikeshop

## prototipo

### Docker: 
Per configurare docker da zero ho seguito questo tutorial: 
https://x-team.com/blog/docker-compose-php-environment-from-scratch/

in Dockerfile/nginx ho dovuto modificare CMD così:
CMD ["nginx", "-g", "daemon off;"] 

senza questo comando non restava attivo nginx e dava messaggio "docker_nginx_1 exited with code 0": 

