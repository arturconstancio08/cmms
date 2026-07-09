# CMMS REI Auto Parts (v20)

Sistema de gestão de manutenção — versão estática com base real do TOTVS.

## Publicar
1. Subir esta pasta para um repositório no GitHub.
2. No Vercel: **Add New -> Project -> Import** do repositório. Framework: **Other**. Sem build — é site estático.
3. O app abre na raiz do domínio (`index.html`).

## Ficheiros
- `index.html` — programa de gestão (CMMS v20)
- `abrir-os.html` — portal de abertura de OS para operadores (v11), em `SEU-DOMINIO/abrir-os.html`
- `DB_REI_dados.js` — base real: 1.472 equipamentos + 16.499 OS (obrigatório na mesma pasta)
- `logo-rei.png` — logótipo

## Avisos
- Sem login: qualquer pessoa com o link acede.
- Alterações (OS novas, triagens, conclusões) ficam no navegador de cada utilizador (`localStorage`) — não são partilhadas entre dispositivos.
