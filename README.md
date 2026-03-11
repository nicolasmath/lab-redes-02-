![GitHub License](https://img.shields.io/github/license/nicolasmath/lab-redes-01)

# Laboratório de Redes 2 - Roteadores Wireless

Alunos: Nicolas Lopes, Sara Oliveira

Professor: José de Assis

Data: 10/03/2026

---

## **1. Objetivo:**
- Realizar uma configuração básica de rede Wifi utilizando 1 roteador e 1 desktop
- Criar uma rede invisível e alterar a senha de acesso para o roteador

O projeto será dividido em 2 etapas:

1. Simulação da Rede no Cisco Packet Tracer
2. Implementação da rede no laboratório real

---

## **2. Equipamentos usados nesse laboratório:**

- 1 Desktop
- 1 Roteador Wireless com 1 porta WAN e 4 portas LAN
- Cabo de rede

---

## **3. Topologia da Rede:**

Diagrama lógico da rede usada neste laboratório. 

```mermaid
graph TD

WAN[Internet / WAN do provedor]

Router[Roteador Wireless<br>1 Porta WAN<br>4 Portas LAN]

PC1[Desktop]

Celular1[Smatphone]

WAN --> |Porta WAN| Router 

Router --> |LAN 4| PC1
Router --> |Wireless| Celular1

```

<p align="center">
  <strong>Imagem da topologia usada neste laboratório:</strong><br><br>
  <img src="Topologia0.png" alt="Topologia da rede" width="600">
</p>

