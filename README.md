# 🛜 Projeto Condomínio de Laboratórios – Campus Itabaiana

Este repositório apresenta a proposta técnica do **Projeto Condomínio de Laboratórios – Campus Itabaiana**. O projeto reúne diferentes laboratórios computacionais, cada um associado a um cliente ou grupo de pesquisa, com infraestrutura lógica própria, site de demonstração e responsável técnico definido.

---

## 🌐 Laboratório 01 – GDRR  
**Grupo de Pesquisa sobre Dinâmica Rural e Regional**

- 👨‍💻 **Técnico responsável:** Marcos Paulo Soares da Silva.

### 📌 Descrição técnica
Laboratório de redes e serviços computacionais desenvolvido para o **Grupo de Pesquisa sobre Dinâmica Rural e Regional (GDRR)** com o objetivo de apoiar atividades de pesquisa, análise de dados e divulgação científica. A infraestrutura de rede é organizada por meio de segmentação em VLANs, garantindo isolamento de tráfego entre pesquisadores, servidores e serviços administrativos, além de maior segurança e controle de acesso.

O ambiente utiliza **switches de camada 2 e camada 3** para comutação e roteamento interno, associados a um **firewall** para proteção da rede. Os serviços são estruturados em servidores dedicados de aplicação, **banco de dados**, **autenticação e web**. O site institucional é disponibilizado via container Docker com Nginx, hospedado em ambiente AWS acadêmico.

### 🌍 IP do site no AWS
```markdown
http://52.202.179.230/
````
---

## 🌐 Laboratório 02 - GEADAS
Grupo de Estudo e Pesquisa em Alfabetização, Discurso e Aprendizagens

- 👨‍💻 **Técnico responsável:** João Andryel Santos Menezes

### 📌 Descrição técnica
Planejamento da infraestrtura de redes do **Grupo de Estudo e Pesquisa em Alfabetização, Discurso e Aprendizagens (GEADAS)** do Campus de Itabaiana, utilizando uma arquitetura segmentada para organizar servidores, estações de pesquisa e dispositivos IoT. Transformando o laboratório em um ambiente tecnológico moderno, facilitando a análise de discursos e o desenvolvimento de novas metodologias de aprendizagem.

### 🌍 IP do site no AWS
```markdown
http://44.217.102.94/
````

---

## 🌐 Laboratório 03 - GPEA
**Grupo de Estudo e Pesquisa em Educação Ambiental de Sergipe**

- 👨‍💻 **Técnico responsável:** Paloma dos Santos

### 📌 Descrição técnica
A proposta foi desenvolvida para atender às necessidades do **Grupo de Estudo e Pesquisa em Educação Ambiental de Sergipe (GPEA)**, garantindo organização lógica da rede, segurança, conectividade e possibilidade de expansão. A infraestrutura é centralizada no Switch de camada 3, responsável pelo roteamento inter-VLAN e pela interligação dos segmentos da rede. A segmentação lógica é realizada por meio de VLANs, separando o tráfego conforme o perfil de uso. O acesso à Internet é realizado pelo Gateway com proteção garantida pelo Firewall responsável pelo controle e filtragem de tráfego. A rede utiliza endereçamento IPv4 e IPv6, seguindo boas práticas atuais de redes de computadores. Essa arquitetura possibilita segurança, desempenho e escalabilidade, além de permitir a integração ao modelo de condomínio de laboratórios, oferecendo suporte adequado às atividades de pesquisa, ensino e extensão do GPEA.

### 🌍 IP do site no AWS
```markdown
http://98.93.165.148/
````

---

## 🌐 Laboratório 04 - GEES
**Grupo de Estudos em Educação Superior**

- 👨‍💻 **Técnico responsável:** Maria Rita Melo de Souza

### 📌 Descrição técnica
O laboratório do GEES possui infraestrutura de rede dimensionada para atender às atividades de pesquisa, armazenamento de dados educacionais, produção científica e colaboração acadêmica. Foi projetado com uma infraestrutura de rede enxuta, segura e escalável, adequada às demandas de pesquisa em Educação e preparada para integração ao modelo de condomínio de laboratórios.

A adesão ao condomínio amplia a capacidade tecnológica do laboratório ao permitir acesso a recursos compartilhados como cluster de processamento, armazenamento centralizado e autenticação unificada. Essa integração reduz custos individuais, aumenta a disponibilidade dos serviços e viabiliza escalabilidade para projetos de maior complexidade.


### 🌍 IP do site no AWS
```markdown
http://34.206.239.171/
````
