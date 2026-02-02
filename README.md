# スタンプラリー

# 概要

## アイテム
- 紙を利用  
- DP or Loreで判別  
 
## スタンプ用紙
- attachableを利用(3Dアイテム)  
- 用紙サイズ: w64, h32  
- スタンプサイズ: w16, h16  
- スタンプサイズは用紙サイズに合わせて縮小・拡大して合わせる  

## スタンプ
- スタンプを押したかどうかは プレイヤー(json)のpropertyで管理  
- 'property:stamp_{number}' : int  
- function stamprally/push/number で押す  
- function stamprally/remove/number で削除  
- function stamprally/give で用紙配布
