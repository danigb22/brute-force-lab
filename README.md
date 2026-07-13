# 🔐 Brute Force Lab

## 📌 Descrição
Projeto prático de cibersegurança da DIO que simula ataques de força bruta em serviços como FTP, Web (DVWA) e SMB, com foco na análise de vulnerabilidades e estratégias de mitigação.

---

## 🎯 Objetivo
O objetivo deste projeto é compreender como ataques de força bruta funcionam em diferentes serviços e como essas vulnerabilidades podem ser exploradas e mitigadas em um ambiente controlado.

---

## 🖥️ Ambiente Utilizado
- Kali Linux  
- Metasploitable 2  
- DVWA (Damn Vulnerable Web Application)  
- Medusa  
- VirtualBox  

---

## 🔍 Atividades Realizadas
Durante o desenvolvimento deste laboratório, foram realizados os seguintes testes:

- Simulação de ataques em serviços do Metasploitable 2  
- Ataques de força bruta em login web utilizando o DVWA  
- Exploração de serviços e identificação de vulnerabilidades  
- Varredura de rede para descoberta de portas abertas utilizando o Nmap (atividade adicional)

---

## 🧠 Aprendizados
Com este projeto, foi possível desenvolver diversos conhecimentos práticos, como:

- Entendimento de como ataques de força bruta funcionam  
- Identificação de serviços vulneráveis  
- Importância de senhas fortes e políticas de segurança  
- Reconhecimento de portas abertas e possíveis riscos  
- Noções básicas de enumeração de serviços  

---

## ⚠️ Vulnerabilidades Observadas
- Uso de senhas fracas  
- Ausência de bloqueio após várias tentativas de login  
- Serviços expostos sem proteção adequada  
- Falta de autenticação multifator  

---

## ⚠️ Dificuldades e Erros Encontrados

- Durante a execução dos testes com o Medusa no módulo HTTP, foram gerados avisos de parâmetros inválidos (PAGE, FORM e FAIL), indicando uso incorreto da sintaxe da ferramenta.

- Mesmo com os avisos, foi possível identificar credenciais válidas, o que demonstrou a importância de compreender corretamente o funcionamento e os parâmetros de cada ferramenta.

- Esse erro também evidenciou diferenças entre ferramentas como Medusa e outras voltadas para formulários web.
---
## 🛡️ Medidas de Mitigação
Para reduzir os riscos identificados, são recomendadas as seguintes práticas:

- Implementação de senhas fortes  
- Uso de autenticação multifator (MFA)  
- Limitação de tentativas de login  
- Monitoramento de acessos e logs  
- Fechamento de portas e serviços desnecessários  
- Uso de ferramentas de proteção como firewall e sistemas de detecção  

---

## 📸 Evidências
<p align="center">
  <a href="https://github.com/user-attachments/assets/b1d3ec54-2de4-4e68-a36f-630fa07c2704">
    <img src="https://github.com/user-attachments/assets/b1d3ec54-2de4-4e68-a36f-630fa07c2704" width="300" alt="Screenshot 1">
  </a>
  <a href="https://github.com/user-attachments/assets/487612b4-198a-4581-baca-026b78123d5a">
    <img src="https://github.com/user-attachments/assets/487612b4-198a-4581-baca-026b78123d5a" width="300" alt="Screenshot 2">
  </a>
  <br><br>
  <a href="https://github.com/user-attachments/assets/324039f1-1a83-42aa-9aa4-3d9c3047cf6b">
    <img src="https://github.com/user-attachments/assets/324039f1-1a83-42aa-9aa4-3d9c3047cf6b" width="300" alt="Screenshot 3">
  </a>
  <a href="https://github.com/user-attachments/assets/2e6c373b-40a1-43d8-aa25-cf7151d4205a">
    <img src="https://github.com/user-attachments/assets/2e6c373b-40a1-43d8-aa25-cf7151d4205a" width="300" alt="Screenshot 4">
  </a>
</p>

---

## 📚 Considerações Finais
Este projeto foi fundamental para entender, na prática, como falhas simples de segurança podem ser exploradas e como medidas básicas podem aumentar significativamente a proteção de sistemas.

---
