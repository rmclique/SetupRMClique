# RM Clique Setup Scripts

Scripts personalizados para instalação e configuração de servidores baseados no Orion Design, adaptados para RM Clique.

## 🚀 Como Usar

### Instalação Rápida
```bash
sudo su
bash <(curl -sSL setup.rmclique.com.br)
```

## 📋 Funcionalidades

### Scripts Principais
- **Setup**: Script inicial que prepara o ambiente e baixa o script principal
- **SetupRMClique**: Script principal com todas as opções de instalação

### Novas Funcionalidades Adicionadas

#### Opção 79 - Remover Docker e sair do swarm
- Remove completamente o Docker do sistema
- Sai do Docker Swarm se estiver em um
- Remove todos os containers, imagens, volumes e redes
- Limpa todos os arquivos relacionados ao Docker

#### Opção 80 - Instalar Pterodactyl Panel
- Instala o Pterodactyl Panel usando Docker
- Configuração automática com Traefik para SSL
- Banco de dados MariaDB incluído
- Redis para cache
- Interface web completa para gerenciamento de servidores de jogos

#### Opção 81 - Instalar PufferPanel
- Instala o PufferPanel usando Docker
- Configuração automática com Traefik para SSL
- Banco de dados MariaDB incluído
- Redis para cache
- Interface web para gerenciamento de servidores

## 📝 Pré-requisitos

- Sistema operacional: Debian 11 (recomendado)
- Acesso root ou sudo
- Conexão com a internet
- Domínio configurado (para opções 80 e 81)

## 🔧 Configuração

### Para Pterodactyl (Opção 80)
- Domínio principal (ex: meudominio.com)
- Subdomínio (ex: painel)
- Email para certificados SSL
- Senha para banco de dados

### Para PufferPanel (Opção 81)
- Domínio principal (ex: meudominio.com)
- Subdomínio (ex: painel)
- Email para certificados SSL
- Senha para banco de dados

## 🛠️ Ferramentas Disponíveis

O script principal inclui 86 opções de instalação:

### 🐳 Containers e Orquestração
- **Docker** - Plataforma de containerização
- **Docker Compose** - Orquestração de containers
- **Docker Swarm** - Cluster de containers
- **Kubernetes** - Orquestração de containers
- **Helm** - Gerenciador de pacotes para Kubernetes
- **Istio** - Service mesh para microserviços

### 🌐 Servidores Web e Proxy
- **Nginx** - Servidor web e proxy reverso
- **Apache** - Servidor web
- **Traefik** - Proxy reverso moderno

### 🗄️ Bancos de Dados
- **MySQL** - Banco de dados relacional
- **PostgreSQL** - Banco de dados relacional avançado
- **MongoDB** - Banco de dados NoSQL
- **Redis** - Banco de dados em memória

### 💻 Linguagens de Programação
- **Node.js** - JavaScript no servidor
- **Python** - Linguagem de programação
- **PHP** - Linguagem para web
- **Java** - Linguagem de programação
- **Go** - Linguagem da Google
- **Rust** - Linguagem de sistemas

### 🔧 Ferramentas de Desenvolvimento
- **Git** - Controle de versão
- **Curl** - Cliente HTTP
- **Wget** - Download de arquivos
- **Vim** - Editor de texto
- **Nano** - Editor de texto simples
- **Htop** - Monitor de sistema
- **Neofetch** - Informações do sistema

### 🎥 Multimídia
- **FFmpeg** - Processamento de vídeo/áudio
- **ImageMagick** - Processamento de imagens

### 🔍 Utilitários
- **JQ** - Processador JSON
- **YQ** - Processador YAML
- **HTTPie** - Cliente HTTP
- **Tmux** - Multiplexador de terminal
- **Screen** - Multiplexador de terminal

### 🔒 Segurança
- **SSH** - Acesso remoto seguro
- **FTP** - Transferência de arquivos
- **SFTP** - FTP seguro
- **Rsync** - Sincronização de arquivos
- **Fail2ban** - Proteção contra ataques
- **UFW** - Firewall
- **Iptables** - Firewall avançado
- **OpenSSL** - Criptografia
- **Certbot** - Certificados SSL
- **Let's Encrypt** - Certificados SSL gratuitos

### ☁️ Cloud Providers
- **AWS CLI** - Amazon Web Services
- **Azure CLI** - Microsoft Azure
- **Google Cloud CLI** - Google Cloud Platform
- **DigitalOcean CLI** - DigitalOcean
- **Linode CLI** - Linode
- **Vultr CLI** - Vultr
- **Heroku CLI** - Heroku
- **Netlify CLI** - Netlify
- **Vercel CLI** - Vercel
- **Surge CLI** - Surge
- **Firebase CLI** - Firebase
- **Supabase CLI** - Supabase

### 🚀 DevOps e Infraestrutura
- **Terraform** - Infraestrutura como código
- **Ansible** - Automação
- **Vagrant** - Ambientes de desenvolvimento
- **VirtualBox** - Virtualização
- **VMware** - Virtualização
- **QEMU** - Emulador
- **KVM** - Virtualização Linux

### 🎮 Painéis de Gerenciamento
- **Opção 79**: Remover Docker e sair do swarm
- **Opção 80**: Instalar Pterodactyl Panel (Gerenciamento de servidores de jogos)
- **Opção 81**: Instalar PufferPanel (Gerenciamento de servidores)
- **Opção 87**: Instalar WireGuard VPN (VPN segura com Traefik)

## 🔒 Segurança

- Todos os scripts incluem verificações de segurança
- Certificados SSL automáticos via Let's Encrypt
- Configuração de firewall automática
- Senhas seguras para bancos de dados

## 📞 Suporte

Para suporte e dúvidas, entre em contato com a RM Clique.

## 📄 Licença

Este projeto está sob licença MIT. Veja o arquivo LICENSE para mais detalhes.

---

**RM Clique** - Soluções em Tecnologia
