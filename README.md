# Grupo51_Fiap_Hackaton_1IADT
Repositório para o Hackaton  do Curso de Pós Gruduação  de AI para Devs - Turma 1IADT

# Links Referências

- [Repositório Github](https://github.com/josehelioaraujo/Grupo51_Fiap_Hackaton_1IADT/tree/main)
- [Arquivo Notebook Colab Grupo51_Fiap_IADT_Hackaton_VisionGuard_Fase5.ipynb](https://colab.research.google.com/drive/1FNAtyO7OAMsimmhRfVDtfgQDK59WDHLo#scrollTo=_s0hcGeiay3H)
- [Video Apresentacao no Youtube](Coloque aqui o link)
   
#  Instruções para executar o projeto no Google Colab
   Executar as células na ordem abaixo:

- Môdulo de Inicialização
    - Importação de libs necessárias
    - Setar Variáveis Globais
    - Setar Parâmetros de Configuração do Modelo Yolo
    - Setar Variáveis globais de Javascript

- Môdulo de Gerenciamento de Logs
  - Classe LoggerManager

- Môdulo de Configuração do Sistema
  - Classe SmtpConfig
  - Classe DatasetConfig
  - Classe ObjectDetectionConfig
  - Classe SystemConfig
  - Classe Configuração

- Môdulo de Utilitários
  - Classe UtilHelper
  - Classe Diagnósticos da WebCam
  - Verificar permissão de acesso da Webcam

- Môdulo da Interface Visual
   - Classe Diagnósticos da WebCam (mover para 'Utilitários')
   - Verificar permissão de acesso da Webcam (mover para 'Utilitários')
   - Classe DisplayUIManager
   - Classe CamaraSetup

-  Môdulo de Notificação de Alertas
   - Classe TwilioMessenger
   - Classe EmailAlertNotifier
   - Classe AlertNotificationManager
   - Classe AlertConfig

- Môdulo de Detecção do Objetos
  - Classe DetectionHistory
  - Classe DetectionResult
  - Classe TargetObjectsManager
  - Classe ObjectorDetector
  - Classe DetectionObjectSystem

- Môdulo Principal - Executor do Detector de Objetos


# 1 - Enunciado do Problema

- A FIAP VisionGuard, empresa de monitoramento de câmeras de segurança, está
analisando a viabilidade de uma nova funcionalidade para otimizar o seu software.

- O objetivo da empresa é usar de novas tecnologias para identificar situações atípicas e que possam colocar em risco a segurança de estabelecimentos e comércios que utilizam suas câmeras.

- Um dos principais desafios da empresa é utilizar Inteligência Artificial para identificar objetos cortantes (facas, tesouras e similares) e emitir alertas para a central de segurança.

- A empresa tem o objetivo de validar a viabilidade dessa feature, e para isso será necessário fazer um MVP para detecção supervisionada desses objetos.

## Objetivos
 -  Construir ou buscar um dataset contendo imagens de facas, tesouras e outros
objetos cortantes em diferentes condições de ângulo e iluminação.

- Anotar o dataset para treinar o modelo supervisionado, incluindo imagens
negativas (sem objetos perigosos) para reduzir falsos positivos.

##  Treinamento do modelo


## Entregável
 -  Documentação detalhando o fluxo utilizado para o desenvolvimento da solução
 - Vídeo de até 15 minutos explicando a solução proposta
 -  Link do github do projeto


## Avaliação
 - Para avaliar o código de vocês nós utilizaremos vídeos como estes do exemplo abaixo:

 - Vídeo de teste

    - https://drive.google.com/file/d/1AV6y7OFPgq9UiU0TMUjoaoYQHsvKO__u/view

- Video 2
  - https://drive.google.com/file/d/1XBhBKY9QHo0xj8gXMYcq92e-vrECrNH3/view

  
