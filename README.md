# 📚 Minha Jornada de Estudos em Cloud Computing (AWS)

Este repositório registra minha evolução prática no aprendizado de computação em nuvem, com foco em **AWS Networking e Segurança**.  
O objetivo é documentar conceitos estudados, configurações realizadas e arquiteturas implementadas durante os laboratórios.

---

## ☁️ Redes na AWS — VPC (Virtual Private Cloud)

Durante os estudos, aprendi desde os conceitos fundamentais até a implementação completa de uma VPC personalizada.

### 🔹 Conceitos estudados
- O que é uma VPC
- Isolamento de rede na nuvem
- Estrutura de sub-redes públicas e privadas
- Comunicação entre serviços dentro da AWS
- Segurança de rede em camadas

---

## 🏗️ Componentes configurados

### Sub-redes
- Sub-rede pública (acesso externo)
- Sub-rede privada (proteção da aplicação e banco)

### Conectividade
- Internet Gateway
- NAT Gateway
- VPC Endpoint

### Segurança
- Security Groups
- Network ACLs

---

## 🔐 Bastion Host

Implementei um **Bastion Host** para acesso seguro às instâncias privadas.

O Bastion funciona como um ponto intermediário de conexão SSH, permitindo:

- Não expor servidores internos à internet
- Controlar acessos administrativos
- Aplicar boas práticas de segurança em cloud

Arquitetura implementada:

```
Internet → Bastion Host (sub-rede pública) → Servidores privados
```

---

## 📊 Monitoramento e Logs

Configurei monitoramento para auditoria e observabilidade:

- Logs de acesso ao S3
- Integração com CloudWatch
- Registro de atividades de rede

Isso permite rastrear acessos e identificar comportamentos suspeitos.

---

## 🎯 Habilidades adquiridas

Ao final dos estudos, passei a conseguir:

- Criar uma VPC do zero
- Segmentar redes públicas e privadas
- Configurar roteamento seguro
- Implementar Bastion Host
- Controlar acesso com Security Groups e ACLs
- Monitorar atividades com logs


---

💡 Este repositório faz parte da minha evolução prática em Cloud Computing e será continuamente atualizado conforme avanço nos estudos.
