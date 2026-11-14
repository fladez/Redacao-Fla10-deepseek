# Fluxo de Produção da Redação

## 1. Planejamento
Consultar painel de pautas, agenda esportiva e reservas. Definir prioridade, prazo, formato e público. Verificar o que já foi publicado sobre o mesmo jogo, personagem ou questão.

## 2. Briefing
Definir fato ou questão central, ângulo, informações necessárias, fontes primárias e secundárias, incertezas, risco de redundância e entregáveis obrigatórios.

## 3. Apuração
Pesquisar informações atuais quando necessário. Separar confirmação de relato atribuído, análise e hipótese. Verificar datas, nomes, placares, competição, mando, horários e disponibilidade de atletas.

## 4. Redação
Começar pelo fato ou tese mais relevante. Organizar em progressão lógica. Dar a cada seção uma função diferente. Integrar contexto apenas quando ajudar a entender a notícia ou análise. Aplicar o manual do formato e as regras de formatação da Fla10:
- Subtítulos internos no formato `<h3>Texto do subtítulo</h3><br>` — usar **apenas um** `<br>` após `</h3>`.
- Encerrar cada parágrafo de texto com `<br><br>`.
- Não confundir a regra dos subtítulos com a dos parágrafos: após o título interno, um `<br>`; após cada parágrafo, dois.

## 5. Revisão
Executar [[Revisão e Controle de Qualidade]]: factualidade, completude, clareza, redundância, estrutura, formatação, SEO e resumo para IA quando aplicáveis. A revisão de formatação deve verificar individualmente todos os subtítulos e parágrafos antes da primeira entrega.

## 6. Entrega
Entregar no formato solicitado. Para matéria, incluir título, subtítulo e componentes obrigatórios. Para trecho, indicar onde encaixa. Para redes, separar versões por plataforma.

## 7. Memória e confirmação de publicação
Quando o responsável informar que a pauta foi publicada, tratar a confirmação e a URL fornecida como evidência do estado publicado. Executar a rotina completa:
1. Criar ou atualizar a ficha da pauta em `06 - Pautas`, registrando título publicado, data, URL pública, formato, ângulo, origem/proveniência e palavra-chave principal quando aplicável.
2. Marcar `status: publicada` e `publicacao_confirmada: true` nos metadados da ficha, quando esse padrão estiver sendo usado.
3. Atualizar [[Painel de Pautas]] com o estado, a URL e um resumo do ângulo, para que futuras prospecções reconheçam o conteúdo e evitem redundância.
4. Acrescentar uma entrada datada em [[Log de Atualizações]] com os arquivos alterados.
5. Registrar em [[Registro de Decisões]] apenas mudanças duradouras de método; publicação individual, por si só, não é uma nova regra editorial.
6. Não afirmar que o site foi editado, que a publicação foi verificada externamente ou que houve sincronização local se a ferramenta só confirmou alterações no GitHub.
7. Executar a revisão pós-publicação: abrir a página publicada, conferir texto e formatação e listar ao editor os erros encontrados, com trecho e correção sugerida, seguindo o checklist de [[Revisão e Controle de Qualidade]].

Registrar regras novas apenas quando forem duradouras; não transformar cada ajuste pontual em política permanente.

## Rotina diária sugerida
1. Conferir agenda e notícias do Flamengo.
2. Revisar pendências e pautas reservadas.
3. Definir prioridades e evitar colisões entre matérias.
4. Produzir e revisar cada peça.
5. Atualizar estado das pautas.
6. Planejar distribuição social relacionada ao conteúdo publicado.
7. Registrar decisões e lições relevantes.


## Regra permanente — fluxo de cobertura por evento esportivo

A programação de matérias deve ser organizada em relação à **data efetiva do evento**, e não apenas à data em que a pauta foi incluída ou será publicada.

### Na véspera do evento
- Produzir e publicar a matéria **Onde assistir**, com os dados de serviço confirmados e as informações disponíveis no momento da apuração.

### No dia do evento

**a) Futebol masculino profissional — equipe principal**
1. **Pré-jogo:** publicar pela manhã, com contexto, informações atualizadas e serviço pertinente.
2. **Pós-jogo:** produzir e publicar logo após o término da partida. É uma primeira notícia de panorama geral, baseada nos fatos e nas poucas informações confiáveis já disponíveis na internet naquele momento. Não tentar antecipar uma análise aprofundada.
3. **Análise jornalística:** publicar mais tarde, depois de aguardar a circulação de informações adicionais, declarações, dados e repercussões que permitam uma abordagem mais profunda. Deve ter pergunta, recorte e interpretação próprios, sem repetir o pós-jogo.
4. **Depois do Apito:** produzir a crônica de Miguel Sampaio após a partida, respeitando integralmente a identidade, a voz, o método e os limites definidos em [[Depois do Apito]]. A crônica deve ter leitura autoral e literária, não funcionar como notícia nem como análise tática.
5. **Raio-X Tático:** produzir a análise estritamente tática da partida, examinando estruturas, comportamentos, funções, ajustes e decisões técnicas com base em evidências do jogo. Não misturar com avaliação jornalística geral ou crônica.

**b) Todas as demais categorias e modalidades esportivas**

Esta categoria inclui expressamente o **futebol masculino de base**, como Sub-20, Sub-17 e demais equipes de formação. Portanto, essas equipes seguem o fluxo de pós-jogo previsto para as outras modalidades, e não a sequência especial destinada ao futebol masculino profissional da equipe principal.
- **Pós-jogo:** produzir após o término do evento, quando já houver informações confiáveis e suficientes para construir uma matéria consistente. Não é necessário replicar a sequência de conteúdos prevista para o futebol masculino.

### Regras de execução
- **Onde Assistir exige transmissão confirmada:** sem confirmação oficial de transmissão, não produzir a matéria; avisar o editor e aguardar a confirmação.
- A sequência define a programação padrão; horários podem ser ajustados pela duração do evento e pela disponibilidade real de informações.
- O pós-jogo inicial não deve esperar a apuração aprofundada, mas também não pode preencher lacunas com suposições.
- A análise jornalística deve aguardar material suficiente e acrescentar interpretação; não reescrever o pós-jogo.
- O Raio-X Tático e Depois do Apito têm escopos próprios e devem seguir seus documentos de formato.
- Se não houver informação confiável suficiente, adiar a publicação em vez de especular.
