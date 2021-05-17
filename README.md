# Douban_Data

从豆瓣电影网站随机爬取了2W名用户以及2W部电影，经数据清洗后剩余数据如下

<table border=0 cellpadding=0 cellspacing=0 width=324 style='border-collapse:
 collapse;table-layout:fixed;width:243pt'>
 <col width=64 span=4 style='width:70pt'>
 <col width=68 style='mso-width-source:userset;mso-width-alt:2417;width:60pt'>
 <tr height=18 style='height:13.8pt'>
  <td height=18 width=64 >用户</td>
  <td align=right width=64 >9,625</td>
  <td width=64 ></td>
  <td width=64 >用户-电影</span></td>
  <td class=xl65 align=right width=68>2,195,882</td>
 </tr>

 <tr height=18 style='height:13.8pt'>
  <td height=18 style='height:13.8pt'>电影</td>
  <td align=right>12,385</td>
  <td></td>
  <td>电影-导演</span></td>
  <td class=xl65 align=right>30,248</td>
 </tr>

 <tr height=18 style='height:13.8pt'>
  <td height=18 style='height:13.8pt'>导演</td>
  <td align=right>6,287</td>
  <td></td>
  <td>电影-演员</span></td>
  <td class=xl65 align=right>56,421</td>
 </tr>
 <tr height=18 style='height:13.8pt'>
  <td height=18 style='height:13.8pt'>演员</td>
  <td align=right>9,598</td>
  <td></td>
  <td>电影-类型</span></td>
  <td class=xl65 align=right>42,335</td>
 </tr>
 <tr height=18 style='height:13.8pt'>
  <td height=18 style='height:13.8pt'>类型</td>
  <td align=right>35</td>
  <td colspan=3 style='mso-ignore:colspan'></td>
 </tr>
 <![if supportMisalignedColumns]>
 <tr height=0 style='display:none'>
  <td width=64 style='width:60pt'></td>
  <td width=64 style='width:60pt'></td>
  <td width=64 style='width:60pt'></td>
  <td width=64 style='width:60pt'></td>
  <td width=68 style='width:60pt'></td>
 </tr>
 <![endif]>
</table>

########################################################

*actorOrder.csv | directorOder.csv | genreOder.csv 顺序代表其相应id*

*final_kg.dat 由电影数据构成的关系图*

*movieinfo.txt 电影数据信息（电影id、电影名、导演、演员、类型、时间、标签、星评、评分、相关电影、豆瓣ID、海报链接）*

*test.txt | train.txt 用户-电影评分数据，分为测试|训练数据*
