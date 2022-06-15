# hse22_project

Ссылка на colab: https://colab.research.google.com/drive/1DcUv7DLhlC1CZt50oxeWekXoX91M3m6s?usp=sharing 

### Для данного задания исследовались 5 видов таксона Actinobacteria, рода Brevibacterium: 

| Organism name       | Assembly | Level | Size(Mb) | GC% | Scaffolds |
| ------------- |:------------------:| -----:| -----:| -----:| -----:|
| Brevibacterium casei     | GCA_016027415.1    | Complete | 3,96009 | 68 | 1 |
| Brevibacterium luteolum     | GCA_011462075.1 | Complete  | 3,17962 | 66,7 | 1 |
| Brevibacterium pigmentatum  | GCA_011617465.1  | Complete  | 3,91313 | 64,7 | 1 |
| Brevibacterium aurantiacum     | GCA_003932995.1 | Complete | 4,03863 | 62,7 | 1 |
| Brevibacterium atlanticum  | GCA_011617245.1 | Complete  | 4,15679 | 65,4 | 1 |

## Анализ аннотированных генов:

| Organism name       |  Assembly | Общая длина последовательностей | Длина аннотированных генов | Доля аннотированных генов в геноме,% |
| ------------- |:------------------:| -----:| -----:|  -----:|
| Brevibacterium casei    |  GCF_016027415 | 3960094 | 3534184  | 89.2 |
| Brevibacterium luteolum     | GCF_011462075 | 3179618 | 2834497  | 89.1 |
| Brevibacterium pigmentatum  | GCF_011617465 | 3913130 | 3490665 | 89.2 | 
| Brevibacterium aurantiacum |  GCF_003932995 | 4038634    | 3593714 | 89 |
| Brevibacterium atlanticum   | GCF_011617245	 | 4156794  | 3701579  | 89 |

<img width="570" alt="image" src="https://user-images.githubusercontent.com/67833171/173706894-9259f991-d5b6-45e2-9c9c-baf88a27db1b.png">


## Предсказание участков Z-DNA:

<img width="727" alt="image" src="https://user-images.githubusercontent.com/67833171/173706963-6c8a0445-6011-4773-b190-fa79ac605ea1.png">

### Гистограммы:

![zh_casei](https://user-images.githubusercontent.com/67833171/173707095-f5b90f7f-10e7-43c5-9548-bc1c9326861c.png)

#### Среднее значение z-score = 2917.3098366599334

![zh_lut](https://user-images.githubusercontent.com/67833171/173707198-d2d9413d-a1c4-4aeb-9125-94f273b313c6.png)

#### Среднее значение z-score = 2788.595775738373

![zh_pig](https://user-images.githubusercontent.com/67833171/173707281-4f76bfc9-a48d-4dc4-a2b5-07c6fddac765.png)

#### Среднее значение z-score = 2312.2305904480254

![zh_aura](https://user-images.githubusercontent.com/67833171/173707299-69116916-503f-4bfd-b2ea-0b2cd51128d9.png)

#### Среднее значение z-score = 2234.3663578797946

![zh_atl](https://user-images.githubusercontent.com/67833171/173707313-9c5cc6bc-0cba-4a56-a1b9-e9ada03ac54b.png)

#### Среднее значение z-score = 2372.4210845755442


## Ассоциируем предсказанные участки Z-DNA с промотерами генов:

### Гистограмма кластеров по количеству генов

![класт_гены](https://user-images.githubusercontent.com/67833171/173709195-2cebf401-4ed5-423e-8cd5-d28cf46d7e05.png)

### Гистограмма кластеров по количеству разных геномов в кластере

![кластеры_орг](https://user-images.githubusercontent.com/67833171/173709256-90282376-e474-4903-af3b-3c46f32817c0.png)

 
### Таблица с информацией по выбранным кластерам

<img width="839" alt="image" src="https://user-images.githubusercontent.com/67833171/173795767-9c780ddc-dbaf-43ce-80cb-34afe517e9ca.png">

#### Полученные гены и их функции:

<img width="353" alt="image" src="https://user-images.githubusercontent.com/67833171/173794965-625937cc-4b90-4498-a7bf-cab829c3b682.png">

<img width="356" alt="image" src="https://user-images.githubusercontent.com/67833171/173795019-5c8ea93e-40fe-4c14-9cc6-4ad745a8876e.png">

<img width="353" alt="image" src="https://user-images.githubusercontent.com/67833171/173795076-7d128f8e-8832-4540-bdb4-d2ac824a4f15.png">

<img width="355" alt="image" src="https://user-images.githubusercontent.com/67833171/173795126-4bb966ea-4353-49f8-968f-cb3acbffd2ca.png">

<img width="353" alt="image" src="https://user-images.githubusercontent.com/67833171/173795176-29bbd554-9919-4757-8085-41842457a9c6.png">

### Множественное белковое выравнивание

Для подтвержения того, что между белками в полученных кластерах хорошее сходство, проводилось их множественное белковое выравнивание на сайте https://www.ebi.ac.uk/Tools/msa/clustalo/

#### Кластер 1 (P1 family peptidase):

<img width="392" alt="image" src="https://user-images.githubusercontent.com/67833171/173710806-11f41fc5-6069-4c06-b061-9affd81c5018.png">
<img width="394" alt="image" src="https://user-images.githubusercontent.com/67833171/173710832-859db7d2-b13f-4a8f-8232-35042bd509df.png">

#### Кластер 2 (50S ribosomal protein L34):

<img width="325" alt="image" src="https://user-images.githubusercontent.com/67833171/173710986-e1892aa7-08f7-432c-8ed1-959e3225a0ac.png">

#### Кластер 3 (hydroxyethylthiazole kinase):

<img width="393" alt="image" src="https://user-images.githubusercontent.com/67833171/173711047-da52ad36-9b4a-4b2b-ae6b-b9cc212bed1a.png">
<img width="311" alt="image" src="https://user-images.githubusercontent.com/67833171/173711057-c9280056-34b6-485d-baf4-fb6c60f421c2.png">

#### Кластер 4 (DUF4350 domain-containing protein):

<img width="443" alt="image" src="https://user-images.githubusercontent.com/67833171/173711468-56c2e5f1-8169-48f5-97ae-be404235945e.png">
<img width="445" alt="image" src="https://user-images.githubusercontent.com/67833171/173711505-3117099c-8b30-4a6e-8523-848ae4dd6164.png">

#### Кластер 5 (succinate dehydrogenase flavoprotein subunit):

<img width="392" alt="image" src="https://user-images.githubusercontent.com/67833171/173711312-6547f14b-bc30-4b4f-8db1-8bca44675305.png">
<img width="390" alt="image" src="https://user-images.githubusercontent.com/67833171/173711347-bd7e2683-e87c-4356-a86c-6ad4a46325a5.png">

#### Кластер 6 (phosphoribosylformylglycinamidine synthase subunit PurQ):

<img width="397" alt="image" src="https://user-images.githubusercontent.com/67833171/173792443-d60cea55-0b1d-4c9b-801c-06a291e447bc.png">
<img width="315" alt="image" src="https://user-images.githubusercontent.com/67833171/173792498-a642210c-dbbb-4ba2-9675-d396d2592b1f.png">

#### Кластер 7 (PIG-L family deacetylase):

<img width="391" alt="image" src="https://user-images.githubusercontent.com/67833171/173711720-9e4f1171-a660-4ba8-a5c2-7669cb136b7d.png">
<img width="390" alt="image" src="https://user-images.githubusercontent.com/67833171/173711754-dd215e62-8818-40db-8338-cb5c3c8ef9b0.png">

#### Кластер 8 (isochorismatase family protein):

<img width="452" alt="image" src="https://user-images.githubusercontent.com/67833171/173792929-16dc22a5-ce43-4996-ad96-87a0f85ef4cb.png">

#### Кластер 9 (ribonuclease P protein component):

<img width="448" alt="image" src="https://user-images.githubusercontent.com/67833171/173793190-d5648f25-6ba9-4657-9629-e664587cd7e2.png">

#### Кластер 10 (FkbM family methyltransferase):

<img width="444" alt="image" src="https://user-images.githubusercontent.com/67833171/173793691-cc531226-8db2-4c1d-af0c-6963cfe5fc09.png">
<img width="445" alt="image" src="https://user-images.githubusercontent.com/67833171/173793762-3fe82aae-d3c2-4995-adf6-15b1fda184c7.png">

## Визуализация расположения участков Z-DNA:


