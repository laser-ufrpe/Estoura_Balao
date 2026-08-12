# Estoura Balão
O Estoura Balão é um projeto de robótica que consiste na construção de um carrinho controlado por um ESP32, desenvolvido com uma proposta lúdica e interativa. O objetivo é promover uma disputa entre dois carrinhos, em que os participantes devem controlar seus veículos para estourar os balões do adversário.

O projeto integra conceitos de programação, eletrônica e fabricação digital, utilizando motores DC, comunicação via Bluetooth, impressão 3D e peças produzidas em MDF.

## 📸 Protótipo do carrinho
<img width="1600" height="900" alt="Estoura Balão" src="https://github.com/user-attachments/assets/802abea7-eaa4-4c36-9874-dbb115a028b2" />

## Materiais

### Eletrônica

- 1x ESP32
- 2x Motores DC (3–6V)
- 1x Ponte H L298N
- Baterias
- Jumpers para conexão dos componentes

### Estrutura

- 1x Chassi de MDF
- 4x Suportes de MDF para os motores (2 para cada lado)
- 2x Rodas impressas em 3D
- 2x O-rings de borracha para as rodas
- 1x Suporte impresso em 3D para o palito
- 1x Palito
- Parafusos e porcas para fixação dos componentes

##  Estrutura dos arquivos

```text
estoura-balao/
│
├── codigo/
│   └── estoura_balao.ino          # Código do ESP32
│
├── corte_mdf/
│   ├── chassi.dxf                 # Arquivo do chassi
│   └── suportes_motores.dxf       # Arquivos dos suportes dos motores
│
├── modelos_3d/
│   ├── rodas.stl                  # Modelo das rodas
│   └── suporte_palito.stl         # Modelo do suporte do palito
│
└── README.md
