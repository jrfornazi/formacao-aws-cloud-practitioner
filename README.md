# formacao-aws-cloud-practitioner
Projeto prático de arquitetura AWS focada em redução de custos e segurança de dados.
# ☁️ AWS Cloud Infrastructure - Abstergo Industries

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

## 📌 Sobre o Projeto
Este repositório contém a proposta de arquitetura de nuvem para a **Abstergo Industries**, focada na migração de sistemas da **Câmara de Mimoso do Sul**. O objetivo principal é a **redução de custos operacionais** e a **segurança de dados sensíveis** utilizando os pilares do AWS Well-Architected Framework.

---

## 🏗️ Estrutura do Repositório

* 📂 **[/arquitetura](arquitetura/)**: Diagramas visuais da rede VPC e fluxo de dados.
* 📂 **[/docs](docs/)**: Relatório detalhado de implementação e justificativas técnicas.
* 📂 **[/scripts](scripts/)**: Automações em Python (Boto3) para gestão de mídia e backups.

---

## 🛠️ Serviços AWS Implementados

1.  **Amazon S3 (Intelligent-Tiering):** Gestão de acervo fotográfico e vídeos de alta resolução (80GB+), com economia automática em arquivos de acesso infrequente.
2.  **Amazon VPC:** Arquitetura de sub-redes públicas e privadas para isolamento de bancos de dados RDS.
3.  **Amazon DynamoDB + DAX:** Alta performance em metadados de imagens, reduzindo latência de milissegundos para microssegundos.

---

## 👨‍💻 Autor
**jrfornazi (Junior)**
*Passionate Photographer & Software Developer*

---
*Projeto desenvolvido como parte do desafio prático de Cloud Practitioner.*
