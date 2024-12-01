# 🌟 Meu Portfólio 🌟

Bem-vindo ao meu portfólio AMS2024-3DS! Aqui você encontrará o projeto de TCC (Trabalho de Conclusão de Curso) desenvolvido em grupo referente ao meu curso técnico de Desenvolvimento de Sistemas na ETEC, além dos cursos e palestras oferecidos pela IBM como mentoria durante esse percurso.

## Status do Projeto: Finalizado.

## 📌 Índice
- [Projetos](#projetos)
- [Educação](#educação)
- [Experiência](#experiência)
- [Contato](#contato)

## 🚀 Projetos

### Projeto TCC (Trabalho de Conclusão de Curso): Second Vision
Descrição: Sistema de Auxílio na Autonomia de Deficientes Visuais em Metrópoles.
Como Funciona: Um Raspberry Pi 5, integrado a uma UPS (Uninterruptible Power Supply) e protegido por uma case impressa em 3D, será responsável por processar as imagens captadas por uma webcam. Nesse processamento, objetos potencialmente perigosos serão identificados utilizando a tecnologia YOLO e baseando-se em um catálogo previamente definido. Além disso, o PyTesseract será utilizado para o reconhecimento óptico de textos em placas estáticas, em conjunto com o PySpellChecker para correções ortográficas baseadas em associações contextuais, garantindo um retorno mais preciso dos textos.

Por conseguinte, essas informações são transmitidas via Bluetooth para nosso aplicativo, desenvolvido em React Native com TypeScript e Expo, de forma que elas sejam reproduzidas sonoramente para guiar o deficiente visual. No aplicativo, também são exibidas informações como o nível da bateria do sistema, o tempo estimado de uso restante e três modos de operação: Híbrido (que detecta tanto objetos quanto textos), Somente Objetos e Somente Textos.

- **Tecnologias:** Python, YOLOv8, PyTesseract, OpenCV-Headless, PySpellChecker, Tesseract-OCR, React-Native, Typescript, Expo, BLE (Bluetooth Low Energy).
- **Materiais:** Raspberry Pi 5, UPS (Uninterruptible Power Supply), SD Card (8 GB), Duas Baterias íon-lítio recarregáveis (3.7 volts), Case feita em impressão 3D, colete flexível, WebCam.
- **Linguagem de modelagem padrão** UML (Unified Modeling Language).
- **Link:** https://github.com/gustavoventieri/SecondVision.git. 

## 🎓 Educação

- **ETEC Zona Leste** – Desenvolvimento de Sistemas no programa Articulado Médio Superior (AMS)
  - *Ano de Conclusão:* (2024)

## 💼 Experiência

Durante o desenvolvimento deste projeto, obtive experiências significativas que envolveram tanto aspectos técnicos quanto práticos, resultando em um sistema funcional e integrado. Abaixo estão os principais destaques:

### Planejamento e Gerenciamento de Projetos
- Estruturação do cronograma do projeto e definição de metas e entregas.
- Pesquisa de tecnologias adequadas, incluindo **BLE (Bluetooth Low Energy)** e visão computacional.

### Habilidades Técnicas e Ferramentas Utilizadas
- Implementação de um servidor **GATT BLE** no **Raspberry Pi 5** para comunicação com dispositivos móveis.
- Desenvolvimento de um aplicativo em **React Native** com **TypeScript**, incluindo integração com hardware via BLE.
- Uso de tecnologias como:
  - **YOLOv8** para detecção de objetos.
  - **PyTesseract** para reconhecimento óptico de textos.
  - **PySpellChecker** para correções ortográficas, garantindo precisão na interpretação de placas e sinais.

### Impressão 3D e Design de Protótipos
- Criação de uma **case customizada** para o Raspberry Pi 5, com funcionalidades adaptadas às necessidades do usuário.

### Integração de Hardware e Software
- Integração de uma **UPS** para fornecer energia contínua ao sistema.
- Uso de baterias de íon-lítio para portabilidade e autonomia.

### Desenvolvimento e Testes
- Implementação de **três modos de operação** no aplicativo:
  - **Híbrido**: Detecta tanto objetos quanto textos.
  - **Somente Objetos**: Detecta apenas objetos.
  - **Somente Textos**: Detecta apenas textos.
- Realização de testes de campo em cenários reais, ajustando os algoritmos para maior precisão.

### Desafios e Soluções
- Solução para comunicação em tempo real entre o servidor e o aplicativo.
- Superação de limitações de hardware por meio de otimização de software.

## 📞 Contato

- **Email:** tiagobryanroliveira@gmail.com 
- **LinkedIn:** https://www.linkedin.com/in/tiago-bryan-ramos-de-oliveira-09882b299/
