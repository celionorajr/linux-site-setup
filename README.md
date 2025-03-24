```markdown
# Desafio de Projeto - Infraestrutura como Código: Provisionamento de Servidor Web Apache

## Descrição

Este projeto faz parte do **Bootcamp Santander - Linux para Iniciantes** oferecido pela **DIO (Digital Innovation One)**. O objetivo deste desafio foi criar um **script de provisionamento** de um servidor web com Apache, utilizando o conceito de Infraestrutura como Código (IaC).

O script automatiza o processo de configuração de um servidor Apache, incluindo a instalação de pacotes essenciais, o download e extração de uma aplicação, e a configuração de permissões para garantir que o servidor web esteja pronto para servir a aplicação.

## Funcionalidades

- **Atualização de pacotes**: O script começa atualizando os pacotes do sistema para garantir que o servidor esteja com a versão mais recente.
- **Instalação de pacotes**: Instala o Apache2 e o Unzip, necessários para rodar o servidor web e descompactar a aplicação.
- **Download e extração de aplicação**: Baixa a aplicação hospedada no GitHub e extrai os arquivos.
- **Configuração de permissões**: Ajusta as permissões de arquivos para garantir que o servidor web Apache possa acessar e servir a aplicação corretamente.
- **Reinício do Apache**: Após a configuração, o Apache é reiniciado para aplicar as mudanças.

O script irá atualizar os pacotes, instalar as dependências necessárias, configurar o Apache e reiniciá-lo para aplicar as mudanças.

---

Desafio realizado com o apoio da **DIO (Digital Innovation One)**, como parte do Bootcamp **Santander - Linux para Iniciantes**.
```
