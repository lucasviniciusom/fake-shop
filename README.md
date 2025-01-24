# **Projeto Fake-Shop**  

Este repositório contém a infraestrutura como código e o pipeline de CI/CD para provisionar e gerenciar a aplicação **Fake-Shop**, utilizando **Kubernetes** no **Amazon EKS**. O objetivo deste projeto é demonstrar a implementação de uma solução automatizada e escalável, integrando práticas modernas de DevOps para orquestração de containers e automação de deploys.

---

## **🛠 Habilidades e Ferramentas Utilizadas**  

- **Terraform**: Para provisionar e gerenciar a infraestrutura no Amazon EKS de maneira declarativa diretamente pela máquina local.
- **Amazon EKS**: Para orquestração de containers com Kubernetes, garantindo alta disponibilidade e escalabilidade.
- **Docker**: Para containerizar a aplicação, assegurando portabilidade e consistência nos ambientes de desenvolvimento e produção.
- **GitHub Actions**: Para implementar automação de CI/CD, garantindo que novas versões do código sejam automaticamente construídas, publicadas e aplicadas ao cluster Kubernetes.

---

## **Objetivos do Projeto**  

- **Automação**: Reduzir o esforço manual com a integração de GitHub Actions, que realiza o build, push e deploy automaticamente a cada atualização no código.
- **Escalabilidade**: Utilizar o Amazon EKS para gerenciar clusters Kubernetes que suportam variações de carga de trabalho de forma eficiente.
- **Infraestrutura como Código**: Simplificar a replicação e manutenção da infraestrutura usando Terraform.
- **Entrega Contínua**: Garantir que a aplicação esteja sempre atualizada em produção com um pipeline automatizado, confiável e ágil.  

---

Este projeto é um exemplo prático de como unir ferramentas de infraestrutura e automação para entregar soluções robustas, escaláveis e eficientes em produção.
