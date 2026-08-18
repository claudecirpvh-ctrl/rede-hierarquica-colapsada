# Rede Hierárquica e Colapsada — Cisco Packet Tracer

## Aluno
Claudecir Rodrigues de Alcantara

## Estrutura da Rede
- **Camada de Núcleo**: Router0, Switch0, Switch1
  - 2 enlaces de cobre → preparado para agregação de 4 Gbps
- **Camada de Distribuição**: Switch5, Switch2
  - Fibra óptica do núcleo → 2 Gbps por enlace
- **Camada de Borda**: Switch4, Switch5, Switch6, Switch7
  - 4 switches, sem redundância
- **Dispositivos finais**:
  - 5 Computadores (PC0 a PC4) — rede esquerda
  - 5 Notebooks (Laptop0 a Laptop4) — rede direita
  - 1 Servidor — rede direita

## Endereçamento IP
- **Rede Esquerda**: 192.168.1.0/24 — Gateway: 192.168.1.1
- **Rede Direita**: 192.168.2.0/24 — Gateway: 192.168.2.1
- **Roteador**:
  - GigabitEthernet0/0: 192.168.1.1/24
  - GigabitEthernet0/1: 192.168.2.1/24

## Arquivos
- `atividade_rede_hierarquica_Claudecir_Alcantara.pkt` — Projeto Cisco Packet Tracer
- `topologia_final.png` — Captura da topologia com todas as luzes verdes
- `teste_ping.png` — Teste de comunicação entre redes (pontuação extra)
-
