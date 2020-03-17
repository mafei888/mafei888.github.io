<html>
	<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN">
	<head>	   		
		<title>vip视频解析器-无广告-在线高清</title>
		<meta http-equiv="pragma" content="no-cache">
		<meta http-equiv="cache-control" content="no-cache">
		<meta http-equiv="expires" content="0">    
		<meta http-equiv="keywords" content="keyword1,keyword2,keyword3">
		<meta http-equiv="description" content="This is my page">
		<script type="text/javascript" 
		src="https://dss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/js/lib/jquery-1-cc52697ab1.10.2.js"></script>
	</head>
	
	<style>
	
		li{
			line-height:45px;
			list-style: none;
		}
		[ifr]{
			position: fixed;
			//left:30%;
		}
		li{
			width:105px;
			float: left;
			
		}
		button{
			padding:5 13 5 13;	
border-radius: 5px; 	
cursor: pointer;
    background: #eee;
    -webkit-border-radius: 5px;
    border: 1px solid #d1d1d1;
    margin: auto auto;		
		}
		[sp1]{
			color:red;
			font-size:28px;
		}
	</style>
	
	<body bac>
		<!-- <a href="#"  dd=66>保存文件 </a> -->
		<div  title='请输入网页链接或m3u8链接,如爱奇艺、优酷等页面地址栏地址。看哪一集就复制哪一集的页面地址哦，鼠标离开输入框自动解析，无视vip限制！' style="
    text-align:  center;
    height: 150px;padding:3px;
"><h2>请输入网页链接或m3u8链接（<a href='javascript:shili()' target='_blank' title='示例说明'>示 例</a>）</h2><input title1='请输入网页链接或m3u8链接,如爱奇艺、优酷等页面地址栏地址，看哪一集就复制哪一集，鼠标离开输入框自动解析，无视vip限制！' ipt value='https://www.iqiyi.com/v_19rxfnb3w4.html?vfrm=pcw_home&vfrmblk=B&vfrmrst=fcs_0_p11' style="
    /* text-align:  center; */
    height: 40;
    width: 600;
    margin: 15;
"><span sp1>请提供正确网址格式！</span><span hidden sp2></span></div>

		<iframe title='5' ifr src="" frameborder="0" width='99%' allowfullscreen height="70%"></iframe>
		<br/>
		
		<!-- <div width="200px">		 -->
		
			<!-- <ul width="" style='width:25%'> -->
				<!-- <li src li1> -->
					
				<!-- </li> -->
						
			<!-- </ul>	 -->
		<!-- </div> -->
		
		<br/>	

	</body>
	<script>
	
	var str = '\u0068\u0074\u0074\u0070\u0073\u003a\u002f\u002f\u006a\u0078\u002e\u0031\u0066\u0066\u0031\u002e\u0063\u006e\u002f\u003f\u0075\u0072\u006c\u003d';	
	var base = $("title").text();		
		$(function(){
			$("[sp1]").hide()
			$("[ifr]").attr('src',str+'https://www.iqiyi.com/v_19rxfnb3w4.html?vfrm=pcw_home&vfrmblk=B&vfrmrst=fcs_0_p11')
			$("[ipt]").focus();
			$("[sp2]").text($("[ipt]").val().trim());			
			$("[ipt]").change(function(){	
				var ipt = $("[ipt]").val().trim();
				if ($("[sp2]").text() == ipt) return;
				$("[sp2]").text(ipt);
				
				$("[ipt]").val(ipt);
				ipt = !ipt?'':(str+ipt);				
				if(($("[ipt]").val().trim()).indexOf('.') > 0){
					$("[ifr]").attr('src',ipt);						
					$("[sp1]").hide()
				}else{					
					//$("[ifr]").attr('src',str+'https://www.iqiyi.com/v_19rxfnb3w4.html?vfrm=pcw_home&vfrmblk=B&vfrmrst=fcs_0_p11')
					$("[sp1]").show().focus();
				}		
			})
		})	
	
		// 示例
		function shili(){
			//location = 'file:///F:/Program%20Files/yp.%E9%9F%B3%E9%A2%91/%E9%A2%91/tj.yy.%E4%B8%8D%E6%80%A8%20(1).mp4';
			//return;			
			var doc = open("file:///F:/Program%20Files/yp.%E9%9F%B3%E9%A2%91/%E9%A2%91/tj.yy.%E4%B8%8D%E6%80%A8%20(1).mp4",'shili')			
			//doc.document.write('<p>hello document</p>');
			/*doc.document.writeln("<p style='color:red'>这是'我的窗口'</p>");
			setTimeout(function(){
				doc.close();
			},2000);
			//location="F:\\test\\a.txt";*/
		}
		
	</script>
	
</html>





