## 个股资金流向趋势

-   接口用途  
     获取个股资金流向历史数据
-   接口调用说明
    ```javascript
    dip.stock.fundflow.getStockTrendHis("sh600005").then((data) => {
        //数据存储、处理逻辑，请自行实现
    });
    ```
-   参数说明
<table>
    <thead><tr><th>参数</th><th>说明</th></tr></thead>
    <tbody>
        <tr><td>code</td><td>股票代码（带市场标识）</td></tr>
    </tbody>
</table>

-   返回说明
<table>
       <thead><tr><th>参数</th><th>说明</th></tr></thead>
       <tbody>
           <tr><td>date</td><td>交易日期</td></tr>
           <tr><td>trade</td><td>收盘价</td></tr>
           <tr><td>changeratio</td><td>涨跌幅</td></tr>
           <tr><td>turnover</td><td>换手率</td></tr>
           <tr><td>netamount</td><td>净流入/万</td></tr>
		   <tr><td>ratioamount</td><td>净流入率</td></tr>
		   <tr><td>r0_net</td><td>主力净流入/万</td></tr>
		   <tr><td>r0_ratio</td><td>主力净流入率</td></tr>
		   <tr><td>r0x_ratio</td><td>主力罗盘</td></tr>
		   <tr><td>cate_ra</td><td>行业净流入率</td></tr>
		   <tr><td>cate_na</td><td>行业净流入/万</td></tr>
       </tbody>
   </table>
