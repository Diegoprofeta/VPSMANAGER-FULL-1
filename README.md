# Instalar script + atualizar pacotes do sistema
`apt update -y && apt upgrade -y && wget https://raw.githubusercontent.com/nexyssh/VPSMANAGER-FULL/master/Plus; chmod 777 Plus; ./Plus`

# Liberar acesso root do sistema
`wget https://raw.githubusercontent.com/nexyssh/VPSMANAGER-FULL/master/senharoot.sh; chmod 777 senharoot.sh; ./senharoot.sh`

# Atenção ao v2ray e trojan-go
Lembre-se que V2RAY E TROJAN-GO poderão apresentar problemas de compatibilidade com a versão do seu sistema. Recomendo instalar em Ubuntu 18.04 ou Debian para o melhor funcionamento.

# Dicas de portas
WEBSOCKET: 80 ou 8080
SSL: 443

# Créditos
Apesar de ser opensource, sempre deixo os créditos pra quem merece. Git:
crazy_vpn (desenvolvedor)
rodrigo12xd (editor)