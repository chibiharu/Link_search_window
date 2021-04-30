# Link_search_window
ページ内アンカーを対象としたシンプルな検索窓です  
<仕様>  
検索対象はページ内のアンカー全て  
インクリメンタルサーチ機能
 
# Requirement
HTML5/CSS3  
javaScript  
jQuery v3.1.0  
 
# Note
以下コードがIEだと機能しないためIEだとアンカーの動収集ができない  
 var fruits = $("a").map(function(i,e){return {href: e.href, text: e.text})
 
# Author
* 作成者 → chibiharu    
* mail → chibiharujijimasa@gmail.com
 
