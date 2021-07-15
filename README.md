# Dojo 

Dojo é uma reunião em torno de um desafio não competitivo e que junte pessoas com vários níveis de habilidade, para testar novas ideias permitindo o aprendizado contínuo. 




## Objeto:
Utilizando os comando ad hoc colete as informações de configuração dos servidores.

Ambiente:
- 1x host Ansible
- 1x host Linux
- 1x host Windows

Requisitos:
- MobaXterm

### Desafio:
- Crie um inventario e com duas categorias linux e windows com os respectivos ips.
Doc: https://docs.ansible.com/ansible/latest/user_guide/intro_inventory.html

### Linux:
- O Servidor está pingando?
Doc: https://ansible-tips-and-tricks.readthedocs.io/en/latest/ansible/commands/
- Verificar a memória livre ou o uso de memória dos hosts
- Verificar o espaço livre em disco de hosts
Doc: https://www.linuxbuzz.com/execute-ansible-ad-hoc-commands/
- Qual é o tempo de atividade do servidores?
Doc: https://www.digitalocean.com/community/cheatsheets/how-to-manage-multiple-servers-with-ansible-ad-hoc-commands
- Qual é o dominio?
Doc:
- Stop o serviço cron
Doc: https://docs.ansible.com/ansible/latest/user_guide/intro_adhoc.html

### Windows:
- O Servidor está pingando?
DOC:
- Qual é o dominio?
DOC:
- Pare o serviço spooler
DOC: https://docs.ansible.com/ansible/latest/collections/ansible/windows/win_service_module.html

