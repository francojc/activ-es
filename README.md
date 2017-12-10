ACTIV-ES
=============================
## Jerid Francom, Mans Hulden, and Adam Ussishkin
### Contact: francojc@wfu.edu

### Version 0.2

A version of the tagged running format corpus in the /eagles directory has been added which includes the EAGLES tagset. This tagset is much more fleshed out than the simplified tagset in the /tagged directory. For information on the tagset refer here: http://nlp.lsi.upc.edu/freeling/doc/tagsets/tagset-es.html.

### Sample

EAGLES 

        Báez/NP000P0  .../Fs  Carrizo/NCMS000  ./Fp   ¿/Fia  Te/NP00000  escribió/VMIS3S0  ?/Fit   ¿/Fia  Quién/PT0CS000  te/PP2CS000  dijo/VMIS3S0  ?/Fit   Ibáñez/NP000P0  .../Fs  Sí/RG  ,/Fc  me/PP1CS000  llegó/VMIS3S0  una/DI0FS0  carta/NCFS000  antes/RG  de/SPS00  ayer/RG  ./Fp   Moes/NP000P0  .../Fs  ¿/Fia  Y/CC  qué/PT0CS000  dice/VMIP3S0  ?/Fit   Garrido/AQ0MS0  .../Fs  Todavía/RG  no/RN  la/PP3FSA00  abrí/VMIS1S0  ./Fp   Alonzo/NCMS000  .../Fs  Miller/VMN0000  .../Fs  Anuncios/NCMP000  por/SPS00  altavoces/NCMP000  ¿/Fia  Qué/NP00000  tal/PD0CS000  ?/Fit   Hola/I  ./Fp   Gracias/NCFP000  ./Fp   Voz/NCFS000  de/SPS00  mujer/NCFS000  ¡/Faa  Bruno/NP00000  !/Fat   ¡/Faa  Bruno/NP00000  !/Fat   ¡/Faa  Concha/NP00000  !/Fat   Sonido/NCMS000  de/SPS00  tren/NCMS000  ¿/Fia  Me/PP1CS000  vas/VMIP2S0  a/SPS00  dejar/VMN0000  esperando/VMG0000  acá/RG  afuera/RG  ?/Fit   ¿/Fia  Está/NP00000  obra/NCFS000  es/VSIP3S0  tuya/AQ0FS0  ?/Fit   Sí/RG  ,/Fc  es/VSIP3S0  un/DI0MS0  guión/NCMS000  ./Fp

Note that the reliability of these tags are most likely to be less than the simplified version which has been documented in the following paper:

Francom, J., Hulden, M., & Ussishkin, A. (2014). [ACTIV-ES: a comparable , cross-dialect corpus of "everyday" Spanish from Argentina, Mexico and Spain.](http://www.lrec-conf.org/proceedings/lrec2014/summaries/691.html) In The ninth international conference on Language Resources and Evaluation (pp. 1733–1737).

### Version 0.1

DESCRIPTION:
ACTIV-ES is a comparable Spanish corpus comprised of film dialogue from Argentine, Mexican and Spanish productions. Titles for each of these three countries were seeded from the Internet Movie Database, subtitle data for the hearing impaired was provided by Opensubtitles.org and was post-processed to correct/remove subtitle, OCR and diacritic artifacts and annotated for part-of-speech.

The data is available in two main formats: 1) running text for each document and 2) 1:5 gram aggregate files. Each format includes a plain text and part-of-speech annotated version. Document names reflect the `language code`, `country`, `year`, `title`, `type`, `genre` (first genre listed in the IMDb), and `IMDb ID`. 

For more information about the development and evaluation of these resources and to cite this work refer to:

Francom, J., Hulden, M. and Ussishkin, A.. (2014) [ACTIV-ES: a comparable, cross-dialect corpus of ‘everyday’ Spanish from Argentina, Mexico, and Spain.](http://www.lrec-conf.org/proceedings/lrec2014/summaries/691.html) In Proceedings of the Ninth Annual Language Resources and Evaluation Conference, Reykjavik, Iceland. European Language Resources Association (ELRA).

## Sample running text

Plain

        Báez ... Carrizo . ¿ Te escribió ? ¿ Quién te dijo ? Ibáñez ... Sí , me llegó una carta antes de ayer . Moes ... ¿ Y qué dice ? Garrido ... Todavía no la abrí . Alonzo ... Miller ... Anuncios por altavoces ¿ Qué tal ? Hola . Gracias . Voz de mujer ¡ Bruno ! ¡ Bruno ! ¡ Concha ! Sonido de tren ¿ Me vas a dejar esperando acá afuera ? ¿ Está obra es tuya ? Sí , es un guión .

Tagged

        Báez/N .../PUNC Carrizo/N ./PUNC ¿/PUNC Te/PRON escribió/V ?/PUNC ¿/PUNC Quién/PRON te/PRON dijo/V ?/PUNC Ibáñez/N .../PUNC Sí/ADV ,/PUNC me/PRON llegó/V una/DET carta/N antes/ADV de/ADPOS ayer/ADV ./PUNC Moes/N .../PUNC ¿/PUNC Y/CC qué/PRON dice/V ?/PUNC Garrido/ADJ .../PUNC Todavía/ADV no/ADV la/DET abrí/V ./PUNC Alonzo/N .../PUNC Miller/N .../PUNC Anuncios/N por/ADPOS altavoces/N ¿/PUNC Qué/PRON tal/DET ?/PUNC Hola/INTERJECTION ./PUNC Gracias/N ./PUNC Voz/N de/ADPOS mujer/N ¡/PUNC Bruno/ADJ !/PUNC ¡/PUNC Bruno/ADJ !/PUNC ¡/PUNC Concha/N !/PUNC Sonido/N de/ADPOS tren/N ¿/PUNC Me/PRON vas/V a/ADPOS dejar/V esperando/V acá/ADV afuera/ADV ?/PUNC ¿/PUNC Está/V obra/N es/V tuya/PRON ?/PUNC Sí/ADV ,/PUNC es/V un/DET guión/N 

## Sample n-gram

Plain

        "","word","ar_orf","es_orf","mx_orf","aes_orf","ar_ord","es_ord","mx_ord","aes_ord"
        "1","a",2654.57,2541.01,2537.99,2576.18,9.92,10,10,9.98
        "2","á",0.24,0.1,0.13,0.15,0.16,0.05,0.08,0.09
        "3","aa",0.36,0.1,0.13,0.19,0.16,0.05,0.08,0.09
        "4","aaaaaa",0.12,0,0,0.04,0.08,0,0,0.02
        "5","aaaaaaaa",0.36,0,0,0.11,0.08,0,0,0.02
        "6","aaaaaaaaaaaaaaaaaaaaaah",0.12,0,0,0.04,0.08,0,0,0.02
        "7","aaaaaaaah",0.12,0.48,0,0.23,0.08,0.16,0,0.09
        "8","aaaaaaaay",0.12,0,0,0.04,0.08,0,0,0.02
        "9","aaaaaaah",0.12,1.05,0,0.46,0.08,0.16,0,0.09
        "10","aaaaaaahhhhh",0.24,0,0,0.08,0.08,0,0,0.02

Tagged

        "","word","ar_orf","es_orf","mx_orf","aes_orf","ar_ord","es_ord","mx_ord","aes_ord"
        "1","a/adpos",2653.58,2540.49,2537.64,2575.59,9.92,10,10,9.98
        "2","a/n",3.36,3.07,2,2.85,1.56,0.98,1.18,1.21
        "3","a/punc",0.12,0.48,0,0.23,0.08,0.22,0,0.12
        "4","á/v",0.24,0,0.13,0.11,0.16,0,0.08,0.07
        "5","aa/n",0.36,0.1,0,0.15,0.16,0.05,0,0.07
        "6","aaaaaa/n",0.12,0,0,0.04,0.08,0,0,0.02
        "7","aaaaaaaa/n",0.36,0,0,0.11,0.08,0,0,0.02
        "8","aaaaaaaaaaaaaaaaaaaaaah/interjection",0.12,0,0,0.04,0.08,0,0,0.02
        "9","aaaaaaaah/interjection",0.12,0.48,0,0.23,0.08,0.16,0,0.09
        "10","aaaaaaaay/interjection",0.12,0,0,0.04,0.08,0,0,0.02

*Codes*

- ar_: Argentina
- mx_: Mexico
- es_: Spain
- aes_: ACTIV-ES 

*Measures*

- Observed relative frequency (_orf): Word occurrence per 100,000
- Observed relative dispersion (_ord): Occurrence of a word per 10 documents



