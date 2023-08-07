# 2022-HumanNutrition
The present article explores a systematic study in regard to the dietary habits of human populations inside various domains, as a way of demonstrating practically and methodically the possibilities brought upfront by associated data.

# ANutriçãoHumana:UmaAnálisedeDados

```
BernardoR.deAlmeida^1 ,LucasM.Almeida^2 ,IgorJoaquimdaS.Costa^3
```
DepartamentodeCiênciadaComputação-UniversidadeFederaldeMinasGerais(UFMG)
BeloHorizonte-MinasGerais-Brasil
bera01@ufmg.br(2021032234)^1 , lucas.ma598@gmail.com(2021031840)^2 ,
igor.joaquim@dcc.ufmg.br(2021032218)^3
**_Abstract._** _Thepresentarticleexploresasystematicstudyinregardtothedietary
habitsofhumanpopulationsinsidevariousdomains,asawayofdemonstrating
practically and methodically the possibilities brought upfrontby associated
data. Inparticular, adatabasecontaininggeneralinformationoftheaverage
humandietinvariouscountrieswillbeelaboratedand,fromthat,insightswill
beextractedfromthepointofviewofdifferentareasofstudy,suchasscience,
sociology,publichealthand/orsimilar._
**_Resumo._** _O presente artigo explora um estudo sistemático dos hábitos
alimentaresdepopulaçõeshumanasemdiversosâmbitosafimdedemonstrar
demaneirapráticaemetódicaaspossibilidadesagregadaseminformações
relativas a esse domínio. Em particular, uma base de dados contendo
informaçõesgeraissobreadietadeváriospaísesseráorganizadae,apartir
dela,informaçõesepercepçõesserãoextraídastangenciandovariadasáreas
deestudo,sejamelasdaciência,sociologia,saúdee/oudeoutras._

## 1.Introdução

```
Anutrição humanaéum tema extremamenteamplodentrodasciências.Oshábitos
alimentaressempreforamumobjetodeestudodegrandeinteresse,agregandoquestões
físicas, políticas, acadêmicas, étnicas e culturais. A título de uma áreade estudos,
pode-sedizerqueanutriçãoestabeleceumagrandetangentecomdiversasoutrasárease
que, emfunçãodessesfatores,concentraumagamamuitovaliosaediversificadade
conhecimentos.Emparticular,dadosreferentesàdietadepopulaçõesabstraemmuitas
informaçõesquetomampartenessesdiversosaspectos,sejamelescontextospolíticos,
descobertascientíficas,padeceresclimáticosequestõescomoasaúdeeafisionomia.
```
```
Opresenteartigotemporobjetivojustamenteexplicitaressegrandepotencialda
nutriçãocomofontededadosedeinformações.Paratal,primeiramente,serárealizadaa
coletaeaorganizaçãodeumagrandebasededadosquemapeieaevoluçãodoshábitos
alimentares humanos ao longo de um período de tempo. Em seguida, análises
particulares serão realizadas, estudos sistemáticos serãoconduzidos,asinformações
coletadas serão resumidase ospotenciais insights serão explícitos, suportados por
pesquisasterceiraseportécnicasdaciênciadedados.
```
## 2.BasesdeDadosNutricionais

```
Osdadosacercadanutriçãohumanasãoprovenientesdeumcompiladodisponívelno
site OurWorldinData ,umainiciativaabertadaorganizaçãosemfinslucrativosGlobal
ChangeDataLabqueagregaváriasinformaçõesrelativasàdietadepopulações.Estas,
por sua vez, são provenientesda Food andAgricultureOrganizationof theUnited
Nations , órgão das Nações Unidas responsável pelocontrole da alimentação e da
agricultura.Emespecial,duasbasesdedadosserãoutilizadasparaaconstruçãodeum
```

compiladogeral.Ambassãorelativasàdietamédiadediversospaísesaolongodeum
determinadoperíodode tempo,porémsediferemna maneiracomoaalimentaçãoé
abstraídae,emparticular,nomodocomoéestratificadaemtermosnutricionais.

**2.1.DescriçãoInicialdasBasesdeDados**

Aprimeirabasededadoséconstruídasobreaparticipaçãopercentualdecadacategoria
de alimento na dieta de um indivíduo. Naturalmente, ela será denominada, por
simplicidade, de "Dieta por Subgrupo".Nela, é registrado o balanço de diferentes
gruposdealimentosnaalimentaçãomédiadaspopulaçõesdeváriospaísesaolongodo
tempo.Nototal,foramavaliados 173 paísesnoperíodode 1961 a2013.Emparticular,
hátrezecolunas:Entity:Nomedopaís;Code:Sigladopaís;Year:Anoaqueosdados
sereferem;Other:Consumomédiode"Outros";AlcoholicBeverages:Consumomédio
de"BebidasAlcoólicas";Sugar:Consumomédiode"Açúcar";Oils&Fats:Consumo
médio de "Óleos e Gorduras";Meat: Consumo médio de "Carne"; Dairy & Eggs:
Consumo médio de "Laticínios e Ovos"; Fruit and Vegetables:Consumomédio de
"Frutase Vegetais";StarchyRoots:Consumomédio de"RaízesAmiláceas";Pulses:
Consumomédiode"Leguminosas";CerealsandGrains:Consumomédiode"Cereaise
Grãos". Aqui, pontua-se que os dados dizem respeito à quantidade média de
quilocaloriasconsumidaporpessoa,pordia.Alémdisso,comomencionado,étratadoo
períodode 1961 a2013,inclusive,masnemtodosospaísespossuemregistrosemtodos
essesanos.Porfim,tambémseressaltaqueháregistrosacercadefederaçõesquenão
existemmais,oudepaísesdepreciados,comoaURSS.

A segunda base de dados estratifica a dieta pelaparticipação percentualde
macronutrientes. Seguindo a mesma lógica do caso anterior, por simplicidade,será
denominada "Dieta por Macronutriente".Nela, é registradoo balançode diferentes
macronutrientes na alimentaçãomédiadaspopulações deváriospaíses ao longodo
tempo.Nototal,foramavaliados 179 paísesnoperíodode 1961 a2013.Emparticular,
hásetecolunas:Entity:Nomedopaís;Code:Sigladopaís;Year:Anoaqueosdadosse
referem; Calories from animal protein: Consumo médio de calorias derivadas de
"ProteínaAnimal";Caloriesfromplantprotein:Consumomédiodecaloriasderivadas
de "Proteína Vegetal"; Calories from fat: Consumo médio decalorias derivadasde
"Gorduras"; Calories from carbohydrates: Consumo médio decalorias derivadasde
"Carboidratos".Asmesmasobservaçõesfeitasparaabasededadosanteriorquantoao
formatodasinformaçõestambémsãoválidasparaesta.

**2.2.LimpezaeOrganizaçãodasBasesdeDados**

Aprimeiracoisaaserfeitaéalimpezadasbasesdedados.Particularmente,valores
faltantes e questões de formatação serão tratados tendo-se emvista a clareza e a
relevânciadasinformaçõesagregadas.Aqui,define-se“valoresfaltantes”comoentradas
quenãocontêminformações(possuemosvalores _NULL_ ou _NaN_ ).

Emdetalhes, comrelaçãoà base“Dieta porSubgrupo”,acoluna"Code"foi
removida, dado que não agrega nenhuma informação particularmente útil para a
presenteanálise,easdemaisforamrenomeadasparafacilitaraleituraeainterpretação.


Alémdisso,osúnicosdadosfaltantesdiziamrespeitoàcoluna"AlcoholicBeverages",
relativaaosEmiradosÁrabesUnidos.Otratamentoescolhidofoiaremoçãodetodasas
entradaspertencentes aessanação, demodo quea basede dadospasse aenglobar
apenas 172 países.Emparticular,agora,hádozecolunasnototal:Country:Nomedo
país; Year: Ano a que osdados se referem; Other: Consumo médio de "Outros";
AlcoholicBeverages:Consumomédiode"BebidasAlcoólicas";Sugar:Consumomédio
de "Açúcar";Oils&Fats: Consumomédiode "ÓleoseGorduras";Meat:Consumo
médiode "Carne";Dairy& Eggs: Consumomédiode "LaticínioseOvos";Fruit&
Vegetables:Consumomédiode"FrutaseVegetais";StarchyRoots:Consumomédiode
"RaízesAmiláceas";Pulses:Consumomédiode"Leguminosas";CerealsandGrains:
Consumomédiode"CereaiseGrãos".

Analogamenteaocasoanterior,abase“DietaporMacronutriente”tambémfoi
tratada,comojádefinido.Porém,nestecaso,nãohaviamentradascomdadosfaltantes,
demodoqueasmodificaçõesrealizadasserestringiramàremoçãodacoluna"Code"eà
renomeaçãodasdemais-seguindoamesmalógicajádiscutida.Emparticular,agora,
aindahá 179 países,masapenasseiscolunasnototal:Country:Nomedopaís;Year:
Anoaqueosdadossereferem;AnimalProtein:Consumomédiodecaloriasderivadas
de"ProteínaAnimal";PlantProtein:Consumomédiodecaloriasderivadasde"Proteína
Vegetal"; Fat: Consumo médio decalorias derivadasde "Gorduras";Carbohydrates:
Consumomédiodecaloriasderivadasde"Carboidratos".

## 3.AnálisedosDados

Umapossívelabordagemquepodeserconsideradaparaefeitodeanálisedizrespeitoa
umasegregaçãoemcategorias,nocaso,formadaspelospaíses.Alémdeserplausível
estudarcomogruposdealimentos secomportamesecorrelacionaminternamente,é
possível usar os mesmos dados nutricionais paraentender o quãodiscrepantes são
diferentespaíses, combasenosseushábitosalimentares.Aotomar umpaís ouseu
continente como umavariável categórica, portas de estudos são abertase questões
interessantes são levantadas. Por exemplo, é esperado que países geograficamente
próximos possuam hábitos alimentares parecidos. Entretanto, é sabido que fatores
sociológicos,comoguerras, doenças,diferençasentresistemaseconômicoseeventos
históricos, possuem impacto direto na alimentação de um povo.Nesse sentido, ao
analisar categoricamente os dados nutricionais de um grupo de países, é possível
destrincharcomotaisfatorestiveram,ounão,impactonasnaçõesestudadas.

**3.1.AnáliseemVariáveisCategóricas:América**

Apartirdasbasesdedados,asinformaçõesreferentesaocontinenteamericanoforam
categorizadasemfunçãodaseparaçãodosgruposAméricadoNorte,AméricaCentrale
América do Sul. Umaprimeiraformade análisequepode serpensadadizrespeito
justamenteaoestudoeàcomparaçãodoshábitosalimentaresdepopulaçõespróximas.

Atabelaabaixomostraque,paragrandepartedosgruposdemacronutrientes,a
América do Norte é aquela que possuimaior variância e desvio padrão, o que é
esperado,vistoqueelaécompostaporapenas 5 países.


```
Tabela1.DesviopadrãodasAméricaspormacronutriente.
```
```
AnimalProtein PlantProtein Fat Carbohydrates
```
```
NorthAmerica 82.308993 33.979521 300.843547 222.
```
```
CentralAmerica 36.243639 25.145046 126.270690 230.
```
```
SouthAmerica 54.905340 19.809516 213.512405 165.
```
Odesviopadrãoéumamétricainteressantedeseranalisadapoiseleevidenciao
quãodistantedamédiaogrupoanalisadoé.Emparticular,vamosconsideraroconsumo
de gordura. Onível de consumo médio desse macronutrienteé odado commaior
variânciaentretodososcoletados.Aoenxergaroprimeirográficoaseguir,referenteaos
trêscontinentes,épossívelnotarque,emboraamédiadeconsumosejamaiorparaa
AméricadoNorte,existemfaixasdetempoemqueoconsumoempaísesdaAmérica
doSulfoimaior,oqueéumindíciodapossívelexistênciade“outliers”.Alémdisso,
comoépossívelvernosegundográficoaseguir,aRepúblicaDominicanaeoMéxico
sempreestãoabaixodamédia,enquantoosEUA,oCanadáeasBermudassemantêm
majoritariamentecomumconsumodegorduramaiorqueessamétrica.

```
Figura1.ConsumoanualmédiodegorduraentreastrêsAméricaseentreos
paísesdaAméricadoNorte.
```
Dos gráficosacima,épossívelextrair ainformaçãode queosEUAéopaís
americanoquemaisconsomegordura.Pelooutrolado,ográficoparaaAméricaCentral
mostraqueoHaitifoiopaísquemenosconsumiuessemacronutrientenasAméricas.


```
Figura2.ConsumoanualmédiodegorduraentreospaísesdaAméricaCentral
eadiferençaentreosconsumosdosEUAedoHaiti.
```
**3.2.AnáliseemVariáveisCategóricas:Renda**

O estudo de macronutrientes pode ser feito em um nível de abstração mais alto,
considerandoquais itenssãomaispresentesnadieta de certospovos e derivandoa
partiçãodecertomacronutrientenasuaprodução.Gerbens-leenes(2010)apresentaque:
"Pessoas em países de baixa renda obtêm energia nutricional principalmente de
carboidratos;a contribuiçãodegordurasé pequena.Pessoasempaísesdealtarenda
derivam sua energia nutricional principalmente de carboidratos e gorduras, com
contribuiçãosubstancialdecarneelaticínios".

Nessadiretriz,consideramosadefiniçãodainstituição _TheWorldBankGroup_
paraclassificarpaísesentrerendaalta,baixaemédia:aseconomiasdebaixarendasão
definidas comoaquelascomumRNB(RendaNacional Bruta)per capita,calculado
utilizandoométodo doAtlasdo BancoMundial,de $1.085oumenos em2021;as
economias derendimentomédioinferior sãoaquelascomumRNBpercapitaentre
$1.086e$4.255;aseconomiasderendimentomédiosuperiorsãoaquelascomumRNB
percapitaentre$4.256e$13.205;aseconomiasderendimentoelevadosãoaquelascom
umRNBpercapitade$13.205oumais.

Ao agregarcategoriasde rendaentreospaíses, novospadrões emergemdos
dados.Emumaprimeiraanálise,ahipótesedeGerbens-leenes(2010)semostracorreta
em relação aos carboidratos, visto que países de todas as rendas consomem esse
macronutrienteemgrandesmedidas.Comrelaçãoaospaísesderendaalta, oconsumo
degorduraseproteínaanimalénotavelmentediferentequandocomparadosaospaíses
de renda baixa e média, existindo indícios, portanto, de uma correlação entre o
desenvolvimentoeconômicodeumanaçãoeoconsumointernodessesmacronutrientes.

```
Figura3.Consumoanualmédiodecarboidratosedegordurasentrepaísesnas
trêscategoriasderenda:alta,médiaebaixa.
```
Umaoutraformadeabordaressaquestãoseriaconsiderarcadafaixaderenda
comoumadistribuiçãodeprobabilidadesdistinta.Dessamaneira,apósnormalizaros
dadosemrelaçãoà categoriaàqualcadapaís pertence,épossívelevidenciarqueo
consumodegorduraécorrelacionadopositivamenteaotempo,umavezque,conformeo


passardosanos,háumaumentonoconsumodessemacronutriente,emmédia.Além
disso,oconsumonormalizadodegordurasecomportaigualmenteemgruposdiferentes,
isto é, os dados coletados destoam da média de sua categoria da mesma forma,
independentedequalsejaovalordessamétrica.Porconsequência,aúnicadiferença
entreasfaixasderendaéovalorqueessamédiaassume,comogrupoderendaalta
possuindoduasvezesamédiadasoutrascategorias.

```
Figura4.Consumoanualmédiodegorduraentrepaísesderendaaltaepaíses
derendabaixaoumédia.
```
Ditoisso,seaspremissastomadasforemverdadeiras,épossívelclassificarum
paíssegundoasuarendausandoapenasinformaçõesdeconsumodemacronutrientes.
Paravalidaressaafirmação,seguimosalógicadeexperimentaçãoapresentadaaseguir:

1. Definiçãodevariáveisúteis:porhipótese,consideramosqueosdadossobreo
    consumo degordura, deproteína e decarboidratos sãodiscrepantesentreos
    diferentesníveisderenda;
2. Coleta deestatísticasagregadas:paracadavariávelescolhida,podemostomar
    comoestimadoresosseusparâmetrosAlphaeBeta-recolhidosdatécnicade
    regressãolinear-easuamédia;
3. Validaçãoda hipótese: paracada experimento,éfeitaumaregressãologística
    multivariadacom67%dosdadosservindocomotreinoe33%comoteste.Parao
    teste,éutilizadaatécnicadebootstrapparagerarintervalosde95%confiança
    sobreoresultado“score”daregressãologística.

Éesperadoqueosdadossobregorduraesobreproteínaanimalapresentemos
melhoresresultadosemcomparaçãoaosoutrosdadoscoletados.Alémdisso,éesperado
que nãoexistamelhora aoconsiderarapenasamédiadeumdadoemcomparaçãoa
consideraramédiaemconjuntocomosparâmetrosdeAlphaeBeta,vistoqueessas
estatísticasagregadasnãosãoindependentesentresi.

```
Aseguir,sãoapresentadosquaisosintervalosdeconfiançaencontradosparaa
```
eficáciadaregressão logísticafeitasobre cadaconjuntode estatísticasconsideradas,

ordenadospelaeficáciamédiadoteste:

```
Tabela2.Intervalosdeconfiançaeeficáciamédiaviabootstrapparacadacombinação
deestatísticaagregadaevariável.
```

```
IntervalodeConfiança95% EficáciaMédia
```
```
Médiapara
Gorduras
```
```
0.767-0.950 0.
```
```
Médiapara
Proteínas
```
```
0.767-0.950 0.
```
```
Alpha,BetaeMédiapara
Carboidratos,GorduraseProteínas
```
```
0.750-0.933 0.
```
```
Médiapara
Carboidratos,GorduraseProteínas
```
```
0.717-0.917 0.
```
```
Médiapara
Carboidratos
```
```
0.650-0.867 0.
```
```
AlphaeBetapara
Carboidratos,GorduraseProteínas
```
```
0.600-0.833 0.
```
```
Conclui-se,pois,queahipóteseinicialsemostraverdadeirae,portanto,queo
```
consumomédiode gordurapossuipotencialparaauxiliarnodiscernimentoentrepaíses

derendaaltaederendabaixaoumédia.

**3.3.Análiseemvariáveiscategóricas:PaísesSoviéticos**

Umdetalheparticularmenteinteressantesobreasbasesdedadosescolhidaséqueelas
contêminformaçõesacercadefederaçõesdepreciadas,istoé,quenãoexistemmais.Em
especial - e sob o contexto de análise das informações alimentares em variáveis
categóricas -, há dados acerca dos hábitosprevalecentes na União das Repúblicas
Socialistas Soviéticas(URSS) duranteseuperíodode existência.Umaperguntaque
surgenessecontextoéexatamenteoquantoadietamédiadaURSSrefleteadietamédia
dospaíses quea compõem.Apartirde algumastécnicasde análise,aseguir,serão
extraídosresultadosediscutidosindíciosquenorteiampossíveisrespostas.

Dentreaspossibilidadesprovenientesdosdados,aabordagemescolhidaserásob
grupos de alimentos, ao invés de macronutrientes, tendo em vista sua maior
granularidade,a qualpermiteatraçagemde ummapaalimentarmaisdetalhadoque
minimizedessemelhançasocultassoboagrupamentoemmacronutrientes.Apergunta
mencionadaanteriormentepodeserabstraídaporumahipótese,sejaela:adietamédia
daURSSrefleteadietamédiadospaísesqueacompõem.Emtermostécnicos,aideia
deuma"dietarefletiraoutra"foimodeladapormeiodedistribuiçõesdeprobabilidades.
Particularmente,ascalorias consumidasnadietasoviéticaestãodistribuídassobreos
diversosgruposdealimentosnabasededadosemvoga.Essadistribuiçãoconfiguraráo
modelo que, sob a hipótese nula, deve ser o mesmo sobre o qualas calorias dos
países-membros são distribuídas. O objetivo dessa análise, pois, é verificar a
factibilidadedesseresultado.


Nototal,aURSSfoicompostapor 15 nações:Armênia,Azerbaijão,Bielorrúsia,
Estônia, Geórgia, Cazaquistão, Quirguistão, Letônia, Lituânia, Moldávia, Rússia,
Tajiquistão,Turquemenistão, Ucrâniae Uzbequistão.Nabase dedados utilizada,há
registrosparaa uniãonoperíodode 1961 (iníciodacoletadedados)a 1991 (queda
dessaunidadefederativa),enquantoqueosregistrosparaospaíses-membroscomeçama
partirde1992,demodoqueoprocessodecoleta,aparentemente,tenhasidocoerente
em termoshistóricos. Tendo em vistaa minimização dediscrepânciasadvindasda
passagemdotempo,operfilalimentardaURSSserátraçadocomosdadosreferentesa
1991,enquanto queparaospaíses-membros,1992.Essasinformações,ainda,foram
normalizadas comrelação ao total de calorias, de modoque, agora,representema
participaçãopercentualdecadagrupodealimentonadietamédiadorespectivopaísou,
emoutraspalavras,adistribuiçãodesuascaloriasemcadacategoriaalimentícia.

```
Figura5.DistribuiçãodadietadaURSSem1991.
```
A hipótese nula define que as distribuições doshábitos alimentares dos 15
países-membroséadistribuiçãodeprobabilidadesdadietamédiadaURSS.Istoimplica
quequaisquerdiferençasseriamfrutoapenasdoacaso,ouseja,devariaçõesfactíveisno
processodeamostragem.Aqui,supõe-sequecadacaloriaéumavariávelaleatóriaque
segue a distribuição dada pelos dados referentes à URSS com relação ao grupo
alimentar ao qual pertence. Assim, os dados para cada país-membro seriamuma
amostra - de tamanho equivalenteà quantidadedecalorias médiaconsumida nessa
federação-dessapopulaçãodecalorias.Ahipótesealternativa,porsuavez,defineque
os dados paracada país-membro não seguem adistribuição dosdadosreferentes à
URSSepossivelmenteháoutrosfatorescríticosqueinfluenciamasdistribuiçõesalém
dachance.Aestatísticadetestefoidefinidacomoa _totalvariationdistance(TVD)_ entre
asdistribuiçõesdaamostraedomodelo.

Assumindo que a hipótese nula sejaverdadeira, paracada país-membro,foi
realizada uma simulaçãoda amostragemdesuarespectiva quantidadedecalorias a
partirdadistribuiçãoreferenteàURSS.Paratal,foiutilizadoomodelodedistribuição


de probabilidadesmultinomial,emque cadagrupodealimentofoiconsideradouma
categoriaassociadaaumaprobabilidadeespecífica.Ocálculodaestatísticafoirealizado
paracadaamostrasimulada, obtendo-seumadistribuiçãodosvaloresassumidospor
essamétrica.Particularmente,paracadaumdesses 15 países, 5000 simulaçõesforam
realizadassobomodelonulo,demodoque 5000 valoresdaestatísticadetesteforam
gerados,permitindoumaaproximaçãorazoáveldesuadistribuição.Aestatísticadeteste
tambémfoicalculadaparaosdadosreaisdecadafederaçãoe,comosvaloresreaise
comadistribuiçãosobomodelonuloemmãos,oestudosetornaumaquestãodeplotar
evisualizarosdadosparaavaliarafactibilidadedeasamostrasdecadapaís-membro
terem sido originadas de uma mesma distribuição de probabilidades, sendo esta
referenteàURSS.Aseguir,paracadaumdos 15 ditosintegrantes,tem-seohistograma
paraosvaloresda estatística simuladossoba hipótesenulaeumamarcação-linha
vermelhanoeixodasabscissas-paraovalordaestatísticadetestereal.

**Figura6.Resultadosdotestedehipóteseparaaalimentaçãosoviética.**
Apartirdosgráficos,énítidoquenenhumvalordaestatísticadetestereferente
aosdados reaisse aproximadosvaloresobtidosapartirdassimulaçõesfeitassobo
modelonulo.Umpassomaisfundo,emnenhumcasohouvesimulaçõesdentreas 5000
realizadas com resultados tão extremos quantoos dados reais. Essasinformações,
portanto,sãoumgrandeindíciodeinvalidadedahipótesenulaedevalidadedahipótese
alternativa,istoé,sãoumaevidênciafortedequeoshábitosalimentaresentreospaíses
soviéticosnomarcodefimdaURSS-atransiçãoentreosanos 1991 e 1992 - nãoeram
bem refletidospelos dados referentes à união. Vale ressaltarque osresultadosnão
explicamdeformaalgumaacausaparaadiscrepância,podendoelatersidoaforma
comque osdados foramextraídos,umamudançaabruptanaalimentaçãodospaíses
entreosanosavaliados,dentreoutras.Porém,osresultadosobtidosabremmargempara
todaumanovagamadeperguntas.Atítulodeexemplo,éperceptívelqueaestatísticade
testequemaisseaproximadassimulaçõeséreferenteàRússia,oqueéconformecomo
fatodeestepaís tersidooprincipalcentropolítico,econômicoeculturaldaURSS.
Nessalinhaderaciocínio,épossívelquestionarseaproximidadedaestatísticadeteste


aosvalores extremosda simulaçãonão estariacorrelacionadaaograudeatuaçãodo
respectivopaís-membronauniãocomoumtodo.

## 4.Conclusões

Asanálisesrealizadaspartemdeumescoporestritoàalimentaçãopropriamenteditae
expandem a perspectiva paraoutros campos doconhecimento, estabelecendonovas
tangentes e agregando diferentes insights. A abordagem via variáveis categóricas
permitiu tratar as discrepâncias entre os perfis nutricionais de diferentes países,
estabelecerparaleloscomfatoressocioeconômicosemumalógicadeavaliaçãodarenda
e discutirquestõespolíticas e culturaisemum contextode hábitosalimentares.Um
caminho de estudo interdisciplinar, pois, foi traçadoe exemplificaaspossibilidades
abertaspordadosrelacionadosàdietadaspopulações.

Emsuma,opresenteartigoabordouaquestãodanutriçãohumanasobaóticada
ciênciadedadosemumesforçodeenaltecerariquezadeinformaçõesassociadasaesse
domínio.Osexperimentosaquiabordadosrepresentamapenasumapequenaporçãodo
potencialagregadoemtalfontededadoseforamumamaneirametódicadedemonstrar
as possíveis aplicações práticas dentro dessa área. Em uma nota de finalização,
ressalta-se,portanto,ovalordessecampodeestudosesuafundamentalidadenosmais
diferentesâmbitospolíticos,econômicos,científicos,sociaiseculturais.

## Referências

Stack Exchange, Inc. Stack Overflow [Online]. Disponível em:
https://stackoverflow.com/(Acessadoem:18/12/2022).

GeeksforGeeks. GeeksforGeeks [Online]. Disponível em:
https://www.geeksforgeeks.org/(Acessadoem:18/12/2022).

NumFOCUS, Inc. Pandas [Online]. Disponível em: https://pandas.pydata.org/
(Acessadoem:18/12/2022).

Waskom, M. Seaborn: Statistical Data Visualization [Online]. Disponível em:
https://seaborn.pydata.org/index.html(Acessadoem:18/12/2022).

Ritchie,H.,Rosado,P.andRoser,M.(2017). _DietCompositions_ [Online].OurWorldin
Data. Disponível em: https://ourworldindata.org/diet-compositions (Acessado em:
18/12/2022).

TheWorldBankGroup. _WorldBankCountryandLendingGroups_ [Online].TheWorld
Bank. Disponível em:
https://datahelpdesk.worldbank.org/knowledgebase/articles/906519 (Acessado em:
18/12/2022).

Gerbens-leenes,P.(2010). _Foodconsumptionpatternsandeconomicgrowth.Increasing
affluence and the use of natural resources_ [Online]. Academia. Disponível em:
https://www.academia.edu/18139385/Food_consumption_patterns_and_economic_gr
owth_Increasing_affluence_and_the_use_of_natural_resources?auto=citations&from
=cover_page(Acessadoem:18/12/2022).


