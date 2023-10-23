<p><link href="/resources/neo4jd3/css/neo4jd3.min.css?v=0.0.1" rel="stylesheet"/></p>
<!DOCTYPE html>

<p><html class="html" lang="ko">
<head>
<title id="mainTitle">메인 </title>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1, shrink-to-fit=no" name="viewport"/>
<meta content="IE=edge" name="X-UA-Compatible"/>
<meta content="text/javascript" name="Content-Script-Type"/>
<meta content="text/css" name="Content-Style-Type"/>
<meta content="telephone=no,email=no,address=no" name="format-detection"/>
<meta content="Research Data Platform" name="apple-mobile-web-app-title"/></p>
<!-- <meta name="robots" content="noindex">  -->
<p><link href="https://dataon.kisti.re.kr/" rel="canonical"/>
<meta content="국가 연구데이터 플랫폼" name="title"/>
<meta content="국가 연구데이터 플랫폼" name="keywords"/>
<meta content="국가 연구데이터 플랫폼 Data ON" name="description"/>
<meta content="국가 연구데이터 플랫폼" property="og:title"/>
<meta content="국가연구데이터플랫폼서비스 Data ON" property="og:description"/>
<meta content="Copyright@2019  DataON. All Rights Reserved." name="copyright"/></p>
<!-- img-src

    https://www.google-analytics.com/   공지사항 에디터 첨부 이미지
    https://nrms.kisti.re.kr/           표/그림 검색 이미지
    https://dataon.kisti.re.kr/         차트 이미지 다운로드 (체크필요)
    blob:                               차트 이미지 다운로드 가능
    https://img.etnews.com/             뉴스기사 첨부 이미지
        -->
<!-- style-src
    http://code.jquery.com/             jquery 
    https://fonts.googleapis.com/       google font
     -->
<!-- script-src
    https://kit.fontawesome.com/        아이콘
    https://www.google-analytics.com/   Google Analytics
    https://www.googletagmanager.com/   Google Tag Manager

    https://s7.addthis.com/             데이터셋 상세페이지 외부 공유 기능
    https://z.moatads.com/ 
    https://v1.addthisedge.com/ 
    https://m.addthis.com/      -->
<p><meta content="default-src * https://www.googletagmanager.com/; 
            img-src 'self' 'unsafe-inline' blob: data: https://www.google-analytics.com/ https://nrms.kisti.re.kr/ https://dataon.kisti.re.kr/ 
                    https://img.etnews.com/ https://a.tile.openstreetmap.org/ https://b.tile.openstreetmap.org/ https://c.tile.openstreetmap.org/;
            style-src 'self' 'unsafe-inline' http://code.jquery.com/ https://fonts.googleapis.com/ 
                    https://cdn.jsdelivr.net/;
            object-src 'self' 'unsafe-inline'  ;
            script-src 'self' 'unsafe-inline' 'unsafe-eval' https://kit.fontawesome.com/  https://www.google-analytics.com/ https://www.googletagmanager.com/ 
                    https://s7.addthis.com/ https://z.moatads.com/ https://v1.addthisedge.com/ https://m.addthis.com/ 
                    http://ajax.googleapis.com/ http://cdnjs.cloudflare.com/ https://cdn.jsdelivr.net/" http-equiv="Content-Security-Policy"/>
<meta content="strict-origin-when-cross-origin" name="referrer">
<link href="/resources/images/favicon/favicon_new.ico" rel="shortcut icon" type="image/x-icon">
<link href="/resources/images/favicon/favicon_new.ico" rel="apple-touch-icon">
<link href="/resources/css/main.css" rel="stylesheet"/>
<link href="/resources/css/mainpage.css" rel="stylesheet"/>
<link href="/resources/css/dist/bootstrap/bootstrap.css" rel="stylesheet">
<link href="/resources/css/all.css" rel="stylesheet">
<link href="/resources/css/dist/summernote/summernote-lite.css" rel="stylesheet"/>
<link href="/resources/css/dist/etc/nprogress.css" rel="stylesheet"/>
<link href="/resources/css/dist/jqplot/jquery.jqplot.css" rel="stylesheet"/>
<link href="/resources/css/dist/tree/ui.fancytree.css" rel="stylesheet">
<link href="/resources/css/style.css" rel="stylesheet"/>
<link href="/resources/css/sub.css" rel="stylesheet"/>
<link href="/resources/css/style_introduce.css" rel="stylesheet"/>
<link href="/resources/css/style_DO_introduce.css" rel="stylesheet"/>
<link href="/resources/css/font/dingbat_xeicon.css" rel="stylesheet"/>
<link href="/resources/css/webfonts.css" rel="stylesheet"/>
<link href="/resources/css/dist/modal/jquery.modal.min.css" rel="stylesheet"/>
<link href="/resources/css/content.css" rel="stylesheet"/>
<link href="//code.jquery.com/ui/1.12.1/themes/base/jquery-ui.css" rel="stylesheet"/></p>
<!-- 추가 (210924 - 데이트피커 사용) -->

<!-- 추가 (210924 - 데이트피커 사용) -->
<!-- <script type="text/javascript" src="/resources/js/dist/jquery/fullpage.min.js"></script> -->

<!-- 추가 (210924 - 데이트피커사용) -->
<p><link href="/resources/css/dist/newDist/bootstrap-datepicker.min.css" rel="stylesheet">
<link href="/resources/css/newAsset/pickadate2/lib/themes/default.css" rel="stylesheet">
<link href="/resources/css/newAsset/pickadate2/lib/themes/default.date.css" rel="stylesheet"/>
<link href="/resources/css/newAsset/pickadate2/lib/themes/default.time.css" rel="stylesheet"/></p>
<!-- 추가 (210924 - 데이트피커사용) -->
<!-- 추가 (210924 - 타임피커 사용) -->

<!-- 추가 (210924 - 타임피커 사용) -->
<!-- 파일 미리보기  -->

<p><link crossorigin="anonymous" href="https://cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.css" integrity="sha256-Mi0V2Z77eSyUGlIC+o/H7p6TKEcic4P/lgUWMzigjqw=" rel="stylesheet"/>
<link href="/resources/css/preview.css" rel="stylesheet"></p>
<!-- Google tag (gtag.js) -->

<p></link></link></link></link></link></link></link></link></meta></head></p>
<body onload="fn_init()">
<!-- 페이지들과 id(wrap)중복으로 변경 -->
<div id="unsupported_wrap">
<div id="#unsupported" style="display: none;">
            현재 사용중이신 Internet Explorer는 지원되지 않는 버전입니다.<br/>
<a href="http://www.google.com/chrome/" target="_blank">Google Chrome</a> 또는 Internet Explorer 10+ 버전의 웹 브라우저 사용을 권장 합니다.
        </div>


<!-- page wrap -->

<!-- 자동 로그아웃 세션 알림창 시작 21.11.18 비네아 박기석 -->
<div class="session_timer" id="session_timer">
<div class="session_timer_header">
<div class="rdppopuptit">
                세션만료알림
            </div>
</div>
<br/>
<!-- 타이머 숫자 표시  -->
<span id="timer"></span> 후 자동 로그아웃됩니다.<br/>
<span>세션을 초기화하시겠습니까?</span><br/><br/>
<button class="btn btn-outline-secondary" onclick="clearTime(30)" type="button">연장</button>
<button class="btn btn-outline-secondary" onclick="session_timer_close()" type="button">무시</button>
</div>
<!-- 자동 로그아웃 세션 알림창 끝 21.11.18 비네아 박기석 -->
<div id="skipNav">
<a class="container_skipNav" href="#container">본문으로 바로가기</a>
<a class="main_skipNav" href="#content">본문으로 바로가기</a>
<a href="#gnb">주메뉴 바로가기</a>
</div>
<div id="wrap">
<header id="header_top">
<div class="header_wrap">
<h1 id="logo"><a href="/index.jsp"><img alt="데이터온" src="assets/logo.png"/></a></h1>
<nav class="gnb" id="gnb">
<h2 class="blind">전체메뉴</h2>
<div class="mo_mem">
<!-- 로그인 후 -->
<strong class="mem_name"></strong>
<ul class="m_mem_list">
<li><a href="/mypage/mypageMain.do?mm=myPage&amp;sm=myPage">마이페이지</a></li>
<li><a href="/user/userLogin.do">로그인</a></li>
<!-- id(engBtn)중복으로 class로 변경 -->
<li><a class="engBtn" href="#" onclick="fn_enMsg(); return false;">ENG</a></li>
</ul>
</div>
<ul>
<!-- 20221005 영문페이지 제외 -->
<!-- 0 level -->
<li><a href="#"><span>DataON</span></a>
<div class="sub">
<ul>
<!-- 1 level start -->
<!-- 1 level 내용 -->
<li>
<a href="/intro/intro01.do">소개</a>
<!-- 2 level -->
<!-- 2 level 내용 -->
<ul>
<li><a href="/intro/intro01.do">사업개요</a></li>
<!-- 2 level 내용 -->
<li><a href="/intro/intro03.do">연혁</a></li>
<!-- 2 level 내용 -->
<li><a href="/intro/intro02.do">서비스개요</a></li>
<!-- 2 level 내용 -->
<li><a href="/intro/intro07.do">연계기관</a></li>
<!-- 2 level 내용 -->
<li><a href="/intro/intro04.do">CI/BI</a></li>
<!-- 2 level 내용 -->
<li><a href="/intro/intro08.do">조직도</a></li>
<!-- 2 level 내용 -->
<li><a href="/intro/intro09.do">Metadata Schema</a></li>
</ul>
</li>
<!-- 1 level 내용 -->
<li>
<a href="/notice/noticeList_R.do">알림</a>
<!-- 2 level -->
<!-- 2 level 내용 -->
<ul>
<li><a href="/notice/noticeList_R.do">공지사항</a></li>
<!-- 2 level 내용 -->
<li><a href="/news/newsList_R.do">뉴스</a></li>
<!-- 2 level 내용 -->
<li><a href="/webinar/webinarList_R.do">행사안내</a></li>
<!-- 2 level 내용 -->
<li><a href="/bestCase/bestCaseList_R.do">우수활용사례</a></li>
</ul>
</li>
<!-- 1 level 내용 -->
<li>
<a href="/faq/faqView_R.do">이용안내</a>
<!-- 2 level -->
<!-- 2 level 내용 -->
<ul>
<li><a href="/faq/faqView_R.do">FAQ</a></li>
<!-- 2 level 내용 -->
<li><a href="/promVide/promVideList_R.do">자료실</a></li>
<!-- 2 level 내용 -->
<li><a href="https://dataon.gitbook.io/dataon-user-guide/" target="_blank">사용자 가이드</a></li>
<!-- 2 level 내용 -->
<li><a href="/metaErr/metaErr.do">사이트 오류 신고</a></li>
</ul>
</li>
<!-- 1 level end -->
</ul>
</div>
</li>
<li><a href="#"><span>검색</span></a>
<div class="sub">
<ul>
<!-- 1 level start -->
<!-- 1 level 내용 -->
<li>
<a href="/search/index.do?mode=all">연구데이터 검색</a>
<!-- 2 level -->
<!-- 2 level 내용 -->
<ul>
<li><a href="/search/index.do?mode=all">통합 검색</a></li>
<!-- 2 level 내용 -->
<li><a href="/search/searchDetail.do">상세 검색</a></li>
</ul>
</li>
<!-- 1 level 내용 -->
<li>
<a href="/search/index.do?mode=inout">콘텐츠별 검색</a>
<!-- 2 level -->
<!-- 2 level 내용 -->
<ul>
<li><a href="/search/index.do?mode=inout">데이터셋 검색</a></li>
<!-- 2 level 내용 -->
<li><a href="/search/index.do?mode=soft">소프트웨어 검색</a></li>
<!-- 2 level 내용 -->
<li><a href="/search/index.do?mode=img">표/그림 검색</a></li>
</ul>
</li>
<!-- 1 level 내용 -->
<li>
<a href="/search/providerSearch.do">데이터 제공처 검색</a>
<!-- 2 level -->
<!-- 2 level 내용 -->
<ul>
<li><a href="/search/providerSearch.do">제공처 검색</a></li>
</ul>
</li>
<!-- 1 level end -->
</ul>
</div>
</li>
<li><a href="#"><span>등록</span></a>
<div class="sub">
<ul>
<!-- 1 level start -->
<!-- 1 level 내용 -->
<li>
<a href="/user/userLogin.do">연구데이터등록</a>
<!-- 2 level -->
<!-- 2 level 내용 -->
<ul>
<li><a href="/user/userLogin.do">등록</a></li>
<!-- 2 level 내용 -->
<li><a href="/user/userLogin.do">관리</a></li>
<!-- 2 level 내용 -->
<li><a href="/user/userLogin.do">통계</a></li>
</ul>
</li>
<!-- 1 level end -->
</ul>
</div>
</li>
<li><a href="#"><span>서비스</span></a>
<div class="sub">
<ul>
<!-- 1 level start -->
<!-- 1 level 내용 -->
<li>
<a href="/user/userLogin.do">분석서비스(CANVAS)</a>
<!-- 2 level -->
</li>
<!-- 1 level 내용 -->
<li>
<a href="/user/userLogin.do">리포지터리 호스팅</a>
<!-- 2 level -->
<!-- 2 level 내용 -->
<ul>
<li><a href="/user/userLogin.do">소개</a></li>
<!-- 2 level 내용 -->
<li><a href="/user/userLogin.do">신청</a></li>
<!-- 2 level 내용 -->
<li><a href="/user/userLogin.do">신청목록</a></li>
<!-- 2 level 내용 -->
<li><a href="/user/userLogin.do">내 리포지터리 관리</a></li>
</ul>
</li>
<!-- 1 level 내용 -->
<li>
<a href="/user/userLogin.do">공유서비스</a>
<!-- 2 level -->
<!-- 2 level 내용 -->
<ul>
<li><a href="/user/userLogin.do">오픈 API 목록</a></li>
<!-- 2 level 내용 -->
<li><a href="/user/userLogin.do">OAI-PMH 목록</a></li>
<!-- 2 level 내용 -->
<li><a href="/user/userLogin.do">신청목록</a></li>
</ul>
</li>
<!-- 1 level 내용 -->
<li>
<a href="/user/userLogin.do">데이터 현황</a>
<!-- 2 level -->
<!-- 2 level 내용 -->
<ul>
<li><a href="/user/userLogin.do">데이터 현황 통계</a></li>
<!-- 2 level 내용 -->
<li><a href="/user/userLogin.do">데이터 활용 통계</a></li>
</ul>
</li>
<!-- 1 level end -->
</ul>
</div>
</li>
<li><a href="#"><span>커뮤니티</span></a>
<div class="sub">
<ul>
<!-- 1 level start -->
<!-- 1 level 내용 -->
<li>
<a href="/user/userLogin.do">내 커뮤니티</a>
<!-- 2 level -->
<!-- 2 level 내용 -->
<ul>
<li><a href="/user/userLogin.do">내 커뮤니티 보기</a></li>
</ul>
</li>
<!-- 1 level 내용 -->
<li>
<a href="/user/userLogin.do">전체 커뮤니티</a>
<!-- 2 level -->
<!-- 2 level 내용 -->
<ul>
<li><a href="/user/userLogin.do">전체 커뮤니티 보기</a></li>
</ul>
</li>
<!-- 1 level end -->
</ul>
</div>
</li>
<li><a href="#"><span>이슈&amp;데이터</span></a>
<div class="sub">
<ul>
<!-- 1 level start -->
<!-- 1 level 내용 -->
<li>
<a href="/search/index.do?covidMode=Y">이슈로 보는 연구데이터</a>
<!-- 2 level -->
<!-- 2 level 내용 -->
<ul>
<li><a href="/search/index.do?covidMode=Y">코로나 바이러스</a></li>
<!-- 2 level 내용 -->
<li><a href="/search/index.do?gpccMode=Y">GPCC</a></li>
<!-- 2 level 내용 -->
<li><a href="/search/index.do?kaggleMode=Y">KAGGLE</a></li>
</ul>
</li>
<!-- 1 level end -->
</ul>
</div>
</li>
</ul>
<a class="all_close" href="#a"><span class="blind">전체메뉴 닫기</span></a>
</nav>
<div class="etc_menu">
<ul class="link">
<!--  알림 -> 사용자가이드 메뉴 변경 2022.04.11-->
<!-- 20221005 영문페이지 제외 -->
<li><a class="popup_onOff" href="https://dataon.gitbook.io/dataon-user-guide/" target="_blank">사용자가이드</a></li>
<!-- 로그인 전 -->
<!-- id(engBtn)중복으로 class로 변경 -->
<li><a class="engBtn" href="#" onclick="fn_enMsg(); return false;">ENG</a></li>
<li><a href="/user/userLogin.do">로그인</a></li>
</ul>
<a class="btn_total" href="#a">
<p class="blind">전체메뉴</p>
<i class="xi-bars"></i>
</a>
</div>
</div>
<div class="gnb_bg" style="overflow: hidden;">
<div class="gnb_etcMenu">
<div class="gnb_etcM_box">
<ul>
<li class="m1"><a href="https://dataon.gitbook.io/dataon-user-guide/" target="_blank"><i class="xi-comment-o"></i>사용자 가이드</a></li>
<li class="m2"><a href="/mydrive/mydriveMain.do"><i class="xi-cloud-o"></i>마이드라이브</a></li>
<li class="m3"><a href="https://dataon.kisti.re.kr/canvas" target="_blank"><i class="xi-list-dot"></i>분석 플랫폼</a></li>
</ul>
</div>
</div>
</div>
</header>
<!-- browser check info -->
<!-- header.jsp와 중복-->
<!-- 
        <div id="#unsupported" style="display: none;">
            현재 사용중이신 Internet Explorer는 지원되지 않는 버전입니다.<br /> <a href="http://www.google.com/chrome/" target="_blank">Google Chrome</a> 또는 Internet Explorer 10+ 버전의 웹 브라우저 사용을 권장 합니다.
        </div> 


        <div id="quick3">
            <div  class="circle">
                <a href ="http://dataon-con.kr/" target="_blank">
                    <img src="/resources/images/quick_contest_button.png" alt="">
                </a>
            </div>
        </div> 
          -->
<!-- QUICK MENU -->
<aside id="quick">
<h2 class="blind">퀵메뉴</h2>
<!--
             <div id="quick3">
                <div  class="circle">
                    <a href ="http://dataon-con.kr/" target="_blank">
                        <img src="/resources/images/quick_contest_button.png" alt="">
                    </a>
                </div>
            </div>   
        -->
<a class="quick_btn" href="#a">
<div>
<div>
<span>QUICK<br/>LINK</span>
</div>
</div>
<span class="blind">열기</span>
</a>
<div class="quick_menu">
<ul>
<li>
<a href="https://dataon.gitbook.io/dataon-user-guide/" target="_blank">
<img alt="" src="assets/icon_quick_1.png"/>
<span>사용자 가이드</span>
</a>
</li>
<li>
<a href="/mydrive/mydriveMain.do">
<img alt="" src="assets/icon_quick_2.png"/>
<span>마이드라이브</span>
</a>
</li>
<li>
<a href="/canvas" target="_blank">
<img alt="" src="assets/icon_quick_3.png"/>
<span>분석 플랫폼</span>
</a>
</li>
<li>
<a href="/cmmnty/selectCmmntyList.do">
<img alt="" src="assets/icon_quick_6.png"/>
<span>커뮤니티</span>
</a>
</li>
<li>
<a href="/faq/faqView_R.do">
<img alt="" src="assets/icon_quick_5.png"/>
<span>FAQ</span>
</a>
</li>
</ul>
</div>
</aside>
</div>
<!-- 서브 상단(visual, location) : s -->
<div id="sub_top">
<section class="visual">
<h2 id="sub_title"></h2>
</section>
<!-- menu navigation -->
<section class="location">
<div class="container">
<form id="headerFrmname" method="post" name="headerFrmname">
<input id="mm" name="mm" type="hidden" value=""/>
<input id="sm" name="sm" type="hidden" value=""/>
<input id="subFirstMenuId" name="subFirstMenuId" type="hidden" value=""/>
<div class="loc_row">
<ul class="location_list">
<li class="home">
<a href="/main.do">
<i class="xi-home"></i> <span class="blind">HOME</span>
</a>
</li>
<li class="dropdown">
<span id="mainMenuNm"></span>
</li>
<li class="dropdown">
<span id="subMenuNm"></span>
</li>
</ul>
<ul class="location_etc">
<li>
<a class="share" href="#" title="공유하기"><span class="blind">공유하기</span></a>
</li>
<li>
<a class="print" href="#" title="프린트하기"><span class="blind">데이터를 드라이브에서 언제,<br/>어디서나 저장 및 공유할 수 있어요!</span></a>
</li>
</ul>
</div>
</form>
</div>
</section>
<!-- 검색 : s -->
<aside id="total_search">
<!-- 아래 SEARCH 버튼에 on클래스이 들어가면 검색화면이 뜬 상태로 페이지가 로드 됩니다 -->
<a class="search_btn" href="#" id="total_search_btn"><span>SEARCH</span></a>
<div class="search_wrap">
<div class="container">
<form action="/search/index.do" id="searchFormMain" method="post" name="IntegratedSearchVO">
<input id="dummy" name="dummy" style="display:none;" type="text">
<fieldset>
<legend>통합 검색</legend>
<ul class="totSch_tab">
<li>
<div class="totSch_item">
<input checked="" id="searchAll" name="searchType" type="radio"/>
<label for="searchAll">통합 검색</label>
</div>
</li>
<li>
<div class="totSch_item">
<label for="searchDetail" onclick="javascript:fn_searchMainDetail();">상세 검색</label>
</div>
</li>
<li>
<div class="totSch_item">
<label for="searchMap" onclick="javascript:fn_searchMainMap();">MAP 검색</label>
</div>
</li>
</ul>
<div class="totSch_input">
<label class="blind" for="search_input">통합 검색</label>
<input id="search_input" name="search_input" placeholder="찾고 싶은 데이터를 입력해 주세요." title="검색어를 입력하세요." type="text"/>
<button class="totSch_btn" onclick="javascript:fn_searchMain();" type="button"><span class="blind">검색하기</span></button>
</div>
<div class="search_tooltip_div">
<button class="search_tooltip_button" onclick="fn_searchTooltip()" type="button"><i class="xi-help"></i>검색 도움말</button>
<div class="search_tooltip" id="search_tooltip">
<div class="search_tooltip_header">
<div class="rdppopuptit">
                            검색 도움말
                        </div>
</div>
<table cellpadding="0" cellspacing="0" class="search_tooltip_table" style="">
<col width="30%"/>
<col width="40%"/>
<col width="30%"/>
<tr style="">
<th>검색 연산자</th>
<th>기능</th>
<th>검색시 예</th>
</tr>
<tr>
<td>공백</td>
<td>두 개의 검색어(식)을 모두 포함하고 있는 문서 검색</td>
<td>(데이터 기술)</td>
</tr>
<tr>
<td>()</td>
<td>우선순위가 가장 높은 연산자</td>
<td>(정확 (데이터|data))</td>
</tr>
<tr>
<td>|</td>
<td>두 개의 검색어(식) 중 하나 이상 포함하고 있는문서 검색</td>
<td>(항공 | 토양)</td>
</tr>
<tr>
<td>!</td>
<td>NOT 이후에 있는 검색어가 포함된 문서는 제외</td>
<td>(데이터 !연구)</td>
</tr>
<tr>
<td>*</td>
<td>검색어의 *란에 0개 이상의 임의의 문자가 포함된 문서 검색</td>
<td>data*</td>
</tr>
<tr>
<td>" "</td>
<td>따옴표 내의 구문과 완전히 일치하는 문서만 검색</td>
<td>"Transform"</td>
</tr>
</table>
</div>
</div>
</fieldset>
</input></form>
<div aria-hidden="true" aria-labelledby="mapSearchModalLabel" class="modal fade" id="mapSearchModal" role="dialog" tabindex="-1"></div>
</div>
</div>
</aside>
<!-- 검색 : e -->
</div>
</div>

<!-- 메인시작 { -->
<main id="main">
<div class="container">
<!-- 메인 컨텐츠 시작 { -->
<div id="content">
<div class="totSch">
<div class="result_detail">


<div class="rstDetail_top clear">
<div class="left">
<a class="btn_def blue" href="#errorModal" rel="modal:open">오류신고</a>
<div class="help_more">
<i class="xi-error"></i>
<span>해당 데이터에 오류가 발견되면 오류신고해주세요.</span>
</div>
<!-- 과제정보 모달 : s -->
<div class="layer_def" id="errorModal">
<div class="layer_content">
<strong class="title">오류신고</strong>
<div class="rpt_Info">
<dl class="rpt_row">
<dt>데이터 정보</dt>
<dd>
<table class="tbl type2">
<caption>오류신고를 진행 하실 데이터 정보를 담은 표입니다.</caption>
<colgroup>
<col style="width:23%"/>
<col/>
</colgroup>
<tbody>
<tr>
<th scope="row">제목(Main)</th>
<td class="text-left">ScienceON 로그 데이터(2022년도)</td>
</tr>
<tr>
<th scope="row">제목(Sub)</th>
<td class="text-left"></td>
</tr>
<tr>
<th scope="row">저자</th>
<td class="text-left">
<!-- 생성자 (한글+영어) -->
<span class="rstD_name">

                                                신수미;


                                        </span>
</td>
</tr>
<tr>
<th scope="row">제공처</th>
<td class="text-left">

                                            국가연구데이터플랫폼 

                                   </td>
</tr>
<tr>
<th scope="row">리포지터리</th>
<td class="text-left">

                                           국가연구데이터플랫폼 

                                   </td>
</tr>
</tbody>
</table>
</dd>
</dl>
<dl class="rpt_row">
<dt>접수 정보</dt>
<dd>
<table class="tbl type2">
<caption>오류신고 접수 정보를 담은 표이며, 메일주소, 오류내용을 입력합니다.</caption>
<colgroup>
<col style="width:23%"/>
<col/>
</colgroup>
<tbody>
<tr>
<th scope="row">아이디</th>
<td class="text-left"></td>
</tr>
<tr>
<th scope="row"><label for="emailAddr">메일주소</label></th>
<td class="text-left">
<input class="w100p" id="emailAddr" name="emailAddr" readonly="readonly" type="text" value=""/>
<div class="info_box type2">
<i class="xi-error"></i>
<span>오류신고 접수 정보를 담은 표이며, 메일주소, 오류내용을 입력합니다.</span>
</div>
</td>
</tr>
<tr>
<th scope="row">오류 구분</th>
<td class="text-left">
<select class="custom-select" id="errRptTypeCd" name="errRptTypeCd">
<option selected="" value="">오류신고분류 </option>
<option value="01">오타</option>
<option value="02">데이터 오류</option>
</select>
</td>
</tr>
<tr>
<th scope="row"><label for="error">오류내용</label></th>
<td class="text-left">
<ul class="bul_list">
<li>개인정보 노출방지를 위해 개인정보 내용은 가급적 자제하여 주시기 바랍니다.</li>
<li>일방적인 욕설 및 부정적인 내용 작성시 원작자의 판단에 따라 신고자에게 피해가 발생할 수 있습니다. 깨끗하고 청렴한 서비스 문화를 위해 필요한 정보만 기재해주시면 감사하겠습니다.</li>
</ul>
                                        
                                       <textarea class="w100p" id="errRptDesc" name="errRptDesc" onkeyup="engKorChkWord(this, 3000)" rows="4"></textarea>
</td>
</tr>
</tbody>
</table>
<a class="btn_def blue modal_btn" href="javascript:void(0);" onclick="fn_MataDataAdd();" rel="">접수하기</a>
</dd>
</dl>
</div>
</div>
</div>
</div>
<div class="right icon_wrap">
<a class="btn_social like" href="javascript:void(0);" id="like" onclick="fn_good();">추천합니다</a>
<a class="btn_social bmark" href="javascript:void(0);" id="bmark" onclick="fn_myDataBtn();">관심데이터</a>
</div>
</div>
<!-- 관심데이터 , 마이데이터  -->
<form id="fr_myData" method="post" name="fr_myData">
<input id="file_id" name="file_id" type="hidden" value="">
<input id="svc_id" name="svc_id" type="hidden" value="">
<input id="source" name="source" type="hidden" value="">
<input id="dataMode" name="dataMode" type="hidden" value="">
<input id="file_gubun" name="file_gubun" type="hidden" value="">
</input></input></input></input></input></form>
<!-- 모달 커뮤니티 공유 -->
<div aria-hidden="true" aria-labelledby="myModalLabel" class="layer_def" id="shareModal" role="dialog" tabindex="-1"></div>
<!--  사용자 공유 -->
<div aria-hidden="true" aria-labelledby="myModalLabel" class="modal fade" id="commModal" role="dialog" tabindex="-1">
</div>
<!-- 상세정보 조회 시작 :: 데이터셋, 소프트웨어, 표/그림 { -->
<div class="rstDetail_box">
<div class="rstDetail_left">
<div class="rstDetail_row">
<!-- 제목 상단 정보 조회 시작 { -->
<ul class="rst_category">
<!-- 등록년도 (=발행년도) :: regist_dttm -->
<i class="country t1">2023</i>
<!-- 국내/외 구분 :: dmabr_slct -->
<i class="country t1">국내</i>
<!-- 접근유형(공개/비공개/엠바고) :: access_type -->
<i class="country t1">공개</i>
<!-- 데이터셋 포함 파일 확장자 :: file_frmt -->
<i class="country t1">zip</i>
<!-- 저작권(라이센스) 유형 :: copyright -->
<i class="country t1">CC-BY-NC</i>
<!-- 작성언어 :: lang_cd (첫번째값-주언어) -->
<i class="country t1">Korean</i>
</ul> <!-- } 제목 상단 정보 조회 종료 -->
<!-- 데이터셋 상세정보 조회 시작 { -->
<!-- 01-1. 데이터셋 제목-주언어 해당 -->
<h3 class="rstD_title">
<!--  선택한 주언어 우선으로 노출되도록 수정 운영_ 20220616 -->


                                    ScienceON 로그 데이터(2022년도)


                                </h3>
<!-- 01-2. 데이터셋 제목-부언어 해당 -->
<!-- 부언어에 해당하는 제목이 주언어 해당 제목의 폰트크기보다 커서 내용의 폰트크기와 통일 _ 비네아 서민진 (22.03.16) -->
<em class="sub_title" style="font-size:16px;">
</em>
<!-- 2021.07.09 :: 생성자(소속기관)으로 표기 -->
<span class="rstD_name">
<!-- 02-1. 데이터셋 생성자-주언어 혹은 부언어 해당 (언어가 없는경우  ko를 default로 하여 조회) -->

                                        신수미(한국과학기술정보연구원);

                                    <span class="rstD_name">
</span>
</span>
<!-- 03-1. 데이터셋 설명-주언어 해당 (주언어가 없는경우 부언어와 매칭하여 조회) -->
<div class="rstD_content">



                                    ScienceON(https://scienceon.kisti.re.kr) 의 사용자 행동 예측 문제 해결을 위한 2022년도 ScienceON 시스템 로그 데이터입니다. 
<br> <br>데이터의 각 필드는 
<br/>사용자IP,서비스 종류,콘텐츠 종류,웹/모바일 구분,로그등록시간,이전URL,요청URL,검색질의어,조회 컨텐츠 와 같습니다. 
<br/> <br/>UTF8로 인코딩되어 있습니다. 
<br/> <br/>해당 데이터는 2023년 DATA‧AI 경진대회 과학기술문제형의 4번 문제 ScienceON 사용자 행동 예측 문제 해결을 위해 제공되는 데이터 입니다. 
<br/> <br/>로그데이터는 2022년 1월~12월까지의 로그데이터입니다. 
<br/>파일명규칙은 (연도월_1: 1일~15일치 데이터, 연도월_2: 16일~말일 데이터), (예제: 2201_1.csv 는 22년도 1월 1일~15일까지 로그입니다.)와 같습니다. 
<br/>
</br></br></div>
<div class="rstD_content">
</div>
<ul class="rst_keyword">
<!-- 04-1. 데이터셋 키워드-주언어 해당 -->
<!-- 04-2. 데이터셋 키워드-부언어 해당 -->
<li><a href="javascript:void(0);">#ScienceON</a></li>
<li><a href="javascript:void(0);">#사용자 해동 예측</a></li>
<li><a href="javascript:void(0);">#로그</a></li>
<li><a href="javascript:void(0);">#웹 서비스</a></li>
<li><a href="javascript:void(0);">#사용자 해동 예측</a></li>
</ul>
</div>
<div class="rstDetail_row">
<h4 class="rstD_title">데이터 생성 이력정보</h4>
<ul class="bul_list embargo_list">
<!-- 05-1. 데이터셋 생성일시 :: creat_dttm -->
<li>
<!--  표준과학연구원 정의 :  kriss -->





                                            데이터등록일

                                        : 2023-08-11
                                    </li>
<!-- 05-2. 데이터셋 엠바고기간 :: embg_start_dttm / embg_end_dttm -->
</ul>
</div>
<div class="rstDetail_row">
<h4 class="rstD_title">특성 정보</h4>
<ul class="bul_list" id="charInformation">
<li>주제분류 = 인터넷 S/W </li>

</ul>
<div class="infoAlign">
<div class="info_box type5 info_2line">
<i class="xi-error"></i>
<span>특성정보는 제공처로부터 수집된 데이터이며, DataON에서 제공하는 이외의 정보를 담고 있습니다.</span>
</div>
</div>
</div>
<!-- 데이터셋에 따른 생성자, 기여자, 과제, 논문과의 연관정보를 그래프로 나타냄 -->
<div class="rstDetail_row">
<h4 class="rstD_title">데이터셋 의미 관계 정보</h4>
<div class="data_area" style="height: 650px;">
<a class="btn_line gray reset_btn" href="javascript:void(0);" onclick="fn_dataSet();">Reset</a>
<div class="data_neo" id="neo4jd3" style="width:100%;height:100%;">
</div>
</div>
<div class="infoAlign">
<div class="info_box type5 info_2line">
<i class="xi-error"></i>
<span>의미관계가 형성된 정보를 클릭하면 통합검색 결과로 이동합니다.</span>
</div>
<div class="info_box type5 info_2line">
<i class="xi-error"></i>
<span>본 서비스는 크로미움(Chromium)기반의 브라우저에서만 제공됩니다.</span>
</div>
</div>
</div>
<div class="rstDetail_row">
<h4 class="rstD_title">관련 과제/논문 정보</h4>
<div class="report_info">
<div class="top">
<div class="info_box type5">
<i class="xi-error"></i>
<span>관련 과제/논문 정보는 데이터 등록자 또는 이용자가 추천한 정보가 제공됩니다.</span>
</div>
</div>
<div class="bottom">
<ul>
<li><span class="stat type1">유발</span>연구데이터가 유발된 과제/논문 정보입니다.</li>
<li><span class="stat type2">관련</span>연구데이터 생산에 참고된 관련 과제/논문 정보입니다.</li>
</ul>
</div>
</div>
<div class="data_tab">
<ul class="data_tabMenu type2 clear tab_begin">
<!-- 09-1. 과제상세정보 호출 :: ps_service_pjt (ps_service_ctlg와 ctlg_sn매칭하여 과제상세정보 조회) -->
<li>
<a class="on" href="javascript:void(0);" title="활성 메뉴">과제</a>
<div class="data_tabSub" id="pjt_view"></div>
</li>
<!-- 09-2. 논문상세정보 호출 :: ps_service_pblctns (ps_service_ctlg와 ctlg_sn매칭하여 과제상세정보 조회) -->
<li>
<a href="javascript:void(0);">논문</a>
<div class="data_tabSub" id="pblctns_view"></div>
</li>
</ul>
<div class="help_more">
<i class="xi-error"></i>
<span>과제명, 논문명을 클릭하면 해당 과제와 논문의 상세정보를 확인할 수 있습니다.</span>
</div>
</div>
</div>
<!-- 10-1. 파일형태가 'path(=다운로드형태)'인 경우  -->
<!-- CASE1. 파일접근유형이 엠바고(03)이면서 엠바고종료일시가 지나지 않은경우 -->
<!-- 문자열로 비교하는 경우 추후 변경되었을 때 오류가 날 수 있으므로 코드 값으로 구분할 수 있도록 수정 : 비네아 서민진 (22.02.09) -->
<!-- CASE2. 파일접근유형이 공개(01)인 경우 -->
<!-- 문자열로 비교하는 경우 추후 변경되었을 때 오류가 날 수 있으므로 코드 값으로 구분할 수 있도록 수정 : 비네아 서민진 (22.02.09) -->
<div class="rstDetail_row">
<h4 class="rstD_title">파일정보</h4>
<div class="review_wrap">
<div class="preview-panel">
<div class="preview-file-list">
<div class="preview-file-header p-0">
<ul class="menu">
<li>
<a class="on" href="#reView">파일목록</a>
</li>
<!-- 바로분석 -->
<li>
<a href="javascript:void(0);" onclick="fn_freeIPACall();">바로분석</a>
</li>
<!-- MyDrive 저장 -->
<li>
<a href="javascript:void(0);" onclick="myRstChkBtn();">MyDrive저장</a>
</li>
<!-- 파일다운로드 -->
<li>
<a href="javascript:void(0);" onclick="goDownload();">다운로드</a>
</li>
</ul>
</div>
<!-- 트리구조의 파일목록 조회 -->
<div class="file-tree overflow-auto" id="previewTree"></div>
</div>
<div class="preview-file-review rst_content look">
<div class="preview-file-header justify" data-role="fileDetail">
<div class="item title" data-match="file_name" id="item">
<ul>
<!-- 미리보기 -->
<li>
<a class="look on" href="javascript:void(0);">미리보기</a>
</li>
<!-- 메타정보보기 -->
<li>
<a class="meta" href="javascript:void(0);">메타정보보기</a>
</li>
</ul>
</div>
<ul class="menu-etc item d-md-block d-none">
<li data-match="file_volume"></li>
<li data-match="file_date"></li>
</ul>
<!-- 메타정보보기 상세조회 -->
<div class="preview-panel-content mb-0">
<div class="preview-panel-body">
<div class="look-body" id="previewContent"></div>
<div class="meta-body input_wrap">
<div class="item">
<!-- 파일명 :: title -->
<dl>
<dt>파일명
                                                                                    </dt>
<dd><div id="fileName"></div></dd>
</dl>
<!-- 파일사이즈 :: file_sz -->
<dl>
<dt>사이즈</dt>
<dd><div id="fileSize"></div></dd>
</dl>
<!-- 파일포맷(확장자) :: file_frmt -->
<dl>
<dt>포맷</dt>
<dd><div id="fileFormat"></div></dd>
</dl>
<!-- 파일키워드 :: kywd -->
<dl>
<dt>키워드</dt>
<dd><div id="fileKeyWord"></div></dd>
</dl>
<!-- 파일설명 :: expl -->
<dl>
<dt class="vea_top">설명</dt>
<dd><div id="fileExp"></div></dd>
</dl>
</div>
</div>
</div>
</div>
<div class="d-none" id="previewMessage">

<!-- page wrap -->
<div class="error_wrap">
<div class="error_container">
<i class="xi-file-image-o"></i>
<strong>



                    미리보기 파일 변환에 실패 하였습니다.<br/>파일 다운로드하여 이용부탁드립니다.


        </strong>
</div>
</div>


</div>
</div>
</div>
</div>
</div>
<div class="infoAlign">
<div class="info_box type5 info_2line">
<i class="xi-error"></i>
<span>본 서비스는 크로미움(Chromium)기반의 브라우저에서만 제공됩니다.</span>
</div>
</div>
</div>
<!-- 10-2. 파일형태가 'lndg(=상세보기형태)'인 경우  -->
<!-- } 데이터셋 상세정보 조회 종료 -->
</div>
<!-- Go to www.addthis.com/dashboard to customize your tools -->
<!-- <script type="text/javascript" src="//s7.addthis.com/js/300/addthis_widget.js#pubid=ra-5fa24345aa366f1a"></script> -->


<div class="rstDetail_right">
<ul class="rst_count">
<li>
<strong id="view_cnt">530</strong>
<i class="xi-eye"></i><span>조회수</span>
</li>
<li>
<strong id="download_cnt">64</strong>
<i class="xi-download"></i><span>다운로드수</span>
</li>
<li>
<span>추천수</span>
<strong id="good_cnt">0</strong>
</li>
<li>
<span>공유수</span>
<strong id="shares_cnt">3</strong>
</li>
<li>
<span>인용횟수</span>
<strong id="citation_cnt">0</strong>
</li>
</ul>
<dl class="rstD_info">
<dt>제공처</dt>
<dd>
<div class="repository_img">
<a href="javascript:void(0);">
<img alt="" onerror="this.src='/resources/images/rep_none.gif'" src="assets/imagePreview.do"/>
</a>
</div>
</dd>
</dl>
<dl class="rstD_info">
<dt>리포지터리</dt>
<dd>

                국가연구데이터플랫폼<br/>
</dd>
</dl>
<dl class="rstD_info rstD_info_url">
<dt>DOI<i class="xi-external-link"></i></dt>
<dd>
<a class="rstD_name" href=".1" target="blank"></a>
<a class="rstD_name" href="https://doi.org/10.22711/idr/985" target="blank">10.22711/idr/985</a>
</dd>
</dl>
<dl class="rstD_info">
<dt>인용정보생성<div class="help_more"><i class="xi-help" title="논문쓸 때 유용한 인용정보를 인용스타일에 따라 자동 생성합니다."></i></div></dt>
<dd>
<form id="frm_quotation" method="get" name="frm_quotation">
<!-- <input type="hidden" name="author"             value="신수미"/> -->
<input name="author" type="hidden" value="신수미"/>
<input name="publisher" type="hidden" value=""/>
<!--  생성일로 변경_ 2023.04.28 -->
<input name="issued" type="hidden" value="2023"/>
<input name="title" type="hidden" value="ScienceON 로그 데이터(2022년도)"/>
<input name="doi" type="hidden" value="10.22711/idr/985"/>
<select id="quotation" name="quotation" onchange="fn_quotation();" title="대상 서비스를 선택하세요.">
<option value="00">인용 스타일을 선택하세요.</option>
<option value="BibTex">BibTex</option>
<option value="IEEE">IEEE</option>
<option value="APA">APA</option>
<option value="Harvard">Harvard</option>
<option value="MLA">MLA</option>
<option value="Vancouver">Vancouver</option>
<option value="Chicago">Chicago</option>
<option value="ACM">ACM</option>
<option value="Science">Science</option>
<option value="Nature">Nature</option>
<option value="Cell">Cell</option>
</select>
</form>
<pre id="p_quotation">
            </pre>
             
            <!-- 과제정보 모달 : s -->
<div class="layer_def right_modal" id="modal_quotation">
<dl class="rpt_row right_modal">
<dd>
<pre id="m_quotation">
                                        </pre>
</dd>
</dl>
</div>
<a class="btn_social copy_icon" href="#modal_quotation" rel="modal:open">
                            자세히 보기</a>
<a class="btn_social copy_icon copy_btn" href="javascript:void(0);" onclick="fn_copyQuotation();">복사</a>
</dd>
</dl>
<dl class="rstD_info">
<dt>라이센스</dt>
<dd>
            CC-BY-NC
        </dd>
</dl>
<dl class="rstD_info">
<dt>공유하기</dt>
<dd class="sns_dd">
<div class="share_wrap">
<ul class="sns">
<li>
<!--  <div id="snsCheck" class="addthis_inline_share_toolbox_ftd3"></div>  -->
<!-- 2022.04.14 카카오톡 추가_운영  -->
<div class="addthis_inline_share_toolbox_nvc5_qecw_eg9l" id="snsCheck"></div>
</li>
</ul>
<div class="right icon_wrap">
<a class="btn_social share share_btn" href="javascript:void(0);" id="share" onclick="fn_btnShare();">커뮤니티공유</a>
<a class="btn_social Ushare share share_btn" href="javascript:void(0);" id="Ushare" onclick="fn_shrDataset();">사용자공유</a>
</div>
</div>
</dd>
</dl>
</div>
</div> <!-- } 상세정보 조회 종료 :: 데이터셋, 소프트웨어, 표/그림 -->
</div>
</div>
</div> <!-- } 메인 컨텐츠 종료 -->
</div>
</main> <!-- } 메인 종료 -->

<form id="fr_mainSearchForm" method="get" name="fr_mainSearchForm">
<input id="mode" name="mode" type="hidden"/>
<input id="search_input" name="search_input" type="hidden"/>
</form>
<footer id="footer">
<div class="footer_wrap">
<div class="footer_logo">
<img alt="데이터온" src="assets/footer_logo.png"/>
</div>
<div class="footer_content">
<ul class="fnb">
<li><a href="/layout/termsOfUse.do">이용약관</a></li>
<li><a href="/layout/privacyPolicy.do">개인정보처리방침</a></li>
<li><a href="https://www.kisti.re.kr/intro/introduce/pageView/14" target="_blank" title="새창">기관소개</a></li>
</ul>
<address>(우)34141 대전광역시 유성구 대학로 245<span>  한국과학기술정보연구원.</span></address>
<p class="copyright">문의메일 : dataon@kisti.re.kr</p>
</div>
</div>
</footer>
</body>
<p></html></p>