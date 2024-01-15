---
title: Енергоспоживання Ethereum
description: Основна інформація, необхідна для розуміння енергоспоживання Ethereum.
lang: uk
---

# Енергетичні витрати Ethereum {#proof-of-stake-energy}

Ethereum — це зелений блокчейн. Механізм консенсусу Ethereum [доказу частки](/developers/docs/consensus-mechanisms/pos) використовує ETH замість [енергії для захисту мережі](/developers/docs/consensus-mechanisms/pow). Споживання енергії Ethereum становить приблизно [~0,0026 ТВт∙год/рік](https://carbon-ratings.com/eth-report-2022) по всій глобальній мережі.

Оцінка споживання енергії для Ethereum надходить від дослідження [Інституту CCRI (Crypto Carbon Ratings Institute)](https://carbon-ratings.com). Вони створили висхідні оцінки споживання електроенергії та вуглецевого сліду мережі Ethereum ([див. звіт](https://carbon-ratings.com/eth-report-2022)). Вони вимірювали споживання електроенергії різними вузлами з різними конфігураціями апаратного та клієнтського програмного забезпечення. Оцінене річне споживання електроенергії мережею в розмірі **2601 МВт∙год** (0,0026 ТВт∙год) відповідає річним викидам вуглецю в обсязі **870 тонн CO2e** із застосуванням регіональних коефіцієнтів вуглецевої інтенсивності. Це значення змінюється залежно від того, як вузли входять і виходять із мережі. Ви можете відстежувати це за допомогою ковзної 7-денної середньої оцінки за допомогою [індексу стійкості мережі Cambridge Blockchain](https://ccaf.io/cbnsi/ethereum) (зауважте, що вони використовують дещо інший метод для своїх оцінок; деталі доступні на їхньому сайті).

Щоб зрозуміти контекст енергоспоживання Ethereum, ми можемо порівняти річні оцінки для деяких інших галузей. Це допомагає нам краще зрозуміти, чи є оцінка Ethereum високою або низькою.

<EnergyConsumptionChart />

На діаграмі вище показано розрахункове річне споживання енергії в ТВт∙год/рік для Ethereum у порівнянні з деякими іншими галузями промисловості. Наведені оцінки ґрунтуються на загальнодоступній інформації, доступ до якої був отриманий у травні 2023 року, а посилання на джерела наведені в таблиці нижче.

|                                | Річне споживання енергії (ТВт∙год) | у порівнянні з PoS Ethereum | Джерело                                                                                                                                                                            |
| :----------------------------- | :--------------------------------: | :-------------------------: | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Глобальні центри обробки даних |                200                 |           77 000х           | [джерело](https://www.iea.org/commentaries/data-centres-and-energy-from-global-headlines-to-local-headaches)                                                                       |
| Золотодобування                |                131                 |           50 000х           | [джерело](https://ccaf.io/cbnsi/cbeci/comparisons)                                                                                                                                 |
| Bitcoin                        |                131                 |           50 000х           | [джерело](https://ccaf.io/cbnsi/cbeci/comparisons)                                                                                                                                 |
| PoW Ethereum                   |                 78                 |           30 000х           | [джерело](https://digiconomist.net/ethereum-energy-consumption)                                                                                                                    |
| YouTube (безпосередньо)        |                 12                 |            4600х            | [джерело](https://www.gstatic.com/gumdrop/sustainability/google-2020-environmental-report.pdf)                                                                                     |
| Ігри в США                     |                 34                 |           13 000х           | [джерело](https://www.researchgate.net/publication/336909520_Toward_Greener_Gaming_Estimating_National_Energy_Use_and_Energy_Efficiency_Potential)                                 |
| Netflix                        |               0,451                |            173х             | [джерело](https://assets.ctfassets.net/4cd45et68cgf/7B2bKCqkXDfHLadrjrNWD8/e44583e5b288bdf61e8bf3d7f8562884/2021_US_EN_Netflix_EnvironmentalSocialGovernanceReport-2021_Final.pdf) |
| PayPal                         |                0,26                |            100х             | [джерело](https://app.impaakt.com/analyses/paypal-consumed-264100-mwh-of-energy-in-2020-24-from-non-renewable-sources-27261)                                                       |
| AirBnB                         |                0,02                |             8х              | [джерело](<https://s26.q4cdn.com/656283129/files/doc_downloads/governance_doc_updated/Airbnb-ESG-Factsheet-(Final).pdf>)                                                           |
| PoS Ethereum                   |               0,0026               |             1x              | [джерело](https://carbon-ratings.com/eth-report-2022)                                                                                                                              |

Складно отримати точні оцінки енергоспоживання, особливо коли об’єкт вимірювання має складний ланцюжок постачання або деталі розгортання, які впливають на його ефективність. Розгляньмо Netflix або YouTube як приклади. Оцінки їх енергоспоживання різняться залежно від того, чи враховують вони лише енергію, яка використовується для обслуговування систем і надання контенту користувачам (_прямі витрати_), чи охоплюють вони витрати, необхідні для виробництва контенту, утримання корпоративних офісів, реклами тощо (_непрямі витрати_). Непряме використання може також враховувати енергію, необхідну для споживання контенту на пристроях кінцевих користувачів, як-от телевізори, комп’ютери та мобільні телефони, що, своєю чергою, залежить від того, які саме пристрої використовуються.

Це питання обговорюється на [Carbon Brief](https://www.carbonbrief.org/factcheck-what-is-the-carbon-footprint-of-streaming-video-on-netflix). У таблиці вище значення, вказане для Netflix, враховує їх _пряме_ та _непряме_ використання, про яке вони самі повідомили. YouTube надає лише оцінку власних _прямих_ енергетичних витрат, які становлять близько [12 ТВт∙год/рік](https://www.gstatic.com/gumdrop/sustainability/google-2020-environmental-report.pdf).

Наведені вище таблиця та графік також містять порівняння з Bitcoin і Ethereum за моделлю доказу роботи. Важливо зазначити, що енергоспоживання мереж із доказом роботи не є статичним і змінюється з кожним днем. Значення, яке використовувалося для доказу роботи Ethereum, було з моменту безпосередньо перед [злиттям](/roadmap/merge/) до доказу частки, як і передбачали в [Digiconomist](https://digiconomist.net/ethereum-energy-consumption). Інші джерела, як-от [індекс стійкості мережі Cambridge Blockchain](https://ccaf.io/cbnsi/ethereum/1), оцінюють споживання енергії набагато нижче (ближче до 20 ТВт∙год/рік). Оцінки енергоспоживання Bitcoin також широко варіюються в різних джерелах, і ця тема викликає багато нюансів для [дебатів](https://www.coindesk.com/business/2020/05/19/the-last-word-on-bitcoins-energy-consumption/) не тільки щодо обсягу спожитої енергії, але й щодо джерел цієї енергії та пов’язаної з цим етики. Енергоспоживання необов’язково точно відображає вплив на навколишнє середовище, оскільки різні проєкти можуть використовувати різні джерела енергії, наприклад меншу або більшу частку відновлюваних джерел. Наприклад, [індекс стійкості мережі Cambridge Blockchain](https://ccaf.io/cbnsi/cbeci/comparisons) вказує на те, що попит на мережу Bitcoin теоретично може забезпечуватися завдяки спалюванню газу або електроенергії, яка інакше була б втрачена під час передавання та розподілення. Шлях Ethereum до сталого розвитку полягав у заміні енергомісткої частини мережі на екологічно чисту альтернативу.

Ви можете переглянути оцінки енергоспоживання та викидів вуглецю для багатьох галузей промисловості на сайті [індексу стійкості мережі Cambridge Blockchain](https://ccaf.io/cbnsi/ethereum).

## Оцінки за кожну транзакцію {#per-transaction-estimates}

У багатьох статтях оцінюються енерговитрати блокчейнів «за транзакцію». Це може вводити в оману, оскільки енергія, необхідна для створення та підтвердження блоку, не залежить від кількості транзакцій у ньому. Одиниця витрат енергії за транзакцію передбачає, що менша кількість транзакцій призведе до менших витрат енергії та навпаки, але це не так. Також оцінки за транзакцію дуже чутливі до того, як визначається пропускна здатність блокчейну, і зміною цього визначення можна маніпулювати, щоб значення здавалося більшим або меншим.

Наприклад, в Ethereum пропускна здатність транзакцій — це не тільки пропускна здатність базового шару, але й сума пропускної здатності всіх його зведень «[шару 2](/layer-2/)». Шар 2 зазвичай не додається в розрахунки, але врахування додаткової енергії, яку споживають секвенсори (малі), і кількості транзакцій, які вони обробляють (великі), імовірно, різко знизить оцінку за транзакцію. Це одна з причин, чому порівняння енергоспоживання за одну транзакцію між платформами може вводити в оману.

## Вуглецевий борг Ethereum {#carbon-debt}

Енерговитрати Ethereum дуже низькі, але так було не завжди. Спочатку в Ethereum використовувався механізм доказу роботи, який мав набагато більші екологічні витрати, ніж поточний механізм доказу частки.

З самого початку в Ethereum планували запровадити механізм консенсусу на основі доказу частки, але для того щоб зробити це без шкоди для безпеки та децентралізації, знадобилися роки цілеспрямованих досліджень і розробок. Тому для запуску мережі було використано механізм доказу роботи. Механізм доказу роботи вимагає, щоб майнери використовували власне обчислювальне обладнання для розрахунку вартості, витрачаючи при цьому енергію.

![Порівняння енергоспоживання Ethereum до та після злиття за допомогою Ейфелевої вежі (330 метрів заввишки) зліва, яка символізує високе енергоспоживання до злиття, і маленької фігурки Lego заввишки 4 см справа, яка відображає різке скорочення енергоспоживання після злиття.](energy_consumption_pre_post_merge.png)

За оцінками CCRI злиття скоротило річне споживання електроенергії Ethereum більш ніж на **99,988 %**. Аналогічно, вуглецевий слід Ethereum зменшився приблизно на **99,992 %** (з 11 016 000 до 870 тонн CO2e). Якщо уявити це в перспективі, то скорочення викидів можна порівняти зі зниженням від висоти Ейфелевої вежі до маленької пластмасової іграшкової фігурки, як показано на малюнку вище. У підсумку, екологічні витрати на захист мережі різко знижуються. Водночас вважається, що безпека мережі покращилася.

## Зелений рівень застосування {#green-applications}

Попри те, що споживання енергії Ethereum дуже низьке, у мережі Ethereum будується значна, дедалі більша й дуже активна спільнота [**регенеративних фінансів (ReFi)**](/refi/). Додатки ReFi використовують компоненти DeFi для створення фінансових додатків, які мають позитивні зовнішні ефекти, що сприяють збереженню навколишнього середовища. ReFi є частиною ширшого руху під назвою [соларпанк](https://en.wikipedia.org/wiki/Solarpunk), який тісно пов’язаний з Ethereum і має на меті поєднати технологічний прогрес і турботу про навколишнє середовище. Децентралізована, бездозвільна та компілятивна природа Ethereum робить цю платформу ідеальним базовим шаром для спільнот ReFi і соларпанк.

Платформи фінансування суспільних благ Web3, як-от [Gitcoin](https://gitcoin.co), проводять кліматичні раунди, щоб стимулювати екологічно свідому розробку на прикладному рівні Ethereum. Завдяки розвитку цих ініціатив (та інших, наприклад [DeSci](/desci/)), Ethereum стає екологічно та соціально позитивною мережевою технологією.

<InfoBanner emoji=":evergreen_tree:">
  Якщо ви вважаєте, що ця сторінка може бути точнішою, поставте питання або повідомте про це. Статистичні дані на цій сторінці являють собою оцінки, засновані на загальнодоступних даних; вони не є офіційною заявою чи обіцянкою команди ethereum.org або Ethereum Foundation.
</InfoBanner>

## Довідкові джерела {#further-reading}

- [Індекс стійкості мережі Cambridge Blockchain](https://ccaf.io/cbnsi/ethereum)
- [Звіт Білого дому про блокчейни з доказом роботи](https://www.whitehouse.gov/wp-content/uploads/2022/09/09-2022-Crypto-Assets-and-Climate-Report.pdf)
- [Викиди Ethereum: висхідна оцінка](https://kylemcdonald.github.io/ethereum-emissions/), _Кайл Макдональд_
- [Індекс енергоспоживання Ethereum](https://digiconomist.net/ethereum-energy-consumption/), _Digiconomist_
- [ETHMerge.com](https://ethmerge.com/), _[@InsideTheSim](https://twitter.com/InsideTheSim)_
- [Злиття: вплив на споживання електроенергії та вуглецевий слід мережі Ethereum](https://carbon-ratings.com/eth-report-2022), _CCRI_
- [Енергоспоживання Ethereum](https://mirror.xyz/jmcook.eth/ODpCLtO4Kq7SCVFbU4He8o8kXs418ZZDTj0lpYlZkR8)

## Пов'язані теми {#related-topics}

- [Бачення Ethereum](/roadmap/vision/)
- [Beacon Chain](/roadmap/beacon-chain)
- [The Merge](/roadmap/merge/)