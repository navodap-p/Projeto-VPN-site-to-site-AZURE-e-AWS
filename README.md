# Integração Multi-Cloud Azure + AWS via VPN Site-to-Site

Este projeto tem como objetivo a construção de um ambiente híbrido entre as plataformas Microsoft Azure e Amazon Web Services (AWS), utilizando uma VPN Site-to-Site. A comunicação entre os recursos nas duas nuvens deve ocorrer exclusivamente por meio de endereços IP privados.

## 🔧 Objetivos do Projeto

- Criar um ambiente multi-cloud entre Azure e AWS.
- Estabelecer uma VPN site-to-site funcional e estável.
- Permitir comunicação entre máquinas virtuais utilizando apenas IPs privados.
- Configurar corretamente as rotas.
- Documentar todos os passos técnicos realizados.

---

## 🖥️ Recursos Criados

### ☁️ Microsoft Azure
- **Rede Virtual (VNet)**
- **Sub-rede Privada**
- **Máquina Virtual (VM)** com IP privado
- **Gateway de VPN**
- **Conexão VPN**

### ☁️ Amazon Web Services (AWS)
- **VPC (Virtual Private Cloud)**
- **Sub-rede Privada**
- **Instância EC2** com IP privado
- **Customer Gateway (CGW)**
- **Virtual Private Gateway (VGW)**
- **Túnel VPN Site-to-Site**


> A documentação completa está disponível no arquivo incluído neste repositório.
