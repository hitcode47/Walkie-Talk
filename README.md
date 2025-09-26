# 📡 Walkie-Talk
Este modelo de **rádio comunicador** faz parte de um projeto de melhoria no âmbito da iniciativa **PETEE Protótipos (UFMG)**.  

Como proposta inicial, foi desenvolvido um protótipo voltado à experimentação em **Telecomunicações** e **Eletrônica de Potência**, aplicável em disciplinas e oficinas de extensão.  

---

## 📌 Objetivo 
- oferecer uma documentação **didática e funcional**, além de contribuir para a diversificação do acervo de protótipos.  
- Demonstrar os conceitos de **transmissão e recepção de sinais de rádio**.  
- Produzir um protótipo de **baixo custo e replicável**, acessível para estudantes.  
- Apoiar atividades de ensino e extensão com um material prático e interativo.  

---

## ⚡ Especificações – Módulo SA828-U

- **Faixa de frequência (UHF):** 400 – 480 MHz  
- **Potência de saída (TX):** até ~1.5 W (≈ 30 a 32.5 dBm)  
- **Sensibilidade de recepção (RX):** ~–124 dBm  
- **Alcance estimado:** 3 – 5 km em campo aberto (dependendo da antena e ambiente)  
- **Alimentação (Vcc):** 3.3 V a 5.5 V (típico 4.2 V)  

### Consumo de Corrente
- RX: ~60 mA  
- TX (alta potência): ~800-900 mA  
- TX (baixa potência): ~350-450 mA  
- Repouso (sleep): ≤ 3 µA  

### Características de Comunicação
- Largura de banda selecionável: 12.5 kHz / 25 kHz  
- Modulação: FM  
- Rejeição de canal adjacente: –60 dBc a 12.5 kHz  
- Códigos de áudio:  
  - CTCSS: 38 níveis  
  - CDCSS: 166 níveis  

### Áudio
- Saída de alto-falante: ~2 W  
- Impedância recomendada: 8 Ω  

### Recursos Extras
- Controle de potência (alto/baixo) via pino H/L  
- Configuração via interface UART e software de PC  
- Oscilador TCXO 1 ppm (alta estabilidade de frequência)  
- Temperatura de operação: –30 °C a +70 °C  


---

## 🧰 Materiais Usados
| Referência | Quantidade | Valor / Modelo | Descrição                             | Datasheet                                                   |
| ---------- | ---------- | -------------- | ------------------------------------- | ----------------------------------------------------------- |
| BT1        | 1          | 1042           | Suporte de bateria                    | –                                                           |
| D1         | 1          | 1N4148WT       | Diodo retificador rápido, 75V / 0.15A | [PDF](https://www.diodes.com/assets/Datasheets/ds30396.pdf) |
| LS1        | 1          | POM-3542P-R    | Microfone eletreto                    | –                                                           |
| LS2        | 1          | KSSG2308       | Alto-falante                          | –                                                           |
| S1         | 1          | PB400OAQR1BLK  | Botão push-button                     | –                                                           |
| SATRX1     | 1          | SA828U         | Módulo de rádio UHF                   | –                                                           |

---

## 🖼️ Modelos 3D
- Arquivos de carcaça e suporte em **STL/STEP**.  
- Visualização no KiCad / Fusion 360.  
*(Inserir link ou pasta `/3d_models`)*  

---

## 🎥 Mídia
- Fotos do protótipo em diferentes etapas.  
- Vídeos de funcionamento.  
- QR Code para acesso rápido a demonstrações.  

---

## 🛠️ Processo de Produção
1. **Definição de requisitos** (alcance, custo, alimentação).  
2. **Projeto esquemático** no KiCad.  
3. **Protótipo em breadboard** para testes iniciais.  
4. **PCB** e montagem final.  
5. **Testes de calibração e validação**.  
6. **Documentação e publicação** no GitHub.  

---

## 📐 Esquemáticos
- Diagramas completos em **KiCad**.  
- Versão PDF para consulta rápida.  
*(Inserir links para `/hardware/esquematico.pdf` ou `/hardware/kicad_project`)*  

---

## 📚 Referências
- Sedra & Smith – *Microeletrônica*.  
- Haykin – *Sistemas de Comunicação*.  
- Tutoriais de RF (AllAboutCircuits, EEVBlog).  
- Documentação interna PETEE.  

---

## 👥 Equipe
- **PETEE – UFMG**  
- Petiano responsável: *[Bruno dos Santos Lopes]*  
- Tutor: *[Nome do Professor]*  

---

## 📢 Licença
Projeto aberto para fins didáticos. Cite **PETEE – UFMG** ao utilizar.  

---
