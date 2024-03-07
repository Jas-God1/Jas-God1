

<!DOCTYPE html>
<!--
  ___ __  __   _   ___ _____ ___  ___ _  _  ___   ___  _
 / __|  \/  | /_\ | _ \_   _/ __|/ __| || |/ _ \ / _ \| |
 \__ \ |\/| |/ _ \|   / | | \__ \ (__| __ | (_) | (_) | |__
 |___/_|  |_/_/ \_\_|_\ |_| |___/\___|_||_|\___/ \___/|____|

Did you know you can get paid to read other people's code?

We're looking for PHP developers.
Join us: https://www.smartschool.be/jobs
-->
<html>
    <head>
                    <title>Spes Nostra Instituut - Smartschool</title>
            <meta charset="utf-8">
            <meta http-equiv="x-ua-compatible" content="ie=edge">
                            <link rel="icon" href="https://static1.smart-school.net/smsc/svg/favicon/favicon.svg">
                <link rel="mask-icon" href="https://static3.smart-school.net/smsc/svg/favicon/mask-icon.svg" color="#ff520e">
                <link rel="apple-touch-icon" href="https://static3.smart-school.net/smsc/img/favicon/apple-touch-icon.png">
                <link rel="manifest" href="/manifest.json">
                                                                    
                
        <!-- jQuery & jQueryUI -->
                    <script type="text/javascript" src="https://static1.smart-school.net/smsc/resources/jquery/2.1.4/jquery.min.rev-c24dfc6104.js"></script>
    
                    <script type="text/javascript" src="https://static5.smart-school.net/smsc/resources/jqueryui/1.12.1/jquery-ui.min.rev-1eb5e4204f.js"></script>
    
                    <link href="https://static3.smart-school.net/smsc/resources/jqueryui/1.12.1/jquery-ui.min.rev-80dc885b8c.css" rel="stylesheet" />
    

                                                <link href="https://static5.smart-school.net/production/Topnav/main.rev-aec32951c4.css" rel="stylesheet" />
    
                    
                            <link href="https://static5.smart-school.net/modules/Homepage/dist/main-built.rev-6e96d7c7ed.css" rel="stylesheet" />
    
            
                        <!-- TinyMCE HEAD -->
                                    <script src="https://static5.smart-school.net/wysiwyg/tinymce-version-6.7.1/js/tinymce/tinymce.min.rev-679c7d3aa2.js"></script>

                            <!-- javascriptContent HEAD -->
            <script type="text/javascript">
        if(!window.SMSC) window.SMSC = {};
        if(!window.SMSC.languagehash) window.SMSC.languageHash = {};

                    window.SMSC.languageHash['general_legacy'] = {
                'nl': { 
                    'version': 'b130f62511'
                },
                'fr': { 
                    'version': 'aee084822d' 
                },
            };
                    window.SMSC.languageHash['general_buttons'] = {
                'nl': { 
                    'version': 'aaef474712'
                },
                'fr': { 
                    'version': '15261c4a92' 
                },
            };
                    window.SMSC.languageHash['component_dialog'] = {
                'nl': { 
                    'version': 'f4eedee503'
                },
                'fr': { 
                    'version': 'd2dd8d9c2b' 
                },
            };
            </script>

        <!-- javascriptURL HEAD -->
                                <script type="text/javascript" src="https://static3.smart-school.net/smsc/resources/jqueryui/langs/jquery.ui.datepicker-nl-BE.min.rev-e896eebacb.js"></script>
            <script type="text/javascript" src="https://static5.smart-school.net/includes/jQuery/plugins/timepicker/timepicker.rev-3f86e13a32.js"></script>
    
                <!-- javascriptContent HEAD -->
                        
                    </head>
    <body class=" modern-ui">
                                    <a href="javascript://" class="skip-link js-skip-link">Spring naar hoofdcontent</a>
<div id="topnavMenuOverlay" class="topnav-menu-overlay" hidden></div>
<header id="smscTopContainer" class="smsc-topnav">
  <nav class="topnav">
    <div data-profile class="topnav__btn-wrapper">
        <button class="js-btn-profile topnav__btn topnav__btn--profile">
            <img src="https://userpicture10.smartschool.be/User/Userimage/hashimage/hash/645_6057ec08-935e-4d62-91cf-b87e3d6230f0/plain/1/res/48" alt="Profiel afbeelding"/>
            <div class="hlp-vert-box">
                <span>Jasper  Goderis </span>
                <span class="topnav__btn__light"></span>
            </div>
            <div class="topnav__menu-arrow" aria-hidden="true"></div>
        </button>
        <div id="profileMenu" class="topnav__menu-wrapper" tabindex="-1" hidden>
            <div class="topnav__menu">
                <a href="/?module=Profile" class="topnav__menuitem topnav__menuitem--img" role="menuitem">
                    <img src="https://userpicture10.smartschool.be/User/Userimage/hashimage/hash/645_6057ec08-935e-4d62-91cf-b87e3d6230f0/plain/1/res/48" alt="Profiel afbeelding"/>
                    <span>Profiel</span>
                </a>
                <a href="/Profile/Notify" class="topnav__menuitem topnav__menuitem--icon topnav__menuitem--icon--notifs" role="menuitem">Instellingen berichtgeving</a>
                <ul class="profile-blocks js-profile-blocks"></ul>
            </div>
        </div>
    </div>

    
    
    
    <a href="/" class="js-btn-home topnav__btn topnav__btn--push-right">Start</a>

    <div data-shortcuts class="topnav__btn-wrapper">
        <button class="js-btn-shortcuts topnav__btn">
          Ga naar
          <div class="topnav__menu-arrow" aria-hidden="true"></div>
        </button>
        <div id="shortcutsMenu" class="topnav__menu-wrapper" tabindex="-1" hidden>
          <div class="topnav__menu topnav__menu--shortcuts js-shortcuts-container js-autosize">
                  
    <a href="/?module=Messages&amp;file=index&amp;function=main"
       class="topnav__menuitem topnav__menuitem--icon module-messages--24"
       role="menuitem"       title="Berichten">
        Berichten
    </a>
                        
    <a href="/?module=Survey&amp;file=index&amp;function=main&amp;courseID=0"
       class="topnav__menuitem topnav__menuitem--icon module-survey--24"
       role="menuitem"       title="Enquête">
        Enquête
    </a>
                        
    <a href="/helpdesk"
       class="topnav__menuitem topnav__menuitem--icon module-ticket--24"
       role="menuitem"       title="Helpdesk">
        Helpdesk
    </a>
                        
    <a href="/?module=LVS&amp;file=index&amp;function=main"
       class="topnav__menuitem topnav__menuitem--icon module-lvs--24"
       role="menuitem"       title="Leerlingvolgsysteem">
        Leerlingvolgsysteem
    </a>
                        
    <a href="/mydoc"
       class="topnav__menuitem topnav__menuitem--icon module-mydoc--24"
       role="menuitem"       title="Mijn documenten">
        Mijn documenten
    </a>
                        
    <a href="/Studentcard"
       class="topnav__menuitem topnav__menuitem--icon module-studentcard--24"
       role="menuitem"       title="Mijn leerlingfiche">
        Mijn leerlingfiche
    </a>
                        
    <a href="/?module=News&amp;file=index"
       class="topnav__menuitem topnav__menuitem--icon module-news--24"
       role="menuitem"       title="Nieuwsberichten">
        Nieuwsberichten
    </a>
                        
    <a href="/online-session"
       class="topnav__menuitem topnav__menuitem--icon module-onlinesession--24"
       role="menuitem"       title="Online sessies">
        Online sessies
    </a>
                        
    <a href="/results"
       class="topnav__menuitem topnav__menuitem--icon module-results--24"
       role="menuitem"       title="Resultaten">
        Resultaten
    </a>
                        
    <a href="/?module=Agenda"
       class="topnav__menuitem topnav__menuitem--icon module-agenda--24"
       role="menuitem"       title="Schoolagenda">
        Schoolagenda
    </a>
                                <hr class="menu-divider"/>
            
    <a href="/?module=Manual&amp;file=manual&amp;function=main"
       class="topnav__menuitem topnav__menuitem--icon module-manual--24"
       role="menuitem"       title="Handleiding">
        Handleiding
    </a>
                                <hr class="menu-divider"/>
            
    <a href="https://www.diddit.be/login?smartschoolPlatform=spes-sint-rembert"
       class="topnav__menuitem topnav__menuitem--icon partner-diddit--24"
       role="menuitem" target="_blank"       title="diddit">
        diddit
    </a>
                        
    <a href=" https://platform.ftrprf.be/"
       class="topnav__menuitem topnav__menuitem--icon partner-ftrprf--24"
       role="menuitem" target="_blank"       title="FTRPRF">
        FTRPRF
    </a>
                        
    <a href="https://myway.i-learn.be/login?smartschoolPlatform=spes-sint-rembert"
       class="topnav__menuitem topnav__menuitem--icon partner-ilearn--24"
       role="menuitem" target="_blank"       title="i-Learn">
        i-Learn
    </a>
                        
    <a href="https://platform.ididdit.be/login?smartschoolPlatform=spes-sint-rembert"
       class="topnav__menuitem topnav__menuitem--icon partner-ididdit--24"
       role="menuitem" target="_blank"       title="iDiddit">
        iDiddit
    </a>
                        
    <a href="https://digitalemethode.be/nl-be/sso?subdomain=spes-sint-rembert"
       class="topnav__menuitem topnav__menuitem--icon partner-signpost-digtale-methode--24"
       role="menuitem" target="_blank"       title="Lernova">
        Lernova
    </a>
                        
    <a href="https://www.pelckmansportaal.be"
       class="topnav__menuitem topnav__menuitem--icon partner-pelckmans--24"
       role="menuitem" target="_blank"       title="Pelckmans Portaal">
        Pelckmans Portaal
    </a>
                        
    <a href="https://api.polpo.be/auth/smartschool-login/https%3A%2F%2Fwww.polpo.be%2Fplatform%2F?type=student&amp;platform=spes-sint-rembert"
       class="topnav__menuitem topnav__menuitem--icon partner-polpo--24"
       role="menuitem" target="_blank"       title="POLPO">
        POLPO
    </a>
                        
    <a href="https://www.scoodle.be/Aanmelden/External?Provider=Smartschool&amp;Platform=spes-sint-rembert.smartschool.be"
       class="topnav__menuitem topnav__menuitem--icon partner-scoodle--24"
       role="menuitem" target="_blank"       title="Scoodle">
        Scoodle
    </a>
                        
    <a href="/Partner/VRT/UITGEKLAARD"
       class="topnav__menuitem topnav__menuitem--icon partner-uitgeklaard--24"
       role="menuitem" target="_blank"       title="Uitgeklaard">
        Uitgeklaard
    </a>

          </div>
        </div>
    </div>

    <div data-courses class="topnav__btn-wrapper">
        <button class="js-btn-courses topnav__btn">
            Vakken
        </button>
    </div>

    
        <a href="/?module=Messages&file=index&function=main" class="js-btn-messages topnav__btn">Berichten
        <span class="js-badge-msg topnav__badge" role="status" aria-label="0 ongelezen berichten" aria-live="polite" aria-relevant="additions" hidden>0</span>
    </a>
    
    <div data-notifs class="topnav__btn-wrapper">
        <button class="js-btn-notifs topnav__btn">Meldingen
            <span class="js-badge-notifs topnav__badge" role="status" aria-label="0 ongelezen meldingen" aria-live="polite" aria-relevant="additions" hidden>0</span>
        </button>
    </div>
      
    <div data-search class="topnav__btn-wrapper">
        <button class="js-btn-search topnav__btn topnav__btn--icon topnav__btn--icon--search" newIntradeskEnabled="" title="Zoeken"></button>
    </div>
    <a href="/?module=Manual&file=manual&function=main" class="js-btn-manual topnav__btn topnav__btn--icon topnav__btn--icon--manual" title="Handleiding"></a>
        <a href="/logout" class="js-btn-logout topnav__btn topnav__btn--icon topnav__btn--icon--exit" title="Afmelden"></a>
  
  </nav>
    </header>

                    		<div id="smscMain" class="smscMain " tabindex="-1">
			    <input type="hidden" id="datepickerAgenda" value="1"/>
<input type="hidden" id="datepickerCalendar" value="0"/>
<input type="hidden" id="datepickerPlanner" value="0"/>
<div id="datePickerMenu" agendaurl="/?module=Agenda" plannerurl="/planner/main/user/645_2945_0/" class="datePickerMenu"></div>
<div id="container" class="homepage">
	<div id="leftcontainer" class="smsc-container--left homepage__left"><div class="homepage__block" id="homepage__block--contact">
    <!-- BEGIN top -->
    <div class="homepage__block__top">
        <div class="homepage__block__top__title">
            <h2 class="smsc-title--1" style="color: #C90001">Contactinformatie</h2>
        </div>
        <div class="homepage__block__top__buttonbar"></div>
    </div>
    <!-- END top -->
    <div class="homepage__block__content">
        <div>Spes Nostra Instituut</div>
<div>Pastoor Staelensstraat 4</div>
<div>8210 Zedelgem</div>
<div>&nbsp;</div>
<div x-ms-format-detection="none">Tel.: 050 20 96 15</div>
<div x-ms-format-detection="none">Fax: </div>
<div>E-mail: <a href="mailto:spes.nostra@sint-rembert.be" class="ssLink">spes.nostra@sint-rembert....</a></div>
<div>Web: <a href="http://www.spesnostrazedelgem.be" target="_blank" class="ssLink">http://www.spesnostrazede...</a></div>
    </div>
</div><div class="homepage__block" id="homepage__block--bibnet">
    
    <div class="homepage__block__content">
        <a class="homepage__image-link" href="http://www.bibliotheek.be/" target='_blank'>
    <div class="homepage__image-link__image smsc-svg--logo_de_bib" title="BibNet"></div>
</a>
<div class="homepage__search">
    <input id="bibnetQuery" type="search" size="23" maxlength="255" onkeydown="javascript:if(event.keyCode == 13){window.open('=' + $('#bibnetQuery').val().replace(' ', '+'));return false}" required />
    <button class="smscButton grey" onclick="javascript:window.open('=' + $('#bibnetQuery').val().replace(' ', '+'));return false;">Zoeken</button>
</div>
    </div>
</div></div>
	<div id="centercontainer" class="smsc-container--main homepage__center"><div class="homepage__block" id="homepage__block--news">
    <!-- BEGIN frametitle -->
        <div class="homepage__block__top">
            <div class="homepage__block__top__title">
                <h2 class="smsc-title--1" style="color: #C90001">Nieuws</h2>
            </div>
            <div class="homepage__block__top__buttonbar"></div>
        </div>
    <!-- END frametitle -->
    <div class="homepage__block__content">
        <div id="news_items"></div>
    </div>
</div><div class="homepage__block" id="homepage__block--student-support">
    <!-- BEGIN frametitle -->
        <div class="homepage__block__top">
            <div class="homepage__block__top__title">
                <h2 class="smsc-title--1" style="color: #C90001">Diensten voor jongeren</h2>
            </div>
            <div class="homepage__block__top__buttonbar"></div>
        </div>
    <!-- END frametitle -->
    <div class="homepage__block__content">
        <div id="student_support"></div>
    </div>
</div></div>
	<div id="rightcontainer" class="smsc-container--right homepage__right"><div class="homepage__block" id="homepage__block--datepicker">
    
    <div class="homepage__block__content">
        <div id="homeAgenda"></div>
    </div>
</div></div>
</div>
<script type="text/javascript" language="javascript">
var _JANUARI		= 'januari';	
var _FEBRUARI		= 'februari';	
var _MAART			= 'maart';	
var _APRIL			= 'april';	
var _MEI			= 'mei';	
var _JUNI			= 'juni';	
var _JULI			= 'juli';	
var _AUGUSTUS		= 'augustus';	
var _SEPTEMBER		= 'september';	
var _OKTOBER		= 'oktober';	
var _NOVEMBER		= 'november';	
var _DECEMBER		= 'december';

var _MAANDAGKORT	= 'ma';	
var _DINSDAGKORT	= 'di';
var _WOENSDAGKORT	= 'wo';
var _DONDERDAGKORT	= 'do';
var _VRIJDAGKORT	= 'vr';
var _ZATERDAGKORT	= 'za';
var _ZONDAGKORT		= 'zo';

var _unixtimedate = '1709840746';
var _getItemsurl = '/?module=Homepage&function=getCalendarItems';
var _calendarUrl = '/?module=Calendar';

</script>
		</div>
                
        <!-- javascript variables -->
        <script type="text/javascript">var SMSC = SMSC || {};</script>
                                        <script type="text/javascript">$.extend(true, SMSC, JSON.parse('\u007B\u0022vars\u0022\u003A\u007B\u0022showNotifyAlerts\u0022\u003Atrue,\u0022isMP\u0022\u003Afalse,\u0022tracklogging\u0022\u003Atrue,\u0022storageToken\u0022\u003A\u00223210b3351aa5c92fbf000acdc7cc3f7a\u0022,\u0022socketUrl\u0022\u003A\u0022https\u003A\\\/\\\/nodejs\u002Ddcg.smartschool.be\u0022,\u0022socketPort\u0022\u003A\u0022443\u0022,\u0022queueUuid\u0022\u003A\u002264d4bfb0\u002Dbb3c\u002D4e41\u002Da4a6\u002Dc2053dada792\u0022,\u0022userID\u0022\u003A2945,\u0022lng_rpc_error_title\u0022\u003A\u0022Melding\u0022,\u0022lng_rpc_error_unknown_msg\u0022\u003A\u0022Er\u0020is\u0020een\u0020onbekende\u0020fout\u0020opgetreden.\u0022,\u0022lng_rpc_error_not_found\u0022\u003A\u0022Het\u0020onderdeel\u0020dat\u0020je\u0020zoekt\u0020is\u0020niet\u0020gevonden.\u0020Mogelijk\u0020is\u0020het\u0020verwijderd\u0020of\u0020onzichtbaar\u0020gemaakt.\u0022,\u0022lng_rpc_error_close\u0022\u003A\u0022Sluiten\u0022,\u0022lng_rpc_error_ok\u0022\u003A\u0022OK\u0022,\u0022lng_rpc_following_errors_appeared\u0022\u003A\u0022Volgende\u0020fouten\u0020zijn\u0020opgetreden\u0022,\u0022campaigns\u0022\u003A\u005B\u005D\u007D\u007D'));</script>

                                        <script type="text/javascript">$.extend(true, SMSC, JSON.parse('\u007B\u0022quickSearch\u0022\u003A\u007B\u0022quicksearch.search_placeholder\u0022\u003A\u0022Zoeken...\u0022,\u0022quicksearch.search_option_own\u002Dplatform\u002Donly\u0022\u003A\u0022Enkel\u0020in\u0020eigen\u0020platform\u0020zoeken\u0022,\u0022quicksearch.search_option_include\u002Ddeleted\u0022\u003A\u0022Ook\u0020\u003Cspan\u0020style\u003D\\\u0022color\u003A\u0023E30000\u003B\u0020font\u002Dweight\u003A\u0020bold\u003B\\\u0022\u003Everwijderde\u003C\\\/span\u003E\u0020gebruikers\u0020tonen\u0022,\u0022quicksearch.default_deleted_string\u0022\u003A\u0022verwijderd\u0022,\u0022quicksearch.search_not_found\u0022\u003A\u0022We\u0020hebben\u0020__SEARCHSTRING__\u0020niet\u0020gevonden.\u0020Probeer\u0020een\u0020andere\u0020zoekterm.\u0022,\u0022quicksearch.search_subtitle_suggestions\u0022\u003A\u0022Suggesties\u0022,\u0022quicksearch.currentUser\u0022\u003A\u0022Aangemelde\u0020gebruiker\u0022,\u0022quicksearch.me\u0022\u003A\u0022Mezelf\u0022,\u0022quicksearch.all_students\u0022\u003A\u0022Alle\u0020leerlingen\u0022,\u0022planner.user_role.1\u0022\u003A\u0022Alle\u0020leerlingen\u0022,\u0022quicksearch.unassigned\u0022\u003A\u0022Niemand\u0022,\u0022quicksearch.search_subtitle_favourites\u0022\u003A\u0022Favorieten\u0022,\u0022quicksearch.mark_as_favourite\u0022\u003A\u0022Toevoegen\u0020aan\u0020favorieten\u0022,\u0022quicksearch.discard_as_favourite\u0022\u003A\u0022Verwijderen\u0020uit\u0020favorieten\u0022,\u0022quicksearch.co_account_type_\u002D1\u0022\u003A\u0022hoofdaccounts\u0022,\u0022quicksearch.co_account_type_\u002D2\u0022\u003A\u0022alle\u0020co\u002Daccounts\u0022,\u0022property.co\u002Daccount\u002Dtype.main\u0022\u003A\u0022Hoofdaccounts\u0022,\u0022bubble_coaccountfilter_title\u0022\u003A\u0022Specifieke\u0020accounttypes\u0020voor\u0020deze\u0020groep\\\/klas\u0020selecteren\u0022,\u0022bubble_coaccountfilter_tokeninput_emptystate\u0022\u003A\u0022Zoek\u0020naar\u0020accounttypes\u0022,\u0022bubble_coaccountfilter_quickfilter_title\u0022\u003A\u0022Snelle\u0020filters\u0022,\u0022quicksearch_clear_selection\u0022\u003A\u0022Selectie\u0020verwijderen\u0022,\u0022\u0025quick\u002Dsearch.co\u002Daccount\u002Dfilter.main\u002Daccounts\u0025\u0022\u003A\u0022Hoofdaccounts\u0022,\u0022\u0025quick\u002Dsearch.co\u002Daccount\u002Dfilter.all\u002Dco\u002Daccounts\u0025\u0022\u003A\u0022alle\u0020Co\u002Daccounts\u0022,\u0022\u0025quick\u002Dsearch.co\u002Daccount\u002Dfilter.non\u002Dprofessional\u002Dco\u002Daccounts\u0025\u0022\u003A\u0022Familie\u0022\u007D,\u0022vars\u0022\u003A\u007B\u0022locale\u0022\u003A\u0022nl\u0022,\u0022userPictureDomain\u0022\u003A\u0022https\u003A\\\/\\\/userpicture10.smartschool.be\u0022,\u0022currentUser\u0022\u003A\u007B\u0022userIdentifier\u0022\u003A\u0022645_2945_0\u0022,\u0022userPictureHash\u0022\u003A\u0022645_6057ec08\u002D935e\u002D4d62\u002D91cf\u002Db87e3d6230f0\u0022,\u0022userPictureUrl\u0022\u003A\u0022https\u003A\\\/\\\/userpicture10.smartschool.be\\\/User\\\/Userimage\\\/hashimage\\\/hash\\\/645_6057ec08\u002D935e\u002D4d62\u002D91cf\u002Db87e3d6230f0\\\/plain\\\/1\\\/res\\\/128\u0022,\u0022name\u0022\u003A\u0022Jasper\u0020\u0020Goderis\u0020\u0022,\u0022nameReverse\u0022\u003A\u0022Goderis\u0020\u0020Jasper\u0020\u0022,\u0022description\u0022\u003A\u0022\u0022,\u0022descriptionReverse\u0022\u003A\u0022\u0022\u007D,\u0022tinyMCEVersion\u0022\u003A\u00226.7.1\u0022,\u0022ssID\u0022\u003A645\u007D\u007D'));</script>

            <script type="text/javascript">$.extend(true, SMSC, JSON.parse('\u007B\u0022wopiConfig\u0022\u003A\u007B\u0022wopiActions\u0022\u003A\u007B\u0022pdf\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Pdf\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/mime_pdf\\\/mime_pdf_16x16.png\u0022\u007D\u007D,\u0022csv\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Excel\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Excel\u002Dcolor\\\/Excel\u002Dcolor_16x16.png\u0022\u007D,\u0022convert\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Excel\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Excel\u002Dcolor\\\/Excel\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022ods\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Excel\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Excel\u002Dcolor\\\/Excel\u002Dcolor_16x16.png\u0022\u007D,\u0022edit\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Excel\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Excel\u002Dcolor\\\/Excel\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022xls\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Excel\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Excel\u002Dcolor\\\/Excel\u002Dcolor_16x16.png\u0022\u007D,\u0022convert\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Excel\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Excel\u002Dcolor\\\/Excel\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022xlsb\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Excel\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Excel\u002Dcolor\\\/Excel\u002Dcolor_16x16.png\u0022\u007D,\u0022edit\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Excel\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Excel\u002Dcolor\\\/Excel\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022xlsm\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Excel\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Excel\u002Dcolor\\\/Excel\u002Dcolor_16x16.png\u0022\u007D,\u0022edit\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Excel\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Excel\u002Dcolor\\\/Excel\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022xlsx\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Excel\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Excel\u002Dcolor\\\/Excel\u002Dcolor_16x16.png\u0022\u007D,\u0022edit\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Excel\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Excel\u002Dcolor\\\/Excel\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022odp\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022PowerPoint\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/PowerPoint\u002Dcolor\\\/PowerPoint\u002Dcolor_16x16.png\u0022\u007D,\u0022edit\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022PowerPoint\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/PowerPoint\u002Dcolor\\\/PowerPoint\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022pot\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022PowerPoint\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/PowerPoint\u002Dcolor\\\/PowerPoint\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022potm\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022PowerPoint\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/PowerPoint\u002Dcolor\\\/PowerPoint\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022potx\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022PowerPoint\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/PowerPoint\u002Dcolor\\\/PowerPoint\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022pps\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022PowerPoint\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/PowerPoint\u002Dcolor\\\/PowerPoint\u002Dcolor_16x16.png\u0022\u007D,\u0022convert\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022PowerPoint\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/PowerPoint\u002Dcolor\\\/PowerPoint\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022ppsm\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022PowerPoint\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/PowerPoint\u002Dcolor\\\/PowerPoint\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022ppsx\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022PowerPoint\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/PowerPoint\u002Dcolor\\\/PowerPoint\u002Dcolor_16x16.png\u0022\u007D,\u0022edit\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022PowerPoint\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/PowerPoint\u002Dcolor\\\/PowerPoint\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022ppt\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022PowerPoint\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/PowerPoint\u002Dcolor\\\/PowerPoint\u002Dcolor_16x16.png\u0022\u007D,\u0022convert\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022PowerPoint\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/PowerPoint\u002Dcolor\\\/PowerPoint\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022pptm\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022PowerPoint\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/PowerPoint\u002Dcolor\\\/PowerPoint\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022pptx\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022PowerPoint\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/PowerPoint\u002Dcolor\\\/PowerPoint\u002Dcolor_16x16.png\u0022\u007D,\u0022edit\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022PowerPoint\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/PowerPoint\u002Dcolor\\\/PowerPoint\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022vdw\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Visio\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Visio\u002Dcolor\\\/Visio\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022vsd\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Visio\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Visio\u002Dcolor\\\/Visio\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022vsdm\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Visio\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Visio\u002Dcolor\\\/Visio\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022vsdx\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Visio\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Visio\u002Dcolor\\\/Visio\u002Dcolor_16x16.png\u0022\u007D,\u0022edit\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Visio\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Visio\u002Dcolor\\\/Visio\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022wopitest\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022WopiTest\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/WopiTest\u002Dcolor\\\/WopiTest\u002Dcolor_16x16.png\u0022\u007D,\u0022edit\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022WopiTest\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/WopiTest\u002Dcolor\\\/WopiTest\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022wopitestx\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022WopiTest\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/WopiTest\u002Dcolor\\\/WopiTest\u002Dcolor_16x16.png\u0022\u007D,\u0022edit\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022WopiTest\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/WopiTest\u002Dcolor\\\/WopiTest\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022doc\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Word\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Word\u002Dcolor\\\/Word\u002Dcolor_16x16.png\u0022\u007D,\u0022convert\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Word\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Word\u002Dcolor\\\/Word\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022docm\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Word\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Word\u002Dcolor\\\/Word\u002Dcolor_16x16.png\u0022\u007D,\u0022edit\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Word\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Word\u002Dcolor\\\/Word\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022docx\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Word\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Word\u002Dcolor\\\/Word\u002Dcolor_16x16.png\u0022\u007D,\u0022edit\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Word\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Word\u002Dcolor\\\/Word\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022dot\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Word\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Word\u002Dcolor\\\/Word\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022dotm\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Word\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Word\u002Dcolor\\\/Word\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022dotx\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Word\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Word\u002Dcolor\\\/Word\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022odt\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Word\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Word\u002Dcolor\\\/Word\u002Dcolor_16x16.png\u0022\u007D,\u0022edit\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Word\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Word\u002Dcolor\\\/Word\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022rtf\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022Word\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/Word\u002Dcolor\\\/Word\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022b\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022WordPrague\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/WordPrague\u002Dcolor\\\/WordPrague\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022fluid\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022WordPrague\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/WordPrague\u002Dcolor\\\/WordPrague\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022note\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022WordPrague\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/WordPrague\u002Dcolor\\\/WordPrague\u002Dcolor_16x16.png\u0022\u007D\u007D,\u0022whiteboard\u0022\u003A\u007B\u0022view\u0022\u003A\u007B\u0022applicationName\u0022\u003A\u0022WordPrague\u0022,\u0022applicationIcon\u0022\u003A\u0022\\\/smsc\\\/img\\\/WordPrague\u002Dcolor\\\/WordPrague\u002Dcolor_16x16.png\u0022\u007D\u007D\u007D,\u0022allowCreate\u0022\u003Atrue\u007D\u007D'));</script>


          
        <!-- javascriptContent Body  -->
                                        <script type="text/javascript">;(function(window, document, $, undefined) { $(document).ready(function(e){ $.datepicker.setDefaults($.datepicker.regional['nl-BE']); }); })(window, document, jQuery);</script>
            <script type="text/javascript">
		var jsTemplates 						= {"tpl_js_homepage_pns_news_all":"<div class=\"news__feed\">    <button       class=\"news__feed__button smsc-svg--{iconSvg}--24\"       onclick=\"oPns.showNewsInDialog({newsID}, {editable})\"       style=\"{style}\">        <div class=\"news__feed__button__content\" style=\"color: #{titleColor}\">            <span class=\"news__feed__button__content--title\">{title}<\/span>            <span class=\"news__feed__button__content--name-date\">{name}{date}<\/span>        <\/div>    <\/button><\/div>"};
		var _NO_ITEM_AVAILABLE					= 'U heeft momenteel geen nieuwe items.';
		var _NO_NEWS_AVAILABLE					= 'Er bevinden zich geen nieuwe nieuwsberichten in deze categorie.';
		var _ACTIONS_MORE						= 'Meer acties';
		var _ACTIONS_ACTION						= 'Dit bestand opslaan';
		var _ACTIONS_VIEW_VISIBLE				= 'Maak zichtbaar';
		var _ACTIONS_VIEW_INVISIBLE				= 'Maak onzichtbaar';
		var _ACTIONS_DISABLE_MODTYPE			= 'Verberg alles van deze module';
		var _PNS_DISABLEDFORMAINTENACE_TITLE	= 'Geplande onderhoudswerken';
		var _PNS_DISABLEDFORMAINTENACE_SUBTITLE	= 'Wegens geplande onderhoudswerken is dit onderdeel even niet beschikbaar.';
		var _DATEPICKER_CALENDAR				= 'Open mijn kalender';
		var _DATEPICKER_AGENDA					= 'Open mijn schoolagenda';
		var _DATEPICKER_PLANNER					= 'Open mijn planner';
	</script>
            <script type="text/javascript">var _LNG_ERROR_TITLE= 'Melding';var _LNG_ERROR_MSG= 'Er is een onbekende fout opgetreden waardoor de gevraagde actie niet kon worden uitgevoerd. Vernieuw de pagina (F5) of meld u opnieuw aan indien uw sessie verlopen is.';var _LNG_PHOTOSTRIPNAVLEFT = 'Navigeer links';var _LNG_PHOTOSTRIPNAVRIGHT = 'Navigeer rechts';var _LNG_PHOTOSTRIPGOTOALBUM = 'Ga naar album';var _LNG_PHOTOSTRIPCLICKTOCLOSE = 'Klik om te sluiten';var _LNG_PHOTOSTRIPCLICKTOENLARGE = 'Klik om te vergroten';var _LNG_FOLDERFILESTRIPCLICKFOLDER = 'Klik om deze map binnen te gaan';var _LNG_FOLDERFILESTRIPCLICKFILE = 'Klik om dit bestand te downloaden';var _LNG_FOLDERFILESTRIPCLICKGOUP = 'Klik om een niveau naar boven te gaan';var _LNG_FOLDERFILESTRIPCLICKGOUP_TEXT = 'Terug naar bovenliggende map';var _LNG_FOLDERFILESTRIPCLICKFILE_OPEN = 'Klik om dit bestand te openen';var _LNG_FOLDERFILESTRIPNOCONTENT = 'Deze map is leeg';var _LNG_LIGHTBOX_IMAGE= 'Afbeelding';var _LNG_LIGHTBOX_OF= 'van';</script>
            <script type="text/javascript">$.extend(true, SMSC, { vars : {"lng":{"add_klas":"","news":{"news_dialog":{"close":"Sluiten"},"edit_news":{"edit_news_close":"Sluiten","edit_news_save":"Opslaan","edit_news_save_and_notify":"Opslaan en melden","edit_news_tab_message":"Bericht","edit_news_tab_options":"Opties","edit_news_tab_groups":"Groepen","edit_news_tab_idk":"In de kijker","edit_news_form_title":"Titel","edit_news_form_message":"Inhoud","edit_news_form_visible":"Zichtbaar","edit_news_form_visible_from":"van ...","edit_news_form_visible_until":"tot ...","edit_news_form_agenda":"Tonen in kalender","edit_news_form_agenda_from":"van ...","edit_news_form_agenda_until":"tot ...","edit_news_form_community":"_COMMUNITY","edit_news_form_icon":"Icoon","edit_news_form_idk_show_in_browser_label":"Browser","edit_news_form_idk_show_in_browser":"Nieuwsbericht 'in de kijker' tonen op de startpagina in de browser","edit_news_form_idk_position_left":"links","edit_news_form_idk_position_top":"midden boven","edit_news_form_idk_position_bottom":"midden onder","edit_news_form_idk_position_right":"rechts","edit_news_form_idk_show_in_app_label":"App","edit_news_form_idk_show_in_app":"Nieuwsbericht 'in de kijker' tonen in de app","edit_news_form_idk_show_in_app_info":"In de app worden 'strips' niet getoond.","edit_news_form_idk_show_in_list_label":"Extra in lijst","edit_news_form_idk_show_in_list":"Nieuwsbericht ook nog eens in de lijst met de gewone nieuwsberichten tonen","edit_news_form_idk_show_in_list_info":"Een 'in de kijker'-bericht wordt standaard niet in de lijst met de gewone nieuwsberichten getoond. Met deze optie kan je dit nieuwsbericht wel in de lijst tonen tussen alle andere nieuwsberichten. Met deze optie staat het bericht dus 'in de kijker' \u00e9n in de lijst.","edit_news_form_idk_info_title_1":"Wat is een 'in de kijker'-bericht?","edit_news_form_idk_info_content_1":"Een 'in de kijker'-bericht is <b>een blokje op de startpagina<\/b> van Smartschool in de browser of in de app. Hierdoor staat het nieuwsbericht 'in de kijker', dus valt het meteen op. Gebruik 'in de kijker'-berichten om het belangrijkste nieuws of foto's van uitstappen onder de aandacht te brengen.","edit_news_form_idk_info_title_2":"Hoe worden 'in de kijker'-berichten gesorteerd?","edit_news_form_idk_info_content_2":"De 'in de kijker'-berichten worden gesorteerd volgens de wijzigdatum. <b>Het bericht dat als laatste werd gewijzigd staat onderaan.<\/b> De uitzondering hierop is het wijzigen van het bericht via de startpagina zelf.","edit_news_form_idk_info_link_href":"\/?module=Manual&file=manual&layout=2&id=handleiding:nieuwsberichten:in-de-kijker","edit_news_form_idk_info_link_label":"Lees alle informatie in de handleiding.","edit_news_form_publish":"Publiceer dit nieuwsbericht voor","edit_news_form_publish_head":"Hoofdaccounts","edit_news_form_publish_co":"Co-accounts","edit_news_form_publish_usc":"Selecteer groepen","edit_news_button":"Wijzigen","edit_news_title":"Nieuwsbericht wijzigen","edit_news_cancel":"Annuleren","edit_news_info":"De wijzigdatum van dit nieuwsbericht wordt niet gewijzigd. Hierdoor blijft het nieuwsbericht op dezelfde plaats staan op de startpagina.","edit_news_form_color":"Kleur titel"}},"studentSupport":{"student_support_name":"Diensten voor jongeren","student_support_empty_state":"Er zijn geen diensten voor jongeren zichtbaar voor je."}},"login":{"isWithAcm":false,"isWithFas":false}}});</script>
    
                                <script type="text/javascript">$.extend(true, SMSC, JSON.parse('\u007B\u0022topnav\u0022\u003A\u007B\u0022lang\u0022\u003A\u007B\u0022badge\u0022\u003A\u007B\u0022badge_unread_notifs\u0022\u003A\u0022Ongelezen\u0020meldingen\u0022\u007D,\u0022courses\u0022\u003A\u007B\u0022courses_menu_title\u0022\u003A\u0022Vakken\u0022,\u0022courses_menu_search_placeholder\u0022\u003A\u0022Zoek\u0020naar\u0020een\u0020vak\u0022,\u0022courses_menu_no_courses\u0022\u003A\u0022Geen\u0020vakken\u0020gevonden\u0022\u007D,\u0022filter\u0022\u003A\u007B\u0022filter_sections_communication\u0022\u003A\u0022Communicatie\u0022,\u0022filter_sections_files\u0022\u003A\u0022Bestanden\u0022,\u0022filter_sections_mycourses\u0022\u003A\u0022Vakken\u0022,\u0022filter_sections_others\u0022\u003A\u0022Anderen\u0022,\u0022filter_options_sort_filter\u0022\u003A\u0022Sorteren\u0020en\u0020filteren\u0022,\u0022filter_filter_sort\u0022\u003A\u0022Sortering\u0022,\u0022filter_filter_bydate\u0022\u003A\u0022Filter\u0020op\u0020periode\u0022\u007D,\u0022go\u0022\u003A\u007B\u0022link.go.name\u0022\u003A\u0022GO\u0021\u0022,\u0022link.go_pro.name\u0022\u003A\u0022GO\u0021\u0020pro\u0022,\u0022link.go_training.name\u0022\u003A\u0022GO\u0021\u0020ondersteuningsaanbod\u0022,\u0022link.go_parents.name\u0022\u003A\u0022GO\u0021\u0020ouders\u0022,\u0022link.go_clb.name\u0022\u003A\u0022GO\u0021\u0020CLB\u0022,\u0022link.go_pro_curricula.name\u0022\u003A\u0022GO\u0021\u0020pro\u0020leerplannen\u0022,\u0022courses_menu_title\u0022\u003A\u0022Mijn\u0020virtuele\u0020ruimtes\u0022,\u0022link_menu_title\u0022\u003A\u0022Snel\u0020naar\u0022,\u0022curriculum_menu_title\u0022\u003A\u0022GO\u0021\u0020leerplannen\u0022,\u0022link_virtualSpace\u0022\u003A\u0022Op\u0020virtuele\u0020ruimtes\u0020van\u0020het\u0020GO\u0021\u0020abonneren\u0022\u007D,\u0022notifications\u0022\u003A\u007B\u0022notifs_placeholder\u0022\u003A\u0022Er\u0020zijn\u0020geen\u0020meldingen.\u0020Je\u0020bent\u0020volledig\u0020up\u002Dto\u002Ddate\u0021\u0022,\u0022notifs_toggle\u0022\u003A\u0022Nieuwe\u0020meldingen\u0020tonen\u0020als\u0020pop\u002Dup\u0022,\u0022notifs_toggle_on\u0022\u003A\u0022Aan\u0022,\u0022notifs_toggle_off\u0022\u003A\u0022Uit\u0022,\u0022notifs_settings\u0022\u003A\u0022Instellingen\u0022,\u0022notifs_clear\u0022\u003A\u0022Alles\u0020wissen\u0022,\u0022notifs_error\u0022\u003A\u0022Het\u0020ophalen\u0020van\u0020de\u0020meldingen\u0020is\u0020mislukt.\u0020Vernieuw\u0020de\u0020pagina\u0020en\u0020probeer\u0020opnieuw.\u0022\u007D,\u0022notification\u0022\u003A\u007B\u0022notif_mark_as_read\u0022\u003A\u0022Uit\u0020de\u0020lijst\u0020verwijderen\u0022\u007D,\u0022profile\u0022\u003A\u007B\u0022profile_img_alt\u0022\u003A\u0022Profiel\u0020afbeelding\u0022\u007D,\u0022search\u0022\u003A\u007B\u0022search_input_placeholder\u0022\u003A\u0022Zoeken\u0022,\u0022search_results_placeholder\u0022\u003A\u0022Waar\u0020ben\u0020je\u0020naar\u0020op\u0020zoek\u003F\u0022,\u0022search_more_results\u0022\u003A\u0022Toon\u0020meer\u0020resultaten\u0022,\u0022search_no_results\u0022\u003A\u0022Er\u0020werden\u0020geen\u0020resultaten\u0020gevonden.\u0022,\u0022search_searching\u0022\u003A\u0022Bezig\u0020met\u0020zoeken\u0020...\u0022,\u0022search_info\u0022\u003A\u0022Geef\u0020een\u0020zoekterm\u0020in\u0020en\u0020druk\u0020op\u0020enter\u0020om\u0020te\u0020zoeken.\u0022,\u0022search_from\u0022\u003A\u0022van\u0022,\u0022search_to\u0022\u003A\u0022naar\u0022,\u0022search_module_persons\u0022\u003A\u0022Personen\u0022,\u0022search_time_all\u0022\u003A\u0022Toon\u0020alles\u0022,\u0022search_time_today\u0022\u003A\u0022Vandaag\u0022,\u0022search_time_last_7_days\u0022\u003A\u0022Deze\u0020week\u0022,\u0022search_time_last_30_days\u0022\u003A\u0022Deze\u0020maand\u0022,\u0022search_time_current_schoolyear\u0022\u003A\u0022Dit\u0020schooljaar\u0022,\u0022search_checkbox_own_platform\u0022\u003A\u0022Enkel\u0020in\u0020eigen\u0020platform\u0020zoeken\u0022\u007D,\u0022toast\u0022\u003A\u007B\u0022toast_close\u0022\u003A\u0022Sluiten\u0022\u007D,\u0022toaster\u0022\u003A\u007B\u0022toaster_sessionextender_title\u0022\u003A\u0022Wilt\u0020u\u0020aangemeld\u0020blijven\u003F\u0022,\u0022toaster_sessionextender_description\u0022\u003A\u0022U\u0020wordt\u0020automatisch\u0020afgemeld\u0020binnen\u0020___id___\u0020seconden.\u0022,\u0022toaster_sessionextender_button\u0022\u003A\u0022OK\u0022\u007D\u007D\u007D\u007D'));</script>

            <!-- Javascript_Topnav -->
                                        <script type="text/javascript" src="https://static5.smart-school.net/production/Topnav/main.rev-7677dcfc8a.js"></script>
    
                            <!-- Javascript_Body_Urls -->
                                <script type="text/javascript" src="https://static3.smart-school.net/smsc/resources/requirejs/2.3.3/require.min.rev-3d6d162db3.js"></script>
            <script type="text/javascript" src="https://static3.smart-school.net/modules/Homepage/dist/main-built.rev-2d83ea3964.js"></script>
            <script type="text/javascript" src="https://static3.smart-school.net/includes/jQuery/plugins/timepicker/langs/jquery.ui.timepicker-nl.rev-a9b91fe807.js"></script>
    
                <!-- Javascript_requirejs_Urls -->
                        
        		<!-- Javascript_legacy_stealjs_Urls -->
                        
                
        <!-- Javascript_symfony -->
                                    
                </body>
</html>
