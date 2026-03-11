# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 11 de março de 2026  
**Empresa:** Freemann Pharma
**Responsável:** Cloe Alberto de Souza  

---

## Introdução

Este relatório apresenta o processo de implementação de serviços em nuvem na empresa **Freemann Pharma**, realizado por **Cloe Alberto de Souza**.  

O objetivo deste projeto foi selecionar e implementar **três serviços da Amazon Web Services (AWS)** que possibilitem a criação de uma **plataforma virtual para uma farmácia fictícia**, garantindo escalabilidade, disponibilidade e **redução de custos operacionais** em comparação a uma infraestrutura local.

A proposta simula um cenário real de adoção de computação em nuvem, permitindo aplicar conceitos fundamentais de arquitetura cloud como **armazenamento escalável, hospedagem de aplicações e gerenciamento de banco de dados**.

---

## Descrição do Projeto

O projeto de implementação foi dividido em **três etapas principais**, cada uma focada em um serviço específico da AWS que contribui para a construção da plataforma digital da farmácia.

---

### Etapa 1: Armazenamento de arquivos e imagens

- **Nome da ferramenta:** Amazon S3 (Simple Storage Service)  
- **Foco da ferramenta:** Armazenamento escalável de arquivos  
- **Descrição de caso de uso:**

O **Amazon S3** foi utilizado para armazenar arquivos estáticos da plataforma, como:

- Imagens de medicamentos  
- Arquivos de layout do site  
- Documentos e materiais informativos  

Esse serviço permite armazenamento altamente disponível e durável, eliminando a necessidade de servidores locais para guardar arquivos. Além disso, seu modelo **pay-as-you-go** reduz custos operacionais, já que a empresa paga apenas pelo armazenamento utilizado.

---

### Etapa 2: Hospedagem da aplicação web

- **Nome da ferramenta:** Amazon EC2 (Elastic Compute Cloud)  
- **Foco da ferramenta:** Hospedagem e processamento da aplicação  
- **Descrição de caso de uso:**

O **Amazon EC2** foi utilizado para hospedar o servidor da aplicação da plataforma da farmácia.

Nesse ambiente é executado:

- Backend da aplicação
- Serviços responsáveis pela lógica de negócio
- Integração com banco de dados

A utilização do EC2 permite escalar a capacidade do servidor conforme o crescimento do acesso à plataforma, garantindo **desempenho e disponibilidade** mesmo em períodos de maior demanda.

---

### Etapa 3: Banco de dados gerenciado

- **Nome da ferramenta:** Amazon RDS (Relational Database Service)  
- **Foco da ferramenta:** Gerenciamento de banco de dados relacional  
- **Descrição de caso de uso:**

O **Amazon RDS** foi utilizado para armazenar os dados estruturados da plataforma, como:

- Cadastro de clientes  
- Catálogo de medicamentos  
- Pedidos realizados na plataforma  
- Informações de estoque  

O serviço oferece recursos de **backup automático, alta disponibilidade e manutenção simplificada**, reduzindo a necessidade de administração manual de banco de dados.

---

## Conclusão

A implementação dos serviços AWS na empresa **Freemann Pharma** possibilita a construção de uma **plataforma virtual moderna, escalável e segura** para a farmácia fictícia.

Entre os principais benefícios obtidos com essa arquitetura estão:

- Redução de custos com infraestrutura física
- Escalabilidade conforme o crescimento da plataforma
- Alta disponibilidade dos serviços
- Maior segurança e gerenciamento simplificado de dados

Recomenda-se a continuidade do uso dos serviços implementados e a avaliação futura de outros recursos da AWS, como **CDN (CloudFront), balanceamento de carga e serviços de monitoramento**, que podem ampliar ainda mais a eficiência e a confiabilidade da plataforma.

---

**Assinatura do Responsável pelo Projeto**

Cloe Alberto de Souza
