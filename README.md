# Instruções
Repositório de php configurado para usar docker e criar ambiente

Para rodar no VScode crie o arquivo launch com o seguinte trecho

"port": 9000,
"pathMappings": {
    "/var/www/html/web": "${workspaceFolder}/web"
}

Assim seu Xdebug funcionará
