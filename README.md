# ☁️ Laboratório AWS — Amazon EC2 e Elastic IP

## 📌 Sobre o projeto.

Realizei a criação de uma instância Amazon EC2 na AWS para explorar conceitos de infraestrutura em nuvem e redes.

O objetivo deste laboratório foi investigar o comportamento do endereço IPv4 público após interromper e iniciar uma instância EC2, além de estudar a utilização do Elastic IP para manter um endereço IP público estático.

## 🎯 Objetivos

- Criar uma instância Amazon EC2.
- Configurar uma rede utilizando Amazon VPC.
- Analisar endereços IPv4 públicos e privados.
- Investigar a alteração do IP público após reiniciar a instância.
- Configurar um Elastic IP (EIP).
- Associar um endereço IP público estático à instância.

## 🛠️ Serviços utilizados

- Amazon EC2
- Amazon VPC
- Sub-rede pública
- Internet Gateway
- Elastic IP

## 🔍 Etapas do laboratório

### 1. Criação da instância EC2

Realizei a criação de uma instância EC2 utilizando Amazon Linux 2023, configurando os parâmetros de rede e selecionando uma sub-rede pública.

📸 **Imagem 1 — Instância EC2 criada**

<img width="1596" height="589" alt="image" src="https://github.com/user-attachments/assets/1a6dac7d-a287-439a-ab68-3e9870b7a821" />



---

### 2. Interrupção da instância

Interrompi a instância EC2 para analisar o comportamento do endereço IPv4 público após a interrupção.

📸 **Imagem 2 — Instância EC2 interrompida**

<img width="1584" height="482" alt="image" src="https://github.com/user-attachments/assets/e348ccc3-1d6b-46ba-a4aa-1b6e53877c0f" />


---

### 3. Inicialização da instância

Realizei a inicialização da instância e observei suas informações de rede, incluindo o endereço IPv4 público atribuído.

📸 **Imagem 3 — Instância EC2 iniciada**

<img width="1562" height="480" alt="image" src="https://github.com/user-attachments/assets/35a83955-9d7f-4f8b-b0e8-8861fe6b5cf6" />


Endereço IPv4 público

34.220.109.204 

Endereços IPv4 privados
10.0.10.40

C==//Ip publico se trata de um ip dinamico, quando a maquina é reinicializada o IP publico muda. IP atual:44.255.189.204 

---

### 4. Configuração do Elastic IP

Nesta etapa, aloquei um Elastic IP e realizei sua associação à instância EC2, permitindo a utilização de um endereço IPv4 público estático.

📸 **Imagem 4 — Elastic IP associado à instância**

<img width="930" height="302" alt="image" src="https://github.com/user-attachments/assets/ddb53de3-2ba1-4db5-ab3a-578c7d4bfe64" />

---<img width="1869" height="738" alt="image" src="https://github.com/user-attachments/assets/6139e7e0-d89d-4a4d-a763-ca0bab4038cb" />
<img width="1653" height="376" alt="image" src="https://github.com/user-attachments/assets/2eb2b23e-41a1-4ec2-874c-098566853755" />



### 5. Validação da configuração

Após a associação do Elastic IP, realizei a validação do endereço IP público, verificando sua permanência após interromper e iniciar novamente a instância.

📸 **Imagem 5 — Validação do Elastic IP**
<img width="802" height="317" alt="image" src="https://github.com/user-attachments/assets/0d0e2b44-a6e5-400a-af2e-1f2ab332c3db" />


---

## 💡 Aprendizados

Durante este laboratório, desenvolvi conhecimentos práticos sobre:

- Gerenciamento de instâncias EC2.
- Endereçamento IPv4 público e privado.
- Configuração de recursos de rede na AWS.
- Comportamento de endereços IP dinâmicos.
- Utilização de Elastic IP.
- Troubleshooting de conectividade em ambientes Cloud.

## 🚀 Conclusão

Este laboratório contribuiu para o desenvolvimento dos meus conhecimentos em infraestrutura de nuvem, redes e gerenciamento de recursos AWS.

Estou construindo meu portfólio de projetos práticos enquanto evoluo meus conhecimentos em Cloud Computing, com o objetivo de futuramente atuar como Engenheiro Cloud.

---

**Projeto desenvolvido durante meus estudos de AWS Cloud Computing.**
