# 🌐 Redes no Azure - AZ-900

As redes no Azure permitem **conectividade segura e escalável** para recursos em nuvem, facilitando a comunicação entre serviços e com ambientes locais.

---

## 🔹 **Rede Virtual do Azure (VNet)**
A **Azure Virtual Network (VNet)** permite que os recursos do Azure **se comuniquem com segurança**, oferecendo isolamento e personalização.

### ✨ **Características**:
- **Isolamento**: Cada VNet é privada e isolada das demais.
- **Sub-redes**: Permite dividir a rede para organização e segurança.
- **Conectividade híbrida**: Pode se conectar a redes locais via **VPN Gateway** ou **ExpressRoute**.
- **Suporte a tráfego seguro** com **firewalls e grupos de segurança de rede (NSG)**.

---

## 🔹 **Grupos de Segurança de Rede (NSG)**
Os **Network Security Groups (NSGs)** controlam o tráfego de entrada e saída das VNets e sub-redes.  

### ✨ **Benefícios**:
- **Filtragem de tráfego** com regras de entrada e saída.
- **Proteção contra acessos não autorizados**.
- **Aplicação em VMs e sub-redes** para segmentação de rede.

---

## 🔹 **Balanceador de Carga do Azure**
O **Azure Load Balancer** distribui o tráfego de entrada entre várias instâncias de serviço, garantindo **alta disponibilidade**.

### ✨ **Tipos**:
- **Público**: Distribui tráfego da internet para recursos do Azure.
- **Interno**: Distribui tráfego dentro da rede privada do Azure.

---

## 🔹 **Gateway VPN do Azure**
O **VPN Gateway** permite conexões seguras entre redes locais e o Azure, utilizando **túneis criptografados**.

### ✨ **Modos de Conexão**:
- **Site a Site (S2S)**: Conexão permanente entre um data center local e o Azure.
- **Ponto a Site (P2S)**: Permite que dispositivos individuais se conectem ao Azure via VPN.
- **ExpressRoute**: Conexão privada e dedicada, com alta velocidade e baixa latência.

---

## 🔹 **Firewall do Azure**
O **Azure Firewall** protege redes no Azure contra **ameaças externas**, oferecendo segurança de nível corporativo.

### ✨ **Principais Recursos**:
- **Filtragem de tráfego baseada em regras**.
- **Prevenção contra ataques DDoS** (serviço separado: Azure DDoS Protection).
- **Monitoramento centralizado** com logs de segurança.

---

## 🔹 **CDN (Content Delivery Network)**
O **Azure CDN** melhora a performance de aplicativos distribuindo conteúdo para **servidores geograficamente próximos aos usuários**.

### ✨ **Vantagens**:
- **Redução de latência** para usuários globais.
- **Melhoria no carregamento de sites e aplicativos**.
- **Escalabilidade para alto tráfego**.

---

## 🔹 **Azure Private Link**
Permite que serviços do Azure sejam acessados de forma **privada e segura**, sem expô-los à internet pública.

### ✨ **Benefícios**:
- **Conexões privadas** entre VNets e serviços PaaS.
- **Redução de riscos de exposição** a ataques externos.
- **Menos necessidade de VPNs ou IPs públicos**.

---

## 🎯 **Resumo**
| Serviço | Função |
|---------|--------|
| **VNet** | Rede privada e isolada no Azure. |
| **NSG** | Controle de tráfego com regras de segurança. |
| **Load Balancer** | Distribuição de tráfego entre instâncias. |
| **VPN Gateway** | Conexão segura entre redes locais e o Azure. |
| **Firewall do Azure** | Proteção contra ameaças na rede. |
| **Azure CDN** | Acelera a entrega de conteúdo globalmente. |
| **Azure Private Link** | Acesso privado a serviços do Azure sem internet. |

---

Este conteúdo cobre os **principais conceitos de redes no Azure** para a certificação **AZ-900**. Se precisar de mais detalhes ou quiser exemplos práticos, me avise! 🚀
