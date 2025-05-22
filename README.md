# Configuração Premium do TP-Link Archer AX11000 para Vivo Fibra
(Maximizando Performance sem Considerar Custos)

## Este guia fornece a configuração avançada definitiva para extrair o máximo desempenho do seu Archer AX11000 na rede Vivo Fibra, cobrindo desde configurações básicas até ajustes profissionais para gaming, streaming e baixa latência.

# 📦 Pré-requisitos
- #### Roteador Archer AX11000 com firmware atualizado.

- #### Plano Vivo Fibra (recomendado 500Mbps+ para aproveitar o Wi-Fi 6).

- #### Cabos Ethernet Cat 6 ou superior.

- #### Dispositivos compatíveis com Wi-Fi 6 (802.11ax).

# 🔧 Passo a Passo para Configuração

### 1️⃣ Acesso ao Painel de Controle
#### Conecte-se ao roteador via:

#### Wi-Fi: Rede TP-Link_XXXX (senha padrão no rótulo do roteador).

#### Cabo Ethernet: Conecte um PC à porta LAN.

### Acesse:

https://emulator.tp-link.com/ax11000-v1-eu/index.html



### 2️⃣ Configuração da Internet (WAN - Vivo Fibra)
### Vá para Advanced > Network > Internet.
![image](https://github.com/user-attachments/assets/e78557d6-c4eb-4ca8-9d77-e4ca8d33d244)

![image](https://github.com/user-attachments/assets/653ccf21-cd82-44dc-baa5-869eb910e847)

![image](https://github.com/user-attachments/assets/059d304b-29f0-4606-b4e7-7b9b0899c818)

#### Selecione:

#### - Tipo de Conexão: PPPoE (Vivo Fibra usa PPPoE).
![image](https://github.com/user-attachments/assets/92513e7b-7e89-499a-ae3a-47733879339d)

#### - Usuário/Senha: Insira os dados fornecidos pela Vivo (geralmente no contrato).

#### - Configurações Avançadas:

#### - MTU: 1492 (padrão PPPoE).
![image](https://github.com/user-attachments/assets/68c3448c-b62d-423d-8280-1a7797f51d33)

#### - DNS Primário/Secundário:

#### - 8.8.8.8 (Google) e 1.1.1.1 (Cloudflare).
![image](https://github.com/user-attachments/assets/cb8711f5-736a-4db2-b5d0-697e81e2feda)

#### - Clonar MAC: Ative se a Vivo bloquear o roteador.
![image](https://github.com/user-attachments/assets/9d4a8ebc-6362-4559-a4df-7c7663d8d4f1)

### 3️⃣ Wi-Fi Tri-Band (Otimizado para Performance Máxima)
#### Acesse Wireless e configure cada banda:

- #### 📶 Banda 2.4GHz (Para dispositivos IoT e legados)
- #### SSID: Casa_2.4G (diferente do 5GHz).

- #### Modo: 802.11ax/n/g/b mixed.

- #### Canal: 1, 6 ou 11 (fixo, evite Auto).

- #### Largura do Canal: 20MHz (evite interferência).

- #### Segurança: WPA3-Personal (senha forte).

- #### 🚀 Banda 5GHz-1 (Para dispositivos premium)
- #### SSID: Casa_5G.

- #### Modo: 802.11ax/ac/n mixed.

- #### Canal: 36, 40, 44, 48 (ou 149-161 se DFS causar problemas).

- #### Largura do Canal: 160MHz (máxima velocidade).

- #### Segurança: WPA3-Personal.

- #### 🎮 Banda 5GHz-2 (Dedicada a Gaming/Streaming)
- #### SSID: Casa_5G_Gaming.

- #### Configuração igual à 5GHz-1, mas com:

- #### QoS Prioritário (em HomeCare).

- #### MU-MIMO/OFDMA Ativados.

### 4️⃣ Recursos Avançados para Performance
#### ⚡ QoS (Quality of Service)
#### Acesse HomeCare > QoS.

#### Priorize:

- #### Gaming > Video Conferencing > Streaming.

- #### Defina a banda total real (ex.: 1000Mbps = 1000000 Kbps).

### 🔒 IPv6 (Ativação)
#### Vá para Advanced > IPv6.

#### Configure:

#### - Tipo de Conexão: PPPoE (mesmo usuário/senha da Vivo).

#### DNS IPv6:

- #### Primário: 2001:4860:4860::8888 (Google).

- #### Secundário: 2606:4700:4700::1111 (Cloudflare).

### 📡 Otimizações Extras
- #### OFDMA/MU-MIMO: Ativados em Wireless > Advanced.

- #### Airtime Fairness: Desativado (pode prejudicar dispositivos lentos).

- #### Beacon Interval: 100 (padrão).

- #### Transmit Power: High (para melhor cobertura).

### 5️⃣ Segurança e Manutenção
- #### Firewall: Ativo (em Security).

- #### Atualização de Firmware: Verifique em System Tools > Firmware Upgrade.

- #### Backup das Configurações: Exporte em System Tools > Backup & Restore.

### 🎯 Resultados Esperados

#### ✔ Latência mínima em jogos (<10ms em LAN).

#### ✔ Velocidade máxima (até 10Gbps via cabo, ~2400Mbps no Wi-Fi 6).

#### ✔ Estabilidade mesmo com múltiplos dispositivos.

### ⚠️ Solução de Problemas

#### Wi-Fi lento? Escolha canais menos congestionados.

#### Dispositivos antigos não conectam? Use banda 2.4GHz com WPA2.
