# ☁️ Tipos de Serviço em Nuvem – IaaS, PaaS e SaaS

Este conteúdo faz parte do bootcamp **GFT Start .NET – DIO** e apresenta os **principais modelos de serviço em nuvem** oferecidos pela plataforma Microsoft Azure.

---

## 🧱 Modelos de Serviço na Nuvem

Na computação em nuvem, os serviços são divididos em **três modelos principais**, baseados no nível de controle, responsabilidade e abstração:

---

### 🔧 IaaS – Infrastructure as a Service

> "Você gerencia o que roda. O provedor gerencia a infraestrutura."

**Infraestrutura como Serviço (IaaS)** oferece recursos básicos como máquinas virtuais, redes, armazenamento e balanceadores de carga.

#### ✅ Características:
- Mais flexibilidade e controle
- Responsabilidade pelo sistema operacional, runtime, apps e dados
- Ideal para migração de sistemas legados

#### 🧪 Exemplos no Azure:
- Azure Virtual Machines (VMs)
- Azure Virtual Network (VNet)
- Azure Load Balancer
- Azure Blob Storage

🔗 Referência:  
[Infrastructure as a Service (IaaS) – Microsoft Learn](https://azure.microsoft.com/pt-br/resources/cloud-computing-dictionary/what-is-iaas/)

---

### 🧱 PaaS – Platform as a Service

> "Você gerencia o aplicativo. A plataforma cuida do resto."

**Plataforma como Serviço (PaaS)** fornece um ambiente pronto para desenvolvimento e hospedagem de aplicações, sem se preocupar com infraestrutura ou sistema operacional.

#### ✅ Características:
- Reduz tempo de desenvolvimento
- Escalabilidade automática integrada
- Foco total no código da aplicação

#### 🧪 Exemplos no Azure:
- Azure App Service
- Azure Functions (serverless)
- Azure SQL Database
- Azure Web Apps + DevOps pipelines

🔗 Referência:  
[Platform as a Service (PaaS) – Microsoft Learn](https://azure.microsoft.com/pt-br/resources/cloud-computing-dictionary/what-is-paas)

---

### 🌐 SaaS – Software as a Service

> "Você só usa o software. Todo o resto é responsabilidade do fornecedor."

**Software como Serviço (SaaS)** entrega aplicações completas prontas para uso, acessadas via navegador, sem instalação ou gerenciamento local.

#### ✅ Características:
- Usuário final não precisa se preocupar com código ou infraestrutura
- Sempre atualizado e disponível
- Ideal para produtividade e colaboração

#### 🧪 Exemplos no Azure / Microsoft:
- Microsoft 365 (Outlook, Word, Excel, Teams)
- OneDrive
- Dynamics 365
- Power BI (versão SaaS)

🔗 Referência:  
[Software as a Service (SaaS) – Microsoft Learn](https://azure.microsoft.com/pt-br/resources/cloud-computing-dictionary/what-is-saas)

---

## 📊 Comparativo: IaaS vs PaaS vs SaaS

| Característica              | IaaS                          | PaaS                       | SaaS                          |
|----------------------------|-------------------------------|----------------------------|-------------------------------|
| Nível de controle          | Alto                          | Médio                      | Baixo                         |
| Quem gerencia o quê        | Cliente gerencia quase tudo   | Cliente gerencia o app     | Tudo é gerenciado pelo provedor |
| Complexidade de setup      | Alta                          | Média                      | Mínima                        |
| Exemplo real               | Azure VM                      | Azure App Service          | Microsoft 365                 |
| Indicado para              | Infraestruturas personalizadas | Devs focados em app        | Usuários finais / empresas    |

---

## ✅ Conclusão

A escolha entre **IaaS**, **PaaS** ou **SaaS** depende do nível de controle e da responsabilidade que você deseja assumir.

- **IaaS** é ideal quando você precisa de controle sobre tudo.
- **PaaS** é perfeito quando você quer focar no desenvolvimento e deixar o ambiente por conta do provedor.
- **SaaS** é a solução mais simples e rápida para acesso a softwares prontos.

Conhecer essas diferenças é essencial para tomar boas decisões na arquitetura de soluções na nuvem.

---

> _“Na nuvem, a escolha do modelo certo define o equilíbrio entre flexibilidade, agilidade e responsabilidade.”_
