# NerfasRO Patches

Repositório público de patches do NerfasRO. Usado pelo patcher (rpatchur) para baixar atualizações automaticamente.

## Estrutura

- `plist.txt` — Lista de patches disponíveis (auto-atualizada pelo CI)
- `web/index.html` — Interface do patcher
- **Releases** → Arquivos `.thor` com as atualizações

## Como funciona

1. O jogador abre o `NerfasRO Patcher.exe`
2. O patcher baixa `plist.txt` e verifica quais patches faltam
3. Baixa os `.thor` necessários das Releases
4. Aplica as mudanças no `nerfasro.grf` local
5. Pronto para jogar!
