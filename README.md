# Skenaariovetoisen penetraatiotestauksen mallinnusmenetelmä

Tämä repositorio on tarkoitettu tukemaan skenaariovetoisen penetraatiotestauksen (SVPT) menetelmien mallinnusta. Se sisältää mallinnukset SVPT-metamenetelmästä ja tilannekohtaisista menetelmistä tietojenkalastelusimulaatioiden organisointiin. SVPT on kehitetty kuntien tarpeisiin, mutta se on usein sellaisenaan sovellettavissa myös muissa organisaatioissa.

Mallit on kehitetty [diagrams.net](https://diagrams.net/) -alustalla, jonka [lähdekoodi](https://github.com/jgraph/drawio) on avointa. Mallit on julkaistu vektorigrafiikkana (SVG) sekä rakenteisena tekstinä (XML), jonka myötä mallit ovat helposti tuotavissa takaisin em. ratkaisuihin ja muokattavissa edelleen. Kontribuutiot ovat tervetulleita.

SVPT perustuu uhka- ja hyökkäysskenaarioiden mallinnukseen sekä [tilannekohtaiseen menetelmäkehitykseen](https://link.springer.com/book/10.1007/978-3-642-41467-1). Uhkaskenaariot auttavat tunnistamaan kohdeyksikköön liittyviä kyberuhkia. Hyökkäysskenaariot auttavat hahmottamaan uhkiin liittyviä mahdollisia kyberhyökkäyksiä. Tilannekohtaiset penetraatiotestausmenetelmät muotoillaan skenaarioiden perusteella siten, että ne simuloivat osaltaan hyökkäysskenaarioiden toteutumista ja tuottavat siten tietoa kohdeyksikön varautumisen tasosta ko. hyökkäyksiin.

Tilannekohtaiset menetelmät perustuvat skenaariovetoisen penetraatiotestauksen [metamenetelmään](/mallit/svg/Metamenetelma.svg), joka pyrkii mallintamaan sovellusalueen tärkeimmät käsitteet ja niiden väliset yhteydet.

Esimerkkejä tilannekohtaisista menetelmistä:

[Tietojenkalastelusimulaatio avoimen lähdekoodin välineillä](/mallit/svg/Tietojenkalastelu1_OSS.svg)

[Tietojenkalastelusimulaatio SaaS-välineellä](/mallit/svg/Tietojenkalastelu1_SaaS.svg)

Tilannekohtaisten menetelmien jalkauttamiseen on tarjolla myös ketterän ohjelmistokehityksen periaatteita hyödyntävä [prosessimalli](/mallit/svg/Prosessimalli.svg).

SVPT on kehitetty osana Kuntien digi- ja kyberturvallisuuden testaus- ja kehittämismenettely -hanketta.
