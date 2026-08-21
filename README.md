# Atividade: Rede Hierárquica Colapsada

Curso: Superior de Tecnologia em Redes de Computadores

## Estrutura da Rede
A montagem segue a divisão hierárquica em 3 camadas, como solicitado:
. **Camada de Núcleo**: 1 Roteador + 2 Switches de Núcleo
   - Roteador com 2 interfaces FastEthernet, conectado aos dois switches de núcleo
   - 4 ligações físicas entre os switches de núcleo, prontas para agregação de link de 4 Gbps
. **Camada de Distribuição**: 2 Switches de Distribuição
   - Conectados aos switches de núcleo por fibra óptica, prontos para agregação de 2 Gbps
. **Camada de Borda/Acesso**: 4 Switches de Borda + Dispositivos Finais
   - Dispositivos: 4 Computadores, 4 Notebooks, 1 Servidor
   - Todos configurados com endereços IP estáticos na faixa 192.168.2.10 a 192.168.2.30, máscara 255.255.255.0

## Resultado dos Testes
Todos os dispositivos se comunicam com sucesso via comando `ping`, com **0% de perda de pacotes**, garantindo o cumprimento do requisito extra de pontuação.

## Arquivos
- Diagrama da rede montada no Cisco Packet Tracer
- Resultado dos testes de conectividade
-
