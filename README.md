
#for upload for v4.1.12 (a0daa900e105c97da8206de33d8bb519ab48e5fa)  

修改说明：  
1.原版v4.1.12修复了v4.1.11中由于带空格的字体名而导致的问题  
2.由于带双引号编码“&quot;”的html代码直接输出到html页面时还是会被浏览器解析而导致问题，故此  
对style属性替换双引号编码“&quot;”为单引号编码“&apos;”  

