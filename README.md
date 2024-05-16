# Portfolio de Elias Andrade - Analista de Infraestrutura e DevOps 🚀

![Elias Andrade - Profile Picture](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/chrome_kpuiYlsq9Q.png)


## Let's Connect!
- 📧 **Email:** [oeliasandrade@gmail.com](mailto:oeliasandrade@gmail.com)
- 🔗 **LinkedIn:** [linkedin.com/elias-andrade-devops](https://www.linkedin.com/in/elias-andrade-21574b2b4/)
- 🐦 **Twitter:** [@Elias_devops](https://twitter.com/Elias_devops)

## Sobre Mim

🔧 Sou um entusiasta de tecnologia apaixonado por automação e eficiência. Com mais de 14 anos de experiência em infraestrutura de TI, estou comprometido em garantir que as operações de infraestrutura sejam suaves, seguras e escaláveis. Minha missão é integrar as melhores práticas DevOps para impulsionar o desenvolvimento e a entrega de software de forma eficaz.


Desde o ínicio de 2024 atuando como Analista DevOps & Platform Engineer em constante evolução, com 14 anos de experiência em Administração de Redes e Infraestrutura, certificado ITIL v3 desde 2012. Desde 2010, venho desempenhando um papel vital em ambientes híbridos Linux e Windows, em diversas nuvens, incluindo cloud privada, on-premises e bare metal.

🛠️ Experiência Profissional 🛠️

Atualmente, atuo como Analista DevOps & Platform Engineer em uma empresa confidencial, localizada em Porto Alegre, atuando remotamente desde abril de 2024. Meu principal foco é liderar a transformação digital e a modernização da infraestrutura de TI da empresa. Colaboro estreitamente com equipes de desenvolvimento e operações para implementar práticas DevOps e adotar tecnologias modernas, impulsionando assim a eficiência operacional e a entrega de software.

💻 Administração de Redes e Sistemas Linux 💻

Como especialista em administração de sistemas Linux, domino distribuições populares como Ubuntu, Debian e CentOS. Desde a configuração inicial até a otimização avançada de desempenho e segurança, estou preparado para enfrentar qualquer desafio neste ecossistema.

☁️ Virtualização e Cloud ☁️

Possuo um vasto conhecimento em virtualização, trabalhando com plataformas como VMware vSphere, VirtualBox, Hyper-V, KVM, QEMU e AWS EC2. Sou hábil na implementação e gerenciamento de ambientes de cloud privada e pública, utilizando ferramentas como Terraform para provisionamento automatizado e escalável.

<!-- Ambiente Grafana para Monitoramento de Containers Ubuntu Server -->

![Ambiente Grafana para Monitoramento de Containers Ubuntu Server](https://raw.githubusercontent.com/elias-andrade-devops/Elias-Andrade-Devops-2024/main/chrome_yQ3oJjukkk.png)


🐳 Docker e Orquestração de Contêineres 🐳

Sou especialista em Docker, gerenciando clusters e orquestrando contêineres para implantação de micro serviços. Utilizo o Kubernetes para escalabilidade horizontal e implantação automatizada de serviços, garantindo alta disponibilidade e performance.

<!-- Imagem da Baleia do Docker -->

![Baleia do Docker](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/_5b2c4b4f-8113-4978-832d-8dd46f144f00.jpeg?raw=true)


🔍 Monitoramento e Análise de Métricas 🔍

Desenvolvo e implemento soluções avançadas de monitoramento utilizando Prometheus, Grafana, Loki e Zabbix. Isso permite uma análise profunda de métricas, garantindo o desempenho, a disponibilidade e a confiabilidade dos sistemas em tempo real.
<!-- Imagem do Cluster no Grafana -->

![Cluster no Grafana](https://raw.githubusercontent.com/elias-andrade-devops/Elias-Andrade-Devops-2024/main/grafanacluster.png)

⚙️ Automação e CI/CD ⚙️

Sou especialista em automação, utilizando ferramentas como Ansible e Puppet Bolt para configurar e gerenciar infraestrutura de forma eficiente e consistente. Implemento pipelines de CI/CD com Jenkins Pipeline, GitLab CI/CD e GitHub Actions, garantindo a integração contínua e a entrega contínua de software de alta qualidade.

## 🚀 Automação de Construção e Push de Imagem Docker

Este repositório utiliza a GitHub Action para automatizar a construção e push de uma imagem Docker quando ocorrem mudanças no código-fonte. A ação é executada em resposta a pushs na branch `develop` e tags no formato de versão `X.Y.Z`.

A ação realiza as seguintes tarefas:

📦 Instala as dependências do projeto.  
✅ Executa os testes automatizados.  
🏗️ Constrói a imagem Docker.  
🚢 Empurra a imagem para um registro Docker privado.  
🛠️ Implanta a imagem no ambiente de staging quando há um push na branch `develop`.  
🚀 Implanta a imagem no ambiente de produção quando uma nova tag é criada.  
🔄 Atualiza o deployment no Kubernetes após a implantação na produção.  
📢 Notifica sobre o status do build no Slack.  

Para mais detalhes sobre a implementação da ação, confira o arquivo `action-docker-image-build.yaml`.

[Veja o yaml da Action](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/action-docker-image-build.yaml)


<!-- Ciclo de Desenvolvimento com Kubernetes -->

![Ciclo de Desenvolvimento com Kubernetes](https://raw.githubusercontent.com/elias-andrade-devops/Elias-Andrade-Devops-2024/main/K8s%20in%20the%20app%20development%20lifecycle%20good%20color.png)


<!-- Tela de Automação de Deploy no Argo via GitHub Actions -->

![Automação de Deploy no Argo via GitHub Actions](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/chrome_Nu8ifskwKv.png?raw=true)

<!-- Print de Sucesso em uma Automação do GitHub Action para Buildar Imagem do Docker -->

![Sucesso em Automatização do GitHub Action para Buildar Imagem do Docker](https://raw.githubusercontent.com/elias-andrade-devops/Elias-Andrade-Devops-2024/main/chrome_mLHk4d46Ey.png)


🔄 Scaling e Alta Disponibilidade 🔄

Implemento soluções de escalabilidade automática e alta disponibilidade, garantindo que os sistemas permaneçam resilientes mesmo em momentos de pico de tráfego. Utilizo práticas como autoscaling e clustering para manter a estabilidade e o desempenho dos serviços.

🛡️ Backup e Segurança 🛡️

Desenvolvo e implemento estratégias de backup automatizado e recuperação de desastres, garantindo a integridade dos dados e a continuidade dos negócios. Implemento políticas de segurança robustas para proteger os recursos da infraestrutura e os dados sensíveis da empresa.

🤖 Automatização e Scripting Avançado 🤖

Sou especialista em automação, utilizando linguagens como Python, Bash e PowerShell para criar scripts e automações que simplificam tarefas operacionais e aumentam a produtividade da equipe. Meu domínio dessas linguagens permite desenvolver soluções eficazes para uma ampla variedade de desafios de TI.

<!-- Script/Menu Interativo em Python para Automação e Gestão de Tasks e Back Office no Kubernetes -->

![Script/Menu Interativo em Python para Automação e Gestão de Tasks e Back Office no Kubernetes](https://raw.githubusercontent.com/elias-andrade-devops/Elias-Andrade-Devops-2024/main/py_v7P8wmuJoi.png)

<!-- Script em Python para Gestão de Segredos -->

![Script em Python para Gestão de Segredos](https://raw.githubusercontent.com/elias-andrade-devops/Elias-Andrade-Devops-2024/main/py_oOy6bfUTIc.png)


✨ Inovação e Melhoria Contínua ✨

Estou sempre buscando maneiras de inovar e otimizar os processos de TI. Lidero projetos de automação e melhoria contínua, visando aumentar a eficiência operacional e reduzir o tempo de inatividade, mantendo-me atualizado com as tendências mais recentes em tecnologia e práticas de DevOps.

## Habilidades

### Sistemas Operacionais

- 💻 **Windows:** Domínio na administração e otimização de ambientes Windows Server, incluindo Windows Server 2012 e anteriores.
- 🐧 **Linux:** Proficiente em gerenciamento de servidores Linux, com experiência em distribuições como Ubuntu, CentOS e RedHat.

### Contêineres e Orquestração

- 🐳 **Docker:** Especialista em contêineres Docker para implementação simplificada e portabilidade de aplicações.
- 🌐 **Kubernetes:** Conhecimento sólido em orquestração de contêineres com Kubernetes, garantindo escalabilidade e alta disponibilidade.

<!-- Instância do MongoDB no MongoDB Compass -->

![Instância do MongoDB no MongoDB Compass](https://raw.githubusercontent.com/elias-andrade-devops/Elias-Andrade-Devops-2024/main/MongoDBCompass_3qsh6eJWBp.png)

### Ferramentas de Controle de Versão e Integração Contínua

- 🛠️ **GitLab:** Experiente em integração contínua, entrega contínua e controle de versão com o GitLab, incluindo o uso de GitLab CI/CD para automatização de pipelines.
- 🔗 **Jenkins:** Proficiente na configuração e manutenção de pipelines de CI/CD com Jenkins, garantindo um fluxo de trabalho eficiente de desenvolvimento.

### Automação e Scripting

- 💪 **PowerShell:** Mestre na automação de tarefas e scripting para facilitar processos repetitivos em ambientes Windows.
- 🐍 **Python:** Experiência em desenvolvimento de scripts Python para automação de tarefas operacionais e administração de sistemas.

### Infraestrutura como Código e Gestão de Configuração

- 🚀 **Terraform:** Proficiente na criação e gerenciamento de infraestrutura como código (IAC) com Terraform, garantindo uma infraestrutura consistente e escalável.
- ⚙️ **Ansible:** Experiência em automação de configuração e gestão de infraestrutura com Ansible, facilitando a implantação e a manutenção de servidores.

## Projetos Destacados

### Migração e Atualização do Redmine

- 📈 **Descrição:** Liderança na migração e atualização de um ambiente legado do Redmine em uma grande empresa de software. Documentei o processo detalhadamente, desde a replicação do ambiente legado até a resolução de problemas e a atualização bem-sucedida para a versão mais recente.
- 📄 **Documentação Detalhada:** [Procedimento de Upgrade do Redmine](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/PROCEDIMENTO-UPGRADE-REDMINE.TXT)
- 🔍 **Arquivos Relevantes:**
  - [Diagrama de Ferramentas DevOps](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/63bd77fd98f7595075546699_platform-tooling-lands.jpg)
  - [Comandos para Configuração de Rede no CentOS](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/COMANDOS%20REDE%20CENTOS%20DHCP%20CENTOS%207%20E%208%20.txt)
  - [Manual de Gestão de Redes no CentOS](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/0be98428-ae96-4465-b50a-7aaec4485f66__Manual_av.pdf)

### Atualização do GitLab em Ambiente de Produção

- 🛠️ **Descrição:** Coordenação e execução da atualização do GitLab de versões legadas 12 e 14 em dois servidores de produção em uma software house com 200 colaboradores.
- 📄 **Acompanhamento Detalhado:** [Registro de Atualização do GitLab](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/acompanhamento%20atualizacao%20gitlab%20(2).txt)
- 🔍 **Arquivos Relevantes:**
  - [Procedimento de Upgrade do GitLab](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/UPGRADING%20REDMINE%20EM%20PRODU%C3%87%C3%83O.txt)
  - [Certificado de Treinamento em LGPD](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/UC-5a0ef873-72db-4632-b593-8b53674122e0.jpg)
  - 📄 **Relatório de Validação do Tempo de Atualização:** [Relatório de Validação](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/d2d26117-4d0a-4ba7-84ed-4a5d90f095af_Relatrio_d.pdf)

### Roteiro de Upgrade do GitLab

- 📋 **Descrição:** Roteiro detalhado para a atualização do GitLab em um ambiente de produção, incluindo comandos completos para instalação das versões específicas.
- 📄 **Roteiro de Upgrade:** [Roteiro de Upgrade do GitLab](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/acompanhamento%20atualizacao%20gitlab.txt)
- 📄 **Comandos Completos de Instalação:** [Comandos de Instalação do GitLab](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/comando%20atualizado%20instala%C3%A7%C3%A3o%20gitlab%20pacotes%20rp.txt)

### 📚📝🔍 Elias Andrade - Acumulador de Conhecimento e Documentador 🚀

Gosto de acumular conhecimento, documentar minhas descobertas e manter meu próprio repositório de conhecimento para referência futura. Aqui estão alguns dos meus documentos:

#### Ubuntu:
- [Manual de Hardening para Linux Ubuntu](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/ubuntu/manual_hardening_linux_ubuntu.txt) 🔒

- [Configuração de Firewall para Ubuntu](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/ubuntu/configuracao_firewall_ubuntu.txt) 🛡️

#### Docker:
- [Gestão de Containers no Docker](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/docker/gestao_containers_docker.txt) 🐳

- [Comandos Docker Avançados](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/docker/comandos_docker_avancados.txt) ⚙️

- [Lista de Comandos Docker](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/docker/comandos-docker.txt) 💻


Neste repositório, você encontrará uma coleção de materiais relacionados a práticas de DevOps, incluindo scripts, manuais e procedimentos para diversas tarefas e configurações comumente encontradas no ambiente de desenvolvimento e operações.

## 📝 Manuais

- **[Manual Completo de Configuração de Execução de Aplicativos no Windows Server 2016](https://github.com/chaos4455/Devops-2024/blob/main/Manual%20Completo%20Configura%C3%A7%C3%A3o%20de%20Execu%C3%A7%C3%A3o%20de%20Aplicativos%20no%20Windows%20Server%202016.pdf):** Um guia detalhado para configurar a execução de aplicativos no Windows Server 2016.

- **[Manual Permitindo a Execução de Scripts e Importando o Módulo do Active Directory no PowerShell](https://github.com/chaos4455/Devops-2024/blob/main/Manual%20Permitindo%20a%20Execu%C3%A7%C3%A3o%20de%20Scripts%20e%20Importando%20o%20M%C3%B3dulo%20do%20Active%20Directory%20no%20PowerShell.pdf):** Instruções para permitir a execução de scripts e importar o módulo do Active Directory no PowerShell.

- **[Manual de Instalação do Wget no CentOS 7](https://github.com/chaos4455/Devops-2024/blob/main/Manual%20de%20Instala%C3%A7%C3%A3o%20do%20Wget%20no%20CentOS%207.pdf):** Um guia passo a passo para instalar o Wget no CentOS 7.

- **[Manual do Projeto Teste de Login RDP em Python](https://github.com/chaos4455/Devops-2024/blob/main/Manual%20do%20Projeto%20Teste%20de%20Login%20RDP%20PYTHON.pdf):** Descrição detalhada do projeto de teste de login RDP em Python.

- **[Manual de Procedimento Configuração da Política Local do Windows para Executar Arquivos de Fornecedores Desconhecidos sem Solicitar Senha de Administrador](https://github.com/chaos4455/Devops-2024/blob/main/%F0%9F%93%98%20Manual%20de%20Procedimento%20Configura%C3%A7%C3%A3o%20da%20Pol%C3%ADtica%20Local%20do%20Windows%20para%20Executar%20Arquivos%20de%20Fornecedores%20Desconhecidos%20sem%20Solicitar%20Senha%20de%20Administrador.pdf):** Procedimento para configurar a política local do Windows para executar arquivos de fornecedores desconhecidos sem solicitar senha de administrador.

## 🔄 Scripts

- **[Script para Teste de Conexão RDP em Python](https://github.com/chaos4455/Devops-2024/blob/main/RDP-connection-test-python.py):** Um script Python para testar a conexão RDP.

- **[Script para Criar Usuário no Active Directory em Windows Server 2016](https://github.com/chaos4455/Devops-2024/blob/main/script-cria-usuario-uo-AD-WS2016):** Cria usuários no Active Directory em um ambiente do Windows Server 2016.

## 📚 Procedimentos

- **[Procedimento Padrão para Uso do DeepFreeze em Ambientes da Empresa e Clientes](https://github.com/chaos4455/Devops-2024/blob/main/Procedimento%20Padr%C3%A3o%20Uso%20do%20DeepFreeze%20em%20Ambientes%20da%20Empresa%20e%20Clientes.pdf):** Procedimento para o uso padrão do DeepFreeze em ambientes corporativos e de clientes.

- **[Processo de Formatação e Configuração de Máquinas Cliente Windows](https://github.com/chaos4455/Devops-2024/blob/main/Processo%20de%20Formata%C3%A7%C3%A3o%20e%20Configura%C3%A7%C3%A3o%20de%20M%C3%A1quinas%20Cliente%20Windows.pdf):** Descreve o processo de formatação e configuração de máquinas cliente Windows.

## 📝 Comandos

- **[Comandos Docker Avançados](https://github.com/chaos4455/Devops-2024/blob/main/comandos-docker-avancasos.md):** Lista de comandos Docker avançados para gerenciar contêineres Docker.

- **[Comandos Docker para Gestão de Containers](https://github.com/chaos4455/Devops-2024/blob/main/comandos-docker-gestao-containers.md):** Lista de comandos para gerenciar containers Docker, incluindo criação, execução, parada e remoção de contêineres.

- **[Comandos para Hardening e Segurança no Linux](https://github.com/chaos4455/Devops-2024/blob/main/comandos-hardening-seguranca-linux.md):** Lista de comandos para fortalecer a segurança em sistemas Linux.

- **[Comandos Linux Ubuntu UFW](https://github.com/chaos4455/Devops-2024/blob/main/comandos-linux-ubuntu-ufw.md):** Lista de comandos para configurar o UFW (Uncomplicated Firewall) no Ubuntu Linux.

- **[Script para Adicionar Regra de Exceção para Execução de Aplicativo](https://github.com/chaos4455/Devops-2024/blob/main/adiciona-regra-excessao-execucao-aplicativo.ps1):** Um script PowerShell para adicionar uma regra de exceção para execução de aplicativos.

- **[Script Python para Ping Host](https://github.com/chaos4455/Devops-2024/blob/main/pinghost.py):** Um script Python para realizar ping em um host.

## 📖 Outros Recursos

- **[Conexão RDP com Credenciais Embutidas (PDF)](https://github.com/chaos4455/Devops-2024/blob/main/Conex%C3%A3o%20RDP%20com%20Credenciais%20Embutidas.pdf)**
- **[Lista de Comandos Docker (MD)](https://github.com/chaos4455/Devops-2024/blob/main/LISTA-COMANDOS-DOCKER-1.MD)**
- **[Tutorial Completo de Gerenciamento de Repositórios Git (PDF)](https://github.com/chaos4455/Devops-2024/blob/main/Tutorial%20Completo%20Gerenciamento%20de%20Reposit%C3%B3rios%20Git.pdf)**

### Exemplo de Comando de Upgrade do Ruby

- 🔧 **Descrição:** Exemplo de comando para atualização do Ruby de 2.7 para 3.0 em ambientes CentOS.
- 📄 **Comando de Upgrade do Ruby:** [Comando de Upgrade do Ruby](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/comando%20atualiza%C3%A7%C3%A3o%20ruby%20de%202-7%20para%203%20mais%20upd.txt)

### Conexão com o PostgreSQL

- 🐘 **Descrição:** Comandos para conectar e configurar o PostgreSQL 10 em ambientes CentOS.
- 📄 **Comandos PostgreSQL:** [Comando de Conexão com o PostgreSQL](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/comando%20conecta%20postgres%2010%20centos%207.txt)

### Configuração do GitLab

- ⚙️ **Descrição:** Comandos para configurar o GitLab em ambientes CentOS.
- 📄 **Comandos de Configuração:** [Comando de Configuração do GitLab](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/comando%20configura%C3%A7%C3%A3o%20gitlab%20centos.txt)

## Ferramentas e Recursos Adicionais

### Comandos de Instalação e Atualização

- 📄 **Lista de Comandos:** [Lista de Comandos - Instalação e Atualização](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/lista%20comandos%20wget%20pacotes%20upgrade%20gitlab%20proj.txt)

### Diagrama Profissão Engenheiro de Plataforma

- 📷 **Diagrama:** ![Diagrama Profissão Engenheiro de Plataforma](https://github.com/elias-andrade-devops/Elias-Andrade-Devops-2024/blob/main/maxresdefault.jpg)


### Outros repositórios mais antigos de quando comecei meus estudos em devops no ano de 2018

### 🐳📚 Elias Andrade - Repositório Docker Commandlets 2018 🚀

Em 2018, iniciei meus estudos com Docker e comecei a explorar as possibilidades oferecidas por essa tecnologia. O repositório `DockerCommandlets` foi o ponto de partida para minha jornada de aprendizado com Docker.

#### Sobre o Repositório
O [DockerCommandlets](https://github.com/chaos4455/DockerCommandlets) é um repositório onde comecei a reunir comandos, scripts e materiais de estudo relacionados ao Docker. Foi aqui que mergulhei no mundo dos contêineres e comecei a experimentar com diferentes funcionalidades e casos de uso do Docker.

### 📚🔍 Elias Andrade - Repositório de Conhecimento 2022 🚀

Em 2019, criei o repositório [Conhecimento](https://github.com/chaos4455/Conhecimento) com o objetivo de compartilhar um misto de cultura DevOps e outras informações úteis acumuladas ao longo dos anos. Este repositório contém uma variedade de comandos, tutoriais, arquivos de informação e comandlets que uso no meu dia a dia e que foram acumulados ao longo do tempo.

#### Sobre o Repositório
O repositório de Conhecimento é uma coleção de recursos úteis compartilhados com a comunidade por Elias Andrade. Ele inclui uma variedade de tópicos, desde comandos de linha de comando até tutoriais detalhados sobre diversas tecnologias.

#### Objetivo
Meu objetivo ao criar este repositório foi tornar fácil o acesso aos arquivos que considero úteis para mim e para outras pessoas. Aqui, você encontrará uma grande variedade de informações destinadas a facilitar o trabalho diário e promover o compartilhamento de conhecimento.

#### Conteúdo
- Comandos úteis para diversas tarefas de administração de sistemas.
- Tutoriais detalhados sobre configuração e uso de diferentes tecnologias.
- Arquivos de informação para referência rápida.
- Comandlets e scripts para automação de tarefas comuns.


### Outras áreas que atuo, estudo, tenho interesse ou projetos.

#### [Visão computacional e NLP = processamento de linguagem natural, llama3, gpt, berd. Chatbots e IA - Portfolio](https://github.com/evolucaoit/portfolio) 🚀
Um repositório contendo o portfólio de Elias Andrade, especialista em Visão Computacional e Processamento de Linguagem Natural. Saiba mais sobre meus conhecimentos nessa área.
#### [Portfólio e jornada analista de redes e infraestrutura - Elias Andrade](https://github.com/chaos4455/Certifica-es) 📚
Este repositório abriga o portfólio de realizações, projetos, experiência e conquistas, destacando minhas habilidades em projetos e experiência como administrador de redes e analista de infraestrutura. Saiba mais sobre meus conhecimentos nessa área.
