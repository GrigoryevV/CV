<html xmlns:o="urn:schemas-microsoft-com:office:office"
xmlns:w="urn:schemas-microsoft-com:office:word"
xmlns="http://www.w3.org/TR/REC-html40">

<head>
<meta http-equiv=Content-Type content="text/html; charset=windows-1251">
<meta name=ProgId content=Word.Document>
<meta name=Generator content="Microsoft Word 11">
<meta name=Originator content="Microsoft Word 11">
<link rel=File-List href="way.files/filelist.xml">
<title>1981-1982 ДНУ Разработка алгоритмов и программирование на языке Фортран
ЕС ЭВМ преобразования Карунена-Лоэва для цифровой обработки нестационарных 
негауссовых сигналов</title>
<!--[if gte mso 9]><xml>
 <w:WordDocument>
  <w:PunctuationKerning/>
  <w:DrawingGridHorizontalSpacing>6 пт</w:DrawingGridHorizontalSpacing>
  <w:DrawingGridVerticalSpacing>6 пт</w:DrawingGridVerticalSpacing>
  <w:DisplayHorizontalDrawingGridEvery>0</w:DisplayHorizontalDrawingGridEvery>
  <w:DisplayVerticalDrawingGridEvery>3</w:DisplayVerticalDrawingGridEvery>
  <w:UseMarginsForDrawingGridOrigin/>
  <w:ValidateAgainstSchemas>false</w:ValidateAgainstSchemas>
  <w:SaveIfXMLInvalid>false</w:SaveIfXMLInvalid>
  <w:IgnoreMixedContent>false</w:IgnoreMixedContent>
  <w:AlwaysShowPlaceholderText>false</w:AlwaysShowPlaceholderText>
  <w:DoNotUnderlineInvalidXML/>
  <w:DoNotShadeFormData/>
  <w:Compatibility>
   <w:SpaceForUL/>
   <w:BalanceSingleByteDoubleByteWidth/>
   <w:DoNotLeaveBackslashAlone/>
   <w:ULTrailSpace/>
   <w:DoNotExpandShiftReturn/>
   <w:FootnoteLayoutLikeWW8/>
   <w:ShapeLayoutLikeWW8/>
   <w:AlignTablesRowByRow/>
   <w:ForgetLastTabAlignment/>
   <w:AdjustLineHeightInTable/>
   <w:LayoutRawTableWidth/>
   <w:LayoutTableRowsApart/>
   <w:UseWord97LineBreakingRules/>
   <w:SelectEntireFieldWithStartOrEnd/>
   <w:UseWord2002TableStyleRules/>
  </w:Compatibility>
  <w:BrowserLevel>MicrosoftInternetExplorer4</w:BrowserLevel>
 </w:WordDocument>
</xml><![endif]--><!--[if gte mso 9]><xml>
 <w:LatentStyles DefLockedState="true" LatentStyleCount="156">
  <w:LsdException Locked="true" Name="Default Paragraph Font"/>
  <w:LsdException Locked="true" Name="No List"/>
 </w:LatentStyles>
</xml><![endif]-->
<style>
<!--
 /* Font Definitions */
 @font-face
	{font-family:Wingdings;
	panose-1:5 0 0 0 0 0 0 0 0 0;
	mso-font-charset:2;
	mso-generic-font-family:auto;
	mso-font-pitch:variable;
	mso-font-signature:0 268435456 0 0 -2147483648 0;}
@font-face
	{font-family:"Calibri Light";
	panose-1:2 15 3 2 2 2 4 3 2 4;
	mso-font-charset:204;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-1610611985 1073750139 0 0 415 0;}
@font-face
	{font-family:Calibri;
	panose-1:2 15 5 2 2 2 4 3 2 4;
	mso-font-charset:204;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-536870145 1073786111 1 0 415 0;}
@font-face
	{font-family:TimesNewRomanPSMT;
	panose-1:0 0 0 0 0 0 0 0 0 0;
	mso-font-alt:"MS Mincho";
	mso-font-charset:128;
	mso-generic-font-family:auto;
	mso-font-format:other;
	mso-font-pitch:auto;
	mso-font-signature:1 134676480 16 0 131072 0;}
@font-face
	{font-family:"\@TimesNewRomanPSMT";
	panose-1:0 0 0 0 0 0 0 0 0 0;
	mso-font-charset:128;
	mso-generic-font-family:auto;
	mso-font-format:other;
	mso-font-pitch:auto;
	mso-font-signature:1 134676480 16 0 131072 0;}
 /* Style Definitions */
 p.MsoNormal, li.MsoNormal, div.MsoNormal
	{mso-style-parent:"";
	margin:0cm;
	margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman";
	mso-fareast-font-family:"Times New Roman";}
h1
	{mso-style-locked:yes;
	mso-style-link:"Заголовок 1 Знак";
	mso-style-next:Обычный;
	margin-top:12.0pt;
	margin-right:0cm;
	margin-bottom:3.0pt;
	margin-left:0cm;
	mso-pagination:widow-orphan;
	page-break-after:avoid;
	mso-outline-level:1;
	font-size:16.0pt;
	font-family:Arial;
	mso-font-kerning:16.0pt;}
h3
	{mso-style-locked:yes;
	mso-style-link:"Заголовок 3 Знак";
	mso-margin-top-alt:auto;
	margin-right:0cm;
	mso-margin-bottom-alt:auto;
	margin-left:0cm;
	mso-pagination:widow-orphan;
	mso-outline-level:3;
	font-size:13.5pt;
	font-family:"Times New Roman";}
a:link, span.MsoHyperlink
	{font-family:"Times New Roman";
	mso-bidi-font-family:"Times New Roman";
	color:blue;
	text-decoration:underline;
	text-underline:single;}
a:visited, span.MsoHyperlinkFollowed
	{mso-style-locked:yes;
	color:purple;
	text-decoration:underline;
	text-underline:single;}
span.1
	{mso-style-name:"Заголовок 1 Знак";
	mso-style-locked:yes;
	mso-style-link:"Заголовок 1";
	mso-ansi-font-size:16.0pt;
	mso-bidi-font-size:16.0pt;
	font-family:"Calibri Light";
	mso-ascii-font-family:"Calibri Light";
	mso-hansi-font-family:"Calibri Light";
	mso-bidi-font-family:"Times New Roman";
	mso-font-kerning:16.0pt;
	font-weight:bold;}
span.3
	{mso-style-name:"Заголовок 3 Знак";
	mso-style-noshow:yes;
	mso-style-locked:yes;
	mso-style-link:"Заголовок 3";
	mso-ansi-font-size:13.0pt;
	mso-bidi-font-size:13.0pt;
	font-family:"Calibri Light";
	mso-ascii-font-family:"Calibri Light";
	mso-hansi-font-family:"Calibri Light";
	mso-bidi-font-family:"Times New Roman";
	font-weight:bold;}
span.apple-converted-space
	{mso-style-name:apple-converted-space;
	font-family:"Times New Roman";
	mso-bidi-font-family:"Times New Roman";}
p.msolistparagraph, li.msolistparagraph, div.msolistparagraph
	{mso-style-name:msolistparagraph;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:8.0pt;
	margin-left:36.0pt;
	mso-add-space:auto;
	line-height:106%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:Calibri;
	mso-fareast-font-family:"Times New Roman";
	mso-bidi-font-family:"Times New Roman";
	mso-fareast-language:EN-US;}
p.msolistparagraphCxSpFirst, li.msolistparagraphCxSpFirst, div.msolistparagraphCxSpFirst
	{mso-style-name:msolistparagraphCxSpFirst;
	mso-style-type:export-only;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:36.0pt;
	margin-bottom:.0001pt;
	mso-add-space:auto;
	line-height:106%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:Calibri;
	mso-fareast-font-family:"Times New Roman";
	mso-bidi-font-family:"Times New Roman";
	mso-fareast-language:EN-US;}
p.msolistparagraphCxSpMiddle, li.msolistparagraphCxSpMiddle, div.msolistparagraphCxSpMiddle
	{mso-style-name:msolistparagraphCxSpMiddle;
	mso-style-type:export-only;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:36.0pt;
	margin-bottom:.0001pt;
	mso-add-space:auto;
	line-height:106%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:Calibri;
	mso-fareast-font-family:"Times New Roman";
	mso-bidi-font-family:"Times New Roman";
	mso-fareast-language:EN-US;}
p.msolistparagraphCxSpLast, li.msolistparagraphCxSpLast, div.msolistparagraphCxSpLast
	{mso-style-name:msolistparagraphCxSpLast;
	mso-style-type:export-only;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:8.0pt;
	margin-left:36.0pt;
	mso-add-space:auto;
	line-height:106%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:Calibri;
	mso-fareast-font-family:"Times New Roman";
	mso-bidi-font-family:"Times New Roman";
	mso-fareast-language:EN-US;}
 /* Page Definitions */
 @page
	{mso-page-border-surround-header:no;
	mso-page-border-surround-footer:no;}
@page Section1
	{size:612.0pt 792.0pt;
	margin:2.0cm 42.5pt 2.0cm 3.0cm;
	mso-header-margin:36.0pt;
	mso-footer-margin:36.0pt;
	mso-paper-source:0;}
div.Section1
	{page:Section1;}
 /* List Definitions */
 @list l0
	{mso-list-id:524830232;
	mso-list-type:hybrid;
	mso-list-template-ids:-1316082112 68747265 68747267 68747269 68747265 68747267 68747269 68747265 68747267 68747269;}
@list l0:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:72.0pt;
	text-indent:-18.0pt;
	font-family:Symbol;}
ol
	{margin-bottom:0cm;}
ul
	{margin-bottom:0cm;}
-->
</style>
<!--[if gte mso 10]>
<style>
 /* Style Definitions */
 table.MsoNormalTable
	{mso-style-name:"Обычная таблица";
	mso-tstyle-rowband-size:0;
	mso-tstyle-colband-size:0;
	mso-style-noshow:yes;
	mso-style-parent:"";
	mso-padding-alt:0cm 5.4pt 0cm 5.4pt;
	mso-para-margin:0cm;
	mso-para-margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	font-size:10.0pt;
	font-family:"Times New Roman";
	mso-ansi-language:#0400;
	mso-fareast-language:#0400;
	mso-bidi-language:#0400;}
</style>
<![endif]-->
</head>

<body lang=RU link=blue vlink=purple style='tab-interval:36.0pt;text-justify-trim:
punctuation'>

<div class=Section1>

<p class=MsoNormal style='margin-top:6.0pt;mso-pagination:none;tab-stops:3.0cm;
mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>1981-1982 ДНУ Разработка алгоритмов и программирование
на языке Фортран ЕС ЭВМ преобразования Карунена-Лоэва для цифровой обработки
нестационарных<span style='mso-spacerun:yes'>  </span>негауссовых сигналов<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;mso-pagination:none;tab-stops:3.0cm;
mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>1982-1983 ДНУ Программирование в машинных
кодах микропроцессора КР580ИК80 микросхемы последовательного интерфейса
КР580ИК55 в составе специализированного вычислительного устройства<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;mso-pagination:none;tab-stops:3.0cm;
mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>1983-1989 ДНУ <span
style='mso-spacerun:yes'> </span>Разработка алгоритмов и программирование на языке
Фортран операционной системы Рафос задач расчёта </span><span style='mso-bidi-font-family:
Arial;color:black'>линейных нестационарных систем управления.</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;mso-pagination:none;tab-stops:3.0cm;
mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>1989 Москва Ин-т пробл. упр. АН СССР<span
style='mso-spacerun:yes'>  </span>Защита диссертации на соискание учёной
степени кандидата физ.-мат. наук на тему<span style='mso-spacerun:yes'> 
</span>«Полиномиальный подход к решению задач анализа и синтеза линейных нестационарных
многосвязных систем автоматического управления». Код ВАК 01.01.11. Системный
анализ и автоматическое управление. <span style='color:black'>http://www.any-book.ru/book/show/id/80590</span><o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;mso-pagination:none;tab-stops:3.0cm;
mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>1985-1988 КБЮ Программирование на Фортран ЕС
ЭВМ известных алгоритмов обработки телеметрии <span
style='mso-spacerun:yes'> </span>по контролю <span
style='mso-spacerun:yes'> </span>расхода топлива в баллистических ракетах<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;mso-pagination:none;mso-layout-grid-align:
none;text-autospace:none'><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>1989 1991 ДМЗ Аппаратное сопряжение, разработка алгоритмов и создания программного
обеспечения <span style='mso-spacerun:yes'> </span>на языке Фортран ОС Рафос
компьютера СМ-3 для управления установкой лазерной подгонкой резисторов на микросхемах<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;mso-pagination:none;mso-layout-grid-align:
none;text-autospace:none'><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>1991-1992 Центр прикладной информатики ин-та кибернетики АН Украины. </span><span
style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;background:white'>Конфигурирование
</span><span lang=EN-US style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:
Arial;background:white;mso-ansi-language:EN-US'>UUCP</span><span
style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;background:white'>-служб
для создания ведомственной сети обмена почтовыми сообщениями между
автотранспортными предприятиями в металлургии. Операционные системы </span><span
lang=EN-US style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;
background:white;mso-ansi-language:EN-US'>Unix</span><span style='mso-bidi-font-size:
5.0pt;mso-bidi-font-family:Arial;background:white'> семейств </span><span
lang=EN-US style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;
background:white;mso-ansi-language:EN-US'>SCO</span><span style='mso-bidi-font-size:
5.0pt;mso-bidi-font-family:Arial;background:white'> и </span><span lang=EN-US
style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;background:white;
mso-ansi-language:EN-US'>FreeBSD</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>1992-1994 СПКБ Орбита <span
style='mso-spacerun:yes'> </span>Разработка и внедрение проекта по созданию
программного обеспечения для оперативного прогноза погоды для самолёта в
полёте.<span style='mso-spacerun:yes'>  </span>База </span><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'>Paradox</span><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>. Среда </span><span lang=EN-US style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>Borland</span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'> </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>Delphi</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>1995 КБЮ </span><span style='mso-bidi-font-size:
5.0pt;mso-bidi-font-family:Arial;background:white'>Конфигурирование </span><span
lang=EN-US style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;
background:white;mso-ansi-language:EN-US'>Dial</span><span style='mso-bidi-font-size:
5.0pt;mso-bidi-font-family:Arial;background:white'>-</span><span lang=EN-US
style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;background:white;
mso-ansi-language:EN-US'>Up</span><span style='mso-bidi-font-size:5.0pt;
mso-bidi-font-family:Arial;background:white'> модемов и службы </span><span
lang=EN-US style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;
background:white;mso-ansi-language:EN-US'>pppd</span><span style='mso-bidi-font-size:
5.0pt;mso-bidi-font-family:Arial;background:white'> в системе </span><span
lang=EN-US style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;
background:white;mso-ansi-language:EN-US'>FreeBSD</span><span style='mso-bidi-font-size:
5.0pt;mso-bidi-font-family:Arial;background:white'> в рамках международной
программы запуска ракетоносителей <span style='color:#252525;mso-bidi-font-weight:
bold'>Морской старт</span><span class=apple-converted-space><span
style='mso-bidi-font-family:Arial;color:#252525'>&nbsp;</span></span><span
style='color:#252525'>(</span></span><span lang=EN style='mso-bidi-font-size:
5.0pt;mso-bidi-font-family:Arial;color:#252525;background:white;mso-ansi-language:
EN;mso-bidi-font-style:italic'>Sea</span><span lang=EN style='mso-bidi-font-size:
5.0pt;mso-bidi-font-family:Arial;color:#252525;background:white;mso-bidi-font-style:
italic'> </span><span lang=EN style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:
Arial;color:#252525;background:white;mso-ansi-language:EN;mso-bidi-font-style:
italic'>Launch</span><span style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:
Arial;color:#252525;background:white'>)<span style='mso-spacerun:yes'>  </span><o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>1996 Бизнес-центр<span
style='mso-spacerun:yes'>  </span>при Днепропетровском Горном университете. Системный
администратор. </span><span style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:
Arial;background:white'>Операционные системы </span><span lang=EN-US
style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;background:white;
mso-ansi-language:EN-US'>Windows</span><span lang=EN-US style='mso-bidi-font-size:
5.0pt;mso-bidi-font-family:Arial;background:white'> </span><span lang=EN-US
style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;background:white;
mso-ansi-language:EN-US'>NT</span><span style='mso-bidi-font-size:5.0pt;
mso-bidi-font-family:Arial;background:white'>4 и </span><span lang=EN-US
style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;background:white;
mso-ansi-language:EN-US'>Windows</span><span lang=EN-US style='mso-bidi-font-size:
5.0pt;mso-bidi-font-family:Arial;background:white'> </span><span lang=EN-US
style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;background:white;
mso-ansi-language:EN-US'>workstation</span><span style='mso-bidi-font-size:
5.0pt;mso-bidi-font-family:Arial;background:white'>.</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>1997 1998 ЧП Корзун. Разработка и
внедрение проекта по создани</span><span style='mso-bidi-font-size:5.0pt;
mso-bidi-font-family:Arial;background:white'>ю ведомственной сети обмена
почтовыми сообщениями между </span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'>агрохозяйствами Днепропетровской области. </span><span
style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;background:white'>Конфигурирование
</span><span lang=EN-US style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:
Arial;background:white;mso-ansi-language:EN-US'>Dial</span><span
style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;background:white'>-</span><span
lang=EN-US style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;
background:white;mso-ansi-language:EN-US'>Up</span><span style='mso-bidi-font-size:
5.0pt;mso-bidi-font-family:Arial;background:white'> модемов и служб </span><span
lang=EN-US style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;
background:white;mso-ansi-language:EN-US'>pppd</span><span style='mso-bidi-font-size:
5.0pt;mso-bidi-font-family:Arial;background:white'>.<span
style='mso-spacerun:yes'>  </span></span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'><span style='mso-spacerun:yes'> </span></span><span
style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;background:white'>Операционная
системы </span><span lang=EN-US style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:
Arial;background:white;mso-ansi-language:EN-US'>RedHat</span><span lang=EN-US
style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;background:white'> </span><span
lang=EN-US style='mso-bidi-font-size:5.0pt;mso-bidi-font-family:Arial;
background:white;mso-ansi-language:EN-US'>Linix</span><span style='mso-bidi-font-size:
5.0pt;mso-bidi-font-family:Arial;background:white'>.<o:p></o:p></span></p>

<h1 style='margin-top:6.0pt;margin-right:0cm;margin-bottom:0cm;margin-left:
0cm;margin-bottom:.0001pt;background:white'><span style='font-size:12.0pt;
mso-bidi-font-size:11.0pt;font-family:"Times New Roman";mso-bidi-font-family:
Calibri;font-weight:normal;mso-bidi-font-weight:bold'>1997 1998 ЦНТБ Разработка
и внедрение</span><span style='font-size:12.0pt;mso-bidi-font-size:11.0pt;
font-family:"Times New Roman";mso-bidi-font-family:Calibri'> </span><span
style='font-size:12.0pt;mso-bidi-font-size:11.0pt;font-family:"Times New Roman";
mso-bidi-font-family:Calibri;font-weight:normal;mso-bidi-font-weight:bold'>проекта
по автоматизации обработки библиографической информации в рамках </span><span
style='font-size:12.0pt;mso-bidi-font-size:16.0pt;font-family:"Times New Roman";
mso-bidi-font-family:Arial;color:black;font-weight:normal;mso-bidi-font-weight:
bold'>стандарта автоматизации библиотек CDS/ISIS. Язык ISIS.<o:p></o:p></span></h1>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>1995 – 1998 Лицей информационных
технологий. Разработка и внедрение проекта по интеграции динамического контента
в </span><span lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri;mso-ansi-language:EN-US'>rtf</span><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>-документы для создания живых учебных
пособий по физике.<span style='mso-spacerun:yes'>  </span></span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>Borland</span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'> </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>C</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>++ </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>Builder</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'> и библитека </span><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'>OWL</span><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>1999-2007 Агросоюз <span
style='mso-spacerun:yes'> </span>Фирма в качестве системы управления
предприятием использовала Финэкспер (</span><span style='mso-bidi-font-size:
5.5pt;mso-bidi-font-family:Arial;color:#222222;background:#EFEFFF'>IDM</span><span
style='mso-bidi-font-family:Arial;color:#222222'>&nbsp; киев</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>). На то время
Финэкспер как системы управления предприятием по некоторым своим возможностям
превосходила 1С. </span><b><span style='mso-bidi-font-size:6.5pt;mso-bidi-font-family:
Arial;color:black;background:white'>. Язык разработки системы </span></b><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>Финэкспер имеет
такое же название Финэкспер. <a
href="http://www.sql.ru/forum/243660-1/kiev-vystavka-upravlenie-predpriyatiem-2005-6-9dek"><span
style='mso-bidi-font-family:Calibri'>http://www.sql.ru/forum/243660-1/kiev-vystavka-upravlenie-predpriyatiem-2005-6-9dek</span></a>
<a href="http://yellow.com.ua/companyrus.aspx?c=9961"><span style='mso-bidi-font-family:
Calibri'>http://yellow.com.ua/companyrus.aspx?c=9961</span></a><o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'><a href="https://web.archive.org/"><span
style='mso-bidi-font-family:Calibri'>https://web.archive.org</span></a><o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>В рамках многолетнего процесса внедрения в
Агросоюзе единой системы управления предприятием разрабатывал и внедрял такие проекты.<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;mso-pagination:none;mso-layout-grid-align:
none;text-autospace:none'><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>1. </span><span style='mso-bidi-font-family:Arial;color:black'>&nbsp;Для
организации транзакционного </span><span style='mso-bidi-font-size:6.5pt;
mso-bidi-font-family:Arial;color:black;background:white'>многопользовательский
доступа к </span><span lang=EN-US style='mso-bidi-font-size:6.5pt;mso-bidi-font-family:
Arial;color:black;background:white;mso-ansi-language:EN-US'>dbf</span><span
style='mso-bidi-font-size:6.5pt;mso-bidi-font-family:Arial;color:black;
background:white'>-файлам<span style='mso-spacerun:yes'>  </span></span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>Финэкспер
использует </span><b><span style='mso-bidi-font-size:6.5pt;mso-bidi-font-family:
Arial;color:black;background:white'><span style='mso-spacerun:yes'> </span></span></b><span
style='mso-bidi-font-size:6.5pt;mso-bidi-font-family:Arial;color:black;
background:white;mso-bidi-font-weight:bold'>сервер Pervasive. В рамках
внедрения </span><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>системы управления предприятием </span><span style='mso-bidi-font-size:
6.5pt;mso-bidi-font-family:Arial;color:black;background:white;mso-bidi-font-weight:
bold'><span style='mso-spacerun:yes'> </span>осуществлен перевод<b> </b></span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>Финэксперта на </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>SQL</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'>-сервер </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>Oracle</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>.<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;mso-pagination:none;mso-layout-grid-align:
none;text-autospace:none'><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>2. Разработан </span><span lang=EN-US style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>Linux</span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'> </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>SUSE</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'> кластер с общим (через </span><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'>SCSI</span><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>-шлейф) дисковым массивом </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>RAID</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'> для хостинга </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>Oracl</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'>а для работы Финэксперта.<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;mso-pagination:none;mso-layout-grid-align:
none;text-autospace:none'><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>3. Настройка и программирование службы </span><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'>DTS</span><span lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'> </span><span lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri;mso-ansi-language:EN-US'>MS</span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'> </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>SQL</span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'> </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>Server</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'> 2000 для извлечения данных из источников разного
типа (</span><span lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri;mso-ansi-language:EN-US'>dbf</span><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>-файлы, данные Финэкспера и т.д.) и
организации хранилища для использования в </span><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'>OLAP</span><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>-сервере </span><span lang=EN-US style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>Analysis</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'><span
style='mso-spacerun:yes'>  </span></span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>services</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>. Таблица фактов
содержала около десяти миллионов строк. Создание и настройка кубов и размерностей
в<span style='mso-spacerun:yes'>  </span></span><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'>OLAP</span><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'> сервере. Организация бизнес-аналитикам доступа к многомерным данным в
</span><span lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri;mso-ansi-language:EN-US'>Excel</span><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'> (с помощью </span><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'>Pivot</span><span lang=EN-US style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'> </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>tables</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>) и через </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>web</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'>-страницы (компонента </span><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'>OWC</span><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>). Использование<span style='mso-spacerun:yes'>  </span>скриптов, </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>SQL</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'> и </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>MDX</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'> запросов. </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>Sybase</span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'> </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>PowerDesigner</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>. <o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;mso-pagination:none;mso-layout-grid-align:
none;text-autospace:none'><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>4. Разработка расширения Финэксперта для экспорта<span
style='mso-spacerun:yes'>  </span>бухгалтерских данных в </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>MS</span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'> </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>SQL</span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'> </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>Server</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'>.<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;mso-pagination:none;mso-layout-grid-align:
none;text-autospace:none'><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>5. Предпроектные обследования на предмет внедрения </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>ERP</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'>-систем Галактика, </span><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'>Oracle</span><span lang=EN-US style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'> </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>Application</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>, </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>Navison</span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'> </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>Axapta</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>2007 – 2009 ДНУ Разработка и внедрение
проекта<span style='mso-spacerun:yes'>  </span>по программному управлению (</span><span
lang=EN-US style='mso-bidi-font-size:13.0pt;mso-ansi-language:EN-US'>Borland</span><span
lang=EN-US style='mso-bidi-font-size:13.0pt'> </span><span lang=EN-US
style='mso-bidi-font-size:13.0pt;mso-ansi-language:EN-US'>C</span><span
style='mso-bidi-font-size:13.0pt'>++ </span><span lang=EN-US style='mso-bidi-font-size:
13.0pt;mso-ansi-language:EN-US'>Builder</span><span style='mso-bidi-font-size:
13.0pt'>.</span><span lang=EN-US style='mso-bidi-font-size:13.0pt;mso-ansi-language:
EN-US'>Firebird</span><span style='mso-bidi-font-size:13.0pt'>) </span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>фотоаппаратом </span><span
style='mso-bidi-font-size:13.0pt'>Olympus SP-350</span><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'> для фотометрического измерения:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;text-indent:36.0pt;
mso-pagination:none;mso-layout-grid-align:none;text-autospace:none'><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>высот выступов
на металлической ленте;<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;text-indent:36.0pt;
mso-pagination:none;mso-layout-grid-align:none;text-autospace:none'><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>состава порошка
фтористого соединеня<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'>c</span><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'> последующим регрессионным анализом, фильтрацией изображений с помощью
преобразования Фурье (Матлаб). <o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>2011 Личная инициатива. Написание
программы на Си для извлечения с сайта </span><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'>dukascopy</span><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>.</span><span lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri;mso-ansi-language:EN-US'>com</span><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'> полной тиковой истории главных валютных пар
рынка форекс за 2010 год. Корреляционный анализ и метод главных компонент. <span
style='mso-spacerun:yes'> </span>Матлаб.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>2009 – 2014 ДНУ Интернет-проект на основе </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>Windows</span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'> </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>sharepoint</span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'> </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>services</span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'> </span><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>3.0<span style='mso-spacerun:yes'> 
</span>для организации полнотекстового поиска внутри электронных книг с
использованием поисковой машины </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>M</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>icrosoft search
server 2010. Объём книг 0.5 терабайта. Использовалась компоненты </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>IFilter</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'> для доступа к файлам формата </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>pdf</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'>, </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>djvu</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>, </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>chm</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'> и др. <a
href="https://web.archive.org/web/20130501115811/http:/vmg.pp.ua/SitePages/home.aspx"><span
style='mso-bidi-font-family:Calibri'>https://web.archive.org/web/20130501115811/http://vmg.pp.ua/SitePages/home.aspx</span></a><o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>2011 – 2014 ДНУ Создание </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>Wi</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'>-</span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>Fi</span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'> <span
style='mso-spacerun:yes'> </span></span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'>сети кафедры на базе роутеров </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>RB</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'>751</span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>U</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>-2</span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>HnD</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'> фирмы </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>Mikrotik</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>.<span
style='mso-spacerun:yes'>  </span><o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>2009 ДНУ Использование </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>SMB</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'>-службы </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>Ubuntu</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'><span
style='mso-spacerun:yes'>  </span>для организации файл-сервера кафедры для
дступа с </span><span lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri;mso-ansi-language:EN-US'>Windows</span><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>-машин<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
10.0pt;mso-bidi-font-family:Arial;color:#333333;background:white'>2011 ДНУ
Разработан проект для&nbsp;дистанционного обучения студентов с использованием
система веб-конференций </span><span style='mso-bidi-font-size:14.0pt;
mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'>bigbluebutton.</span><span
style='mso-bidi-font-size:10.0pt;mso-bidi-font-family:Arial;color:#333333;
background:white'> </span><span style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:
TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>2011 – 2014 ДНУ </span><span
style='mso-bidi-font-size:10.0pt;mso-bidi-font-family:Arial;color:#333333;
background:white'>Разработан проект для&nbsp;дистанционного тестирования
студентов с использованием </span><span style='mso-bidi-font-size:14.0pt;
mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'>системы
тестирования О</span><span lang=EN-US style='mso-bidi-font-size:14.0pt;
mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT;
mso-ansi-language:EN-US'>pentest</span><span style='mso-bidi-font-size:14.0pt;
mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'>
ХПИ<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>2011 – 2014 ДНУ <span
style='mso-spacerun:yes'> </span>Создана лаборатория по обучению студентов
основам параллельного программирования с использованием технологии </span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT;mso-ansi-language:EN-US'>Mpich</span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT'> </span><span style='mso-bidi-font-size:
14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;margin-right:0cm;margin-bottom:0cm;
margin-left:42.55pt;margin-bottom:.0001pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>2011 -2014 ДНУ Создание и эксплуатация
специализированного облака на базе хост-машины </span><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'>Ubuntu</span><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'> для хостинга виртуальных машин под управлением </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>qemu</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'> на которых запускаются операционные системы </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>Routeros</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'> маршрутизаторов фирмы </span><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'>Mikrotik</span><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>, </span><span lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri;mso-ansi-language:EN-US'>JunOs</span><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'> фирмы </span><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'>Juniper</span><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>. Для запуска <span style='mso-spacerun:yes'> </span></span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>CISCO</span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'> </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>IOS</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'> использовался </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>Dynamips</span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'> </span><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>или </span><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'>IoU</span><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>. Виртуальные машины объединяются в сеть с произвольной
топологией.<span style='mso-spacerun:yes'>  </span>Сетевые соединения
между<span style='mso-spacerun:yes'>  </span>маршрутизаторами эмулируются с
помощью протокола </span><span lang=EN-US style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>UDP</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>. Для
автоматизации настройки сети используется оболочка </span><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'>GNS</span><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>3. Для обеспечения приватности внешнего доступа к облаку используется
протокол </span><span lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri;mso-ansi-language:EN-US'>OpenVPN</span><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'> с использованием RSA-сертификатов. Для
удалённой работы с оболочкой<span style='mso-spacerun:yes'>  </span></span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>GNS</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'>3 организован доступ к удалённому рабочему<span
style='mso-spacerun:yes'>  </span>столу </span><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'>Ubuntu</span><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'> с использованием технологии </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>Nomachine</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>, основанные на
X-протоколе и ssh. Облако позволяет организовать виртуальную учебную
лабораторию для изучения сетевых технологий любого уровня сложности (</span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>VPN</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'>, </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>MPLS</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>). </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>Mikrotik<span style='mso-spacerun:yes'>   </span>user
meeting </span><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>Москва</span><span lang=EN-US style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'> – 2012 </span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'>и</span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'> </span><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'>киев</span><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri;mso-ansi-language:EN-US'> <span lang=EN-US>– 2012 <o:p></o:p></span></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'><a href="http://mum.mikrotik.com/presentations/RU12/victor.pdf"><span
style='mso-bidi-font-family:Calibri'>http://mum.mikrotik.com/presentations/RU12/victor.pdf</span></a><o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>ДНУ Методички к выполнению лабораторных
работ. Техническую и методическую подготовку лабораторных работ осуществил я.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>1993 Программирование на Си 96 </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>c</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>1995 Синхронизация параллельных процессов
в операционной системе ОС РВ 96с<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>1998 Программирование межпроцессного
взаимодействия в операционной системе </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>Linux</span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'> </span><span
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'><span
style='mso-spacerun:yes'> </span>96с<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'>2000
Основы языка </span><span lang=EN-US style='mso-bidi-font-size:14.0pt;
mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT;
mso-ansi-language:EN-US'>PHP</span><span style='mso-bidi-font-size:14.0pt;
mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'>
72 </span><span lang=EN-US style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:
TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT;mso-ansi-language:
EN-US'>c</span><span style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:
TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>2003Создание сайтов на языке </span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT;mso-ansi-language:EN-US'>PHP</span><span
style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT'> в среде </span><span lang=EN-US
style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT;mso-ansi-language:EN-US'>Makromedia</span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT'> </span><span lang=EN-US
style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:
EN-US'>Dreamviewer</span><span style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri'> 72 с<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'>2006
Создание сайта каталога товаров с использованием технологии </span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT;mso-ansi-language:EN-US'>ASP</span><span
style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT'>.</span><span lang=EN-US
style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT;mso-ansi-language:EN-US'>NET</span><span
style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT'><o:p></o:p></span></p>

<p class=MsoNormal><span style='font-size:11.0pt'>2008 Григор’єв, В.М. Лабораторний
практикум із комп’ютерних мереж [Текст]: навч. посіб./ В.М. Григор’єв, В.С.
Хандецький. &#9472; <span style='mso-spacerun:yes'> </span>Д.: РВВ ДНУ, 2008.
–<span style='mso-spacerun:yes'>  </span>124 с.<span style='text-transform:
uppercase'><o:p></o:p></span></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>2009 Лабораторный практикум по программированию
в сетях TCP-IP с помощью библиотеки Winsock операционных систем Windows 148 </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>c</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span lang=UK
style='mso-bidi-font-size:20.0pt;mso-font-kerning:16.0pt;mso-ansi-language:
UK;mso-bidi-font-weight:bold'>2010 Лабораторний практикум із комп’ютерних
мереж. Адаптація під програмний емулятор </span><span lang=EN-US
style='mso-bidi-font-size:20.0pt;mso-font-kerning:16.0pt;mso-ansi-language:
EN-US;mso-bidi-font-weight:bold'>Cisco</span><span lang=EN-US style='mso-bidi-font-size:
20.0pt;mso-font-kerning:16.0pt;mso-ansi-language:UK;mso-bidi-font-weight:bold'>
</span><span lang=EN-US style='mso-bidi-font-size:20.0pt;mso-font-kerning:16.0pt;
mso-ansi-language:EN-US;mso-bidi-font-weight:bold'>Packet</span><span
lang=EN-US style='mso-bidi-font-size:20.0pt;mso-font-kerning:16.0pt;mso-ansi-language:
UK;mso-bidi-font-weight:bold'> </span><span lang=EN-US style='mso-bidi-font-size:
20.0pt;mso-font-kerning:16.0pt;mso-ansi-language:EN-US;mso-bidi-font-weight:
bold'>Tracer</span><span lang=UK style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri;mso-ansi-language:UK'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'>2012
Григорьев,В.М.Сетевые информационные технологии:Лабораторный Практикум и
курсовое проектирование/В.М.Григорьев.&#9472;Д.:ДНУ,2012.–241с.<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;text-indent:27.75pt'><span
lang=UK style='mso-bidi-font-size:14.0pt;mso-ansi-language:UK'>&quot;Системне
програмне забезпечення&quot;. Лабораторний практикум та курсова робота. /
Григор’єв В.М., Пономарьов І.В.- Дніпропетровськ: ДНУ, 2012. –<span
style='mso-spacerun:yes'>  </span>230 с.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span lang=UK
style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT;mso-ansi-language:UK'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span style='mso-bidi-font-size:14.0pt'>2013 В. М. Григор’єв<b
style='mso-bidi-font-weight:normal'> <span style='mso-spacerun:yes'> </span></b>Комп’ютерні
мережі. Практичне видання.<b style='mso-bidi-font-weight:normal'> </b></span><span
style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT'>.&#9472;Д.:ДНУ,2013.–96с.</span><b
style='mso-bidi-font-weight:normal'><span style='mso-bidi-font-size:14.0pt'><o:p></o:p></span></b></p>

<p class=MsoNormal style='margin-top:6.0pt;margin-right:0cm;margin-bottom:0cm;
margin-left:42.55pt;margin-bottom:.0001pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'>Издана
монография <o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='color:black'>Компьютерные
сети. Виртуализация в проектировании и обучении [Текст] : монография / В. М.
Григорьев, В. С. Хандецкий. - Д. : Акцент, 2012. - 224 с. ISBN
978-966-2607-51-2<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='color:black'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='color:black'>Разработаны
учебные курсы (лекции, материалы для проверки знаний, лабораторный практикум)<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='color:black'>Системное
программное обеспечение<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='color:black'>Системное
программирование<o:p></o:p></span></p>

<p class=MsoNormal>Операционные системы</p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'>Коммуникационные
компьютерные технологии<span style='color:black'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='color:black'>Сетевые
информационные технологии</span><span lang=UK style='mso-ansi-language:UK'><o:p></o:p></span></p>

<p class=MsoNormal style='mso-hyphenate:none;tab-stops:14.45pt'><span lang=UK
style='mso-ansi-language:UK;mso-bidi-font-weight:bold'>Распределённая обработка
информации<o:p></o:p></span></p>

<p class=MsoNormal style='mso-hyphenate:none;tab-stops:14.45pt'><span lang=UK
style='mso-ansi-language:UK;mso-bidi-font-weight:bold'>технологій сучасних
бездротових мереж<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='color:black'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>2015 Пирофф Настройка доступа к
корпоративной сети с помощью </span><span lang=EN-US style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri;mso-ansi-language:EN-US'>Kerio</span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri'> </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>VPN</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'>.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>2015 Пирофф Выгрузка данный из
конфигурации 1С<span style='mso-spacerun:yes'>  </span></span><span
style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT'>«Торговля и склад» в систему
бизнес-аналитики </span><span lang=EN-US style='mso-bidi-font-size:14.0pt;
mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT;
mso-ansi-language:EN-US'>qlikview</span><span style='mso-bidi-font-size:14.0pt;
mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'>.
Конфигурация </span><span lang=EN-US style='mso-bidi-font-size:14.0pt;
mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT;
mso-ansi-language:EN-US'>qlikview</span><span style='mso-bidi-font-size:14.0pt;
mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'>.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>2015-2016 Пирофф О</span>птимизации
объёмов закупок из условия получения максимума прибыли от продаж при
ограничении на сумму закупки с помощью надстройки Экзел «Поиск решения» <span
style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>2014-2015 Пирофф Интеграция
Интернет-магазина под управлением 1С-Битрикс с конфигурацией 1С </span><span
lang=DE style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:DE'>v</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'>7 «Торговля и склад». Взаимодействие с
исполнителями осуществлялось в системе Мегаплан.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>2015 Пирофф Подключение сетевого хранилища
к </span><span lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:
Calibri;mso-ansi-language:EN-US'>Windows</span><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'> серверу по протоколу </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>iSCSI</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'>.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>2014-2016 Пирофф </span><span
style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT'>Менеджер проекта по разработке 1С-конфигурация
по автоматизации внешнеэкономической деятельности (ВЭД) фирмы Пирофф. Разработанное
техзадание включало в себя описание бизнес-процесса ВЭД, содержало
предполагаемую структуру справочников, документов и регистров 1С. <span
style='mso-spacerun:yes'> </span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT;
mso-ansi-language:EN-US'>UML</span><span style='mso-bidi-font-size:14.0pt;
mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'>-диаграммы
бизнес-процессов создавались в </span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT;
mso-ansi-language:EN-US'>MS</span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'>
</span><span lang=EN-US style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:
TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT;mso-ansi-language:
EN-US'>Visio</span><span style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:
TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'>. Фирма<span
style='mso-spacerun:yes'>  </span>Пирофф осуществляет оптовую продажу
пиротехнических изделий (ПИ). Объём номенклатуры составляет около полторы тысяч
изделий. В начале производственного цикла Пирофф высылает нескольким китайским
производителям задание на производство образцов ПИ. Принятые образцы отправляются
в производство. Произведенные ПИ проходят проверку, отправляются на склад
экспортёра, грузятся в контейнеры, доставляются из Китая на таможню РФ,
растамаживаются, доставляются и оприходываются на склад Пирофф. Ввозимая и
продаваемая номенклатура должна строго соответствовать лицензиям. Разработанная
конфигурация отслеживает взаиморасчёты с производителями, экспортёрами,
транспортниками, экспортёров с производителями. Конфигурация базируется на
типовой конфигурации 1С </span><span lang=EN-US style='mso-bidi-font-size:14.0pt;
mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT;
mso-ansi-language:EN-US'>v</span><span style='mso-bidi-font-size:14.0pt;
mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'>7
«Торговля и склад». Объём нового программного кода превышает объём кода типовой
конфигурации. Проект разработан и внедряется. </span><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'>Взаимодействие с исполнителем </span><span
lang=EN-US style='mso-bidi-font-size:11.0pt;mso-bidi-font-family:Calibri;
mso-ansi-language:EN-US'>AstrovIT</span><span style='mso-bidi-font-size:11.0pt;
mso-bidi-font-family:Calibri'> осуществлялось в системе </span><span
style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT'>onlyoffice<span
style='mso-spacerun:yes'>  </span></span><span lang=EN-US style='mso-bidi-font-size:
14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT;
mso-ansi-language:EN-US'>piroff</span><span style='mso-bidi-font-size:14.0pt;
mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'>.</span><span
lang=EN-US style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT;mso-ansi-language:EN-US'>onlyoffice</span><span
style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT'>.</span><span lang=EN-US
style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT;mso-ansi-language:EN-US'>org</span><span
style='mso-bidi-font-size:14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;
mso-bidi-font-family:TimesNewRomanPSMT'>/<o:p></o:p></span></p>

<p class=MsoNormal style='margin-top:6.0pt;text-align:justify;mso-pagination:
none;mso-layout-grid-align:none;text-autospace:none'><span style='mso-bidi-font-size:
14.0pt;mso-fareast-font-family:TimesNewRomanPSMT;mso-bidi-font-family:TimesNewRomanPSMT'>2016
Создана программы на Си для сегментации покупателей и товаров методом полного
перебора всех сочетаний контрагентов (до 32).</span><span style='mso-bidi-font-size:
11.0pt;mso-bidi-font-family:Calibri'><o:p></o:p></span></p>

</div>

</body>

</html>
