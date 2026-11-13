# Sino
## Cofre (`privado/`)

Site pessoal privativo: painel, registro de eventos passados, programação de ordens de
investimento, contas a pagar, calculadora de datas e liturgia romana diária, tudo ligado a
uma central de avisos. Os dados ficam só no aparelho, cifrados com AES-256-GCM (chave
derivada da senha com PBKDF2-SHA256, 600 mil rodadas). Funciona no PC e no celular e pode
ser instalado como app. Abra `privado/index.html` por https (ex.: GitHub Pages) ou localhost.
