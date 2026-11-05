# Pantanal em Decisão — jogo científico online

**Jogo digital para professores de Biologia — PROFBIO / Ecologia Viva.**

**Jogar:** https://pantanal-em-decisao-ecologia.onrender.com

## Como jogar em sala (4 equipes, 20 professores)

1. No computador do mediador, abra o site e clique em **Abrir sala para quatro equipes**.
2. Projete o **código de seis caracteres** ou compartilhe o link gerado pelo site.
3. Cada equipe abre o endereço em um celular/notebook e escolhe um território: **Cabeceiras, Norte, Central ou Sul**. Cinco professores discutem ao redor do dispositivo.
4. O mediador inicia a partida e conduz as fases: **expansão econômica → seca prolongada → incêndios → negociação → avaliação final**.
5. Cada equipe registra suas decisões com justificativa científica. A negociação final exige **três votos coincidentes** e créditos remanescentes suficientes.
6. O mediador pode **exportar o relatório JSON** da partida.

**Plano B:** o botão **Experimentar no mesmo computador** permite registrar manualmente as decisões das quatro equipes, sem depender de conexões entre aparelhos.

## Conexão online

O site é estático, hospedado no Render e mantido no repositório GitHub `ernandes-sobreira/ecologia`. A sincronização da sala utiliza WebRTC por meio do serviço público de sinalização PeerJS Cloud (componente gratuito de terceiros). **O computador do mediador precisa permanecer aberto e conectado**. Redes institucionais com restrições a WebRTC podem impedir a conexão entre dispositivos; nesse caso, use o modo local. Não há contas de alunos nem servidor próprio de banco de dados.

## Metodologia científica e limites

O jogo é um **cenário fictício de ensino**, inspirado em processos documentados na Bacia do Alto Paraguai. Os índices internos (0–100), custos de créditos e efeitos entre setores são **didáticos, não observações, estimativas validadas nem previsões quantitativas**. A conexão entre territórios representa mecanismos condicionais, não uma rede hidrológica modelada. O jogo não atribui automaticamente a seca ao desmatamento, nem apresenta o fogo como fenômeno ecologicamente uniforme.

- Caballero et al. (2025). *Decadal hydroclimatic changes in the Pantanal*. Scientific Reports: https://www.nature.com/articles/s41598-025-01980-6
- Barros-Rosa et al. (2026). *Climatic and Hydrological Changes Drive Contemporary Fire Regime Transitions in the World's Largest Wetland*. Global Change Biology: https://pmc.ncbi.nlm.nih.gov/articles/PMC13545500/

## Fotografias

Todas as imagens fotográficas são de arquivos reais da Wikimedia Commons; nomes de autores e licenças estão na aba **Fontes e créditos** do jogo. As fotos ilustram os ambientes, não delimitam os territórios funcionais.

- Filipefrazao — *Pantanal, Mato Grosso, Brasil* — CC BY-SA 3.0.
- Lucas Rocha Ribeiro — *Paisagem Pantanal* — CC BY-SA 4.0.
- Stoni111121 — *Southern Pantanal wetlands* — CC BY-SA 4.0.
- Marcella Montenegro — *Incêndios Florestais no Pantanal* — CC BY-SA 4.0.

O código-fonte do jogo não depende de backend ou de login. Para acessar o jogo online, use o endereço do Render no topo deste documento.