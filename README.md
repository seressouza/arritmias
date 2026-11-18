# Missão Cardio: arritmias e dispositivos implantáveis

App de estudo da aula ativa de **Arritmias e dispositivos cardíacos implantáveis** (Fisioterapia Aplicada à Cardiologia).

O que tem no app:

- **8 missões**: as 4 perguntas de cada tema, com resposta, fonte (diretriz e seção) e pérolas clínicas.
- **4 casos clínicos**: o aluno escolhe a conduta e recebe a justificativa com a fonte.
- **32 flashcards**: revisão rápida, em ordem aleatória.
- **3 regras de ouro** e a lista das 4 diretrizes.

O progresso fica salvo no navegador de cada aluno. Não há login nem coleta de dados.

## Como publicar no GitHub Pages

1. No GitHub, crie um repositório novo (por exemplo, `missao-cardio-arritmias`) e marque **Public**.
2. Clique em **Add file → Upload files** e envie `index.html`, `README.md` e `.nojekyll`. Depois clique em **Commit changes**.
3. Vá em **Settings → Pages**. Em **Source**, escolha **Deploy from a branch**, branch **main**, pasta **/(root)**, e clique em **Save**.
4. Em 1 a 2 minutos o link aparece no topo da página: `https://SEU-USUARIO.github.io/missao-cardio-arritmias/`.

Dica: o `.nojekyll` começa com ponto e pode ficar oculto no seu computador. Se não conseguir enviá-lo, o app funciona sem ele.

## Como editar o conteúdo

Todo o conteúdo fica dentro do `index.html`, na linha que começa com `const DATA =`. Ali estão os temas, as perguntas, as respostas, as pérolas e os casos. Edite o texto entre aspas e salve; as cores e o layout não mudam.

## Fontes

- Diretriz SBC de Análise e Emissão de Laudos Eletrocardiográficos – 2022 (Arq Bras Cardiol 2022;119(4):638-680)
- Diretriz Brasileira de Fibrilação Atrial – 2025 (Arq Bras Cardiol 2025;122(9):e20250618)
- Diretriz Brasileira de Reabilitação Cardiovascular – 2020 (Arq Bras Cardiol 2020;114(5):943-987)
- Diretriz Brasileira de Dispositivos Cardíacos Eletrônicos Implantáveis – 2023 (Arq Bras Cardiol 2023;120(1):e20220892)
- Critérios de instabilidade: diretrizes da American Heart Association de suporte avançado de vida (ACLS)

Material de estudo. Não substitui a avaliação clínica nem a leitura das diretrizes.
