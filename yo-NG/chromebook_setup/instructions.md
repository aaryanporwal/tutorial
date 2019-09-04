O lè [fo abala yìí kọjá](http://tutorial.djangogirls.org/en/installation/#install-python) tí ìwọ kò bá lo Chromebook kan. Tí o bá n lo, ìrírí ìṣàgbékalẹ̀ rẹ yíò yàtọ̀ díẹ̀. O lè fojú fo àwọn ìtọ́sọ́nà ìṣàgbékalẹ̀ yòókù náà.

### Cloud IDE (PaizaCloud Cloud IDE, AWS Cloud9)

Cloud IDE jẹ́ irinṣẹ́ kan èyí tí yíò fún ẹ ní olóòtú kóòdù kan àti anfààní sí kọ̀mpútà kan tó n ṣiṣẹ́ lórí íntánẹ́ẹ̀tì níbi tí o ti lè ṣàgbékalẹ̀, kọ, àti mú ètò náà ṣiṣẹ́. Fún àkókò ti àlàyé náà, cloud IDE yíò ṣiṣẹ́ gẹ́gẹ́ bí *kọ̀mpútà agbègbè* rẹ. Yóò ṣeéṣe fún ẹ láti ma ṣiṣẹ́ pẹ̀lú àwọn àṣẹ nínú atọ́kùn èbúté kan gẹ́gẹ́ bí àwọn ọmọ kíláàsì rẹ lórí OS X, Ubuntu, tàbí Windows, ṣùgbọ́n èbúté rẹ yíò gba ìsopọ̀ mọ́ kọ̀mpútà kan tó n ṣiṣẹ́ ní ibòmíràn tí cloud IDE gbé kalẹ̀ fún ẹ. Àwọn ìtọ́sọ́nà náà rèé fún àwọn cloud IDE (PaizaCloud Cloud IDE, AWS Cloud9). O lè yan ẹyọkan nínú àwọn cloud IDE náà, kí o sì tẹ̀lé ìtọ́sọ́nà ti cloud IDE náà.

#### PaizaCloud Cloud IDE

1. Lọ sí [PaizaCloud Cloud IDE](https://paiza.cloud/)
2. Forúkọ sílẹ̀ fún account kan
3. Tẹ *New Server*
4. Tẹ bọ́tìnnì Terminal (ní apá òsì ti fèrèsé náà)

Ní báyìí ó yẹ ko rí atọ́kùn kan pẹ̀lú pẹpẹ-ẹ̀gbẹ́ kan, àwọn bọ́tìnnì ní apá òsì náà. Tẹ bọ́tìnnì "Terminal" láti ṣí fèrèsé èbúté pẹ̀lú ìṣítí bíi èyí:

{% filename %}Terminal{% endfilename %}

    $
    

Èbúté náà lórí PaizaCloud Cloud IDE ti ṣetán fún àwọn àṣẹ rẹ. O lè ṣàtúnṣe ìwọ̀n fèrèsé yẹn láti mu kó tóbi díẹ̀ si.

#### AWS Cloud9

1. Lọ sí [AWS Cloud9](https://aws.amazon.com/cloud9/)
2. Forúkọ sílẹ̀ fún account kan
3. Tẹ *Create Environment*

Ní báyìí ó yẹ ko rí atọ́kùn kan pẹ̀lú pẹpẹ-ẹ̀gbẹ́ kan, fèrèsé pàtàkì nlá kan pẹ̀lú àwọn ọ̀rọ̀, àti fèrèsé kékeré kan ní ìsàlẹ̀ tó rí bíi èyí:

{% filename %}bash{% endfilename %}

    yourusername:~/workspace $
    

Agbègbè ìsàlẹ̀ yìí ni èbúté rẹ. O lè lo èbúté náà láti fi àwọn àṣẹ ránṣẹ́ sí kọ̀mpútà Cloud 9 tó jìnnà náà. O lè ṣàtúnṣe ìwọ̀n Ferese náà láti mú kó tóbi díẹ̀ si.

### Àyíká Àìrí

Àyíká àìrí kan (tí a tún pè ní virtualenv) dà bíi àpótí àdáni kan tí a lè kó kóòdù kọ̀mpútà tó wúlò sínú rẹ̀ fún iṣé kan tí a n ṣiṣẹ́ lórí. A má n lò wọ́n láti tọ́jú onírúurú àwọn ẹyọ kóòdù tí a fẹ́ fún onírúurú àwọn iṣẹ́ wa lọ́tọ̀ọ̀tọ̀ kí àwọn nnkan má lè dàpọ̀ láàrin àwọn iṣẹ́.

Nínú èbúté rẹ ní ìsàlẹ̀ atọ́kùn Cloud 9 náà, ṣe àwọn tó tẹ̀lé yìí:

{% filename %}Cloud 9{% endfilename %}

    sudo apt update
    sudo apt install python3.6-venv
    

Tí èyí kò bá tún ṣiṣẹ́, béèrè lọ́wọ́ olùkọ́ rẹ fún ìrànlọ́wọ́ díẹ̀.

Lẹ́yìn náà, ṣe:

{% filename %}Cloud 9{% endfilename %}

    mkdir djangogirls
    cd djangogirls
    python3.6 -mvenv myvenv
    source myvenv/bin/activate
    pip install django~={{ book.django_version }}
    

(ṣe àkíyèsí pé lórí ìlà ìkẹyìn a lo àmì fàágùn tí àmì ìdọ́gba sì tẹ̀le: `~=`).

### GitHub

Ṣẹ̀dá account [GitHub](https://github.com) kan.

### PythonAnywhere

Àlàyé Django Girls náà ní abala kan lórí nnkan tí a n pè ní Ìṣàgbékalẹ̀ (Deployment), eyi tó jẹ́ ìlànà mímú kóòdù tó n mú ètò ayélujára tuntun rẹ ṣiṣẹ́ àti gbígbé rẹ̀ sí kọ̀mpútà tó wà lárọ̀ọ́wọ́tó gbangba kan (tí a n pè ní server) kí àwọn èèyàn mìíràn le rí iṣẹ́ rẹ.

Apá yìí má jẹ́ àjèjì nígbà tí o bá n ṣe àlàyé náà lórí Chromebook kan níwọ̀n bí a ti n lo kọ̀mpútà kan tó ti wà lórí íńtánẹ́ẹ̀tì (tó jẹ́ òdìkejì sí, ká sọ pé, kọ̀mpútà àgbélétan kan). Àmọ́ o, ó ṣì wúlò, tí a bá ronú nípa ààyè-iṣẹ́ Cloud 9 wa gẹ́gẹ́ bíi ibi kan fún iṣé wa "ti ń lọ lọ́wọ́" àti Python Anywhere gẹ́gẹ́ bíi ibi kan láti ṣàfihàn iṣẹ́ wa bó ṣe n túbọ̀ péye.

Nítorí náà, forúkọ sílẹ̀ fún account Python Anywhere tuntun kan ní [www.pythonanywhere.com](https://www.pythonanywhere.com).