# Ponderada-S6-M5-EC-2024

Nome: Rodrigo Sales Freire dos Santos

Repositorio para a entrega da atividade de Ponderada-S6-M5-EC-2024. Para concluir a atividade desenvolvi uma placa PCI que contem um Raspberry Pico que a partir da leitura da luminosidade do ambiente, aciona algun dispositivo de saida atraves de um rele e um transistor. O projeto foi desenvolvido no software KiCad.


# Imagens do Projeto

## Desenho Esquematico
![alt text](/imagens/DesenhoEsquematico.png)


## Placa PCI
![alt text](/imagens/PlacaPCI.png)

# Imagem 3D

![alt text](/imagens/Imagem3D_1.png)


![alt text](/imagens/Imagem3D_2.png)


# Lista de Materiais

| Reference      | Value         | Datasheet                                                    | Footprint                                                      | Qty | DNP |
|----------------|---------------|--------------------------------------------------------------|----------------------------------------------------------------|-----|-----|
| `Led Vermelha`           | LED           | ~                                                            | LED_THT:LED_D3.0mm                                             | 1   |     |
| `Diodo`           | D             | ~                                                            | Diode_SMD:D_MiniMELF                                          | 1   |     |
| `Pin out`           | Pin Out       | ~                                                            | Connector_PinHeader_1.00mm:PinHeader_1x01_P1.00mm_Vertical    | 1   |     |
| `Relay`           | Relay_SPST-NO | ~                                                            | Relay_THT:Relay_SPST_Schrack-RT1-FormA_RM5mm                  | 1   |     |
| `Photo Resistor` | A1050       | [Datasheet](http://cdn-reichelt.de/documents/datenblatt/A500/A106012.pdf) | OptoDevice:R_LDR_D6.4mm_P3.4mm_Vertical                       | 1   |     |
| `Transistor BC548`           | BC548         | [Datasheet](https://www.onsemi.com/pub/Collateral/BC550-D.pdf) | Package_TO_SOT_THT:TO-92_Inline                               | 1   |     |
| `Resistor 240Ω`           | 240Ω          | ~                                                            | Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal | 1   |     |
| `Resistor 10kΩ`           | 10kΩ          | ~                                                            | Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal | 1   |     |
| `Raspberry Pico`           | Pico          |                                                              | MCU_RaspberryPi_and_Boards:RPi_Pico_SMD_TH                    | 1   |     |

# Arquivos

Todos os arquivos de execução do projeto no Kicad estão disponiveis na pasta "Arquivos" deste repositorio.

- Arquivo do Kicad: Ponderada Semana 6.kicad_pro
- Desenho Esquematico: Ponderada Semana 6.kicad_sch
- PCB: Ponderada Semana 6.kicad_pcb

Os arquvis gerados para a fabricação da placa PCI estão disponiveis na pasta "Gerbers" deste repositorio.