# TOEIC 狀態一覽
狀態說明:: 錯題：待複習 → 已複習｜傾向・補強：改進中 → 已克服。改狀態＝改該區塊的 status 屬性。
	- ## 今日閃卡
		- {{cards [[card]]}}
			- Summary: 9 items, 9 review counts [[Sep 11th, 2026]]
				- Remembered:   8 (88%)
				- Forgotten :   1 (11%)s
	- ## 待辦（行動計畫）
		- {{query (task NOW LATER TODO DOING)}}
	- ## 錯誤傾向
	  collapsed:: true
		- ### 改進中
		  {{query (and (property type "錯誤傾向") (property status "改進中"))}}
		- ### 已克服
		  collapsed:: true
		  {{query (and (property type "錯誤傾向") (property status "已克服"))}}
		- 完整內容 → [[錯誤傾向]]
	- ## 分項補強
	  collapsed:: true
		- ### 改進中
		  {{query (and (property type "補強重點") (property status "改進中"))}}
		- ### 已克服
		  collapsed:: true
		  {{query (and (property type "補強重點") (property status "已克服"))}}
		- 完整內容 → [[TOEIC 補強計畫]]
	- ## 錯題
	  collapsed:: true
		- ### 待複習
		  {{query (and (property type "錯題") (property status "待複習"))}}
		- ### 已複習
		  collapsed:: true
		  {{query (and (property type "錯題") (property status "已複習"))}}
		- ### 全部錯題
		  collapsed:: true
		  {{query (property type "錯題")}}