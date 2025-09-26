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

| Categoria                     | Especificação |
|-------------------------------|---------------|
| **Faixa de frequência (UHF)** | 400 – 480 MHz |
| **Potência de saída (TX)**    | até ~1.5 W (≈ 30 a 32.5 dBm) |
| **Sensibilidade (RX)**        | ~–124 dBm |
| **Alcance estimado**          | 3 – 5 km em campo aberto (dependendo da antena e ambiente) |
| **Alimentação (Vcc)**         | 3.3 V a 5.5 V (típico 4.2 V) |

### Consumo de Corrente  

| Modo                  | Corrente típica |
|------------------------|-----------------|
| RX                     | ~60 mA |
| TX (alta potência)     | ~800 – 900 mA |
| TX (baixa potência)    | ~350 – 450 mA |
| Repouso (sleep)        | ≤ 3 µA |

### Comunicação  

| Parâmetro                  | Especificação |
|-----------------------------|---------------|
| Largura de banda            | 12.5 kHz / 25 kHz |
| Modulação                   | FM |
| Rejeição de canal adjacente | –60 dBc a 12.5 kHz |
| Códigos de áudio            | CTCSS (38 níveis), CDCSS (166 níveis) |

### Áudio  

| Parâmetro                  | Especificação |
|-----------------------------|---------------|
| Saída do alto-falante       | ~2 W |
| Impedância recomendada       | 8 Ω |

### Recursos Extras
- Controle de potência (alto/baixo) via pino H/L  
- Configuração via interface UART e software de PC  
- Oscilador TCXO 1 ppm (alta estabilidade de frequência)  
- Temperatura de operação: –30 °C a +70 °C  


---

## 🧰 Materiais Usados
| Referência | Quantidade | Valor / Modelo | Descrição                             | Datasheet                                                   |
| ---------- | ---------- | -------------- | ------------------------------------- | ----------------------------------------------------------- |
| BT1        | 1          | 1042           | Suporte de bateria                    | [PDF](https://www.diodes.com/assets/Datasheets/ds30396.pdf) |
| D1         | 1          | 1N4148WT       | Diodo retificador rápido, 75V / 0.15A | [PDF](https://www.diodes.com/assets/Datasheets/ds30396.pdf) |
| LS1        | 1          | POM-3542P-R    | Microfone eletreto                    | [PDF](https://www.diodes.com/assets/Datasheets/ds30396.pdf) |
| LS2        | 1          | KSSG2308       | Alto-falante                          | [PDF](https://www.diodes.com/assets/Datasheets/ds30396.pdf) |
| S1         | 1          | PB400OAQR1BLK  | Botão push-button                     | [PDF](https://www.diodes.com/assets/Datasheets/ds30396.pdf) |
| SATRX1     | 1          | SA828U         | Módulo de rádio UHF                   | [PDF](https://www.diodes.com/assets/Datasheets/ds30396.pdf) |

---

## 📐 Esquemáticos
- **Esquemático**  
  ![Walkie Talk](https://github.com/hitcode47/Walkie-Talk/blob/main/Imagens%20e%20esquem%C3%A1ticos/esquem%C3%A1tico_WT.png)  

- **Footprint**  
  ![Walkie Talk](https://github.com/hitcode47/Walkie-Talk/blob/main/Imagens%20e%20esquem%C3%A1ticos/esquem%C3%A1tico_footprint_WT.png)  


---
## 🖼️ Modelos 3D  

- 📂 [Arquivos de carcaça e suporte (STL/STEP)](./3d_models)  

### PCB  

- **Modelo Frontal**  
  ![PCB Frontal](https://github.com/hitcode47/Walkie-Talk/blob/main/Imagens%20e%20esquem%C3%A1ticos/walkie%20talk.png)  

- **Modelo de Fundo**  
  ![PCB Fundo](https://github.com/hitcode47/Walkie-Talk/blob/main/Imagens%20e%20esquem%C3%A1ticos/walkie%20talk_back.png)  


---

## 🎥 Mídia    

- **Vídeo 1 – Visão PCB**  
  [![Vídeo 1](./media/video1_thumb.png)](https://youtu.be/KtvOQ1vCON0)  

- **Vídeo 2 – Visão Compacta**  
  [![Vídeo 2](./media/video2_thumb.png)](https://youtu.be/7ha7i7AOuKI)  

- **Vídeo 3 – Visão Explodida**  
  [![Vídeo 3](./media/video3_thumb.png)](https://youtu.be/o6cVx7rBvNw)  

---

## 🛠️ Processo de Produção (Ainda em construção)
1. **Definição de requisitos** (alcance, custo, alimentação).  
2. **Projeto esquemático** no KiCad.  
3. **Protótipo em breadboard** para testes iniciais.  
4. **PCB** e montagem final.  
5. **Testes de calibração e validação**.  
6. **Documentação e publicação** no GitHub.  

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
