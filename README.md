 AMAZUL LAB — Laboratório Nuclear Interativo

Challenge FIAP 2026 | Marinha do Brasil — AMAZUL

Disciplina: Disruptive Architectures: IoT, IoB & Generative IA
Sprint: 1 — Ideação
Status: Proposta conceitual — implementação futura

Sobre o projeto

O Amazul Lab é uma proposta de laboratório virtual interativo que busca aproximar a sociedade da tecnologia nuclear por meio da educação, gamificação e experiências digitais.

O módulo de Internet das Coisas (IoT) pretende demonstrar como sensores e dispositivos conectados podem coletar, transmitir e disponibilizar dados ambientais, permitindo que usuários compreendam conceitos de monitoramento de forma acessível.

Nesta Sprint, o projeto apresenta apenas a arquitetura conceitual, sem implementação física dos dispositivos.

Problema identificado

A tecnologia nuclear ainda é pouco compreendida pela sociedade e frequentemente associada apenas à radiação, riscos e aplicações militares.

Além disso, conceitos de monitoramento ambiental e comunicação entre dispositivos podem ser difíceis de visualizar sem experiências práticas.

Nossa proposta busca transformar esses conceitos em experiências educativas e interativas.

Solução proposta

O Amazul Lab contará com um laboratório virtual que permitirá ao usuário:

Visualizar dados ambientais simulados.

Compreender como sensores IoT funcionam.

Acompanhar gráficos e indicadores.

Receber alertas educativos baseados em cenários fictícios.

Participar de atividades de mitos e verdades sobre tecnologia nuclear.

Consultar fontes de informação relacionadas aos conteúdos.

Componentes previstos

Componente

Função

Sensor de temperatura

Medir temperatura ambiente

Sensor de umidade

Medir umidade relativa do ar

Detector de radiação

Medir radiação ambiental

ESP32

Receber e transmitir leituras

Wi-Fi

Conectar o dispositivo à rede

MQTT

Transportar mensagens entre dispositivos e sistema

Broker MQTT

Encaminhar mensagens ao backend

Backend/API

Processar e validar os dados

Banco de dados

Armazenar informações

Plataforma educativa

Exibir gráficos, explicações e atividades

Os componentes representam uma proposta para implementação futura.

Comunicação e arquitetura

A arquitetura conceitual prevê que os sensores sejam conectados a um microcontrolador ESP32.

As leituras seriam transmitidas pela rede Wi-Fi utilizando o protocolo MQTT.

Um broker MQTT encaminharia as mensagens ao backend, responsável pelo processamento e armazenamento.

A plataforma educativa apresentaria os resultados ao usuário.

Fluxo previsto:

Sensores → ESP32 → Wi-Fi/MQTT → Broker MQTT → Backend → Banco de Dados → Plataforma Educativa

Fluxograma de funcionamento

O processo será dividido nas seguintes etapas:

Início do monitoramento.

Coleta das leituras ambientais.

Transmissão das informações.

Recebimento e processamento dos dados.

Comparação com faixas didáticas predefinidas.

Exibição dos indicadores ou alertas educativos.

Apresentação de conteúdos e atividades interativas.



Integração com Banco de Dados

O projeto educativo já possui uma modelagem Oracle composta pelas entidades:

CATEGORIA: classificação dos conteúdos.

AFIRMACAO: afirmações educativas.

ALTERNATIVA: opções de resposta.

FONTE: referências informativas.

O módulo IoT poderá utilizar esses conteúdos para relacionar as simulações às atividades de aprendizagem.

O armazenamento das leituras dos sensores será planejado em uma etapa futura.

Tecnologias previstas

ESP32

Sensores ambientais

Wi-Fi

MQTT

Java ou .NET

Oracle Database

Flutter/Dart

Evolução futura

Nas próximas etapas, pretendemos estudar a viabilidade de:

Implementar um simulador de sensores.

Desenvolver comunicação MQTT.

Criar endpoints para recebimento de leituras.

Construir dashboards educativos.

Integrar as simulações às atividades de mitos e verdades.

Vídeo de apresentação

Link: 

O vídeo apresentará o problema, a solução proposta, os componentes IoT, a comunicação e o fluxograma.

Integrantes

Ilda Ester Mussungayi Afonso — RM 568233


Instituição: FIAP
Curso: Análise e Desenvolvimento de Sistemas
Empresa parceira: Marinha do Brasil / AMAZUL

Observação

Esta é uma proposta exclusivamente educativa e conceitual. Os dados e alertas apresentados nas simulações serão fictícios e não deverão ser utilizados para decisões reais de segurança radiológica.
