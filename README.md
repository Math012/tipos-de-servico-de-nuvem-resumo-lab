# Tipos de serviço de nuvem na azure(lassS, PassS e SaaS)

### laaS (infraestrutura como serviço)

-  Recursos: Servidores e armazenamento, firewalls/segurança de rede, planta física/edifício do datacenter.
  
-  O recurso é mais personalizado, somos responsáveis por manter o recurso ativo.
  
-  Cria uma infraestrutura de TI de pagamento conforme o uso, alugando servidores, máquinas virtuais, armazenamento, redes e sistemas operacionais de um provedor de nuvem.
  
-  Exige mais gestão, assim deixando o processo mais caro.
  
### - PaaS (plataforma como serviço)

- Recursos: Sistemas operacionais, ferramentas para desenvolvedores, análise de negócios de gerenciamento de database.

- Fornece um ambiente para a criação, o teste e a implantação de aplicativos de software, sem focar no gerenciamento da infraestrutura subjacente.

- Exemplo: a empresa precisa de um banco de dados e não vai se preocupar em gerenciar a máquina virtual, isso se torna um PaaS (plataforma como serviço).

### SaaS (software como serviço)

- Recursos: aplicativos/apps hospedados.

- Exemplo de SaaS: Microsoft teams, onde o gerenciamento de recursos na plataforma é feito através de licenças pagas.

- A aplicação já está pronta.

- Os usuários se conectam e usam aplicativos com base em nuvem pela internet: por exemplo, Microsoft Office 365, e-mails e calendários.

# Modelos de Responsabilidade Compartilhada
  - Responsabilidades:
    - Informações pessoais.
    - dispositivos (moveis e PCs).
    - contas e identidades.
    - infraestrutura de identidade e diretório.
    - aplicativos.
    - controles de rede.
    - sistema operacional.
    - hosts físicos.
    - rede física.
    - datacenter físico(provider).
      
### Datacenter físico

- Toda a responsabilidade é da empresa que gerencia o datacenter.

- Sempre será responsabilidade da empresa administrar as responsabilidade: informações e dados, dispositivos (moveis e PCs) e contas e identidades.

## laaS

- No modelo de serviço laaS a Microsoft(provider) é responsável pelas responsabilidades: hosts físicos, rede física e datacenter físico.

## PaaS

- No modelo de serviço PaaS a Microsoft(provider) é responsável pelas responsabilidades: hosts físicos, rede física, datacenter e sistema operacional e compartilha a responsabilidade com a infraestrutura de identidade e diretório, aplicativos e controle de rede.

## SaaS

- No modelo de serviço SaaS a Microsoft(provider) é responsável pelas responsabilidades: aplicativos, controles de rede, sistema operacional, hosts físicos, rede física, datacenter físico(provider) e compartilha a responsabilidade com a infraestrutura de identidade e diretório.

