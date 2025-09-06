# 🚀 Desafio AWS EC2 – Santander Code Girls 2025

Este repositório contém minhas anotações e práticas realizadas durante o desafio de **Gerenciamento de Instâncias EC2 na AWS**, como parte do bootcamp **Santander Code Girls 2025** em parceria com a DIO.

---

## 🎯 Objetivos do Desafio
- Aplicar os conceitos aprendidos sobre **EC2** em um ambiente prático.
- Documentar processos técnicos de forma clara e organizada.
- Utilizar o **GitHub** para compartilhar documentação técnica.

---

## 🖥️ O que eu pratiquei
1. Criação de uma instância **EC2**.
2. Configuração de **Security Groups** (regras de entrada e saída).
3. Conexão via SSH à instância criada.
4. Instalação de pacotes básicos (exemplo: Apache, Nginx ou outro).
5. Teste de funcionamento e acesso externo.

---

## 🔑 Principais Aprendizados
- A diferença entre **Security Groups** e **NACLs**.
- A importância de escolher corretamente a **região** da instância.
- Como parar/iniciar instâncias e entender o impacto nos custos.
- Como documentar o processo em Markdown.

---

## 📚 Referências
- [Documentação oficial AWS – Gerenciamento de EC2](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/concepts.html)  
- [GitHub Markdown Guide](https://www.markdownguide.org/basic-syntax/)  
- [Formação GitHub Certification (GitBook)](https://gitbook.com)  

---

# ☁️ Computação em Nuvem

## 🚀 Benefícios
- **Pague apenas o que usar**  
- Escalabilidade: aumente ou reduza a capacidade sob demanda  
- Melhor resposta à demanda sem desperdício de recursos  

---

## 🏗️ Modelos de Implantação

### ☁️ Cloud-based (Nuvem)
- Toda a aplicação roda **na nuvem**  
- Possibilidade de **migrar aplicações existentes** ou **criar novas** diretamente na infraestrutura  
- Escolha entre:
  - **Infraestrutura de baixo nível** (EC2, VPC, RDS)  
  - **Serviços de alto nível** (Lambda, DynamoDB, etc.)

---

### 🏢 On-premises (Nuvem Privada)
- Tudo roda no **data center local da empresa**  
- Uso de **virtualização** e automação para eficiência  
- Parecido com TI tradicional, mas com camadas de orquestração

---

### 🔄 Híbrida (Hybrid)
- Mistura **recursos on-premises** e **nuvem**  
- Ideal quando não é viável migrar tudo para a nuvem (questões legais, custos ou legado)

📌 **Resumo rápido:**
- **Nuvem = tudo online**  
- **On-premises = tudo local**  
- **Híbrido = melhor dos dois mundos**  

---

# 🖥️ Amazon EC2 - Elastic Compute Cloud

O [Amazon EC2](https://aws.amazon.com/ec2/) fornece **capacidade computacional segura e redimensionável** na nuvem.  
Com uma instância EC2, você executa **servidores virtuais** na AWS.

### 🔑 Características
- AWS **cria e mantém os data centers**  
- **Provisionamento em minutos**  
- **Pague apenas pelo tempo de execução**  
- **Multitenancy**: hardware subjacente é compartilhado  
- Suporte a **Windows** ou **Linux**

---

# ⚙️ Tipos de Instâncias EC2

### 🟢 General Purpose (T, M, A)
- **Equilíbrio entre CPU, memória e rede**  
- Exemplos: `t3/t4g`, `m6i/m7g`  
- Indicadas para: aplicações web, servidores pequenos e bancos de dados médios  

---

### 🔴 Compute Optimized (C)
- **Alta taxa de CPU por memória**  
- Exemplos: `c6i, c7g`  
- Indicadas para: processamento intensivo, jogos, renderização, aplicações de alto desempenho  

---

### 🔵 Memory Optimized (R, X, z)
- **Mais RAM por vCPU**  
- Exemplos: `r6i, x2idn`  
- Indicadas para: bancos de dados em memória, análises em tempo real, caches grandes  

---

### 🟡 Storage Optimized (I, D, H)
- **Discos rápidos (SSD/HDD locais)**  
- Exemplos: `i3, i4i, d3`  
- Indicadas para: Big Data, Data Warehousing, Elasticsearch, sistemas distribuídos  

---

### 🟣 Accelerated Computing (P, G, F, Trn, Inf)
- **Uso de GPUs, FPGAs e chips especializados**  
- Exemplos:  
  - `p4/p5` → Machine Learning e IA  
  - `g5` → Gráficos 3D e renderização  
  - `inf1/inf2, trn1` → IA com chips AWS  
- Indicadas para: IA, HPC, gráficos e simulações científicas  

---

