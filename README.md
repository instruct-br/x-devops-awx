# School of DevOps - AWX-XdevOps:


# O que é o Ansible:

O Ansible é uma ferramenta de automação, que permite automatizar tarefas de gerenciamento e configuração de servidores, aplicativos e infraestrutura de rede. O Ansible usa arquivos chamados playbooks e inventário.

### Playbooks:

Playbook é um arquivo YAML que contém uma série de tarefas e instruções de como um sistema deve ser configurado e gerenciado, incluindo as configurações do sistema operacional, instalação de pacotes, criação de usuários, configurações de serviços e etc.

### Inventários:

O inventário é um arquivo que lista os hosts ou servidores que serão gerenciados pelo Ansible. Ele é utilizado para especificar as informações de conexão, como endereço de IP, nome do host, porta SSH e outros parâmetros de conexão necessários para se conectar e gerenciar o servidor. O Ansible utiliza o inventário para saber em quais servidores executar os playbooks.

# AWX:

O AWX (Ansible Web eXperience) é uma plataforma de automação de infraestrutura de código aberto baseada em Ansible, fornece uma interface gráfica do usuário (GUI) moderna, intuitiva e um conjunto de APIs para gerenciar e automatizar. Ele permite o gerenciamento centralizado inventários, credenciais, tasks e Ansible Playbooks.

### Qual problema a ferramenta resolve?

O AWX resolve o problema de gerenciar a configuração e implantação de servidores e aplicativos de forma repetitiva, com pouca intervenção manual.

Com o Ansible AWX, os usuários podem definir e executar tarefas em vários servidores, gerenciar configurações e automatizar processos de implantação, eliminando a necessidade de execução manual de tarefas em cada servidor individualmente. Isso economiza tempo e minimiza erros que podem ocorrer com o gerenciamento manual. Além disso, o Ansible AWX oferece um histórico de execução de tarefas e uma interface fácil de usar para gerenciamento de credenciais, o que pode ser útil em ambientes de TI complexos.

### Funcionalidades
Executa tarefas de gerenciamento e configuração de servidores, aplicativos e infraestrutura de rede.
Usa arquivos chamados playbooks e inventário.
Gerencia inventários, credenciais, tasks e Ansible Playbooks.
Possui uma interface gráfica do usuário (GUI) moderna e intuitiva.
Permite o gerenciamento centralizado de tarefas e a automatização de processos de implantação.
Conecta-se aos hosts (sistemas remotos) usando SSH e executa tarefas neles, como a instalação de pacotes, a configuração de arquivos de configuração e a execução de comandos.

# Demo

Para demonstrar o uso do Ansible AWX, vamos seguir os seguintes passos:

- Subir as VMS.
- Localizar os IPs das VMS.
- Inserir as chaves SSH nas VMs.
- Executar playbooks do Galaxy Ansible.

# Prós e Contras:

### Prós do AWX:

- Fornece uma interface gráfica do usuário moderna e intuitiva para gerenciamento centralizado de inventários, credenciais, tarefas e playbooks do Ansible.
- Permite a automação de tarefas de gerenciamento e configuração de servidores e aplicativos de forma repetitiva, com pouca intervenção manual.
- Elimina a necessidade de execução manual de tarefas em cada servidor individualmente, economizando tempo e minimizando erros que podem ocorrer com o gerenciamento manual.
- Oferece um histórico de execução de tarefas e uma interface fácil de usar para gerenciamento de credenciais.
- Executa essas funcionalidades via SSH, sem a necessidade de um agente instalado em cada máquina.

### Contras do AWX:

- O gerenciamento de grandes volumes de servidores pode ser desafiador e requer um bom planejamento de inventário e gerenciamento de tarefas.
- O AWX requer conhecimento técnico em Ansible e infraestrutura de rede para instalação, configuração e uso efetivo.
- A implementação do AWX pode ser complexa e requer um ambiente bem configurado para funcionar corretamente.

