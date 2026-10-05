# 🌌 Acervo de Localização do Nasuverse (PT-BR)
### Legendas de Alta Fidelidade para *The Garden of Sinners* e *Fate/stay night [Unlimited Blade Works]*

---

## 📖 Sobre Este Projeto

O universo ficcional criado por **Kinoko Nasu** e pela **Type-Moon** é amplamente reconhecido por sua densidade filosófica, riqueza de diálogos e um sistema de magia minucioso e complexo. Quando o estúdio **ufotable** adaptou essas obras para a animação — começando com a revolucionária heptalogia de filmes de *The Garden of Sinners* em 2007 e culminando na série televisiva de *Fate/stay night [Unlimited Blade Works]* em 2014 —, elevou a narrativa visual a um patamar cinematográfico raramente visto na indústria.

No entanto, para o público de língua portuguesa, a experiência muitas vezes foi comprometida. Durante anos, as versões disponíveis em português sofreram com:
- **Erros crassos de fansubs amadores da época da TV** (traduções literais que geraram termos bizarros como *"A Sabre"* e *"O Bárbaro"*).
- **Cortes de cenas estendidas de Blu-ray**, já que as legendas antigas foram feitas com base nas exibições televisivas, deixando cenas inteiras de 5 a 10 minutos sem tradução ou com dessincronias grosseiras.
- **Perda de vocativos essenciais** que definem as relações interpessoais (como a eliminação de *"Senpai"* e dos sufixos honoríficos japoneses).
- **Traduções robóticas e literais** das músicas de encerramento e abertura compostas por Yuki Kajiura e interpretadas pelo grupo Kalafina e por Aimer.

Este repositório é fruto de um trabalho artesanal e rigoroso de engenharia de legendagem e tradução literária, trazendo para a comunidade lusófona as **versões definitivas em português brasileiro** de duas das maiores obras do *Nasuverse*.

---

## 📦 Conteúdo do Acervo

O acervo contém **74 arquivos de legendas** (37 pares duplos), cobrindo integralmente as duas sagas:

### 1. The Garden of Sinners (*Kara no Kyoukai* / 空の境界) — Coleção Completa (10 Títulos)
* **Filme 1:** *Vista Panorâmica (Overlooking View / 俯瞰風景)* [2007]
* **Filme 2:** *Especulação de Assassinato — Parte 1 (A Study in Murder 1 / 殺人考察(前))* [2007]
* **Filme 3:** *Sentimento de Dor Remanescente (Remaining Sense of Pain / 痛覚残留)* [2008]
* **Filme 4:** *O Vazio (The Hollow Shrine / 伽藍の洞)* [2008]
* **Filme 5:** *Espiral do Paradoxo (Paradox Spiral / 矛盾螺旋)* [2008]
* **Filme 6:** *Registros do Esquecimento (Oblivion Recording / 忘却録音)* [2008]
* **Filme 7:** *Especulação de Assassinato — Parte 2 (A Study in Murder 2 / 殺人考察(後))* [2009]
* **Epílogo:** *The Garden of Sinners: Epílogo (Epilogue / 空の境界 終章)* [2010]
* **Filme 8:** *Recordando o Verão: Refrão Extra (Extra Chorus / 未来福音 extra chorus)* [2013]
* **Filme 9:** *Recordando o Verão (Future Gospel / 劇場版 空の境界 未来福音)* [2013]

> **Total em Kara no Kyoukai:** 10 filmes auditados, somando **7.433 eventos de fala**, placas e poemas líricos.

---

### 2. Fate/stay night [Unlimited Blade Works] (2014) — Série Completa (27 Episódios)
* **Especiais:**
  * **S00E01 — Prólogo (*Episode 00: Prologue*):** O clássico episódio duplo de 49 minutos narrado inteiramente sob a perspectiva de Rin Tohsaka.
  * **S00E02 — Sunny Day:** O epílogo alternativo oficial do jogo/Blu-ray onde Saber permanece no mundo moderno.
* **1ª Temporada (Episódios 01 a 12):**
  * Inclui os episódios estendidos de 47 e 48 minutos (Ep 01 e Ep 12) com todas as cenas restauradas de Kirei Kotomine, Gilgamesh e Caster.
* **2ª Temporada (Episódios 13 a 25):**
  * O clímax completo da Guerra do Santo Graal, o confronto filosófico entre Shirou e Archer, e o despertar do *Unlimited Blade Works*.

> **Total em Unlimited Blade Works:** 27 episódios, somando **8.927 falas e efeitos visuais**.

---

## 🛠️ Arquitetura das Legendas: O Padrão Duplo

Cada episódio e filme deste repositório é disponibilizado em duas versões complementares:

### 🎨 1. Legenda Master Estilizada (`.pt-BR.ass`)
Feita sob medida para reprodutores compatíveis com Advanced SubStation Alpha (como **Jellyfin no modo nativo, MPV, MPC-HC e VLC**):
* **Tipografia Original do Blu-ray:** Utiliza exatamente as **24 fontes tipográficas embutidas** nos contêineres MKV originais da ufotable (*Cronos Pro, Arno Pro, Georgia, Trebuchet MS, Constantia, EraserDust*).
* **Camadas Semióticas Visuais:** Diferenciação visual imediata entre diálogos normais, pensamentos/monólogos internos (em itálico refinado), memórias do passado (*flashbacks*), feitiços em alemão e placas em tela (*Signs* posicionadas com coordenadas exatas nos quadros da animação).
* **Músicas com Sincronia Silábica/Lírica:** As aberturas e encerramentos contam com estilos dedicados, mantendo a métrica e a tradução poética alinhada às estrofes musicais.

### 📺 2. Legenda Universal Higienizada (`.pt-BR.srt`)
Criada para garantir compatibilidade 100% livre de falhas em qualquer ambiente:
* **Sanitização de Código:** Remoção de tags complexas de posicionamento (`{\pos}`, `{\an}`, `{\fad}`), de quebras de linha duras do ASS (`\N`) e de sobreposições frame-a-frame de signos que costumam travar Smart TVs da Samsung (Tizen), LG (webOS), Roku e consoles de videogame.
* **Leveza e Reprodução sem Transcode:** Permite que servidores como Jellyfin e Plex transmitam o vídeo em *Direct Play*, sem consumo desnecessário de CPU/GPU do host para queima de legendas (*burn-in*).

---

## 🖋️ Técnicas de Tradução e Filosofia de Localização

A tradução deste acervo não foi tratada como um mero processo mecânico de conversão de palavras, mas como um trabalho de **localização literária contextualizada**:

### 1. Fidelidade Canônica ao Nasuverse
A terminologia mágica e filosófica foi rigorosamente uniformizada com os cânones oficiais da Type-Moon e das *Visual Novels*:
* **Classes de Servos:** Mantidos os nomes originais sagrados — *Saber*, *Archer*, *Lancer*, *Rider*, *Caster*, *Assassin*, *Berserker* e *Ruler*.
* **Conceitos de Taumaturgia:** *Guerra do Santo Graal, Espíritos Heroicos, Feitiços de Comando, Fantasma Nobre, Campo Delimitado, Projeção (Trace on), Reforço*.
* **Conceitos de Kara no Kyoukai:** *Olhos Místicos de Percepção da Morte, Origem, Garan no Dou (O Santuário Vazio), Tânato, Distorção Espacial, Conto de Fadas*.

### 2. Respeito aos Honoríficos e Vocativos Japoneses
Em animes de drama e mistério, a forma como um personagem se dirige ao outro carrega camadas profundas de hierarquia social, distanciamento emocional ou carinho velado:
* Sakura Matou chama Shirou de **"Senpai"** — restaurado o vocativo original, eliminando a antiga aberração de *"Veterano"* ou *"Calouro"*.
* Rin Tohsaka e Shirou Emiya tratam-se inicialmente por **"Tohsaka"** e **"Emiya-kun"**, marcando a distância formal entre colegas de classe que gradualmente se transforma em cumplicidade.
* Taiga Fujimura é carinhosamente chamada de **"Fujimura-sensei"** (ou Fuji-nee em momentos de descontração).

### 3. Adaptação Poética das Canções (Kalafina e Aimer)
Músicas de encerramento em obras da ufotable não são meros créditos; elas funcionam como o epílogo emocional de cada ato dramático. As canções foram adaptadas buscando a **ressonância lírica e a emoção pura em português brasileiro**:
* **The Garden of Sinners:** *Oblivious*, *Kimi ga Hikari ni Kaete Yuku*, *Kizuato*, *ARIA*, *Sprinter*, *Fairytale*, *Seventh Heaven*, *Snow is Falling* e a monumental *Alleluia*.
* **Fate/stay night [UBW]:** Aberturas *ideal white* (Mashiro Ayano) e *Brave Shine* (Aimer); encerramentos *Believe* e *Ring Your Bell* (Kalafina); canção de inserção *Last Stardust* (Aimer) durante o épico embate do Episódio 20.
* **Cântico de Unlimited Blade Works:** Preservada a mística clássica do encantamento em inglês estilizado intercalado com a voz interna em português (*"I am the bone of my sword / Steel is my body and fire is my blood..."*).

### 4. Restauração Histórica de Cenas Exclusivas de Blu-ray
As transmissões originais de TV no Japão cortaram minutos preciosos de episódios para encaixar nos blocos comerciais de 30 minutos. As edições Blu-ray Box da ufotable devolveram essas cenas. Este acervo localizou e reinseriu cada uma delas:
* **S01E02:** O monólogo interno e conserto da janela quebrada por Shirou usando taumaturgia alemã, e a conversa estendida entre Rin e Archer na sala de estar.
* **S01E10:** Consertado o descompasso histórico de 90 segundos que os fansubs tinham em relação ao áudio e abertura do episódio.
* **S01E12:** Todas as conversas estendidas entre Kirei Kotomine e Gilgamesh no porão da Igreja de Fuyuki, e os diálogos de Caster sobre o Graal.
* **S00E01 (Prólogo):** A cena completa de 49 minutos com todas as reflexões de Rin Tohsaka na véspera do ritual de invocação.

---

## 🚀 Como Utilizar

### Estrutura de Pastas Sugerida:
Para que o seu media player ou servidor (Jellyfin / Plex / Emby / Kodi) reconheça automaticamente as legendas com idioma e prioridade corretos, basta manter a legenda na mesma pasta do arquivo de vídeo com o mesmo nome base:

```text
📁 Series/Fate+Stay Night - Unlimited Blade Works (2014)/
   ├── Fate+Stay Night - Unlimited Blade Works - S01E01 - A Winter Day.mkv
   ├── Fate+Stay Night - Unlimited Blade Works - S01E01 - A Winter Day.pt-BR.ass
   └── Fate+Stay Night - Unlimited Blade Works - S01E01 - A Winter Day.pt-BR.srt
```

### Configurações Recomendadas no Player:
* **No Jellyfin / Emby:** Configure seu usuário com idioma de legenda preferido em `Portuguese (Brazil)`. O Jellyfin selecionará nativamente o arquivo `.pt-BR.ass` externo estilizado.
* **No VLC / MPV:** O arquivo `.ass` carregará automaticamente todas as fontes e estilos tipográficos originais embutidos no contêiner do vídeo.

---

## 📜 Créditos e Preservação

* **Obra Original:** Kinoko Nasu & Takashi Takeuchi (*Type-Moon*)
* **Produção e Animação:** *ufotable*
* **Trilhas Sonoras:** Yuki Kajiura & Hideyuki Fukasawa
* **Engenharia de Legendagem e Localização:** Feito artesanalmente com rigor técnico e respeito absoluto à lore para preservação cultural do acervo.

> *"I am the bone of my sword..."* — Que você aproveite a melhor experiência possível ao mergulhar nos mistérios do Santo Graal e do Vazio.
