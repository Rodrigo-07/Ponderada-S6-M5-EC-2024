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
| `D1`           | LED           | ~                                                            | LED_THT:LED_D3.0mm                                             | 1   |     |
| `D2`           | D             | ~                                                            | Diode_SMD:D_MiniMELF                                          | 1   |     |
| `J1`           | Pin Out       | ~                                                            | Connector_PinHeader_1.00mm:PinHeader_1x01_P1.00mm_Vertical    | 1   |     |
| `K1`           | Relay_SPST-NO | ~                                                            | Relay_THT:Relay_SPST_Schrack-RT1-FormA_RM5mm                  | 1   |     |
| `PhotoResistor1` | A1050       | [Datasheet](http://cdn-reichelt.de/documents/datenblatt/A500/A106012.pdf) | OptoDevice:R_LDR_D6.4mm_P3.4mm_Vertical                       | 1   |     |
| `Q1`           | BC548         | [Datasheet](https://www.onsemi.com/pub/Collateral/BC550-D.pdf) | Package_TO_SOT_THT:TO-92_Inline                               | 1   |     |
| `R1`           | 240Ω          | ~                                                            | Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal | 1   |     |
| `R2`           | 10kΩ          | ~                                                            | Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal | 1   |     |
| `U1`           | Pico          |                                                              | MCU_RaspberryPi_and_Boards:RPi_Pico_SMD_TH                    | 1   |     |
