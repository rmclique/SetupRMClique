# RM Clique Setup Scripts

Scripts personalizados para instalação e configuração de servidores baseados no Orion Design, adaptados para RM Clique.

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

## 🚀 Como Usar

### Instalação Rápida
```bash
bash <(curl -sSL https://raw.githubusercontent.com/SEU_USUARIO/SEU_REPO/main/Setup)
```

### Instalação Manual
1. Clone o repositório:
```bash
git clone https://github.com/SEU_USUARIO/SEU_REPO.git
cd SEU_REPO
```

2. Torne os scripts executáveis:
```bash
chmod +x Setup SetupRMClique
```

3. Execute o script inicial:
```bash
./Setup
```

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

## 📋 Opções Disponíveis

O script principal inclui 86 opções de instalação:

### Desenvolvimento
- Docker, Docker Compose, Kubernetes
- Node.js, Python, PHP, Java, Go, Rust
- Git, Curl, Wget

### Servidores Web
- Nginx, Apache, Traefik
- MySQL, PostgreSQL, MongoDB, Redis

### Ferramentas
- Vim, Nano, Htop, Neofetch
- FFmpeg, ImageMagick, JQ, YQ

### Segurança
- SSH, FTP, SFTP, Rsync
- Fail2ban, UFW, Iptables
- OpenSSL, Certbot, Let's Encrypt

### Cloud Providers
- AWS CLI, Azure CLI, Google Cloud CLI
- DigitalOcean, Linode, Vultr
- Heroku, Netlify, Vercel

### DevOps
- Terraform, Ansible, Vagrant
- VirtualBox, VMware, QEMU, KVM

### Novas Funcionalidades
- **Opção 79**: Remover Docker e sair do swarm
- **Opção 80**: Instalar Pterodactyl Panel
- **Opção 81**: Instalar PufferPanel

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
