<!DOCTYPE html>
<html>
<meta charset="UTF-8">
<title>Homepage Engineering Mechanics</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<link rel="stylesheet" href="css/demo2.css">

<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Raleway", sans-serif}
body, html {
    height: 100%;
    line-height: 1.8;
}
/* Full height image header */

.bgimg-0 {
    background-position: center;
    background-size: cover;
	background-color: #ddd;
    min-height: 100%;
}

.bgimg-1 {
    background-position: center;
    background-size: cover;
	background-image: url("images/1.jpg");
    height: 100%;
}
.bgimg-2 {
    background-position: center;
    background-size: cover;
	background-image: url("images/2.jpg");
    height: 100%;
}
.bgimg-3 {
    background-position: center;
    background-size: cover;
	background-image: url("images/3.jpg");
    height: 100%;
}
.bgimg-4 {
    background-position: center;
    background-size: cover;
	background-image: url("images/4.jpg");
    height: 100%;
}
.bgimg-5 {
    background-position: center;
    background-size: cover;
	background-image: url("images/5.jpg");
    height: 100%;
}
.bgimg-6 {
    background-position: center;
    background-size: cover;
	background-image: url("images/6.jpg");
    height: 100%;
}
.bgimg-7 {
    background-position: center;
    background-size: cover;
	background-image: url("images/7.jpg");
    height: 100%;
}
.bgimg-8 {
    background-position: center;
    background-size: cover;
	background-image: url("images/8.jpg");
    height: 100%;
}
.bgimg-9 {
    background-position: center;
    background-size: cover;
	background-image: url("images/9.jpg");
    height: 100%;
}
.bgimg-10 {
    background-position: center;
    background-size: cover;
	background-image: url("images/10.jpg");
    height: 100%;
}




.w3-bar .w3-button {
    padding: 16px;
}
</style>
<body>


<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-white w3-card" id="myNavbar">
	<a id="stage" class="w3-bar-item" href="images/semmundial.jpg"><img id="spinner" src="images/MBstar1.png" width="40px" height="40px"></a>
    
	<a href="#home" class="w3-bar-item w3-button" style="text-align: left; padding-top: 8px; padding-bottom: 1px; margin-top: auto;">
		<h1 class="homepage-pce">HOMEPAGE P/XM<span><i>v1.10</i></span></h1><h2 class="pce-title">Engineering Mechanics & Prototyping and Testing</h2>
	</a>
    	
		

	<!-- Right-sided navbar links -->
    <div class="w3-hide-small">
      <a href="#about" class="w3-bar-item w3-button">Geral</a>
      <a href="#main" class="w3-bar-item w3-button">Principal</a>
      <a href="#docs" class="w3-bar-item w3-button">Docs</a>
	  
	    <div class="w3-bar-item w3-button">
			<a class="dropbtn">Sh.Points<i class="ht-caret-down"></i></a>
			<div class="dropdown-content">
				<a href="#shpoint1">RG Truck Tests Worldwide</a>
				<a href="#shpoint2">Classic Engines Euro VI</a>
				<a href="#shpoint3">TP/PEC - Teamspaces</a>
				<a href="#shpoint4">Bus Chassis Euro VI</a>
				<a href="#shpoint5">TP/EB - Proj. Mgmt LTS</a>
				<a href="#intranetgroups">Intranet Groups/Pages</a>
<!-- Para adicionar um subnível no menu
				<div class="w3-button2">
					<a href="#" class="dropbtn-left"><i class="ht-caret-left"></i>Item 3</a>
					<div class="dropdown-content-left">
						<a href="#">Sub item 1</a>
						<a href="#">Sub item 2</a>
					</div>
				</div>
-->

			</div>
	  </div>
	  
	  <a href="#linquis" class="w3-bar-item w3-button">Links</a>
      <a href="#library" class="w3-bar-item w3-button">Consultas</a>
	  <a href="#sgi" class="w3-bar-item w3-button">SGI</a>
	  <a href="#external" class="w3-bar-item w3-button">Serv.Ext</a>
	  <a href="#misc" class="w3-bar-item w3-button">Misc</a>





	  </div>
	
	
	
    <!-- Hide right-floated links on small screens and replace them with a menu icon -->

    <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium" onclick="w3_open()">
      <i class="ht ht-list-menu"></i>
    </a>
  </div>
</div>

<!-- Sidebar on small screens when clicking the menu icon -->
<nav class="w3-sidebar w3-bar-block w3-black w3-card w3-animate-left w3-hide-medium w3-hide-large" style="display:none" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-large w3-padding-16">Close ?</a>
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">Geral</a>
  <a href="#main" onclick="w3_close()" class="w3-bar-item w3-button">Principal</a>
  <a href="#docs" onclick="w3_close()" class="w3-bar-item w3-button">Documentos</a>
  <a href="#library" onclick="w3_close()" class="w3-bar-item w3-button">Bibliotecas</a>
  <a href="#sgi" onclick="w3_close()" class="w3-bar-item w3-button">SGI</a>
  <a href="#external" onclick="w3_close()" class="w3-bar-item w3-button">Servi&ccedilo Externo</a>
  <a href="#misc" onclick="w3_close()" class="w3-bar-item w3-button">Miscellaneous</a>
  <a href="#test" onclick="w3_close()" class="w3-bar-item w3-button">Test</a>
 
</nav>

<!-- Header with full-height image -->

<header class="bgimg-0 w3-display-container" id="home">
  
      <div class="slidercontainer">
        <div class="mySlides fade">
            <div class="contentsl bgimg-1 w3-jumbo-s"></div>
        </div>
        <div class="mySlides fade">
            <div class="contentsl bgimg-2 w3-jumbo-s"></div>
        </div>
        <div class="mySlides fade">
            <div class="contentsl bgimg-3 w3-jumbo-s"></div>
        </div>
        <div class="mySlides fade">
            <div class="contentsl bgimg-4 w3-jumbo-s"></div>
        </div>
		<div class="mySlides fade">
            <div class="contentsl bgimg-5 w3-jumbo-s"></div>
        </div>
        <!-- Navigation arrows -->
        <a class="leftsl" onclick="plusSlides(-1)">&#10094;</a>
        <a class="rightsl" onclick="plusSlides(1)">&#10095;</a>
    </div>
	
   
</header>




<!-- About Section -->
<div class="w3-container" style="padding:128px 16px" id="about">
  <h3 class="w3-center">Geral</h3>
  
  
  <div class="w3-row-padding w3-center" style="margin-top:64px">
    <div class="w3-quarter">
      <a target="_blank" href="http://brnet.intra.corpintra.net/Quem/pessoas2/default.asp?msg=Favor%20preencher%20pelo%20menos%20um%20dos%20campos"><i class="ht ht-phone-book w3-jumbo w3-center"></i>
      <p class="w3-small">Quem &eacute quem</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://teams.e.corpintra.net/teams/"><i class="ht ht-network w3-jumbo w3-center"></i>
      <p class="w3-small">Daimler Teams</p></a>
    </div>
    <div class="w3-quarter">
      <a target="_blank" href="https://dialplan.app.corpintra.net/"><i class="ht ht-call w3-jumbo"></i>
      <p class="w3-small">Dialplan</p></a>
    </div>
    <div class="w3-quarter">
      <a target="_blank" href="http://dict.leo.org/ende/index_en.html#/search=&searchLoc=0&resultOrder=basic&multiwordShowSingle=on"><i class="ht ht-leo w3-jumbo"></i>
      <p class="w3-small">Dicion&aacuterio Alem&atildeo</p></a>
    </div>
    <div class="w3-quarter">
      <a target="_blank" href="http://dictionary.cambridge.org/"><i class="ht ht-cambridge w3-jumbo"></i>
      <p class="w3-small">Dicion&aacuterio Ingl&ecircs</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://dcterm.e.corpintra.net/dcterm/UI7/index.xsl?call=changeDialogLang&DialogLang=2057#Terminology"><i class="ht ht-dict w3-jumbo"></i>
      <p class="w3-small">Dicion&aacuterio DCTerm</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://social.intra.corpintra.net/docs/DOC-97172"><i class="ht ht-fork w3-jumbo"></i>
      <p class="w3-small">Card&aacutepio Unificado</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://social.intra.corpintra.net/docs/DOC-97171"><i class="ht ht-fork w3-jumbo"></i>
      <p class="w3-small">Card&aacutepio Cantina</p></a>
    </div>
	
	
	</div>
	  <div class="w3-row-padding w3-center" style="margin-top:-50px">
	
	
	<div class="w3-quarter">
      <a target="_blank" href="http://rondaponto.br154.corpintra.net:3000/login"><i class="ht ht-timer w3-jumbo"></i>
      <p class="w3-small">Consulta marca&ccedil&atildeo de ponto</p></a>
    </div>	
	<div class="w3-quarter">
      <a target="_blank" href="https://mylead.es.corpintra.net/lead/default.jsp"><i class="ht ht-feedback w3-jumbo"></i>
      <p class="w3-small">LEAD-IT</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="http://s154asronp01.br154.corpintra.net:8080/baseguranca"><i class="ht ht-ronda w3-jumbo"></i>
      <p class="w3-small">Libera&ccedil&atildeo de visitantes</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="http://intra.corpintra.net/Projects/c2c/channel/documents/1575092_mapa.pdf"><i class="ht ht-map w3-jumbo"></i>
      <p class="w3-small">Localiza&ccedil&atildeo dos Pr&eacutedios</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://brnet.intra.corpintra.net/colaborador/rhonline/?param=NTAuMTQzLjI1MS4zOTguNDIwLjIzLzAxLzIwMTk="><i class="ht ht-rhonline w3-jumbo"></i>
      <p class="w3-small">RH Online</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="http://brnet.intra.corpintra.net/Colaborador/Transporte_Pessoal/default.asp?c2c=y"><i class="ht ht-bus w3-jumbo"></i>
      <p class="w3-small">Transporte pessoal</p></a>
    </div>
    <div class="w3-quarter">
      <a target="_blank" href="https://daimler.sabacloud.com/Saba/Web_spf/EU1PRD0023/app/me/plans"><i class="ht ht-teacher w3-jumbo"></i>
      <p class="w3-small">Daimler Learning Management System</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="http://weblearning.app.corpintra.net/webLearning/"><i class="ht ht-laptop-1 w3-jumbo"></i>
      <p class="w3-small">Tutoriais NX e Smaragd</p></a>
    </div>
  </div>
</div>




<div class="w3-container w3-light-grey" style="padding:128px 16px" id="main">
  <h3 class="w3-center">Principal</h3>
  
  <div class="w3-row-padding w3-center" style="margin-top:64px">
	<div class="w3-quarter">
      <a target="_blank" href="https://kanbo.app.corpintra.net"><i class="ht ht-kanbo w3-jumbo w3-center"></i>
      <p class="w3-small">KanBo</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://wcp.app.corpintra.net/cloudcockpit/Logon/Login.aspx"><i class="ht ht-finas w3-jumbo w3-center"></i>
      <p class="w3-small">World Comm. Platform</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="http://cst.e.corpintra.net/AuftragsCockpit/DecisionSite.aspx?uid=QU5EUkNBUiAg"><i class="ht ht-finas w3-jumbo w3-center"></i>
      <p class="w3-small">Doku-Cockpit</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="http://zeus.e.corpintra.net/"><i class="ht ht-zeus w3-jumbo w3-center"></i>
      <p class="w3-small">Zeus</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://en-truckengine.es.corpintra.net/"><i class="ht ht-peg w3-jumbo w3-center"></i>
      <p class="w3-small">PEG</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://etools.app.corpintra.net/esuite_dvpr/Layouts/eSuite_dvpr/dvprmain"><i class="ht ht-dvpr w3-jumbo w3-center"></i>
      <p class="w3-small">eDVP&R</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://etools.app.corpintra.net/esuite_vrr/layouts/esuite_vrr/vrrmain.aspx"><i class="ht ht-vrr w3-jumbo w3-center"></i>
      <p class="w3-small">eVRR</p></a>
    </div>	
	<div class="w3-quarter">
      <a target="_blank" href="https://icm.e.corpintra.net/"><i class="ht ht-icm w3-jumbo w3-center"></i>
      <p class="w3-small">ICM</p></a>
    </div>
     
   </div>
   
   
   <div class="w3-row-padding w3-center" style="margin-top:-50px">
    <div class="w3-quarter">
      <a target="_blank" href="https://icm.e.corpintra.net/grafana/d/18pa9CmWz/tg-lg-home?orgId=1"><i class="ht ht-grafana w3-jumbo w3-center"></i>
      <p class="w3-small">Grafana</p></a>
    </div> 
	<div class="w3-quarter">
      <a target="_blank" href="https://truckbom-planner.e.corpintra.net/TruckBOM-planner/Login.aspx"><i class="ht ht-truckbom w3-jumbo w3-center"></i>
      <p class="w3-small">TruckBOM Planner</p></a>
    </div>   
	<div class="w3-quarter">
      <a target="_blank" href="https://deviation.e.corpintra.net/"><i class="ht ht-aetool w3-jumbo w3-center"></i>
      <p class="w3-small">AE-Tool</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://sap-mobility.e.corpintra.net/sap/bc/ui2/flp/FioriLaunchpad.html?sap-client=010#Z_TBOM_20_DOCU_BRO-display?sap-system=TRUCKBOM_MAINT"><i class="ht ht-bom w3-jumbo w3-center"></i>
      <p class="w3-small">DokuBrowser</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://zgdokclient.app.corpintra.net/zgdok/client/#/home"><i class="ht ht-zgdok w3-jumbo w3-center"></i>
      <p class="w3-small">ZGDOK Web</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://sma4u.es.corpintra.net/sma4u/smaragd/"><i class="ht ht-sma4u w3-jumbo w3-center"></i>
      <p class="w3-small">Sma4U</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://mt-woerth.destr.corpintra.net/Messtechnik/index_en.html"><i class="ht ht-dtms w3-jumbo w3-center"></i>
      <p class="w3-small">Daimler Trucks<br>Measurement Systems</p></a>
    </div>
  
  </div>
  
  <div class="w3-row-padding w3-center" style="margin-top:-50px">
	<div class="w3-quarter">
      <a target="_blank" href="\\S154FSBC0002\D154_G10157\900 Administrativo - Times\950 DAM5\953 Atividades Semanais"><i class="ht ht-education w3-jumbo w3-center"></i>
      <p class="w3-small">Programa&ccedil&atildeo da oficina Motores</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="\\S154FSBC0001\D154_G10162\POS\01-Programação B.P"><i class="ht ht-education w3-jumbo w3-center"></i>
      <p class="w3-small">Programa&ccedil&atildeo BP</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="\\S154FSBC0001\D154_G10162\BUS\02-BDE\01- Programa de oficina Ônibus"><i class="ht ht-education w3-jumbo w3-center"></i>
      <p class="w3-small">Programa&ccedil&atildeo oficina Bus</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="\\S154FSBC0001\D154_G10162\TRUCK\025 _ DTE_Testes_veiculos\25.1_Prog_Oficina_Revisor_PSVs\25.11_Programacao_2020"><i class="ht ht-education w3-jumbo w3-center"></i>
      <p class="w3-small">Programa&ccedil&atildeo oficina Trucks</p></a>
    </div>  
  
  
  </div>
</div>







<div class="w3-container" style="padding:128px 16px" id="docs">
  <h3 class="w3-center">Documentos</h3>
  
  <div class="w3-row-padding w3-center" style="margin-top:64px">
    <div class="w3-quarter">
      <a target="_blank" href="https://daimler.sharefile.eu/app/#/dashboard"><i class="ht ht-sharefile w3-jumbo w3-center"></i>
      <p class="w3-small">Daimler ShareFile</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="http://nfenet.br154.corpintra.net/nfenet"><i class="ht ht-document w3-jumbo w3-center"></i>
      <p class="w3-small">Portal NFe</p></a>
    </div>
    <div class="w3-quarter">
      <a target="_blank" href="http://legalcore.login.mercedes-benz.com.br/conta/login"><i class="ht ht-document w3-jumbo w3-center"></i>
      <p class="w3-small">Legal One</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="http://fornecedores1.mercedes-benz.com.br/Transportes/Login"><i class="ht ht-truck w3-jumbo w3-center"></i>
      <p class="w3-small">Solic.Transp.</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="\\S154FSBC0001\D154_G10162\BUS\02-BDE\01- Programa de oficina Ônibus\SS Ônibus 2020"><i class="ht ht-document w3-jumbo w3-center"></i>
      <p class="w3-small">Solic.Serv. BDE</p></a>
    </div>

		
  </div>
</div>








<div class="w3-container w3-light-grey" style="padding:128px 16px" id="shpoint1">
  <h3 class="w3-center">RG Truck Tests Worldwide</h3>
  
  <div class="w3-row-padding w3-center" style="margin-top:64px">
	
	<div class="w3-quarter">
      <a target="_blank" href="https://team.sp.wp.corpintra.net/sites/06388/SitePages/DaimlerHome.aspx"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">Home</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://team.sp.wp.corpintra.net/sites/06388/BRA/SitePages/Home.aspx"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">Brasil</p></a>
    </div>	
	<div class="w3-quarter">
      <a target="_blank" href="https://team.sp.wp.corpintra.net/sites/06388/MX/SitePages/Home.aspx"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">Mexico</p></a>
    </div>	
	<div class="w3-quarter">
      <a target="_blank" href="https://team.sp.wp.corpintra.net/sites/06388/GER/SitePages/Home.aspx"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">Germany</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://team.sp.wp.corpintra.net/sites/06388/RSA/SitePages/DaimlerHome.aspx"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">South Africa</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://team.sp.wp.corpintra.net/sites/06388/UAE/SitePages/Home.aspx"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">South Africa</p></a>
    </div>	
	
	

  </div>
</div>	
	
	
	
	
<div class="w3-container" style="padding:128px 16px" id="shpoint2">
  <h3 class="w3-center">Classic Engines Euro VI</h3>
  
  <div class="w3-row-padding w3-center" style="margin-top:64px">
	
	<div class="w3-quarter">
      <a target="_blank" href="https://team.sp.wp.corpintra.net/sites/04285/TeamSpace/ClassicEnginesEuroVI/SitePages/Classic%20Engines.aspx"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">Classic Engines EuroVI<br>Home</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://team.sp.wp.corpintra.net/sites/04285/TeamSpace/ClassicEnginesEuroVI/SitePages/BR900%20Brazil.aspx"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">BR900 Brazil<BR>Home</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://team.sp.wp.corpintra.net/sites/04285/TeamSpace/ClassicEnginesEuroVI/BR900%20Brazil%20Documents/Forms/AllItems.aspx"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">BR900 Brazil<BR>Documents</p></a>
    </div>
	
	</div>
  <div class="w3-row-padding w3-center" style="margin-top:-50px">
	
	
	<div class="w3-quarter">
      <a target="_blank" href="https://team.sp.wp.corpintra.net/sites/04285/TeamSpace/ClassicEnginesEuroVI/OM460_Brazil/SitePages/OM460%20Brazil.aspx"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">OM460 Brazil<BR>Home</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://team.sp.wp.corpintra.net/sites/04285/TeamSpace/ClassicEnginesEuroVI/Documents%20OM460%20Brazil/Forms/AllItems.aspx"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">OM460 Brazil<BR>Documents</p></a>
    </div>
    <div class="w3-quarter">
      <a target="_blank" href="https://team.sp.wp.corpintra.net/sites/04285/TeamSpace/ClassicEnginesEuroVI/Documents%20OM460%20Brazil/Forms/AllItems.aspx?RootFolder=%2Fsites%2F04285%2FTeamSpace%2FClassicEnginesEuroVI%2FDocuments%20OM460%20Brazil%2F0400%5FParts%20Tracking%2FAMS%2FHuL&FolderCTID=0x012000406A394A19FC11459206FF85845554BA&View=%7B3AE730BB%2D0D67%2D4070%2D9AE4%2DCF6391BFAC0D%7D"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">OM460 Brazil<BR>AMS HuL</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://team.sp.wp.corpintra.net/sites/04285/TeamSpace/ClassicEnginesEuroVI/Documents%20OM460%20Brazil/Forms/AllItems.aspx?RootFolder=%2Fsites%2F04285%2FTeamSpace%2FClassicEnginesEuroVI%2FDocuments%20OM460%20Brazil%2F0400%5FParts%20Tracking%2Fchange%20request%2F01%20Project%20Master%20List&FolderCTID=0x012000406A394A19FC11459206FF85845554BA&View=%7B3AE730BB%2D0D67%2D4070%2D9AE4%2DCF6391BFAC0D%7D"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">OM460 Brazil<BR>ICM Master List</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://team.sp.wp.corpintra.net/sites/04285/TeamSpace/ClassicEnginesEuroVI/Documents%20OM460%20Brazil/Forms/AllItems.aspx?RootFolder=%2Fsites%2F04285%2FTeamSpace%2FClassicEnginesEuroVI%2FDocuments%20OM460%20Brazil%2F0600%5FProject%20Functional%20Areas%2F0601%5FLocal%20Hub%20LCM&FolderCTID=0x012000406A394A19FC11459206FF85845554BA&View=%7B3AE730BB%2D0D67%2D4070%2D9AE4%2DCF6391BFAC0D%7D"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">OM460 Brazil<br>Shopping List/Invoices</p></a>
    </div>

  </div>	
</div>	
	
	
	
<div class="w3-container w3-light-grey" style="padding:128px 16px" id="shpoint3">
  <h3 class="w3-center">TP/PEC - Teamspaces</h3>
  
  <div class="w3-row-padding w3-center" style="margin-top:64px">
	
	<div class="w3-quarter">
      <a target="_blank" href="https://team.sp.wp.corpintra.net/sites/05876/Classic_Engines_Euro_VI_TPPEC/SitePages/IntroBR900.aspx"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">BR900 Home</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://team.sp.wp.corpintra.net/sites/05876/Classic_Engines_Euro_VI_TPPEC/BR900/SitePages/DocumentManagement.aspx"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">BR900 EuroVI Documents</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://team.sp.wp.corpintra.net/sites/05876/Classic_Engines_Euro_VI_TPPEC/OM460EuroVI/SitePages/DocumentManagement.aspx"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">OM460 EuroVI Documents</p></a>
    </div>
		

  </div>		
</div>	
	
	
	
<div class="w3-container" style="padding:128px 16px" id="shpoint4">
  <h3 class="w3-center">Bus Chassis Euro VI</h3>
  
  <div class="w3-row-padding w3-center" style="margin-top:64px">
	
	<div class="w3-quarter">
      <a target="_blank" href="https://team.latam.sp.wp.corpintra.net/sites/02928/SitePages/Home.aspx"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">Home</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://team.latam.sp.wp.corpintra.net/sites/02928/Communication/Forms/AllItems.aspx?id=%2Fsites%2F02928%2FCommunication%2F06%5FTest%20Plan%2FEndurance%2FBrazil"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">Bus RG Brazil</p></a>
    </div>
  </div>		
</div>	
	
	
<div class="w3-container w3-light-grey" style="padding:128px 16px" id="shpoint5">
  <h3 class="w3-center">TP/EB - Project Management LTS</h3>
  
  <div class="w3-row-padding w3-center" style="margin-top:64px">
	
	<div class="w3-quarter">
      <a target="_blank" href=""><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">Home</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://team.latam.sp.wp.corpintra.net/sites/04274/Documents/Forms/AllItems.aspx?id=%2Fsites%2F04274%2FDocuments%2FLTS%5FClassic%2F100%5FScope%2F180%5FTests"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">LTS Classic<br>Tests</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://team.latam.sp.wp.corpintra.net/sites/04274/Documents/Forms/AllItems.aspx?id=%2Fsites%2F04274%2FDocuments%2FLTS%5FEHHE%5FEu6%2F100%5FScope%2F180%5FTests"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">LTS EH-HE Eu6<br>Tests</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://team.latam.sp.wp.corpintra.net/sites/04274/Documents/Forms/AllItems.aspx?id=%2Fsites%2F04274%2FDocuments%2FLTS%5FEntry%2F100%5FScope%2F180%5FTests"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">LTS Entry<br>Tests</p></a>
    </div>
  </div>		
</div>	
	
	
	

<div class="w3-container" style="padding:128px 16px" id="intranetgroups">
  <h3 class="w3-center">Intranet Groups / Pages</h3>
   
  <div class="w3-row-padding w3-center" style="margin-top:64px">

	<div class="w3-quarter">
      <a target="_blank" href="https://social.intra.corpintra.net/groups/assembly-retrofit-dedicated-powertrain-prototype-trucks-br900-euro-vi"><i class="ht ht-shared-folder w3-jumbo w3-center"></i>
      <p class="w3-small">V354 V355 V356<br>(Carlos Gon&ccedilalves)</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://social.intra.corpintra.net/groups/br900-engine-mechanics"><i class="ht ht-shared-folder w3-jumbo w3-center"></i>
      <p class="w3-small">BR900 Mechanics<br>(Peter Schick)</p></a>
    </div>
		
  </div>

  
</div>	
	
	
<div class="w3-container" style="padding:128px 16px" id="linquis">
  <h3 class="w3-center">Links</h3>
	
  <div class="w3-row-padding w3-center" style="margin-top:64px">
	<div class="w3-col s2">
      <a target="_parent" href="C:\Users\HETANAK\Documents\06_Finas\Controle_FiNAS.xlsx"><i class="ht ht-excel w3-jumbo w3-center"></i>
      <p class="w3-small">Controle Finas<br>&nbsp<br>&nbsp</p></a>
    </div>
	<div class="w3-col s2">
      <a target="_parent" href="C:\Users\HETANAK\Documents\10_EMPB\Controle_EMPBs.xlsx"><i class="ht ht-excel w3-jumbo w3-center"></i>
      <p class="w3-small">Controle EMPB<br>&nbsp<br>&nbsp</p></a>
    </div>
	<div class="w3-col s2">
      <a target="_parent" href="C:\Users\HETANAK\Documents\00_Learn!_\05_Normas\Indice_de_normas.xlsx"><i class="ht ht-excel w3-jumbo w3-center"></i>
      <p class="w3-small">&Iacutendice de normas<br>&nbsp<br>&nbsp</p></a>
    </div>	
	<div class="w3-col s2">
      <a target="_parent" href="C:\Users\HETANAK\Documents\01_P-PE_Management\mob-aproj_Controle.xlsx"><i class="ht ht-excel w3-jumbo w3-center"></i>
      <p class="w3-small">Controle MOB-APROJ<br>&nbsp</p></a>
    </div>		

  </div>
</div>







<div class="w3-container w3-light-grey" style="padding:128px 16px" id="library">
  <h3 class="w3-center">Consultas</h3>
  
  <!--
  <p class="w3-center w3-large">Key features of our company</p>
  -->
  
  <div class="w3-row-padding w3-center" style="margin-top:64px">
    <div class="w3-quarter">
      <a target="_blank" href="https://docmaster.es.corpintra.net/DocMasterHTML/Welcome.jsp"><i class="ht ht-books w3-jumbo"></i>
      <p class="w3-small">DocMaster - Normas</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="C:\Users\HETANAK\Documents\00_Learn!_\02_Bibliotecas\NX BRASIL Snapshot ListaBM-Codes.xlsx"><i class="ht ht-bus3d w3-jumbo"></i>
      <p class="w3-small">Lista de Snapshots</p></a>
    </div>
    <div class="w3-quarter">
      <a target="_blank" href="https://busdoc.i.daimler.com/public/fct/code_ENG.html"><i class="ht ht-bug w3-jumbo"></i>
      <p class="w3-small">C&oacutedigos de Falhas - El&eacutetrica</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://engs-prod.e.corpintra.net/cont/kto/index.en.html"><i class="ht ht-bolts w3-jumbo"></i>
      <p class="w3-small">KTO Online</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://retailfactory.mercedes-benz.com/WIS-net/ssl.jnlp"><i class="ht ht-ssl w3-jumbo w3-center"></i>
      <p class="w3-small">Pesq. SSL</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://aftersales.i.daimler.com/ewatoken/startEWA.jnlp?app=Repair&EWASERVERURL=retailfactory.mercedes-benz.com&EWASERVERPORT=443&EWASSL=true"><i class="ht ht-manuten w3-jumbo w3-center"></i>
      <p class="w3-small">WIS/ASRA</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="http://brnet.intra.corpintra.net/produtos/curvas/curvas.asp"><i class="ht ht-charts w3-jumbo w3-center"></i>
      <p class="w3-small">Curvas de desempenho</p></a>
    </div>
	 
	
  </div>
</div>






<div class="w3-container" style="padding:128px 16px" id="sgi">
  <h3 class="w3-center">SGI</h3>
  
  <div class="w3-row-padding w3-center" style="margin-top:64px">
    <div class="w3-quarter">
      <a target="_blank" href="http://intra.corpintra.net/intra-mb-brasil/sistema-gestao-integrada"><i class="ht ht-open-book w3-jumbo w3-center"></i>
      <p class="w3-small">Documentos SGI</p></a>
    </div>
    <div class="w3-quarter">
      <a target="_blank" href="file:///\\S154S000001F.BR154.CORPINTRA.NET\D154_G10002\OLF – Aspectos e Impactos Ambientais_atualizados\2019\300_Aspectos_SBC\310_Banco_de_Dados\310_LAI_Aspectos e Impactos Ambientais_SBC.2.accdb"><i class="ht ht-waste w3-jumbo"></i>
      <p class="w3-small">Aspectos e Impactos Ambientais</p></a>
    </div>
    <div class="w3-quarter">
      <a target="_blank" href="https://bictruck.e.corpintra.net/bicportal/portal/domain/domain.action#target=viewStartingPageDispatcher&type=view&id=d&viewId=d"><i class="ht ht-open-book w3-jumbo w3-center"></i>
      <p class="w3-small">PROMIS Prozess Portal (PPP)</p></a>
    </div>
    <div class="w3-quarter">
      <a target="_blank" href="https://team.sp.wp.corpintra.net/sites/04285/pmconnect/CVDSSTandards/cvdsApp/index.html"><i class="ht ht-cvds w3-jumbo w3-center"></i>
      <p class="w3-small">CVDS Lean<br>Web App</p></a>
    </div>
    <div class="w3-quarter">
      <a target="_blank" href="https://team.sp.wp.corpintra.net/sites/04285/pmconnect/CVDSSTandards/SitePages/Time.aspx"><i class="ht ht-sharepoint w3-jumbo w3-center"></i>
      <p class="w3-small">Sharepoint<br>CVDS Lean</p></a>
    </div>
	
	
  </div>
</div>






<div class="w3-container w3-light-grey" style="padding:128px 16px" id="external">
  <h3 class="w3-center">Servi&ccedilo Externo</h3>
  
  <div class="w3-row-padding w3-center" style="margin-top:64px">
    <div class="w3-quarter">
      <a target="_blank" href="https://www.melhorcambio.com/"><i class="ht ht-coin w3-jumbo w3-center"></i>
      <p class="w3-small">Cota&ccedil&atildeo de moedas</p></a>
    </div>
    <div class="w3-quarter">
      <a target="_blank" href="https://wx1.getthere.net/DispatcherServlet?requestType=logininq&site=daimler"><i class="ht ht-plane w3-jumbo"></i>
      <p class="w3-small">GetThere - Hoteis e Passagens de avi&atildeo</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://www.concursolutions.com/"><i class="ht ht-concur w3-jumbo"></i>
      <p class="w3-small">Concur - Presta&ccedil&atildeo de contas</p></a>
    </div>
  </div>
</div>




<div class="w3-container" style="padding:128px 16px" id="misc">
  <h3 class="w3-center">Miscellaneous</h3>
  
  <div class="w3-row-padding w3-center" style="margin-top:64px">
    <div class="w3-quarter">
      <a target="_blank" href="https://cbfc-psj.app.corpintra.net:53201/irj/portal/"><i class="ht ht-sap w3-jumbo w3-center"></i>
      <p class="w3-small">SAP NetWeaver</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://social.intra.corpintra.net/docs/DOC-60756"><i class="ht ht-key w3-jumbo w3-center"></i>
      <p class="w3-small">Senhas/Acessos</p></a>
    </div>
	<div class="w3-quarter">
      <a target="_blank" href="https://zulaplus.e.corpintra.net/"><i class="ht ht-zula w3-jumbo w3-center"></i>
      <p class="w3-small">Zulassungtool</p></a>
    </div>	
  </div>
</div>



<div class="w3-container w3-light-grey" style="padding:128px 16px" id="test">
  <h3 class="w3-center">Teste</h3>
 
   
  <div class="w3-row-padding w3-center" style="margin-top:64px">
    <div class="w3-col s2">
      <a href="sip:87018302@vc.daimler.com"><i class="ht ht-vmr w3-jumbo w3-center"></i></a>
      <p class="w3-small">870 18302<br>HETANAK vMR</p><p class="w3-small">Chairperson: 1256#<br>Participant: 4569#</p>
    </div>
	

  </div>
</div>










<!-- Footer -->
<footer class="w3-center w3-black w3-padding-64" id="footer">
  <a href="#home" class="w3-button w3-light-grey"><i class="ht ht-swipe-up w3-margin-right"></i>To the top</a>
  <div class="w3-xlarge w3-section"><br>
  <p class="w3-medium">Powered by <a href="https://www.w3schools.com/w3css/default.asp">w3.css Team</a>. Adapted by Helder Tanaka</p>
  <p>
	<a target="_parent" href="#footer"><i class="ht ht-facebook w3-margin-right"></i></a>
	<a target="_parent" href="#footer"><i class="ht ht-twitter w3-margin-right"></i></a>
	<a target="_parent" href="#footer"><i class="ht ht-instagram w3-margin-right"></i></a>
	<a target="_parent" href="#footer"><i class="ht ht-snapchat w3-margin-right"></i></a>
	<a target="_parent" href="#footer"><i class="ht ht-linkedin w3-margin-right"></i></a>
	<a target="_parent" href="#footer"><i class="ht ht-youtube"></i></a>
	  </p>
	
</footer>
 
 
 

<script>
		// Modal Image Gallery
		function onClick(element) {
		  document.getElementById("img01").src = element.src;
		  document.getElementById("modal01").style.display = "block";
		  var captionText = document.getElementById("caption");
		  captionText.innerHTML = element.alt;
		}


		// Toggle between showing and hiding the sidebar when clicking the menu icon
		var mySidebar = document.getElementById("mySidebar");

		function w3_open() {
			if (mySidebar.style.display === 'block') {
				mySidebar.style.display = 'none';
			} else {
				mySidebar.style.display = 'block';
			}
		}

		// Close the sidebar with the close button
		function w3_close() {
			mySidebar.style.display = "none";
		}




		
		//Background slideshow

		
// Create an Index for Slides			
var slideIndex = 0;

// Create a var to identify the slides
var slides = document.getElementsByClassName("mySlides");
			
// Timeout for automatic slide change
var timeoutHandle;

var numImagens = slides.length;

function showSlides() {    
	var i;    
	for (i = 0; i < slides.length; i++) {
		slides[i].style.display = "none"; 
	}
	slideIndex++;
	if (slideIndex > slides.length) {slideIndex = 1} 
	slides[slideIndex-1].style.display = "block"; 
	timeoutHandle = setTimeout(showSlides, 5000); // Change image every 5 seconds
}

//run showSlides() function
showSlides();

function currentSlide(no) {
	var i;
	for (i = 0; i < slides.length; i++) {
		slides[i].style.display = "none";
	}
	slideIndex = no;
	slides[no-1].style.display = "block";
	clearTimeout(timeoutHandle);
	timeoutHandle = setTimeout(showSlides, 5000);
}

function plusSlides(n) {
	slideIndex += n;
	if (slideIndex < 1) {
		currentSlide(slides.length);
	}

	if( slideIndex > slides.length) {
		currentSlide(1);
	}

	else { currentSlide(slideIndex); }
}
			
		
		

		/* When the user clicks on the button, 
toggle between hiding and showing the dropdown content 
function myFunction() {
  document.getElementById("myDropdown").classList.toggle("show");
}

// Close the dropdown menu if the user clicks outside of it
window.onclick = function(event) {
  if (!event.target.matches('.dropbtn')) {
    var dropdowns = document.getElementsByClassName("dropdown-content");
    var i;
    for (i = 0; i < dropdowns.length; i++) {
      var openDropdown = dropdowns[i];
      if (openDropdown.classList.contains('show')) {
        openDropdown.classList.remove('show');
      }
    }
  }
} 

*/




		
</script>


</body>
</html>
