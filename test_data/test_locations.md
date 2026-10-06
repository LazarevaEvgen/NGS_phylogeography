***`1. Загрузка FASTA-файла для теста устранения избыточности`***
[`Файл с тестовой выборкой для прореживания тут`](https://github.com/LazarevaEvgen/influenza_phylogeography/blob/main/test_data/HA_test_2021_2024.fa)

Загрузите файл и запустите алгоритм прореживания в соответствующей ячейке:

<img width="1198" height="409" alt="image" src="https://github.com/user-attachments/assets/68e2b77a-30cd-4403-9e44-51ccc734aefd" />

***`2. Список реассортантов с NA от низкопатогенного субтипа (генотип D1), относящихся к генетической линии G2d по гену гемагглютинина`***

📝**Скопируйте следующий список лейблов в соответствующую ячейку:**

*КОгда будете выводить список локаций на карту проверьте корректность геокодинга (например, локацию "SK" лучше обозначить как "Saskatchewan Canada").*

<img width="1200" height="178" alt="image" src="https://github.com/user-attachments/assets/e8f3ac7a-1a8e-4a6d-a09f-46c996b4ed1e" />

A/chicken/Pennsylvania/00304-005/2026 | A / H5N1 | NA | 2026-01-06 | EPI ISL 20377862 | 2.3.4.4b |
A/black vulture/Tennessee/00826-002/2026 | A / H5N1 | NA | 2026-01-01 | EPI ISL 20391569 | 2.3.4.4b |
A/mallard duck/Maine/00405-001/2026 | A / H5N1 | NA | 2026-01-05 | EPI ISL 20383471 | 2.3.4.4b |
A/canada goose/New York/01437-002/2026 | A / H5N1 | NA | 2026-01-20 | EPI ISL 20398118 | 2.3.4.4b |
A/black vulture/Alabama/00463-001/2026 | A / H5N1 | NA | 2026-01-05 | EPI ISL 20391567 | 2.3.4.4b |
A/canada goose/Wisconsin/01189-003/2026 | A / H5N1 | NA | 2026-01-07 | EPI ISL 20398126 | 2.3.4.4b |
A/american wigeon/North Carolina/00573-002/2026 | A / H5N1 | NA | 2026-01-03 | EPI ISL 20383500 | 2.3.4.4b |
A/domestic duck/Indiana/01283-001/2026 | A / H5N1 | NA | 2026-01-21 | EPI ISL 20391597 | 2.3.4.4b |
A/canada goose/California/01186-001/2026 | A / H5N1 | NA | 2026-01-09 | EPI ISL 20398102 | 2.3.4.4b |
A/turkey vulture/Alabama/01311-001/2026 | A / H5N1 | NA | 2026-01-20 | EPI ISL 20398191 | 2.3.4.4b |
A/chicken/Nebraska/01344-001/2026 | A / H5N1 | NA | 2026-01-22 | EPI ISL 20398135 | 2.3.4.4b |
A/chicken/California/00317-001/2026 | A / H5N1 | NA | 2026-01-06 | EPI ISL 20377803 | 2.3.4.4b |
A/american crow/Iowa/00267-001/2026 | A / H5N1 | NA | 2026-01-05 | EPI ISL 20377961 | 2.3.4.4b |
A/western gull/California/00713-002/2026 | A / H5N1 | NA | 2026-01-01 | EPI ISL 20383440 | 2.3.4.4b |
A/chicken/Montana/01513-002/2026 | A / H5N1 | NA | 2026-01-27 | EPI ISL 20398134 | 2.3.4.4b |
A/chicken/Colorado/01534-002/2026 | A / H5N1 | NA | 2026-01-29 | EPI ISL 20398129 | 2.3.4.4b |
A/chicken/Oklahoma/00305-001/2026 | A / H5N1 | NA | 2026-01-07 | EPI ISL 20377863 | 2.3.4.4b |
A/muscovy duck/Florida/01376-001/2026 | A / H5N1 | NA | 2026-01-21 | EPI ISL 20398167 | 2.3.4.4b |
A/turkey/North Carolina/00181-003/2026 | A / H5N1 | NA | 2026-01-05 | EPI ISL 20377904 | 2.3.4.4b |
A/bald eagle/Minnesota/05665-001/2025|A / H5N1|NA|2025-10-19|EPI ISL 20459023|2.3.4.4b|
A/snow goose/Missouri/06124-005/2025|A / H5N1|NA|2025-12-08|EPI ISL 20370284|2.3.4.4b|
A/skunk/USA/03499-001/2025|A / H5N1|NA|2025-01-01|EPI ISL 20371445|2.3.4.4b|
A/chicken/Wyoming/02382-001/2025|A / H5N1|NA|2025-10-16|EPI ISL 20265857|2.3.4.4b|
A/canada goose/Wisconsin/01189-003/2026|A / H5N1|NA|2026-01-07|EPI ISL 20398126|2.3.4.4b|
A/snow goose/South Dakota/05250-001-R/2025|A / H5N1|NA|2025-11-24|EPI ISL 20377866|2.3.4.4b|
A/chicken/Kansas/06573-001/2025|A / H5N1|NA|2025-12-18|EPI ISL 20370415|2.3.4.4b|
A/chicken/Arkansas/06561-001/2025|A / H5N1|NA|2025-12-22|EPI ISL 20370324|2.3.4.4b|
A/snow goose/Nebraska/05379-003/2025|A / H5N1|NA|2025-12-05|EPI ISL 20336740|2.3.4.4b|
A/green-winged teal/Louisiana/06771-026/2025|A / H5N1|NA|2025-11-12|EPI ISL 20459014|2.3.4.4b|
A/canada goose/New York/01530-001/2026|A / H5N1|NA|2026-01-27|EPI ISL 20406378|2.3.4.4b|
A/snow goose/Mississippi/06771-014/2025|A / H5N1|NA|2025-12-06|EPI ISL 20459030|2.3.4.4b|
A/snow goose/Mississippi/06771-023/2025|A / H5N1|NA|2025-12-14|EPI ISL 20459036|2.3.4.4b|
A/snow goose/Missouri/06604-006/2025|A / H5N1|NA|2025-12-17|EPI ISL 20406288|2.3.4.4b|
A/chicken/South Dakota/06521-001/2026|A / H5N1|NA|2026-04-23|EPI ISL 20459073|2.3.4.4b|
A/american wigeon/Oklahoma/04975-002/2025|A / H5N1|NA|2025-11-08|EPI ISL 20323800|2.3.4.4b|
A/american wigeon/North Carolina/00573-002/2026|A / H5N1|NA|2026-01-03|EPI ISL 20383500|2.3.4.4b|
A/american wigeon/North Carolina/00314-005/2025|A / H5N1|NA|2025-12-20|EPI ISL 20383503|2.3.4.4b|
A/bird/Florida/07109-001/2026|A / H5N1|NA|2026-01-23|EPI ISL 20489319|2.3.4.4b|
A/lesser scaup/Wisconsin/04230-008/2025|A / H5N1|NA|2025-11-08|EPI ISL 20319523|2.3.4.4b|
A/bald eagle/Maryland/05416-002/2026|A / H5N1|NA|2026-02-04|EPI ISL 20454150|2.3.4.4b|
A/Chicken/SK/FAV-0326-1/2025|A / H5N1|NA|2025-10-01|EPI ISL 20208421|2.3.4.4b|
A/canada goose/Oklahoma/02624-001/2026|A / H5N1|NA|2026-02-13|EPI ISL 20421246|2.3.4.4b|
A/red-tailed hawk/Iowa/06281-001/2025|A / H5N1|NA|2025-12-16|EPI ISL 20370338|2.3.4.4b|
A/red fox/Florida/06623-001-R/2025|A / H5N1|NA|2025-12-16|EPI ISL 20391474|2.3.4.4b|
A/canada goose/Colorado/03594-001/2025|A / H5N1|NA|2025-10-28|EPI ISL 20309785|2.3.4.4b|
A/chicken/Mississippi/24-038164-001/2024|A / H5N1|NA|2024-12-19|EPI ISL 19711045|2.3.4.4b|
A/western gull/USA/002655-001/2025|A / H5N1|NA|2025-01-01|EPI ISL 19776958|2.3.4.4b|
A/American green-winged teal/USA/IZ24 0776/2024|A / H5N1|NA|2024-10-17|EPI ISL 19870995|2.3.4.4b|
A/Canada Goose/ON/FAV-0055-6/2025|A / H5N1|NA|2025-01-22|EPI ISL 20399619|2.3.4.4b|
A/canada goose/West Virginia/005199-001/2025|A / H5N1|NA|2025-01-28|EPI ISL 19776929|2.3.4.4b|
A/chicken/New Mexico/25-011508-001-R2/2025|A / H5N1|NA|2025-03-31|EPI ISL 19890776|2.3.4.4b|
A/muscovy duck/Georgia/016493-001/2025|A / H5N1|NA|2025-05-10|EPI ISL 20309845|2.3.4.4b|
A/Ross s goose/Louisiana/W24-1056/2024|A / H5N1|NA|2024-12-11|EPI ISL 19777459|2.3.4.4b|
A/canada goose/Illinois/000616-002/2024|A / H5N1|NA|2024-12-31|EPI ISL 19705484|2.3.4.4b|
A/skunk/Texas/010155-001/2025|A / H5N1|NA|2025-03-19|EPI ISL 20307869|2.3.4.4b|
A/snow goose/Kansas/W24-1007B/2024|A / H5N1|NA|2024-12-02|EPI ISL 19777438|2.3.4.4b|
A/chicken/Arkansas/24-037005-001/2024|A / H5N1|NA|2024-12-10|EPI ISL 19705380|2.3.4.4b|
A/canada goose/North Dakota/003472-001/2025|A / H5N1|NA|2025-01-27|EPI ISL 19743116|2.3.4.4b|
A/duck/Ohio/24-038008-001/2024|A / H5N1|NA|2024-12-16|EPI ISL 19711095|2.3.4.4b|
A/chicken/North Dakota/24-034804-001/2024|A / H5N1|NA|2024-11-21|EPI ISL 19678086|2.3.4.4b|
A/canada goose/Kentucky/003126-001/2025|A / H5N1|NA|2025-01-13|EPI ISL 19743135|2.3.4.4b|
A/herring gull/Michigan/007071-004/2025|A / H5N1|NA|2025-02-25|EPI ISL 20307556|2.3.4.4b|
A/snow goose/Kentucky/W24-1065/2024|A / H5N1|NA|2024-12-13|EPI ISL 19777445|2.3.4.4b|
A/bald eagle/Pennsylvania/005865-001/2025|A / H5N1|NA|2025-01-31|EPI ISL 20311661|2.3.4.4b|
A/turkey/South Dakota/24-035690-001/2024|A / H5N1|NA|2024-12-01|EPI ISL 19678944|2.3.4.4b|
A/swine/Oregon/031570-032/2024|A / H5N1|NA|2024-10-26|EPI ISL 19736960|2.3.4.4b|
A/Cackling Goose/BC/AIVPHL-2575/2024|A / H5N1|NA|2024-10-27|EPI ISL 19751754|2.3.4.4b|
A/Red Tailed Hawk/BC/AIVPHL-2966/2025|A / H5N1|NA|2025-01-06|EPI ISL 19788009|2.3.4.4b|
A/Canada Goose/AB/FAV-0352-3/2024|A / H5N1|NA|2024-11-05|EPI ISL 20399721|2.3.4.4b|
A/Great Horned Owl/AB/FAV-0211-2/2025|A / H5N1|NA|2025-05-06|EPI ISL 20399616|2.3.4.4b|
A/Tundra Swan/ON/FAV-0443-1/2024|A / H5N1|NA|2024-12-06|EPI ISL 20399492|2.3.4.4b|
A/owl/Oregon/014765-001/2025|A / H5N1|NA|2025-03-10|EPI ISL 20311568|2.3.4.4b|
A/duck/Tennessee/038885-003/2024|A / H5N1|NA|2024-12-26|EPI ISL 19737103|2.3.4.4b|
A/duck/Utah/24-035686-002/2024|A / H5N1|NA|2024-11-27|EPI ISL 19678910|2.3.4.4b|
A/chicken/Washington/24-034062-001/2024|A / H5N1|NA|2024-11-13|EPI ISL 19678090|2.3.4.4b|
A/Cackling Goose/BC/AIVPHL-2560/2024|A / H5N1|NA|2024-10-23|EPI ISL 19751745|2.3.4.4b|
A/Cackling Goose/BC/AIVPHL-2675/2024|A / H5N1|NA|2024-11-17|EPI ISL 19787975|2.3.4.4b|
A/chicken/Arizona/003936-002/2025|A / H5N1|NA|2025-02-03|EPI ISL 19743311|2.3.4.4b|
A/dairy cow/Nevada/W250620054-1/2025|A / H5N1|NA|2025-03-02|EPI ISL 20505260|2.3.4.4b|
A/Brown pelican/California/D2500891/2025|A / H5N1|NA|2025-01-21|EPI ISL 20348413|2.3.4.4b|
A/Barn owl/California/D2414017/2024|A / H5N1|NA|2024-11-05|EPI ISL 20348373|2.3.4.4b|
A/cat/Illinois/0790314/2025|A / H5N1|NA|2025-03-16|EPI ISL 20348038|2.3.4.4b|

***`3. Список локаций для кластеров G2c и G2d, полученных входе филогенетического аназила общемировой выборки с 2020 по начало 2026 года`***

Для начала получим список локаций где были зарегистрированы обе эти линии:

<img width="1199" height="328" alt="image" src="https://github.com/user-attachments/assets/67806073-7c4b-4ed9-96cf-a0bb7b9e0dba" />

**`G2d`**
["AB", "Aichi", "Akita", "Alabama", "Alaska", "Aomori", "Arizona", "Arkansas", "Austria", "BC", "California", "Casa Grande", "Chiba", "China", "Colorado", "Connecticut", "Croatia", "Delaware", "District of Columbia", "Durango", "Estonia", "Florence", "Florida", "Fukuoka", "Fukushima", "Georgia", "Germany", "Germany-SH", "Gifu", "Gunma", "Hawaii", "Hebei", "Hiroshima", "Hokkaido", "Hong Kong", "Hyogo", "Ibaraki","Iturup Island Sakhalin Oblast Russia", "Idaho", "Illinois", "India", "Indiana", "Iowa", "Ishikawa", "Italy", "Iwate", "Izabal", "Japan", "Jeju", "Kagawa", "Kansas", "Kentucky", "Khabarovsk", "Kirov", "Japan Kochi", "Komsomolsk-na-Amure", "Kumamoto", "Litchfield Park", "Louisiana", "MB", "Magadan", "Maine", "Maryland", "Massachusetts", "Michigan", "Minnesota", "Mississippi", "Missouri", "Miyagi", "Montana", "NB", "NL", "NS", "NT", "Nebraska", "Netherlands", "Nevada", "New Hampshire", "New Jersey", "New Mexico", "New York", "Niigata", "North Carolina", "North Dakota", "Norway", "ON", "Ohio", "Oita", "Okayama", "Oklahoma", "Oregon", "Osaka", " Prince Edward Island Canada", "Pennsylvania", "Primorsky Krai", "Puerto Rico", "QC", "Queen Creek", "Rhode Island", "Tyuleniy Island Sea of Okhotsk", "SK", "Saga", "Saitama", "Sakhalin", "San Marcos", "San Tan Valley", " Shimane Prefecture Japan", "Sonora", "South Carolina", "South Dakota", "South Korea", "Surprise", "Sweden", "Tennessee", "Texas", "Tochigi", "Tokushima", "Tottori", "Toyama", "US", "Utah", "Vermont", "Vietnam", "Virginia", "WV", "Washington", "West Virginia", "Wisconsin", "Wyoming", "Yamaguchi"]

**`G2c`**
["Aichi", "Akita", "Bangladesh", "Beijing", "Chelyabinsk region", "Chiba", "China", "Chongming", "Ehime", "Fukui", "Fukuoka", "Fukushima", "Guangdong", "Gunma", "Hebei", "Henan china", "Hiroshima", "Hokkaido", "Hong Kong", "Hyogo", "Ibaraki", "India", "Iwate", "Japan", "Jiangsu", "Jiangxi", "Jiujiang", "Kagawa", "Kagoshima", "Kalmykia", " Kamchatka Krai Russia", "Kanagawa", "Khabarovsk", "Laos", "Mangystau", "Miyagi", "Miyazaki", "Nagasaki", "Nepal", "Netherlands", "Niigata", "Novosibirsk region", "Okayama", "Okinawa", "Omsk region", "Philippines", "Qinghai", "Saga", "Saitama", "Shandong", "Shanxi", "Shiga", "Shizuoka", "South Korea", "Tochigi", "Tokyo", "Tottori", "Tyumen", "Ussuriysk", "Vietnam", "Wakayama", "Yamagata"]

***🗺️`4. Создание карты циркуляции генетических линий G2c, G2d и G2d с NA от LPAI`***

Вставьте списки локаций в ячейки, введите название для каждой группы локаций и выберите цвет

<img width="1190" height="290" alt="image" src="https://github.com/user-attachments/assets/637a1bc0-c0a0-449f-8890-21bf7f2205dc" />
