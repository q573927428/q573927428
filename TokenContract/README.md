1。设置白名单：setFeeWhiteList，参数：地址,true

2。设置黑名单：setBlackList，参数：地址,true

3。批量设置黑名单：batchSetBlackList，参数：地址列表,true，形如：["地址1","地址2"]，貌似bscscan要"地址1","地址2"传

4。开放交易：startTrade

5。修改合约卖出数量：setNumToSell，参数：数量，默认值：500000000000000000，表示0.5个

6。修改LP分红条件：setHolderRewardCondition，参数：数量(最小精度)，默认值：100000000000000000000，表示100U

7。修改交易税：setFee，参数：营销,营销2,LP分红，默认值：50,50,400，表示0.5%,0.5%,4%

8。提取合约里的BNB：claimBalance，提取到营销钱包

9。提取合约里的代币：claimToken，参数：代币合约,数量(最小精度)，提取到营销钱包

10。修改限购数量：setLimitAmount，参数：数量(最小精度)，默认值：1000000000000000000，表示限购1个，传0表示不限购

11。排除地址不参与LP分红：setExcludeHolder，参数：参数：地址,true

