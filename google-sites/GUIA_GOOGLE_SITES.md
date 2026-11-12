# Site SANES no Google Sites: passo a passo

Conteúdo tirado da planilha **SITE SANES**, das abas `Config_Publica`, `FAQ_Publico`,
`Acervo_Site_SANES` e `Protocolos_Drive`.

> Abas **não usadas**, porque têm dados internos ou pessoais que não devem ir para um
> site público: `Usuarios`, `Perfis_Usuarios`, `Logs_Seguranca`, `Acessos_Medicos`,
> `Canal_Mais_Etica` (relatos), `SAC_Manifestacoes`, `Escala_Plantao`, `Trocas_Escala`,
> fóruns, `Membros_*`, `Medicos_*`, `Gestao_Vista_KPIs` e `Matriz_Riscos_HFMEA`
> (essas duas estão marcadas como `internal_members`).

## Arquivos

| Arquivo | Para quê |
|---|---|
| `site-completo.html` | Prévia do site inteiro. Abra no navegador para ver como fica. |
| `incorporar/orientacoes.html` | Bloco "Orientações ao paciente" |
| `incorporar/faq.html` | Bloco "Dúvidas frequentes" (perguntas que abrem e fecham) |
| `incorporar/qualidade.html` | Bloco "Qualidade e Segurança" com indicadores |
| `incorporar/materiais.html` | Bloco "Materiais e acervo" com links do Drive |
| `incorporar/contato.html` | Bloco "Contato" |

## 1. Criar o site

1. Acesse **sites.google.com** com a conta da SANES e clique em **+ Em branco**.
2. Título do site: **SANES — Serviço de Anestesiologia**.
3. Em **Temas** (à direita), escolha **Simple** ou **Vision**. Cor principal: `#0F5C74`.
4. Logo: o campo `logo_url` da planilha está vazio. Se tiver a logo, use **Inserir logotipo**.

## 2. Criar as páginas (aba Páginas, botão +)

Monte as páginas abaixo. Em cada uma, adicione o bloco HTML assim:
**Inserir → Incorporar → Incorporar código**, cole **todo** o conteúdo do arquivo
indicado, clique em **Avançar → Inserir**. Depois estique a caixa para baixo até
o conteúdo aparecer inteiro, sem barra de rolagem.

| Página | O que colocar |
|---|---|
| **Início** | Banner (Cabeçalho > "Banner grande"), título *Anestesia segura, ética e humanizada*, o texto **Quem somos** e Missão / Visão / Valores (veja o texto abaixo). Botão **Inserir → Botão**: "Fale pelo WhatsApp", link `https://wa.me/556193806274`. |
| **Orientações ao paciente** | `incorporar/orientacoes.html` + `incorporar/faq.html` |
| **Qualidade e Segurança** | `incorporar/qualidade.html` |
| **Materiais** | `incorporar/materiais.html` |
| **Canal Mais Ética** | Texto abaixo (caixa de texto normal) |
| **Contato** | `incorporar/contato.html` + **Inserir → Mapa**: "Hospital Santa Lúcia Sul, Brasília" |

### Textos para as caixas de texto

**Quem somos**
A SANES é um serviço especializado em anestesiologia e medicina perioperatória dedicado à assistência segura, ética e humanizada em procedimentos cirúrgicos e diagnósticos, atuando de forma integrada às equipes hospitalares e ambulatoriais. Tradição consolidada em Brasília/DF.

**Missão**
Proporcionar assistência anestesiológica segura, ética e acolhedora em todas as etapas perioperatórias, fundamentada em protocolos clínicos baseados em evidências.

**Visão**
Ser referência em governança clínica, segurança do paciente, educação continuada e excelência assistencial em anestesiologia.

**Valores**
Segurança do Paciente • Ética e Bioética • Cuidado Humanizado • Transparência • Atualização Científica • Trabalho Multiprofissional

**Canal Mais Ética**
A organização reafirma seu compromisso permanente com os princípios da Ética Profissional, da Bioética, da transparência institucional e da confidencialidade. Para relatos, elogios ou sugestões, escreva para anestesiasanes@gmail.com.
*(Quando houver o formulário, preencha `link_documento_canal_etica` na planilha e coloque um botão aqui.)*

**Rodapé** (passe o mouse no fim da página → **Adicionar rodapé**)
SANES — Serviço de Anestesiologia · Responsável Técnico: Dr. Rodrigo Barbosa Aires — Médico Anestesiologista | CRM-DF / RQE · (61) 3445-0000 · Seg. a sex., 07h30–18h00

## 3. Antes de publicar: confira

- **Permissão dos links do Drive**: as pastas e o documento de antibiótico profilático só abrem para o público se estiverem em "Qualquer pessoa com o link". Se forem só para a equipe, remova esses cartões de `materiais.html`.
- **Indicadores e protocolos clínicos**: confirme com a coordenação se podem ficar públicos. Se forem só para médicos, coloque essas páginas em um segundo Google Site com acesso restrito ao domínio ou a e-mails convidados (**Compartilhar → Publicado → Restrito**).
- **Campos vazios na planilha**: `logo_url`, `link_documento_preparo`, `link_pesquisa_satisfacao`, `link_notificacao_incidente_drive`, `link_documento_canal_etica` e `link_documento_hfmea`. Quando preencher, dá para adicionar um botão para cada um.
- **FAQ-05 (unhas, cílios…)**: o texto da planilha tinha títulos colados e o erro "oias". No site, organizei com subtítulos e corrigi para "Joias". Vale corrigir na planilha também.

## 4. Publicar

**Publicar** (canto superior direito) → endereço, por exemplo `sites.google.com/view/sanes-anestesia` → **Publicar**.
Para usar domínio próprio: **Configurações → Domínios personalizados**.
