# hse22_project_Firmicutes

Род: Planococcus

Colab: https://colab.research.google.com/drive/13XVbMmDadGVuvP3NoVdmjjsQp02_PbZp?usp=sharing

## Таблица с данными аннотированных генов

| Organism name                     |   Count annotated gene |   Len annotated gene |   Percent annotate gene |   Count Z-DNA region(without filters) |   Count Z-DNA region(with filters) |   Summary len Z-DNA region |
|:----------------------------------|-----------------------:|---------------------:|------------------------:|--------------------------------------:|-----------------------------------:|---------------------------:|
| Planococcus halocryophilus        |                   3382 |              2982815 |                      87 |                               3424893 |                               4477 |                      43544 |
| Planococcus donghaensis           |                   3236 |              2901287 |                      87 |                               3305371 |                               4598 |                      44796 |
| Planococcus faecalis              |                   3465 |              3022203 |                      86 |                               3495892 |                               5127 |                      50110 |
| Planococcus halotolerans          |                   3521 |              3023395 |                      86 |                               3519247 |                               5314 |                      51304 |
| Planococcus antarcticus DSM 14505 |                   3702 |              3176320 |                      83 |                               3765545 |                               5226 |                      50638 |

## Гистограммы распредления ZH-Score

<p float="left">
  <img src="/pic/hist1.png" width="410" />
  <img src="/pic/hist2.png" width="410" />
  <img src="/pic/hist3.png" width="410" />
  <img src="/pic/hist4.png" width="410" />
  <img src="/pic/hist5.png" width="410" />
</p>

## Расположение предсказанных z-dna:

<p float="left">
  <img src="/pic/zdna1_1.png" width="700" />
</p>
<p float="left">
  <img src="/pic/zdna2_1.png" width="700" />
</p>
<p float="left">
  <img src="/pic/zdna3_1.png" width="700" />
</p>
<p float="left">
  <img src="/pic/zdna4_1.png" width="700" />
</p>
<p float="left">
  <img src="/pic/zdna5_1.png" width="700" />
</p>

## Гомологичные связи между белками выбранных геномов (создание кластеров)

<img src="/pic/raspr.png" width="700" />

<img src="/pic/raspr2.png" width="700" />

## Определение кластеров гомологов-белков

|   # Species |   Genes |   Alg.-Conn. | GCF_002009235.1_ASM200923v1   | GCF_001687665.2_ASM168766v2   | GCF_001687585.2_ASM168758v2   | GCF_004785625.2_ASM478562v2   | GCF_001687565.2_ASM168756v2   |   zh-score_mean |
|------------:|--------:|-------------:|:------------------------------|:------------------------------|:------------------------------|:------------------------------|:------------------------------|----------------:|
|           5 |       5 |            1 | WP_058385925.1                | WP_065526864.1                | WP_008496041.1                | WP_112224563.1                | WP_006828442.1                |        51823.8  |
|           5 |       5 |            1 | WP_071153796.1                | WP_238323772.1                | WP_236610195.1                | WP_112224415.1                | WP_040851819.1                |        25815    |
|           5 |       5 |            1 | WP_006828953.1                | WP_006828953.1                | WP_008497448.1                | WP_006828953.1                | WP_006828953.1                |        16271.6  |
|           5 |       5 |            1 | WP_071153694.1                | WP_065526851.1                | WP_008496052.1                | WP_112224562.1                | WP_197684182.1                |         8049.27 |
|           5 |       5 |            1 | WP_071154348.1                | WP_065526596.1                | WP_008498931.1                | WP_112223746.1                | WP_065537022.1                |         3858.66 |
|           5 |       5 |            1 | WP_058385912.1                | WP_065526850.1                | WP_008496053.1                | WP_112224485.1                | WP_065537124.1                |         3686.15 |
|           5 |       5 |            1 | WP_071154690.1                | WP_065527560.1                | WP_040850764.1                | WP_112224781.1                | WP_006828956.1                |         3428.53 |
|           5 |       5 |            1 | WP_058384417.1                | WP_065525482.1                | WP_008496849.1                | WP_135815226.1                | WP_006829289.1                |         2846.38 |
|           5 |       5 |            1 | WP_058385357.1                | WP_065526296.1                | WP_008496420.1                | WP_112222408.1                | WP_006829589.1                |         2306.71 |
|           5 |       5 |            1 | WP_038703546.1                | WP_039863440.1                | WP_039863440.1                | WP_218673378.1                | WP_040852855.1                |         1823.39 |


## Множественное белковое выравнивание

Выравнивание было выполнено ClustalW.


<details>
  <summary>cluster_1</summary>
    
  ```  
CLUSTAL 2.1 multiple sequence alignment


WP_065526864.1      MKKQEIRIQGARAHNLKNIDVVIPRDKLVVMTGLSGSGKSSLAFDTIYAEGQRRYVESLS
WP_008496041.1      MKKQEIRIQGARAHNLKNIDVVIPRDKLVVMTGLSGSGKSSLAFDTIYAEGQRRYVESLS
WP_006828442.1      MKKQEIRIQGARAHNLKNIDVVIPRDKLVVMTGLSGSGKSSLAFDTIYAEGQRRYVESLS
WP_058385925.1      MRNQEIRIQGARANNLKNIDVVIPRDKLVVMTGLSGSGKSSLAFDTIYAEGQRRYVESLS
WP_112224563.1      MRNQEIKIQGARAHNLKNVDITIPRDKLVVMTGLSGSGKSSLAFDTIYAEGQRRYVESLS
                    *::***:******:****:*:.**************************************

WP_065526864.1      AYARQFLGQMDKPDVDLIEGLSPAISIDQKTTSKNPRSTVATVTEIYDYMRLMFARIGKP
WP_008496041.1      AYARQFLGQMDKPDVDLIEGLSPAISIDQKTTSKNPRSTVATVTEIYDYMRLMFARIGKP
WP_006828442.1      AYARQFLGQMDKPDVDLIEGLSPAISIDQKTTSKNPRSTVATVTEIYDYMRLMFARIGKP
WP_058385925.1      AYARQFLGQMDKPDVDLIEGLSPAISIDQKTTSKNPRSTVATVTEIYDYMRLMYARIGKP
WP_112224563.1      SYARQFLGQMDKPDVDLIEGLSPAISIDQKTTSKNPRSTVATVTEIYDYMRLMYARVGKA
                    :****************************************************:**:**.

WP_065526864.1      ICPNHGIEISSQTIEQMVDRIVEYPERTKMQILAPIVSGRKGTHVKLLEDIKKQGYVRVR
WP_008496041.1      ICPNHGIEISSQTIEQMVDRIVEYPERTKMQILAPIVSGRKGTHVKLLEDIKKQGYVRVR
WP_006828442.1      ICPNHGIEISSQTIEQMVDRIVEYPERTKMQILAPIVSGRKGTHVKLLEDIRKQGYVRVR
WP_058385925.1      ICPNHGIEISSQTIEQMVDRIVEYPERTKMQILAPIVSGRKGTHVKLLEDIKKQGYVRVR
WP_112224563.1      ICPNHGIEISSQTIEQMVDRLVVYPERTKMQILAPLVSGRKGTHAKLFEDIKKQGYVRVR
                    ********************:* ************:********.**:***:********

WP_065526864.1      VNGELIDLDDDITLDKNKKHNIEVVIDRIIIKEGIAPRLSDSLESALRLAEGRVLVDVME
WP_008496041.1      VNGELIDLDDDITLDKNKKHNIEVVIDRIIIKEGIAPRLSDSLESALRLADGRVLVDVME
WP_006828442.1      VNGELIDLDDDIALDKNKKHNIEVVIDRIIIKEGIAPRLSDSLESALRLANGRVLVDVME
WP_058385925.1      VDGELIDLDDDIALDKNKKHNIEVVIDRIIIKEGIAPRLSDSLESALRLAEGRVLVDVME
WP_112224563.1      VNGELFDLDDNIDLDKNKKHSIEVVIDRIVMKEGIAPRLSDSLESALRLSDGRVLVDVME
                    *:***:****:* *******.********::******************::*********

WP_065526864.1      QEELLFSEHHACPICGFSIGELEPRMFSFNSPFGACPDCDGLGMKLEVDPELVIPDWSVS
WP_008496041.1      KEELLFSEHHACPICGFSIGELEPRMFSFNSPFGACPECDGLGMKLEVDPELVIPDWNVS
WP_006828442.1      QEELLFSEHHACPICGFSIGELEPRMFSFNSPFGACPECDGLGMKLEVDPELVIPDWNVS
WP_058385925.1      QEELLFSEHHACPICGFSIGELEPRMFSFNSPFGACPECDGLGIKLEVDPELVIPDWTAT
WP_112224563.1      QEELLFSEHHACPICGFSIGELEPRMFSFNSPFGACPECDGLGHKLEVDPELVVPDWSLS
                    :************************************:***** *********:***. :

WP_065526864.1      LNKGAIVPWQPTSSQYYPQLLKAICHHYKIDMDVPVSDLPEEHINVIMRGSGKDKIRFRY
WP_008496041.1      LNKGAIVPWQPTSSQYYPQLLKAVCQHYKIDMDIPVSELPEEYINVIMRGSGEDKIRFRY
WP_006828442.1      LNKGAIVPWQPTSSQYYPQLLKAICNHYKIDMDIPVSDLPEEHINVILRGSGNDKIRFRY
WP_058385925.1      LNKGAIVPWQPTSSQYYPQLLKAVCQHYKIDMDIPVSELPEEHINIILRGSGNDKIRFRY
WP_112224563.1      LNEHAVAPWKPSSSQYYPQLLKALCTHYKIDMDAPVSELPEEHMNLVLRGSGSEKIRFRY
                    **: *:.**:*:***********:* ******* ***:****::*:::****.:******

WP_065526864.1      ENDYGQIRDNHIHFEGVLSNVDRRYRETSSDYIREQMEKYMGQQACPTCEGYRLKPESLS
WP_008496041.1      ENDYGQIRDNHIQFEGVLSNVDRRYRETSSDYIREQMEKYMGQQACPTCEGYRLKPESLS
WP_006828442.1      ENDYGQIRDNHIHFEGVLSNVDRRYRETSSDYIREQMEKYMGQQPCPACEGYRLKPESLS
WP_058385925.1      ENDYGQIRDNHINFEGVLSNVDRRYRETSSDYIRDQMEKYMGQQSCTVCEGYRLKPESLS
WP_112224563.1      ENDYGQIRDNHINFEGVLSNVDRRYRETSSDYTREQMEKYMAEQPCPACTGYRLKPESLA
                    ************:******************* *:******.:*.*..* *********:

WP_065526864.1      VKVNNLHIGTVAEFSIVEAYEFFDHLKLSEKDMQIAKLILREIQERIGFLINVGLDYLTL
WP_008496041.1      VKVNNLHIGTVAEFSIVEAYEFFDQLKLSEKDMQIAKLILREIQERIGFLINVGLDYLTL
WP_006828442.1      VKVNDLHIGTVAEFSIVEAHQFFDQLKLSEKDMQIAKLILREIQERIGFLINVGLDYLTL
WP_058385925.1      VKVNGLHIGTVAEFSIVEANQFFDQLVLSEKDMQIAKLILREIQERIGFLINVGLDYLTL
WP_112224563.1      VKVNGLHIGKVSEFSIVEADEFFKNLELSEKDMQISLLILREIKERLGFLINVGLDYLTL
                    ****.****.*:******* :**.:* ********: ******:**:*************

WP_065526864.1      NRASGTLSGGEAQRIRLATQIGSRLTGVLYILDEPSIGLHQRDNDRLIETLKSMRDIGNT
WP_008496041.1      NRASGTLSGGEAQRIRLATQIGSRLTGVLYILDEPSIGLHQRDNDRLIETLKSMRDIGNT
WP_006828442.1      NRASGTLSGGEAQRIRLATQIGSRLTGVLYILDEPSIGLHQRDNDRLIETLKSMRDIGNT
WP_058385925.1      SRASGTLSGGEAQRIRLATQIGSRLTGVLYILDEPSIGLHQRDNDRLIETLKSMRDIGNT
WP_112224563.1      NRASGTMSGGEAQRIRLATQIGSRLSGVLYILDEPSIGLHQRDNDRLINTLKNMRDIGNT
                    .*****:******************:**********************:***.*******

WP_065526864.1      LIVVEHDEDTMLAADYLIDVGPGAGVHGGEIIAAGTPDKVMKNKKSLTGQYLSGKKFIPL
WP_008496041.1      LIVVEHDEDTMLAADYLIDVGPGAGVHGGEIIAAGTPDKVMKNKKSLTGQYLSGKKFIPL
WP_006828442.1      LIVVEHDEDTMLAADYLIDVGPGAGVHGGEIIAAGTPDKVMKNKKSLTGQYLSGKKFIPL
WP_058385925.1      LIVVEHDEDTMLAADYLIDVGPGAGAHGGEIIAAGTPEKVMKNKKSLTGQYLSGKKFIPV
WP_112224563.1      LIVVEHDEDTMLAADYLIDIGPGAGVHGGEIIAAGTPEKVMKNRKSLTGQYLSGKKFIPL
                    *******************:*****.***********:*****:***************:

WP_065526864.1      PAERRMPSDRKILIRGANQNNLKKVDVDIPLGLFTAVTGVSGSGKSTLINEILYKTLAHR
WP_008496041.1      PAERRTPSDRKIAIRGANQNNLKKVDVDIPLGLFTAVTGVSGSGKSTLINEILYKTLAHR
WP_006828442.1      PAERRVPSDRKISIRGANQNNLKKVDVDIPLGLFTAVTGVSGSGKSTLINEILYKTLAHR
WP_058385925.1      PAERRVPSDRKISIRGANQNNLKKVDVDIPLGLFTAVTGVSGSGKSTLINEILYKTLAHR
WP_112224563.1      PAERREPDGRAISIRGASENNLKKVDVDIPIGVFTAVTGVSGSGKSTLVNEILYKTLASK
                    ***** *..* * ****.:***********:*:***************:********* :

WP_065526864.1      LNRAKAKPGQFDSIEGTQELEKVIEIDQSPIGRTPRSNPATYTGVFDDVRDVYATTNEAK
WP_008496041.1      LNRAKAKPGQFDSIEGTEELEKVIEIDQSPIGRTPRSNPATYTGVFDDVRDVYATTNEAK
WP_006828442.1      LNRAKTKPGHFDSIEGTEELEKVIEIDQSPIGRTPRSNPATYTGVFDDVRDVYATTNEAK
WP_058385925.1      LNRAKAKPGHFDLIEGTEELEKVIDIDQSPIGRTPRSNPATYTGVFDDIRDVYATTNEAK
WP_112224563.1      LNKAKIKPGKAESVKGYEQLEKVIDIDQSPIGRTPRSNPATYTGVFDDIRDVYAKTNEAK
                    **:** ***: : ::* ::*****:***********************:*****.*****

WP_065526864.1      VRGYKKGRFSFNVKGGRCEACRGDGIIKIEMHFLPDVYVPCEICHGKRYNRETLEVKYKN
WP_008496041.1      VRGYKKGRFSFNVKGGRCEACRGDGIIKIEMHFLPDVYVPCEICHGKRYNRETLEVKYKN
WP_006828442.1      VRGYKKGRFSFNVKGGRCEACRGDGIIKIEMHFLPDVYVPCEICHGKRYNRETLEVKYKN
WP_058385925.1      VRGYKKGRFSFNVKGGRCEACRGDGIIKIEMHFLPDVYVPCEICHGKRYNRETLEVKYKN
WP_112224563.1      VRGYQKGRFSFNVKGGRCEACRGDGIIKIEMHFLPDVYVPCEVCHGKRYNRETLEVKYKD
                    ****:*************************************:****************:

WP_065526864.1      KSIADVLAMTVEDALSFFENIPKINRKLQTIVDVGLGYITMGQPATTLSGGEAQRVKLAS
WP_008496041.1      KSIADVLAMTVEDALSFFENIPKINRKLQTIVDVGLGYITMGQPATTLSGGEAQRVKLAS
WP_006828442.1      KSIADVLAMTVEDAYSFFENIPKINRKLKTIVDVGLGYVTMGQPATTLSGGEAQRVKLAS
WP_058385925.1      KSIADVLAMTVEDGYAFFENIPKINRKLKTIVDVGLGYIKLGQPATTLSGGEAQRVKLAS
WP_112224563.1      KSIADVLAMTVEDAYSFFENVPKINRKLKTIVDVGLGYVTMGQPATTLSGGEAQRVKLAS
                    *************. :****:*******:*********:.:*******************

WP_065526864.1      ELHKRSNGKSFYILDEPTTGLHADDISRLLLVLQRLVENGDTVLTIEHNLDVIKTADYII
WP_008496041.1      ELHKRSNGKSFYILDEPTTGLHADDISRLLLVLQRLVENGDTVLTIEHNLDVIKTADHII
WP_006828442.1      ELHKRSNGKSFYILDEPTTGLHADDISRLLLVLQRLVENGDTVLTIEHNLDVIKTADHII
WP_058385925.1      ELHKRSNGKSFYILDEPTTGLHADDISRLLVVLQRLVENGDTVLTIEHNLDVIKTADYII
WP_112224563.1      ELHKRSNGKSFYILDEPTTGLHADDISRLLKVLQKLVDNGDTVLTIEHNLDVIKTADYLI
                    ****************************** ***:**:*******************::*

WP_065526864.1      DLGPEGGDKGGTILATGTPEEIAAVDDSYTGKYLKPILERDRARMESLVKGASRKKKAVK
WP_008496041.1      DLGPEGGDKGGTILATGTPEEIAAVDNSYTGKYLKPILERDRARMESLVKGASRKKKVVK
WP_006828442.1      DLGPEGGDKGGTILATGTPEEIAAAENSYTGKYLKPILERDRARMDALVKGAGRRKKAVK
WP_058385925.1      DLGPEGGDKGGMILATGTPEEIAAVENSYTGKYLKPVLERDRARMDAVVKGASRKKKTVK
WP_112224563.1      DLGPEGGDKGGTILATGTPEEIAEVENSYTGKYLKPILERDRARMEAKVNKASRRKKVAK
                    *********** *********** .::*********:********:: *: *.*:**..*

  ```
</details> 

<details>
  <summary>cluster_2</summary>
    
  ```  
  CLUSTAL 2.1 multiple sequence alignment


WP_238323772.1      ------------MSTGVIFSLVTALGLIRLPDVYTRTHAASKSSTLGVLCVLLAAFIHFW
WP_236610195.1      ------------MSTGVIFSLVTALGLIRLPDVYTRTHAASKSSTLGVLCVLLAAFIHFW
WP_071153796.1      ------------MSTGVIFSVVTALGLIRLPDVYTRTHAASKSSTLGVLCVLLAAFIHFW
WP_040851819.1      ------------MSTGVVFSLVTALGLIRLPDVYTRTHASSKSSTLGVLCVLLATFIHFW
WP_112224415.1      MTTIANILIIILISAGVLFSVVTALGLVRLPDVYTRTHAASKSSTLGVLAILSGTFIHFW
                                :*:**:**:******:***********:*********.:* .:*****

WP_238323772.1      LIEGIFNTQLIIAIAFLFITAPVGGHLIGRAAYMSGISVADETVRDDMEVAIKNQKNELL
WP_236610195.1      LIEGIFNTQLIIAIAFLFITAPVGGHLIGRAAYMSGISVADETVRDDMKVAIKNKKDELL
WP_071153796.1      LIEGIFNTQLIIAIAFLFITAPVGGHLIGRAAYMSGIKVTEETVRDDMKDAVKEAKQELR
WP_040851819.1      LVEGIFNTQMIIAIAFLFITAPVGGHLIGRAAYMSGIKVAEETVRDDMEDALAEQKKKLM
WP_112224415.1      LIEGIFNTQMIIAIAFLFITAPVGGHLIGRAAYISGTKVAEQTVRDDLGPAVERKKKRFA
                    *:*******:***********************:** .*:::*****:  *: . *..: 

WP_238323772.1      NNKTPEE
WP_236610195.1      NNKTPEE
WP_071153796.1      DRKPTEL
WP_040851819.1      DNKTTEQ
WP_112224415.1      LKKESN-
                     .* .: 
    ```
</details> 


<details>
  <summary>cluster_3</summary>
    
  ```  
  CLUSTAL 2.1 multiple sequence alignment


WP_006828953.1        MARKQQTRKRRVKKNIESGIAHIRSTFNNTIVTITDMQGNAVSWSSAGALGFRGSRKSTP
WP_006828953.1_2      MARKQQTRKRRVKKNIESGIAHIRSTFNNTIVTITDMQGNAVSWSSAGALGFRGSRKSTP
WP_006828953.1_3      MARKQQTRKRRVKKNIESGIAHIRSTFNNTIVTITDMQGNAVSWSSAGALGFRGSRKSTP
WP_006828953.1_4      MARKQQTRKRRVKKNIESGIAHIRSTFNNTIVTITDMQGNAVSWSSAGALGFRGSRKSTP
WP_008497448.1        MARKQQTRKRRVKKNIESGIAHIRSTFNNTIVTITDMQGNAVSWSSAGALGFRGSRKSTP
                      ************************************************************

WP_006828953.1        FAAQMAAETAAKTSIEHGLKTLEVTVKGPGSGREAAIRALQAAGLEVTAIKDVTPVPHNG
WP_006828953.1_2      FAAQMAAETAAKTSIEHGLKTLEVTVKGPGSGREAAIRALQAAGLEVTAIKDVTPVPHNG
WP_006828953.1_3      FAAQMAAETAAKTSIEHGLKTLEVTVKGPGSGREAAIRALQAAGLEVTAIKDVTPVPHNG
WP_006828953.1_4      FAAQMAAETAAKTSIEHGLKTLEVTVKGPGSGREAAIRALQAAGLEVTAIKDVTPVPHNG
WP_008497448.1        FAAQMAAEAAAKTSIEHGLKTLEVTVKGPGSGREAAIRALQAAGLEVTAIKDVTPVPHNG
                      ********:***************************************************

WP_006828953.1        CRPPKRRRV
WP_006828953.1_2      CRPPKRRRV
WP_006828953.1_3      CRPPKRRRV
WP_006828953.1_4      CRPPKRRRV
WP_008497448.1        CRPPKRRRV
                      *********
    ```
</details> 


<details>
  <summary>cluster_4</summary>
    
  ```  
  CLUSTAL 2.1 multiple sequence alignment


WP_071153694.1      MMRKAEIKRNTNETKVAIKFSLDGEGKSVIDTGVPFMDHMLDLFIKHGLFDGDITADGDT
WP_197684182.1      -MRKAEIKRNTNETKVAINFSLDGEGKSVIDTGVPFMDHMLDLFIKHGLFDGDIKADGDT
WP_065526851.1      -MRQAEIKRNTNETKVAINFSLDGEGKSVIDTGVPFMDHMLDLFIKHGLFDGEIKADGDT
WP_008496052.1      -MRQAEIKRNTNETKVAISFALDGEGKSVIDTGVPFMDHMLDLFIKHGLFDGDIKADGDT
WP_112224562.1      MMRKAELKRNTNETKIDIAFSLDGEGKADIETGVPFMDHMLDLFIKHGLFDGDIKADGDT
                     **:**:********: * *:******: *:*********************:*.*****

WP_071153694.1      HIDDHHTTEDIGIVLGQAVKEALGDKKGIRRYGNAFVPMDDALAQVIIDCSNRPHLEFRS
WP_197684182.1      HIDDHHTTEDIGIVLGQAVKEALGDKKGIRRYGNAFVPMDDALAQVVIDCSNRPHLEFRS
WP_065526851.1      HIDDHHTTEDIGIVLGQAVKEALGDKKGIRRYGNAFVPMDDALAQVVIDCSNRPHLELRC
WP_008496052.1      HIDDHHTTEDIGIVLGQAVKEALGDKKGIRRYGNAFVPMDDALAQVVIDCSNRPHLEFRC
WP_112224562.1      HIDDHHTTEDIGIVLGQAVREALGDKKGIRRYGNAFVPMDDALAQVVIDCSNRPHLEFRG
                    *******************:**************************:**********:* 

WP_071153694.1      QPLTEKVGTFDTELIQEFLWKFALESRMNVHVIVHYGKNTHHIIEAIFKALARALDEATM
WP_197684182.1      QPLNEKVGTFDTELIQEFLWKFALESRMNVHVIVHYGKNTHHIIEAIFKALARALDEATG
WP_065526851.1      DSLKEKVGTFDTELVEEFLWKFALESRMNVHVIVHYGKNTHHIIEAIFKALARALDEATM
WP_008496052.1      ELPKEKVGTFDTELVEEFLWKFALESRMNVHVIVHYGKNTHHIIEAIFKALARALDEATM
WP_112224562.1      DIPNEKVGTFDTELVYEFLWKFALESRMNVHVIIHYGKNTHHIIEAVFKALARALDEATS
                    :  .**********: *****************:************:************ 

WP_071153694.1      IDPRVKGVPSTKGLLT
WP_197684182.1      IDPRVKGVPSTKGLLT
WP_065526851.1      IDPRVKGVPSTKGLLT
WP_008496052.1      IDPRVKGVPSTKGLLT
WP_112224562.1      IDPRVKGVPSTKGLLT
                    ****************
    ```
</details> 


<details>
  <summary>cluster_5</summary>
    
  ```  
  CLUSTAL 2.1 multiple sequence alignment


WP_065526596.1      MEKPMTVAQSLRHARHDFLNDLQLIKMNMDLGRLQEAQALIRSYAEASMHASRLADIGLP
WP_008498931.1      MEKPMTVAQSLRHARHDFLNDLQLIKMNLDLGRLQEAQALIRSYAEASMHASRLADIGLP
WP_071154348.1      MEKPMTVAQSLRHARHDFLNELQLIKMNLDLGRLQEAQAIIRSHAEASMHASRLADIGLP
WP_065537022.1      MEKTMTVAQSLRHARHDYLNELQLIKLNLDLGRLQEAQVIIRSHAEAAMHASRLSDIGLP
WP_112223746.1      MDDSITVAQALRHARHDFLNELQLIQMKLDLGRGQDVKSIIRSRAEAAVQLNRLSALKMP
                    *:..:****:*******:**:****::::**** *:.: :*** ***::: .**: : :*

WP_065526596.1      LTEEWLLTVNWRFPGFNFLVECQAVAAPAHLDGEFRRFLEGFVELAKKQLSPYQVFDCEI
WP_008498931.1      LTEEWLLTVNWRFPGFNFHVECQAVTAPAHLDGEFRRFLDDFVELAKKHLSPYQVFDCEM
WP_071154348.1      LTEEWLLTANWRFLEFDFQVMCLAVQAPAQKDAELRCFLEDFVQSAKLHLTPYEVYSSEI
WP_065537022.1      LTEEWLLTANWRFPECCFHVECLAVKAPSHLDAAFRRFLESFVETAKERLDSYQAFHGTI
WP_112223746.1      AAEHWLLTAEWRFPEFRFHLECLAQAGITTKDAAFADWLEQFFSSLKEQADTASDISCRT
                     :*.****.:***    * : * *  . :  *. :  :*: *..  * :  . .      

WP_065526596.1      LLTSDAAFFEIIIKCSESWPDLKLVETDGFTVRKECSEDGTIVAVRAQMEG
WP_008498931.1      LLKSDAAFFEINIKCSESWPDLNIVEADGFTVRKECSEDSTMIAVRAQMEG
WP_071154348.1      LLTSSSSFFEISITGPGSWLDLELVESAGFTVTKECSEDSVMIVVRAQMEG
WP_065537022.1      LLISTTASFEMNITCPGNWLNLELSEAPGFTVRKECSEDSTMIAVRAQMEG
WP_112223746.1      VLKEQQSDFEIGLDLNGNLPDTQLPEVPGLLARKEIAADSLKIIVSAKMEG
                    :* .  : **: :    .  : :: *  *: . ** : *.  : * *:***
    ```
</details> 


<details>
  <summary>cluster_6</summary>
    
  ```  
  CLUSTAL 2.1 multiple sequence alignment


WP_058385912.1      MIIGIIDYGMGNLFSVEQALKKLECTVIVSDDPAVLLEAEGILLPGVGAFPDAMELLNDK
WP_065537124.1      MIIGIIDYGMGNLFSVEQALKKLECTVIVSDDPAVLLEAEGILLPGVGAFPDAMELLNEK
WP_008496053.1      MIIGIIDYGMGNLFSVEQALKKLECTVIVSDDPAVLVEAEGILLPGVGAFPDAMELLNQK
WP_065526850.1      MIIGIIDYGMGNLFSVEQALKKLECTVIISDDPAVLEEAEGIILPGVGAFPDAMELLNQK
WP_112224485.1      MIIGIIDYGMGNLFSVEQALKKLDCTVILSDDPETLLEAEAILLPGVGAFPDAMELLNSK
                    ***********************:****:**** .* ***.*:***************.*

WP_058385912.1      GLSGFIQSLPEKNIPLLGICLGMQLLYEDSSEVKPTKGLGLLTGQIRRFEKGTYRIPHMG
WP_065537124.1      GLSKFIQSLKEKNIPLLGICLGMQLLYEDSSEVKSTKGLGLLTGQIRRFEKGTYRIPHMG
WP_008496053.1      GLSEFIQSLPSKNIPLLGICLGMQLLYEDSSEVKPTKGLGLLEGQIRRFEKGTYRIPHMG
WP_065526850.1      GLSEFIQSLPEKNIPLLGICLGMQLLYEDSSEVKPTKGLGLLTGQIRRFEKGTYRIPHMG
WP_112224485.1      GLSEFIRSLPEKGIPLLGICLGMQLLYEDSLEVRMTKGLGLLKGKIRRFEKGTYRIPHMG
                    *** **:** .*.***************** **: ******* *:***************

WP_058385912.1      WNRLEFSHMPYWLEDVLSDTHVYFVHSFLAINTKQQEVLATASYGGLNVPGVVGTGLITG
WP_065537124.1      WNRLEFSRVPYWLDEVLSDTHVYFVHSFLAVNTNEQEVWATASYGGLNVPGVVGNGLITG
WP_008496053.1      WNRLEFSSVPYWLDDVLSDTHVYFVHSFLAVNTNKQQVWATASYGELDVPGVVGTGLITG
WP_065526850.1      WNRLEFSHMPYWLDDLLSDTHVYFVHSFLAVNTKEQEVLATASYGNSSVPGVVGKGLITG
WP_112224485.1      WNRLEFPRMPFWLDSLQVDTHVYFVHSFYVTEAEETEIFAEAEYGNIKVPGVVGKGLVTG
                    ******. :*:**:.:  ********** . :::: :: * *.**  .******.**:**

WP_058385912.1      MQFHPEKSGDFGHYLLEQWISNVR-------RNLHV-
WP_065537124.1      MQFHPEKSGDFGHHLLEQWISNVR-------RNLHV-
WP_008496053.1      MQFHPEKSGDFGHYLLEQWIANVR-------RNLND-
WP_065526850.1      MQFHPEKSGDFGHYLLEQWIANVR-------RNLND-
WP_112224485.1      MQFHPEKSGDFGHYLLEQWIANIKGDNNGQLSNLSGN
                    *************:******:*::        **   
    ```
</details> 


<details>
  <summary>cluster_7</summary>
    
  ```  
  CLUSTAL 2.1 multiple sequence alignment


WP_065527560.1      MNSIILSFENVTFTYMQEDESVKPAVKDLSFSIEDGEWIALVGHNGSGKSTIAKLMNGLL
WP_040850764.1      MNSIILSFENVTFTYMQEDESVKPAVKDLSFSIQDGEWIALVGHNGSGKSTIAKLMNGLL
WP_071154690.1      MNSTILSFENVTFTYTQEDESVKPAVADLSFSIQDGEWIALVGHNGSGKSTIAKLMNGLL
WP_006828956.1      MNSIILSFENVTFTYAQEDESVKPAVQDLTFSIQDGEWIALVGHNGSGKSTIAKLMNGLL
WP_112224781.1      MNTEILSFENVTFTYNTEDETMRPAVENVTFSIESGEWIALVGHNGSGKSTMAKLMNGLL
                    **: ***********  ***:::*** :::***:.****************:********

WP_065527560.1      FPQAGKVEAMSKLMTEQSLWDIRSQMGMVFQNPDNQFVGATVQDDVAFALENNGVPHEEM
WP_040850764.1      FPQTGKVEAIGKLMTEESLWDIRSQMGMVFQNPDNQFVGATVQDDVAFALENNGVPHEEM
WP_071154690.1      FPQTGQVSAMGKLMAEESLWDIRSQMGMVFQNPDNQFVGATVQDDVAFALENNGVPHKEM
WP_006828956.1      FPQTGKVSAMGKLMAEESLWDIRSEIGMVFQNPDNQFVGATVQDDVAFALENNGVPHEEM
WP_112224781.1      FPNEGKVKVFGHTMSEETLWDIRSQMGMVFQNPDNQFVGATVQDDVAFALENNGVPHAQM
                    **: *:*..:.: *:*::******::******************************* :*

WP_065527560.1      VVRVKEALQQVKMADYLDHEPHHLSGGQKQRVAIAGALALRPRLLILDEATSMLDPQGRM
WP_040850764.1      VVRVKEALQQVKMADYLDHEPHHLSGGQKQRVAIAGALAMRPRLLILDEATSMLDPQGRM
WP_071154690.1      VVRVKEALHQVKMDDYLDHEPHHLSGGQKQRVAIAGALALRPRLLILDEATSMLDPQGRM
WP_006828956.1      VVRVKEALHQVKMEAYLDHEPHHLSGGQKQRVAIAGALALRPRLLILDEATSMLDPQGRM
WP_112224781.1      VERVHVALSQVKMEDYKDHEPHHLSGGQKQRVAIAGALAMRPKLLILDEATSMLDPQGRM
                    * **: ** ****  * **********************:**:*****************

WP_065527560.1      EVIETIRELKEATGLTVISITHDLEEAALADRILVMNAGEKQLEGKPDVVFRSGNELTNL
WP_040850764.1      EVIETIRELRKATGLTVISITHDLEEAALADRILVMNAGEKQLEGKPEAVFLSSNELTNL
WP_071154690.1      EVIETIRELREATGLTVISITHDLEEAALADRILVMNAGHKQLEGIPESVFLSGNELTTL
WP_006828956.1      EVIETIRELREATGLTVISITHDLEEAALADRILVMNAGHKQLEGTPKEVFLSGNELTTL
WP_112224781.1      EVIETIRRLRESTGLTVISITHDLEEAALAERIIVMNRGQKHVEGTPAAVFNEGSELTEM
                    *******.*:::******************:**:*** *.*::** *  ** ...*** :

WP_065527560.1      GLDLPFSMRMTHLLREVGIELQGEHMTEDELVDELWTFYSRK
WP_040850764.1      GLDLPFSMRMTHLLREVGVELQGEHMTEDELVDELWTFYSRK
WP_071154690.1      GLDLPFSMRMTHLLREAGVALQGEHMTEEELVDELWTFYSRK
WP_006828956.1      GLDLPFAMRMTHLLQEAGVALQGEHMTEDELVDELWTFYSGK
WP_112224781.1      GLDLPFAMRMTHLLQEAGVALQEEHMTEDKLVDELWKYYSRA
                    ******:*******:*.*: ** *****::******.:**  
    ```
</details> 


<details>
  <summary>cluster_8</summary>
    
  ```  
  CLUSTAL 2.1 multiple sequence alignment


WP_065525482.1      MSYATQKLAEEKVFKDPVHRYIHVRDQVIWDLINSREVQRLRRIKQLGTSYLVFHGAEHS
WP_008496849.1      MSYATQKLAEEKVFKDPVHRYIHVRDQVIWDLINSREVQRLRRIKQLGTSYLVFHGAEHS
WP_058384417.1      MSYATQKLAEEKVFKDPVHRYVHVRDQVIWDLINSREVQRLRRIKQLGTSYLVFHGAEHS
WP_006829289.1      MSYATQKLAEEKVFKDPVHRYIHVRDQVIWDLINSREVQRLRRIKQLGTSYLVFHGAEHS
WP_135815226.1      MDYANQKLAEEKVFKDPVHRYIHVRDQVIWDLINAREFQRMRRIKQLGTSYLVFHGAEHS
                    *.**.****************:************:**.**:*******************

WP_065525482.1      RFNHSLGVYEIVRRISDDIFHGRPEWDESERLVVLCAALLHDLGHGPFSHSFEKVFALDH
WP_008496849.1      RFNHSLGVYEIVRRISDDIFHGRPEWDESERLVVLCAALLHDLGHGPFSHSFEKVFALDH
WP_058384417.1      RFNHSLGVYEIVRRISDDIFHGRPEWDENERLVVLCAALLHDLGHGPFSHSFEKVFSVDH
WP_006829289.1      RFNHSLGVYEIVRRISDDIFHGRPEWDESERLVVLCAALLHDLGHGPFSHSFEKVFAVDH
WP_135815226.1      RFSHSLGVYEIVRRILDDIFHGRPEWDESERLVVLCAALLHDLGHGPFSHSFEKVFNVDH
                    **.************ ************.*************************** :**

WP_065525482.1      EEYTRKILLGDTEVNEILQKVSTDFPTKVAEVIAKTYSNKQVVSLISSQIDADRMDYLQR
WP_008496849.1      EEYTRKILLGDTEVNEILQKVSTDFPTKVAEVIAKTYSNKQVVSLISSQIDADRMDYLQR
WP_058384417.1      EEFTRKILLGNTEVNEILQNVSPEFPTKVAEVIAKTYSNKQVVSLISSQIDADRMDYLQR
WP_006829289.1      EEFTRKILLGNTEVNEILQKVSPEFPTKVAEVIAKTYSNKQVVSLISSQIDADRMDYLQR
WP_135815226.1      EDFTREILQGDTEVNSILKKVAADFPKKVAEVIGKTYANKQVVSLISSQIDADRMDYLQR
                    *::**:** *:****.**::*:.:**.******.***:**********************

WP_065525482.1      DAYYTGVSYGHFDMERILRVMRPLDDQVVIKSSGMHAVEDYIMSRYQMYWQVYFHPVARS
WP_008496849.1      DAYYTGVSYGHFDMERILRVMRPLDDQVVIKSSGMHAVEDYIMSRYQMYWQVYFHPVARS
WP_058384417.1      DAYYTGVSYGHFDMERILRVMRPLGDQVVIKSSGMHAVEDYIMSRYQMYWQVYFHPVARS
WP_006829289.1      DAYYTGVSYGHFDMERILRVMRPLDDQVVIKSSGMHAVEDYIMSRYQMYWQVYFHPVARS
WP_135815226.1      DAYYTGVSYGHFDMERILRVMRPFEDQVVIKSSGMHAVEDYIMSRYQMYWQVYFHPVARS
                    ***********************: ***********************************

WP_065525482.1      AEVILRKILQRAKELSASGYKFEQPPTHFLSFFDQSFTLKEYLALDEGVLMTYFQLWMTE
WP_008496849.1      AEVILRKILQRAKELSASGYKFEQPPTHFLSFFDQSFTLKEYLALDEGVLMTYFQLWMTE
WP_058384417.1      AEVILRKILQRAKELSGNGYKFEQPPTHFLSFFDRSFTLKDYLALDEGVLMTYFQLWMTE
WP_006829289.1      AEVILRKILQRAKELSESGYKFEQPPTHFLSFFDRSFTLKDYLALDEGVLMTYFQLWMTE
WP_135815226.1      AEVILRKILQRAKYLSGHGYKFEQPPTHFLAFFDQSFTLKDYLALDEGVLMTYFQLWITE
                    ************* **  ************:***:*****:****************:**

WP_065525482.1      RDPILADLCDRFVNRRLFQYVDFDPGKDYKKLGELAELFRSAGIDPEYYLIDDSTSDLPY
WP_008496849.1      RDPILADLCDRFVNRRLFQYVDFDPGKDYKKLGELAELFRSAGIDPEYYLIDDSTSDLPY
WP_058384417.1      RDPILSDLCDRFVNRRLFQYVDFDPAKNYKKLGELTELFRSAGIDPEYYLIDDSTSDLPY
WP_006829289.1      RDPILSDLCDRFVNRRLFQYVDFDPANNYKKLGELEELFRSAGIDPEYYLIDDSTSDLPY
WP_135815226.1      RDPILSDLCDRFVNRRLFQYVDFDPGKDYKKLGELAQLFQKAGIDPEYYLIDDSTSDLPY
                    *****:*******************.::******* :**:.*******************

WP_065525482.1      DFYRPGEEEERLPIHLLMPNGDIKELSRLSQIVDAISGKRRTDYKLYFPAELLIDGKKTA
WP_008496849.1      DFYRPGEEEERLPIHLLMPNGDIKELSRLSQIVDAISGKRRTDYKLYFPAELLIDGKKTA
WP_058384417.1      DFYRPGEEEERLPIHLLMPNGDIKELSRLSQIVDAISGKRRTDYKLYFPAELLIDGKKTA
WP_006829289.1      DFYRPGEEEERLPIHLLMPNGDIKELSRLSQIVDAISGKRRTDYKLYFPAELLIDGKKKA
WP_135815226.1      DFYRPGEEEERLPIHLLMPTGDIKELSRLSQIVDGISGKRRTDYKLYFPAELLIDGKKKE
                    *******************.**************.***********************. 

WP_065525482.1      IKQQILEMLREGGV
WP_008496849.1      IKHQILEMLREGGI
WP_058384417.1      IKQQILEMLREGGV
WP_006829289.1      IKQQILEMLREGGV
WP_135815226.1      IKQQILELLREGGV
                    **:****:*****:
    ```
</details> 


<details>
  <summary>cluster_9</summary>
    
  ```  
  CLUSTAL 2.1 multiple sequence alignment


WP_065526296.1      MVEKQFTITDEAGMHARPASALVGAVSKFSSDITLEHNGKKVNLKSILGVMSLGIPSGSV
WP_008496420.1      MVEKQFTITDEAGMHARPASALVGAVSKFTSDITLEHNGKKVNLKSILGVMSLGIPSGSV
WP_058385357.1      MVEKQFTITDEAGMHARPASALVGAVSKFKSDITIEHKGKKVNLKSILGVMSLGVPSGSV
WP_006829589.1      MVEKQFTITDEAGMHARPASALVGAVSKFKSDITIEHKGKKVNLKSILGVMSLGVPSGSV
WP_112222408.1      MTEKQFTITDEAGMHARPASALVGTVSKFKSDIQLEYKGKKVNLKSILGVMSLGISSGSV
                    *.**********************:****.*** :*::****************:.****

WP_065526296.1      VTIAADGPDENEAIEQAGAVMEKEGISNQ
WP_008496420.1      VTIAADGADENEAIEQAGAVMEKEGISNQ
WP_058385357.1      VTIAADGEDENEAIEQATAVMEKEGISNQ
WP_006829589.1      VTIAADGEDENEAIEKAADVMNTEGISTQ
WP_112222408.1      VTISADGEDEDEAMAKIEEAMKAEGISN-
                    ***:*** **:**: :   .*: ****. 
    ```
</details> 


<details>
  <summary>cluster_10</summary>
    
  ```  
  CLUSTAL 2.1 multiple sequence alignment


WP_038703546.1        -----MNVNDGIRARELRVIDQNGEQLGIKTRIEALEIAARVNLDLVLVAPQAKPPVARI
WP_039863440.1        -----MNVNDGIRARELRVIDQNGEQLGIKTRIEALEIAARVNLDLVLVAPQAKPPVARI
WP_039863440.1_2      -----MNVNDGIRARELRVIDQNGEQLGIKTRIEALEIAARVNLDLVLVAPQAKPPVARI
WP_040852855.1        -----MNVNEGIRARELRVIDQNGEQLGIKTRNEALEIAARVNLDLVLVAPQAKPPVARI
WP_218673378.1        MISKDSNVNEGIRARELRVIDQNGEQLGIKTRNEALEIAGRVNLDLVLVAPQAKPPVARI
                            ***:********************** ******.********************

WP_038703546.1        MDHGKFKFEQQKKDREIRKNQKVIIVKEVRLSPSIDDHDFNTKLRNAIKFLEKGDKVKAS
WP_039863440.1        MDHGKFKFEQQKKDREIRKNQKVIVVKEVRLSPSIDDHDFNTKLRNAIKFLEKGDKVKAS
WP_039863440.1_2      MDHGKFKFEQQKKDREIRKNQKVIVVKEVRLSPSIDDHDFNTKLRNAIKFLEKGDKVKAS
WP_040852855.1        MDHGKFKFEQQKKDREIRKNQKVIVVKEVRLSPSIDDHDFNTKLRNAIKFLEKGDKVKAS
WP_218673378.1        MDHGKFKFEQQKKEREIRKNQKVIVVKEVRLSPGIDDHDFNTKLRNAIKFLEKGDKVKAS
                      *************:**********:********.**************************

WP_038703546.1        IRFKGRAITHKEIGQRVLERFAEACKEVATVEQRPKMDGRSMFLMLAPVNEKE
WP_039863440.1        IRFKGRAITHKEIGQRVLERFAEACKEVATVEQRPKMDGRSMFLMLAPVNEKE
WP_039863440.1_2      IRFKGRAITHKEIGQRVLERFAEACKEVATVEQRPKMDGRSMFLMLAPVNEKE
WP_040852855.1        IRFKGRAITHKEIGQRVLERFAEACKEVATVEQRPKMDGRSMFLMLAPVNEKE
WP_218673378.1        IRFKGRAITHKEIGQRVLERFAEACKEVATVEQRPKMDGRSMFLMLAPVNEKE
                      *****************************************************
    ```
</details> 
