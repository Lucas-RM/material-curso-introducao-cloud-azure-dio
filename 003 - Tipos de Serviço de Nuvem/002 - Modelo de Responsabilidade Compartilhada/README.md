# **Modelo de Responsabilidade Compartilhada**

> O **Modelo de Responsabilidade Compartilhada** é um framework que define as obrigações de segurança e conformidade entre o provedor de serviços em nuvem e o cliente. 
> 
> Em vez de o provedor assumir toda a responsabilidade, as tarefas são divididas com base no tipo de serviço utilizado (IaaS, PaaS ou SaaS).

---

- **No IaaS**, o provedor é responsável pela segurança da infraestrutura física, incluindo data centers, servidores, armazenamento e redes. O cliente é responsável pela segurança do sistema operacional, aplicativos, dados, configurações de firewall e gerenciamento de identidades.
  
  ---
    
- **No PaaS**, o provedor gerencia e protege a infraestrutura e a plataforma de execução de aplicativos, incluindo sistemas operacionais, middleware e ambientes de runtime. O cliente foca na segurança dos aplicativos que desenvolve, nos dados que processa e nas permissões de acesso.
    
    ---
    
- **No SaaS**, o provedor cuida da maior parte das responsabilidades, incluindo infraestrutura, plataforma e aplicativos. O cliente é responsável principalmente pela gestão de identidades de usuários e pelos dados inseridos no sistema.
  
---

## Identificar os casos de uso apropriados para cada serviço de nuvem (IaaS, PaaS e SaaS)

---

### Casos de Uso para IaaS

- **Migração de Data Centers**: Empresas que desejam mover suas infraestruturas físicas para a nuvem sem reestruturar completamente seus aplicativos.
  
  ---
  
- **Necessidade de Controle Total**: Organizações que precisam de controle granular sobre o ambiente de TI, incluindo sistemas operacionais e configurações de rede.
  
  ---
  
- **Ambientes de Teste e Desenvolvimento**: Criação rápida de ambientes de desenvolvimento e teste que podem ser facilmente provisionados e desprovisionados.
  
---

### Casos de Uso para PaaS

- **Desenvolvimento Ágil de Aplicações**: Equipes que desejam focar no desenvolvimento de aplicativos sem se preocupar com a gestão da infraestrutura.
  
  ---
  
- **Aplicações Web e Móveis**: Construção e implantação de aplicativos escaláveis com suporte integrado para diversas linguagens e frameworks.
  
  ---
  
- **Análise de Dados e Business Intelligence**: Utilização de ferramentas integradas para análise, processamento e visualização de dados.
  
---

### Casos de Uso para SaaS

- **Soluções de Produtividade**: Acesso a ferramentas como email, processamento de texto e planilhas sem a necessidade de instalação local (e.g., Microsoft 365).
  
  ---
  
- **Gestão de Relacionamento com Clientes (CRM)**: Implementação rápida de sistemas para gerenciar interações com clientes (e.g., Dynamics 365).
  
  ---
  
- **Colaboração e Comunicação**: Plataformas que facilitam a comunicação interna e externa, compartilhamento de arquivos e gerenciamento de projetos.