# Criando uma Instância Gerenciada de SQL no Azure (Via Portal)

## Visão Geral

Guia de como criar uma **Instância Gerenciada do SQL do Azure** (PaaS) com alta compatibilidade com o SQL Server, combinando gestão automatizada com escalabilidade, segurança e integração com redes virtuais (VNet).

## Pré-requisitos

- Assinatura ativa do Azure
- Permissões para criar recursos

## Etapas do Processo

### 1. Acessar o Portal
- Vá para: [https://portal.azure.com](https://portal.azure.com)

### 2. Navegar até "SQL do Azure"
- Clique em **“SQL do Azure”** > **“Criar”**

### 3. Escolher "Instância única"
- Na tela de opções de implantação, selecione **"Instância única"** e clique em **"Criar"**

### 4. Preencher Informações Básicas
- **Grupo de Recursos**: novo ou existente
- **Nome da instância**
- **Região**
- **Autenticação SQL**: definir login e senha

### 5. Configurar Rede
- Acesso **público** ou **privado** via **VNet/Sub-rede**

### 6. Revisar e Criar
- Clique em **“Revisar + criar”**
- Após validação, clique em **“Criar”**

## Acompanhamento da Implantação
- Acompanhe o progresso pelas **notificações** do portal
- Acesse a instância pelo **grupo de recursos**

## Dicas de Gerenciamento

- **Tags** para organização (ex: `Ambiente=Produção`)
- **Backups automáticos** com retenção configurável
- **Segurança de rede** com NSG e identidades gerenciadas

## Recursos Adicionais

- [Visão geral da instância gerenciada](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/sql-managed-instance-paas-overview?view=azuresql)
- [Criação via PowerShell](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/instance-create-quickstart?tabs=azure-powershell)
- [Criação via Azure CLI](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/instance-create-quickstart?tabs=azure-cli)
