# Grupo51_Fiap_Hackaton_1IADT
Repositório para o Hackaton  do Curso de Pós Gruduação  de AI para Devs - Turma 1IADT

# 1 - Entregáveis

- [Repositório Github](https://github.com/josehelioaraujo/Grupo51_Fiap_Hackaton_1IADT/tree/main)
- [Notebook Colab Grupo51_Fiap_1IADT_Hackaton_VisionGuard_Fase5_Apresentacao.ipynb](https://colab.research.google.com/drive/1POVCnfqhgoobDySziqvGO2RVrORzoM0E)
- [Video Apresentacao no Youtube](https://www.youtube.com/watch?v=q48p0YTGFFQ)


# 2 - Enunciado do Problema

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
 

# 3 -Instruções para executar o projeto no Google Colab
   Executar as células na ordem sequencial abaixo, até a seção **Môdulo Principal - Execução do Projeto**:
    - 


## Módulo de Inicialização
- Importação de libs necessárias
- Setar Variáveis Globais
- Setar Parâmetros de Configuração do Modelo Yolo
- Setar Variáveis globais de Javascript

## Módulo de Gerenciamento de Logs
- Classe LoggerManager

## Módulo de Configuração do Sistema
- Classe SmtpConfig
- Classe DatasetConfig  
- Classe ObjectDetectionConfig
- Classe SystemConfig
- Classe Configuração

## Módulo de Utilitários
- Classe UtilHelper
- Classe Diagnósticos da WebCam
- Verificar permissão de acesso da Webcam

## Módulo da Interface Visual
- Classe DisplayUIManager
- Classe CamaraSetup

## Módulo de Notificação de Alertas
- Classe TwilioMessenger
- Classe EmailAlertNotifier
- Classe AlertNotificationManager
- Classe AlertConfig

## Módulo de Detecção do Objetos
- Classe DetectionHistory
- Classe DetectionResult 
- Classe TargetObjectsManager
- Classe ObjectorDetector
- Classe DetectionObjectSystem

## Módulo Principal - Execução do Projeto
 - [WebCam] Execução com Webcam
 - [Videl] Execução com Video


