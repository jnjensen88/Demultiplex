# Demux output summary

## Output

All fastqs are gzipped and stored in the `Assignment-the-third/out/` directory. There are also three summary tsvs.

### Samples

The count and percentage of reads that went into each file is stored in `stats_files.tsv`
| File basename | Record Count | Percentage of all records |
|---------------|--------------|---------------------------|
| TACCGGAT      | 71376106     | 19.64948315364762         |
| TCTTCGAC      | 40223838     | 11.07342038463195         |
| CTCTGGAT      | 32848576     | 9.043047833588924         |
| CTAGCTCA      | 16522520     | 4.548566692554029         |
| TGTTCCGT      | 15146782     | 4.169832937383457         |
| TCGAGAGT      | 10936729     | 3.010826511627145         |
| AGAGTCCA      | 10640614     | 2.9293075407821627        |
| TATGGCAC      | 10459887     | 2.8795543062486164        |
| TAGCCATG      | 10054938     | 2.768073882343361         |
| ATCATGCG      | 9481052      | 2.610085951632848         |
| AACAGCGA      | 8396171      | 2.311423666340731         |
| GTCCTAAG      | 8365105      | 2.3028713527184217        |
| AGGATAGC      | 8322630      | 2.2911781987524265        |
| GTAGCGTA      | 7639445      | 2.1031008028193288        |
| ACGATCAG      | 7611984      | 2.0955409275736505        |
| GCTACTCT      | 6753597      | 1.859231301831247         |
| ATCGTGGT      | 6544042      | 1.801541863824323         |
| GATCAAGG      | 6244848      | 1.7191752597583567        |
| CGATCGAT      | 5344118      | 1.4712088189863564        |
| CGGTAATC      | 4615765      | 1.270696899725747         |
| TCGGATTC      | 4264662      | 1.1740400089212089        |
| CACTTCAC      | 3927043      | 1.081095195528736         |
| TCGACAAG      | 3642158      | 1.0026677872273235        |
| GATCTTGC      | 3506814      | 0.9654082644404223        |
| hopped        | 613814       | 0.1689799083810072        |
| unknown       | 49763497     | 13.699640548730605        |

### Index swapping

Reads per index pair are summarized in `stats_indexes.tsv`. Matched index pairs and hopped index pairs are shown individually, but unknown pairs are grouped together.

The number of records that had hopped indexes (with index error correction of <= 1 base) was 613814