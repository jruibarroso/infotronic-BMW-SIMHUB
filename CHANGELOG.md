# Changelog

Todas as alterações relevantes do **InfoTronic BMW SIMHUB** ficam registadas neste ficheiro.
O formato segue o [Keep a Changelog](https://keepachangelog.com/pt-PT/1.1.0/).

## [Por lançar]

## [1.29] - 2026-10-29

Primeira versão pública.

### Adicionado
- Suporte a quadrantes BMW E-Series e F-Series.
- Escolha do chassis (E-Series ou F-Series) no configurador `infotronic_BMW_SIMHUB.exe`. A placa guarda a escolha e ajusta sozinha a velocidade do barramento CAN (100 kbps para o E-Series e  500 kbps para o F-Series).
- Avisos de ABS, ESP (controlo de tração em atuação) e DSC OFF no F-Series, a partir da telemetria do jogo.
- Modo de condução SPORT+ no F-Series ao arrancar.
- Botão **Testar quadrante** no configurador, para verificar o quadrante antes de iniciar o SimHub e o jogo.
- Configuração dos limiares dos avisos (pneus, travões, pastilhas e motor) no configurador.
- Fórmula `NCalc.txt` para colar no SimHub (dispositivo "Custom serial devices").

### Notas
- Jogos testados: Assetto Corsa (o mais compatível) e RaceRoom Racing Experience.
- Na primeira execução do `infotronic_BMW_SIMHUB.exe`, o Windows pode mostrar o aviso do SmartScreen porque o `.exe` não está assinado. Carrega em **Mais informações → Executar mesmo assim**.

[Por lançar]: https://github.com/jruibarroso/infotronic-BMW-SIMHUB/compare/v1.29...HEAD
[1.29]: https://github.com/jruibarroso/infotronic-BMW-SIMHUB/releases/tag/v1.29
