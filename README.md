# ☁️ Cloud Formation - Infrastructure as Code - Site Filmes 1/1

## 📌 Sobre o Projeto

Este repositório faz parte do projeto **Site Filmes AWS**, onde foi construída uma aplicação completa utilizando serviços da AWS.

O projeto evolui de um **site estático (front-end)** para uma **plataforma completa (front + backend)** utilizando boas práticas de:

- Infraestrutura como Código (IaC)  
- Automação (CI/CD)  
- Arquitetura em nuvem  

---

## 🧠 Objetivo do Projeto

Demonstrar, na prática, como construir uma aplicação completa na AWS utilizando:

- Infraestrutura com CloudFormation  
- Pipeline de deploy com GitHub Actions  


---

## 🏗️ Etapas do Projeto

### ✅ Etapa 1 – CloudFormation (Infraestrutura como Código)

Criação da infraestrutura inicial utilizando templates:

✔️ **Amazon S3** – Hospedagem do site estático  
✔️ **Amazon CloudFront** – Distribuição CDN + OAC 🔒  
✔️ **Amazon Route 53** – Gerenciamento de domínio  
✔️ **AWS Certificate Manager** – HTTPS 🔐  

📌 Nessa etapa, toda a infraestrutura é definida via código, permitindo reuso, padronização e automação.

 ⏳ Etapa 2 – Versionamento no GitHub *(próxima etapa)*

 ⏳ Etapa 3 – Pipeline CI/CD 
 
 ⏳ Etapa 4 – Backend Serverless

![CloudFormation](imagens/imagem.png)
---

## 🏗️ Arquitetura do Projeto

### 🎨 Front-end (Site Estático)

- Amazon S3  
- Amazon CloudFront  
- AWS Certificate Manager  
- Amazon Route 53  
- AWS WAF  

### ⚙️ Back-end (Serverless)

- Amazon API Gateway  
- AWS Lambda  
- Amazon DynamoDB  

### ☁️ Infraestrutura & DevOps

- AWS CloudFormation  
- GitHub  
- GitHub Actions  

---

## 📁 Estrutura do Projeto

```
aws-filmes-platform/
|
├── s3.yaml
├── cloudfront.yaml
├── policy.yaml
├── route53.yaml
├── LICENSE
├── README.md


```

---

## 🔄 Fluxo do Projeto

1. CloudFormation  
2. GitHub  
3. GitHub Actions  
4. Ambientes DEV e PRD  
5. Deploy do front no S3  
6. Backend com Lambda + API Gateway  

---

## 📜 Licença

MIT

---

## 👨‍💻 Autor

**Luiz Augusto Souza**

* 💼 LinkedIn: [Link](https://www.linkedin.com/in/luiz-inhesta-341b4b311/)
* 💻 YouTube: [Link](https://youtu.be/css8Vk6vtDo)
