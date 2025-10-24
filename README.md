# Aws-cloud-fundamentals-cloudFormation
Este projeto tem como objetivo exemplificar o uso da ferramenta AWS CloudFormation, um serviço de Infraestrutura como Código (IaC) que permite modelar, provisionar e gerenciar recursos AWS de forma automatizada. Com ele, é possível definir toda a infraestrutura em arquivos de template, tornando o deployment de ambientes completo mais rápido, consistente e menos propenso a erros.

## Objetivo
Demonstrar, na prática, como criar e gerenciar infraestrutura na AWS usando templates CloudFormation, implementando recursos de forma declarativa e reproduzível, seguindo as melhores práticas aprendidas no decorrer do curso. 

## Documentação

> documentação base:
> [AWS CloudFormation - Getting Started](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/GettingStarted.html)

1. Acesse sua conta [AWS](https://aws.amazon.com/pt/free);
2. Navegue buscando pelo serviço "CloudFormation".

  <img width="1448" height="312" alt="image" src="https://github.com/user-attachments/assets/b8f86720-6411-4a92-95ab-036a69c37489" />

3. Selecione o botão "Create stack" (Criar pilha) para começar

  <img width="1639" height="653" alt="image" src="https://github.com/user-attachments/assets/0139ef09-b388-4289-822a-01e40abee007" />
  
4. Em "Prerequisite - prepare template" (Pré-requisito - prepare o template), escolha entre "Choose an existing template" (Template pronto) ou "Build from Infrastructure Composer" (Fazer upload de template), como o propósito deste projeto é desenvolver, optei por um template pronto como é ministrado no curso.
5. Em "Specigy template", escolha "Upload a template file" (Upload o arquivo de template), dentre, "Amazon S3 URL" e "Sync from Git".
6. Faça o upload no arquivo que você gerou com as configurações necessarias para o seu projeto.
7. click em , "next" para continuar.
   
   <img width="1774" height="841" alt="image" src="https://github.com/user-attachments/assets/0bad1819-1954-49db-a2ff-5b45d9af0b31" />
