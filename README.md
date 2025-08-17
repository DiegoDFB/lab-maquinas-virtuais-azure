# lab-maquinas-virtuais-azure
Documentação sobre o curso de Fundamentos de Microsoft Azure na DIO.

**Progresso e Aprendizado em Fundamentos de Microsoft Azure**

**1. Introdução**

Este documento tem como objetivo registrar o progresso e os conhecimentos adquiridos durante o curso de Fundamentos de Microsoft Azure da DIO, abordando os seguintes tópicos:

**Introdução à computação em nuvem**

**Benefícios da computação em nuvem**

**Tipos de serviços de nuvem**

**Criação de máquinas virtuais no Azure**


**2. Introdução à Computação em Nuvem**

A computação em nuvem é um modelo que permite o acesso sob demanda a recursos computacionais (como servidores, armazenamento, redes e aplicações) pela internet, sem a necessidade de gerenciamento físico direto.

**Principais Conceitos**

**Escalabilidade:** Ajuste automático de recursos conforme a demanda.

**Elasticidade:** Capacidade de expandir ou reduzir recursos rapidamente.

**Pagamento por uso (Pay-as-you-go):** Cobrança baseada no consumo.

**Acesso remoto:** Disponibilidade de serviços de qualquer lugar com internet.

**3. Benefícios da Computação em Nuvem**

**Redução de Custos:**	Elimina gastos com infraestrutura física e manutenção.

**Alta Disponibilidade:**	Serviços redundantes garantem menor tempo de inatividade.

**Escalabilidade Flexível:**	Aumento ou redução de recursos conforme a necessidade.

**Segurança Avançada:**	Proteção de dados com criptografia, firewalls e conformidade regulatória.

**Atualizações Automáticas:**	Manutenção e patches gerenciados pelo provedor de nuvem.


**4. Tipos de Serviços de Nuvem**

**a) IaaS (Infrastructure as a Service)**

**O que é:** Fornece infraestrutura virtualizada (máquinas virtuais, redes, armazenamento).


**b) PaaS (Platform as a Service)**

**O que é:** Oferece um ambiente para desenvolvimento e implantação de aplicações.


**c) SaaS (Software as a Service)**

**O que é:** Software completo gerenciado pelo provedor e acessado via navegador.


**5. Criando Máquinas Virtuais no Azure**

**Passo a Passo para Criação de uma VM no Azure**

Acessar o Portal Azure (https://portal.azure.com).

Criar um Recurso → "Máquina Virtual".

Configuração Básica:

Assinatura: Selecionar a conta Azure.

Grupo de Recursos: Criar ou selecionar um existente.

Nome da VM: Definir um nome único.

Região: Escolher a localização do datacenter.

Imagem: Selecionar o sistema operacional (ex: Windows Server ou Ubuntu).

Tamanho: Escolher a configuração de CPU, RAM e armazenamento.

Habilitar Backup Automático para evitar perda de dados.

Configurar Grupos de Segurança de Rede (NSG) para restringir tráfego não autorizado.


**6. Configurando um Banco de Dados no Microsoft Azure**

O Azure oferece diversos serviços de banco de dados, incluindo:

**Azure SQL Database (Banco de dados relacional gerenciado)**

**Azure Cosmos DB (Banco de dados NoSQL distribuído globalmente)**

**Azure Database for MySQL/PostgreSQL (Bancos de dados open-source gerenciados)**


**Passo a Passo para Criar um Banco de Dados SQL no Azure**
**1. Acessar o Portal Azure**

**2. Criar um Recurso de Banco de Dados SQL**

No menu lateral, selecione "Criar um recurso".

Na barra de pesquisa, digite "SQL Database" e selecione o serviço.

Clique em "Criar".

**3. Configurar os Detalhes Básicos**
**Assinatura:**	Selecione a assinatura Azure onde o banco será criado.

**Grupo de Recursos:**	Crie um novo ou selecione um existente para organizar recursos relacionados.

**Nome do Banco:**	Defina um nome único (ex: meubancosql).

**Servidor:**	Crie um novo servidor lógico (ex: sqlserver-001).

**Localização:**	Escolha a região do datacenter (ex: East US).

**Tipo de Banco:**	Selecione "Uso Geral" (para casos padrão) ou "Hiperescala" (alta performance).

**Computação + Armazenamento:**	Escolha o modelo (ex: DTU ou vCore) e ajuste o tamanho conforme necessidade.


**4. Configurar Autenticação e Segurança**

**Método de Autenticação:**

**Autenticação SQL:** Define um usuário e senha para acesso ao banco.

**Azure Active Directory:** Permite autenticação integrada com contas Microsoft.


**5. Configurar Rede (Firewall e Segurança)**

**Redes:**

**Ponto de extremidade público:** Permite acesso externo (restringível por firewall).

**Ponto de extremidade privado:** Recomendado para maior segurança (VNet Integration).

**Firewall:**

Adicione regras para permitir conexões de IPs específicos (ex: seu IP corporativo).
