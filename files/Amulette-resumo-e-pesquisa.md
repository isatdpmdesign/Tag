# Amulette — Resumo do Projeto e Pesquisa de Mercado

> Documento de trabalho · Confidencial · Uso interno da Isadora
> Objetivo: consolidar o conceito, a pesquisa de concorrentes e os próximos passos para começar a validar a ideia.

---

## 1. O conceito

Uma **joia de segurança pessoal** — colar, pulseira, brinco ou anel — que funciona como localizador e botão de socorro, **sem parecer um dispositivo de rastreamento**. Para quem olha de fora (inclusive um agressor), é só uma joia bonita.

Como funciona a intenção:

- O responsável (pai, mãe, parceiro) consegue ver a **localização em tempo real** de quem usa.
- Em uma emergência, a pessoa aciona um **gatilho discreto** (ex.: três toques, um gesto ou uma palavra-chave configurável no app) e uma **notificação de socorro + localização** é enviada ao responsável.

**Público-alvo:** crianças e adolescentes, e também **adultos — com foco em mulheres em situação de vulnerabilidade**. Modelos masculinos e femininos.

**Diferencial pretendido:** um dispositivo **autônomo**, que não dependa do celular (já que o celular pode ser roubado, quebrado ou desligado), somado ao **olhar de designer** da Isadora para transformar isso em joia desejável.

---

## 2. O que já existe no mercado

### Fora do Brasil
- **invisaWear** (EUA) — o player mais consolidado. Colares, pulseiras e chaveiros que parecem joias comuns, com botão escondido. Um clique duplo dispara localização por GPS para até 5 contatos de emergência (e, opcionalmente, autoridades).
- **ResQ Jewelry, Street Smart Women** e similares — mesma pegada de "joia com botão de pânico".

**Ponto-chave:** quase todos **dependem do celular**. A joia é apenas um botão Bluetooth; quem faz o trabalho pesado (GPS, internet, envio) é o app no telefone.

### No Brasil
- O que existe é mais **básico**: botões de pânico tradicionais, sem o disfarce de joia bonita.
- Os dispositivos usados pela Justiça (medida protetiva) são aparelhos **óbvios e sem apelo de design**.
- **Nenhum concorrente encontrado** ocupando o conceito exato: joia de segurança + tecnologia + design desejável no mercado brasileiro. **Esse espaço está livre.**

---

## 3. Como a tecnologia funciona (e o custo de cada caminho)

### Caminho A — Depende do celular (barato) ✅ recomendado para começar
- A joia é só um **botão Bluetooth** simples (como o de uma chave de carro).
- Alcance de ~9–10 metros do celular.
- O **app** usa o GPS e a internet do próprio telefone para disparar o socorro.
- **Fabricação barata**, porque a "inteligência" está no app. Já existem botões Bluetooth prontos e baratos no mercado.

### Caminho B — Autônomo (caro) 💭 versão dos sonhos
Para não depender do celular, o dispositivo precisaria embutir:
- Chip de **GPS** (localização),
- Chip de **conexão celular / mini-SIM** (envio sozinho pela rede),
- **Bateria** para alimentar tudo.

É, na prática, um mini-celular disfarçado de joia. Tecnicamente possível (é o que fazem coleiras de pet e relógios infantis com chip), mas:
- **Bateria** é o grande obstáculo: GPS + dados ligados o tempo todo consomem muito. Numa joia pequena, a carga dura pouco — e ninguém quer carregar um anel toda noite.
- **Não é só um produto, é um serviço**: cada aparelho precisa de plano de dados, servidores, app e possivelmente uma central de emergência. Vira um negócio de **mensalidade**, não de venda única.

### A regra de ouro: BEACON não é rastreador ⚠️
Essa é a conclusão mais importante da pesquisa — evita gastar dinheiro no caminho errado.

**Rastreamento em tempo real, em qualquer lugar, só existe com GPS + chip de celular (rede móvel) dentro do dispositivo.** Ponto. Não há etiqueta fininha nem beacon barato que resolva isso — se resolvesse, os concorrentes já teriam feito. É a física do problema.

### O que NÃO serve (e por quê)
- **RFID:** curtíssimo alcance, precisa de leitor colado. **Não tem localização em tempo real.** Fora.
- **AirTag (Apple):** não tem chip próprio — usa a rede de iPhones ao redor. Sozinha, num lugar isolado, é cega. Não serve para emergência real. (Ainda assim é "melhor" que um beacon genérico, porque a Apple tem uma rede mundial de "ouvintes".)
- **Beacon BLE / etiqueta BLE** (ex.: KKM C6, C2, e a maioria dos beacons baratos): o beacon **não sabe onde ele está**. Ele só fica "gritando" um número por Bluetooth (alcance ~80 m em espaço aberto). Alguém precisa estar bem perto, com um app leitor, para "ouvir". Serve para rastrear caixas num galpão com leitores fixos — **não** para uma pessoa andando pela cidade, onde não há ninguém para ouvir. É a mesma limitação da AirTag, mas **sem** a rede mundial por trás. Fora, para o caso real de emergência.

### O que serve de verdade
- **GPS + chip LTE (rede móvel)** dentro do aparelho: é a tecnologia das tornozeleiras de monitoramento e dos rastreadores "LTE". Resolve o caso real — mas traz de volta tamanho, bateria e **mensalidade do chip de dados**.
- **Botão Bluetooth + celular da própria pessoa** (modelo Flic): barato e ótimo para validar, mas depende do celular estar com a pessoa e ligado.

---

## 4. Avaliação honesta

**O que é força real:**
- O **design** e a **marca** — é aqui que a Isadora ganha de quem já existe.
- O ângulo emocional: proteger quem se ama. Tem alma.
- O espaço no Brasil para "joia de segurança desejável" está aberto.

**O que precisa de pé no chão:**
- A ideia de joia de segurança **não é inédita** (invisaWear e outros já existem).
- A versão **autônoma** é a parte mais difícil e cara — esbarra na **física da bateria**, não na criatividade.
- Executada por completo, isso é uma **empresa de hardware + telecom** (fábrica, chip de dados, servidor, regulação), que exige capital alto e sócio técnico.

**Conclusão:** a versão autônoma fica guardada como sonho. A versão **viável hoje** é a que usa o celular + a identidade de design da Isadora.

---

## 5. Próximos passos (do menor custo ao maior)

1. **Registrar o nome da marca** no **INPI** (barato e importante). Ideia não se registra; marca sim.
   - Antes, conferir na busca do INPI (e no Google/Instagram) se **"Amulette"** está livre no ramo.
2. **Validar o interesse sem fabricar nada:**
   - Criar desenhos das joias + uma **página de apresentação** ("em breve" / pré-lançamento).
   - Mostrar ao público e medir interesse real (inclusive testar **pré-venda/reserva**).
   - Se ninguém se interessa, você economizou uma fortuna. Se se interessam, tem prova para avançar.
3. **Protótipo baratinho:**
   - Comprar um **botão Bluetooth pronto**.
   - Fazer a "casca" da joia em **resina, em casa** (molde de silicone, embutindo o botão), para testar visual e encaixe.
4. **Só depois** pensar em investir em produção.

**Como divulgar sem entregar o ouro:** mostre o **benefício** (a joia que pede socorro com sua localização) e a emoção. **Nunca** mostre o *como* técnico (qual chip, qual botão, como monta por dentro). Ninguém copia o que não vê.

> Lembrete: a maior proteção não é o segredo da ideia — é **execução, marca e design**, e sair na frente fazendo.

---

## 5.1 Patentes e "white label" — posso usar a tecnologia? ⚖️

> Resumo jurídico de orientação — **não é aconselhamento legal**. Antes de investir, consultar um advogado/agente de propriedade industrial (muitos fazem a 1ª conversa de graça).

A resposta tem três camadas:

**1. A tecnologia de base é livre.** Bluetooth de baixa energia (BLE), GPS pelo celular e app que envia SMS são padrão da indústria, de domínio comum. Ninguém é dono disso. A própria invisaWear compra os chips de fornecedores (ex.: Silicon Labs). Você pode montar e vender no Brasil usando essa base sem dever nada a eles.

**2. As patentes deles são específicas — e só é preciso não copiar aquilo.** As "8 patentes" da invisaWear não cobrem "joia de segurança". Cobrem um método técnico particular: como o aparelho fica em estado de baixíssima energia ("dormindo") e, ao ser apertado, "acorda" e dispara o sinal — ou seja, a **solução deles para o problema da bateria** (uma patente se chama literalmente "técnicas de gestão de energia para aumentar a vida da bateria"). Usando um botão pronto (tipo Flic) ou um módulo de fornecedor, você usa a solução *daquele fabricante*, não a patente deles.

**3. Patente é territorial.** Uma patente registrada nos EUA **só vale nos EUA**. Para bloquear alguém no Brasil, teriam que ter registrado a mesma patente **no INPI brasileiro** — o que a maioria das startups desse porte não faz (é caro por país). Provavelmente o caminho está livre aqui, mas **confirmar com busca no INPI**.

### Respostas diretas
- **Eles patentearam a tecnologia?** Só uma parte bem específica (economia de bateria), e provavelmente só nos EUA. A base, não.
- **Posso montar em casa e vender?** A **montagem**, sim: comprar módulos prontos, embutir na joia de resina, criar marca e app. Isso é um produto **"white label"** (marca própria sobre tecnologia de terceiros) — legal e comum. O que **não** se faz em casa é fabricar a eletrônica; ela vem pronta do fornecedor.
- **Consigo comprar a tecnologia?** Sim. Fabricantes (muitos na China — KKM, Honeycomm etc.) vendem o "miolo" pronto (botão BLE ou módulo GPS) para você colocar sua marca. É assim que quase toda marca pequena de eletrônico começa.

**O que fica só seu (e é onde está o valor):** o **design da joia**, a **marca Amulette**, a **experiência do app** e a **história**. A tecnologia é commodity, igual para todos — ganha quem embala melhor.

---

## 6. A marca

**Nome escolhido: Amulette** (versão afrancesada de "amuleto").

- Vem do latim *amuletum* — objeto que protege. Já carrega **proteção** na origem.
- Som internacional, com charme, e **não parece batido** no Brasil (a palavra "amuleto" sozinha é muito usada por joalherias como Vivara e Monte Carlo — por isso a versão "Amulette" diferencia).
- **A confirmar:** busca no INPI para garantir que está livre para registro.

Referências de significado exploradas: *amor* (latim: amor), *proteger* (latim: tueri → tutela), *custódia* (guarda/proteção), *égide* (grego: escudo de proteção).

---

## 7. Arquitetura final da Amulette (conceito definitivo) ✅

Depois de descartar o que não funciona, chegamos ao conceito que junta tudo. Existem **duas versões**, lançadas em ordem:

### Versão 1 — Amulette Bluetooth (faz agora, na bancada)
- Módulo **BLE** pequeno e leve (tipo Flic), embutido na joia de resina.
- **Depende do celular** da própria pessoa para enviar SOS + localização.
- Sem recarga (bateria de anos), fina e delicada — cabe até em peças pequenas.
- Serve para **validar a marca**, gerar caixa e provar demanda.

### Versão 2 — Amulette 4G autônoma (a "dos sonhos", fase futura)
Funciona **sozinha, sem celular por perto** — é a ideia original. Como cada peça se resolve:
- **Onde fica:** num **relicário** (pingente/pulseira de tamanho médio que abre ou tem compartimento) — NÃO numa joia miúda, e NÃO afogado em resina maciça. A resina/design ficam na **casca**; a tecnologia num **compartimento**.
- **Localização:** chip **GPS** próprio (tamanho de uma unha) — acha a posição sozinho.
- **Envio:** modem **4G** próprio + SIM/eSIM — manda a localização pela rede de telefonia sozinho, sem celular. (Existem módulos combinados GPS+4G de 1–2 cm.)
- **Antena:** vem junto no módulo; só precisa "respirar" (compartimento com ar / resina fina), nunca selada em metal ou resina densa.
- **Bateria:** recarregável pequena, ao lado do módulo. Dura dias (não anos).
- **Recarga:** por **indução** (sem fio) — apoia o pingente fechado num dock, a energia atravessa a resina. Sem buraco, sem tampa aparente, joia lisa por fora. (Alternativa mais simples: dois contatos magnéticos atrás.)
- **Truque de bateria:** manda a posição periodicamente (ex.: a cada 10–30 min) e vira **tempo real só quando o SOS é acionado** — assim a bateria/módulo ficam menores.
- **Custos inerentes:** SIM + **plano de dados mensal** (a mensalidade = o negócio recorrente) e **homologação Anatel** para vender em escala.

**Sistema "núcleo + casca" (o diferencial de negócio):** um núcleo de tecnologia recarregável que **encaixa/desencaixa** de várias cascas resinadas (colar hoje, pulseira amanhã). Vende-se um núcleo e várias cascas com seus designs → receita recorrente + o design no centro.

> A verdade que fecha tudo: o **chip nunca foi o problema** — GPS e modem cabem. O muro é a **bateria** (não encolhe, precisa recarregar). Por isso a v1 é Bluetooth (empurra o gasto de energia pro celular) e a v2 é 4G com bateria recarregável e carcaça pensada. Não é sonho vs. realidade — é a **ordem** em que vêm.

---

## 8. Fabricação — quem faz o quê

### A casca (joia) — você faz
- **Molde impresso em 3D** + fundição. Você imprime o molde/modelo-mestre, não a peça final.
- **Resina:** ótima para protótipo e para a versão Bluetooth. Escolher resina **tough/resistente** (não a comum, que amarela e trinca).
- **Metal inox (fundição por cera perdida):** mais durável e premium — é o que os concorrentes usam (aço inox). Caminho: imprime o mestre em 3D → molde → funde o metal. Excelente para o produto final.

### ⚠️ Armadilha do metal (importante para a versão 4G)
Metal **bloqueia sinal de rádio e recarga por indução** (efeito "gaiola de Faraday"). Então:
- Para a versão **Bluetooth** simples: metal maciço até funciona (BLE é mais tolerante, e é o que a invisaWear faz).
- Para a versão **4G + indução**: **não pode** ser metal maciço em volta da antena e da bobina de recarga. Precisa de uma **"janela" não-metálica** (resina, cerâmica ou vidro) sobre a parte da antena/carga. Solução real: peça **híbrida** — corpo de metal + seção de resina/vidro onde ficam antena e bobina.

### O núcleo (tecnologia) — fábrica ODM
- Empresa **ODM** (há no Alibaba) projeta e monta o núcleo sob medida (GPS+4G, bateria, indução, tamanho de encaixe).
- Envolve conversa, projeto, MOQ maior e investimento. É a **fase 2**, com dinheiro em mãos.

### Conexão (o "chip")
- O **módulo 4G** (hardware) vem com o núcleo, da fábrica.
- A **linha de dados** é escolha sua: **chip físico** (SIM) é mais fácil para testar, mas exige slot (ruim para joia lacrada); **eSIM** é soldado, sem slot — **ideal para joia selada com indução**, mais elegante, porém mais burocrático de configurar.
- **O cliente NUNCA coloca o chip.** Você entrega já conectado (eSIM embutido) e **cobra a mensalidade** — essa é a receita recorrente do negócio.

### Homologação Anatel (o que é)
- A **Anatel** é o órgão que regula telecomunicações no Brasil (equivalente à FCC dos EUA).
- Toda coisa que **transmite rádio** (Bluetooth, Wi-Fi, 4G) e é **vendida** no Brasil precisa ser **homologada** — é exigência legal para comercializar, garante que o aparelho não interfere nas redes.
- Envolve teste em laboratório credenciado + papelada + taxa. A fábrica ODM costuma ajudar; às vezes o módulo já tem parte da certificação.
- **Para protótipo e uso próprio, não precisa.** Só para **vender em escala**. É custo de fase de lançamento, não agora.

---

*Documento gerado a partir da conversa de brainstorm. Próxima etapa sugerida: esboçar a página de apresentação e os primeiros desenhos das joias.*
