orphan branch
#Ê×ÏÈ¿ËÂ¡²Ö¿â
$git clone https://github.com/tsingyy/git-rep.git
#½øÈëÄ¿Â¼£¬È»ºóĞÂ½¨·ÖÖ§
$cd git-rep
$git checkout --orphan newbranch
#É¾³ı¾ÉÄ¿Â¼Ê÷ÖÖËùÓĞÎÄ¼ş£¬È»ºóĞÂ½¨README.md£¬È»ºó´æÖÁ»º´æÇø£¬Ìá½»µ½±¾µØ²Ö¿â£¬È»ºóÍÆËÍµ½Ô¶³Ì²Ö¿â
$git rm -rf .
$echo "orphan branch" > README.md
$git add .
$git commit -m "add file README,md"
$git push origin newbranch
#ÕâÑù¾ÍÍê³ÉÁËÔÚÏÖÓĞ²Ö¿âÉÏ´´½¨¹Â¶ù·ÖÖ§£¬¹Â¶ù·ÖÖ§µÄÒâË¼¾ÍÊÇ¸Ã·ÖÖ§ÖĞÃ»ÓĞÈÎºÎÄÚÈİ£
#¸úÖ®Ç°´´½¨µÄÆäËû·ÖÖ§Ã»ÓĞÈÎºÎ¹ØÁª
