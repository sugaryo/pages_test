# GitHub Pages rendering test.

## sub pages.

- [hoge](pages/hoge.md)
- [moge](pages/moge.md)

## sample me.

- `[2006年11月～]` １社目 実習生配属
- `[2007年04月～2013年02月]` １社目：SIer
- `[2013年03月～2016年09月]` ２社目：受託・SES
- `[2016年10月～2017年09月]` ３社目：SES
- `[2017年12月～現在]` 個人事業主
  - 2021年から **消費税課税事業者** 。
  - 2024年10月に **インボイス取得** 。
 
参考表示のための `コードブロック` 表示テスト。

> **note:**  
> hogehoge, mogemoge, piyopiyo.  
> xxxxxxxxxxxxxx.  

## emoji.

- :warning: 注意
- :sparkling_heart: 得意
- :sweat_drops: 困り
- :tada: グッド
- :white_flower: よくできました
- :cherry_blossom: さくら
- :sparkles: キラキラ
- :star2: スター
- :beginner: ビギナー
- :fire: 進捗遅延


## sample code.

```java
	/**
	 * {@link ObjectMapper} の遅延初期化シングルトンホルダ。
	 * 
	 * @author sugaryo
	 */
	private static final class SingletonHolder {
		// Initialization-on-demand-holder idiom
		
		/** デフォルトのObjectMapper */
		private static final ObjectMapper mapper = new ObjectMapper();
		
		/** PrettyPrint設定のObjectMapper */
		private static final ObjectMapper pretty = new ObjectMapper().enable( SerializationFeature.INDENT_OUTPUT );
	}
```


## native html table.
<table><thead>
  <tr>
    <th colspan="6">Results</th>
  </tr></thead>
<tbody>
  <tr>
    <td>No</td>
    <td>Competition</td>
    <td>John</td>
    <td>Adam</td>
    <td>Robert</td>
    <td>Paul</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Swimming</td>
    <td>1:30</td>
    <td>2:05</td>
    <td>1:15</td>
    <td>1:41</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Running</td>
    <td>15:30</td>
    <td>14:10</td>
    <td>15:45</td>
    <td>16:00</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Shooting</td>
    <td>70%</td>
    <td>55%</td>
    <td>90%</td>
    <td>88%</td>
  </tr>
</tbody>
