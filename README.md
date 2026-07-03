# CMMS REI Auto Parts (v6)

Sistema de gestão de manutenção — versão estática com base real do TOTVS.

## Publicar
1. Subir esta pasta para um repositório no GitHub.
2. No Vercel: **Add New → Project → Import** do repositório. Framework: **Other**. Sem build — é site estático.
3. O app abre na raiz do domínio (index.html).

## Ficheiros
- `index.html` — o programa de gestão (CMMS v6)
- `abrir-os.html` — portal de abertura de OS para operadores (v4) — abre em `SEU-DOMINIO/abrir-os.html`
- `DB_REI_dados.js` — base real: 1.472 equipamentos + 16.499 OS (obrigatório na mesma pasta)
- `logo-rei.png` — logótipo

## Avisos
- Sem login: qualquer pessoa com o link acede.
- Alterações (OS novas, triagens) ficam no navegador de cada utilizador (localStorage) — não são partilhadas entre dispositivos.
