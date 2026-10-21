# voxcanal-motor-status

Estado público do motor de coleta do VOXCANAL (https://voxcanalsp.com.br).

Este repositório é gravado automaticamente pelo fluxo do motor ao fim de cada rodada (6h46, 12h46 e 18h46, horário de Brasília). Serve para a conferência diária e o espelho no Dropbox lerem a situação do motor sem credencial.

- `ultima_rodada.json` - quando rodou, semáforo geral (verde, amarelo ou vermelho), quantidade de achados, erros de DOSP e nome do boletim.
- `coleta/BOLETIM_AAAA-MM-DD_HHMM.md` - boletim de cada rodada (resumo dos diários oficiais lidos e das falhas).

Os achados completos ficam no repositório privado do motor. Nada aqui é editado à mão.

Leitura direta: https://raw.githubusercontent.com/GianniniMario/voxcanal-motor-status/main/ultima_rodada.json
