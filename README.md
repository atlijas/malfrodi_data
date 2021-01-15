# Málfróði: Data

Í þessari gagnahirslu má finna öll þau gögn sem orðið hafa til sem afurðir [Málfróða](https://malfrodi.is).

### Óviðeigandiheit orða
Skjalið [proprieties.tsv](https://github.com/atlijas/malfrodi_data/blob/main/proprieties.tsv) inniheldur gögn á forminu *orð*/*óviðeigandiheitaeinkunn*/*fjöldi atkvæða*. Orð sem fá háa einkunn eru talin óviðeigandi.

| Orð | Óviðeigandiheitaeinkunn | Atkvæði |
| --- | ----------------------- | ------- |
| hórusonur        | 9.71  | 7 |
| bófi             | 6.83  | 6 |
| ærumeiðingarbrot | 0.83  | 6 |

### Formlegheit orða
Skjalið [formalities.tsv](https://github.com/atlijas/malfrodi_data/blob/main/formalities.tsv) inniheldur gögn á forminu *orð*/*formlegheitaheitaeinkunn*/*fjöldi atkvæða*. Orð sem fá háa einkunn eru talin formleg og orð sem fá lága einkunn óformleg.

| Orð | Formlegheitaeinkunn | Atkvæði |    
| --- | ----------------------- | ------- |
| sjálfrennireið   | 8.82  | 11 |
| endaþarmur       | 6.27  | 11 |
| cancela          | 0.38  | 13 |


### Setningapör
Skjalið [sentence_relations.tsv](https://github.com/atlijas/malfrodi_data/blob/main/sentence_relations.tsv) inniheldur gögn á forminu *upprunaleg setning*/*leiðrétt setning*/*fjöldi samþykkta á leiðréttingu*/*fjöldi hafnanna á leiðréttingu*.

| Grunnsetning | Leiðrétt setning | Samþykkt | Hafnað |
| ------------ | ---------------- | -------- | ------ |
| Að fara á reiðhjól verður vinsælla í London. | Að ferðast á reiðhjóli verður vinsælla í London. | 7 | 0 |
| Ef þau væru of veik mætti svæfa þau fyrir fullt. | Ef þau væru of veik mætti svæfa þau fyrir fullt og allt. | 4 | 0 |
| Sannfæringakraftur hugans nær engum takmörkunum. | Sannfæringakraftur hugans hefur engin takmörk. | 8 | 1 |

### Gæði setninga
Skjalið [sentences.tsv](https://github.com/atlijas/malfrodi_data/blob/main/sentences.tsv) inniheldur setningar sem flestar innihalda a.m.k. eina villu (eða rangt mál). Gögnin eru á forminu *setning*/*gæðaeinkunn með tilliti til málfars og staf- og greinarmerkjasetningar*.

| Setning | Gæðaeinkunn | Atkvæði |
| ------- | ----------- | ------- |
| Óvíst er hvar fundurinn mun fara fram. | 8.5 | 2
| Nico Rosberg, tilkynnti gírkasavandræði á 29. hring. | 3.67 | 3 |
| Neymer segir að draumur hans sé eki á enda. | 0.67 | 3 |


### Samheiti
Skjalið [synonyms.tsv](https://github.com/atlijas/malfrodi_data/blob/main/synonyms.tsv) inniheldur gögn sem eru á forminu *grunnorð*/*mögulegt samheiti*/*fjöldi samþykkta á orðapari*/*fjöldi hafnanna á orðapari*.
| Grunnorð | Samheiti | Samþykkt | Hafnað|
| -------- | -------- | -------- | ----- |
| bíll | bifreið | 12 | 0 |
| kona | kvenmaður | 12 | 0 |
| nýr | glænýr | 7 | 2 |
