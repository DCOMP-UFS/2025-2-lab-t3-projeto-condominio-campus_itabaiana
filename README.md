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
