# Script-Servidor-Web

Este repositório contém um script em Shell para a provisão de um servidor web utilizando o Apache. O projeto foi desenvolvido como parte do Bootcamp Santander - Linux para Iniciantes, com foco em Infraestrutura como Código (IaC).

## Descrição

O script automatiza o processo de instalação e configuração de um servidor web Apache em sistemas baseados em Linux. Ele executa as seguintes etapas:

- Atualização da lista de pacotes e do sistema.
- Instalação do servidor web Apache.
- Download de arquivos de um repositório remoto para configurar o site.
- Configuração de permissões e estrutura necessária para o funcionamento do servidor.

## Funcionalidades

- Provisão automatizada de um servidor web com Apache.
- Configuração inicial do ambiente de servidor web.
- Script simples e reutilizável para diferentes ambientes.

## Requisitos

- Sistema operacional Linux.
- Permissões de superusuário (root) para executar o script.

## Como usar

### Passo 1: Clone o repositório

```bash
git clone https://github.com/JoaoAzevedo184/Script-Servidor-Web.git
```

### Passo 2: Acesse o diretório do projeto

```bash
cd Script-Servidor-Web
```

### Passo 3: Dê permissão de execução ao script

```bash
chmod +x script.sh
```

### Passo 4: Execute o script

```bash
sudo ./script.sh
```

O script irá realizar automaticamente as configurações necessárias para provisionar o servidor web.

## Estrutura do Código

O script está dividido nas seguintes etapas:

1. **Atualização do sistema**: Atualiza os pacotes instalados no sistema.
2. **Instalação do Apache**: Instala o servidor web Apache utilizando o gerenciador de pacotes.
3. **Configuração do servidor**: Realiza o download de arquivos necessários e configura o ambiente para o servidor web.
4. **Permissões e estrutura**: Configura permissões adequadas para os arquivos e diretórios criados.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para criar issues ou abrir pull requests com melhorias ou correções.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

Se você precisar de algo mais personalizado ou específico, me avise!
