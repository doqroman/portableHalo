# ポータブル後光
![メイン画像](https://raw.githubusercontent.com/doqroman/portableHalo/master/images/thumbnail.jpg)
---
---
### 必要なもの
- レーザーカッター
- 3Dプリンター(フィラメント)
- [アクリル板(白)2mm厚](https://www.hazaiya.co.jp/category/akuriru_3.html)
- [テープLED](http://amzn.asia/d/enwciwZ) なんか安い気がするからこれとか
- [arduinoProMicro(互換機)](http://amzn.asia/d/07rGVtV) 安いからこれとか
- [microUSBケーブル](http://amzn.asia/d/9vwHQET)
- [タクトスイッチ](http://akizukidenshi.com/catalog/g/gP-02561/)
- [電子ワイヤー](http://akizukidenshi.com/catalog/g/gP-06756/)
- [ジャンパワイヤー](http://amzn.asia/d/7V4xsde)
- [ブレッドボード](http://amzn.asia/d/8CKCoHu)
- [乾電池ケース](http://akizukidenshi.com/catalog/g/gP-10207/)
- [アクリサンデー接着剤](http://amzn.asia/d/3OnWLN0)
- [単三乾電池](http://amzn.asia/d/f5cYfEI)
- [ビニールテープ](http://amzn.asia/d/7CiNfFG)
- [マスキングテープ](http://amzn.asia/d/6qS5qGf)
- [ニッパーとか](http://amzn.asia/d/1DCqvtW)
- [やすり](http://amzn.asia/d/glVdTya)
- [はんだごて](http://amzn.asia/d/8xQIUw6)([はんだ](http://amzn.asia/d/8z42gBc))
---
### つくりかた
1. gripデータ(stl)を出力する  
![画像_1]()  
2. カットデータでアクリルを切る(cut_2は2つ必要)  
![画像_2]()  
3. cut_1とcut_2(ひとつ)をマスキングテープで仮止めする  
![画像_3]()  
4. 仮止めしたものをアクリサンデー接着剤でくっつける(超慎重に)  
![画像_4]()			
5. テープLEDを8個1セットで8本切り出す  
![画像_5]()  
6. 切り出してくっつけたアクリルにテープLEDを貼る  
![画像_6]()  
7. テープLEDにワイヤーをはんだづけする(それぞれのGND,Din,5Vを共通でつなぐ)  
![画像_7]()  
8. 共通でつないだGND,Din,5Vにジャンパワイヤーをはんだづけする  
![画像_8]()  
9. cut_2のもうひとつでふたをするようにマスキングテープで仮止めする(3本のワイヤーは穴から出しておく)  
![画像_9]()  
10. タクトスイッチにジャンパワイヤーをはんだづけする  
![画像_10]()  
11. arduino(互換機)をブレッドボードに挿してプログラムを書き込む	(この互換機だとボード選択はLeonardo)  
![画像_11]()
```
//あああ
```
12. arduinoに電池、LED、タクトスイッチをつなげてテスト(タクトスイッチを押して光り方が変わる)  
![画像_12]()  
13. 問題なければLED、タクトスイッチをブレッドボードからはずす  
![画像_13]()  
14. 仮止めしていたアクリルをアクリサンデー接着剤でくっつける(超慎重に)  
![画像_14]()  
15. 出力されたgripデータ(_base)にアクリルを差し込む(ワイヤーはグリップの中に入れる)  
![画像_15]()  
16. タクトスイッチをグリップの穴に固定する(ワイヤーはグリップの中に入れる)  
![画像_16]()  
17. arduinoと電池、LED、タクトスイッチをつなげてビニールテープで固定  
![画像_17]()  
18. 全部グリップの中に入れてふたをして完成  
![画像_18]()  

Updating...