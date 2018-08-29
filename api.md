### 广告主
#### 广告主获取媒体、第三方列表（ID、名称、信誉值）
#### 广告主创建智能合约（合约内容）
#### 广告主查看自己创建的合约列表

### 媒体
#### 媒体查看合约列表（未确认，已确认，已完成）
#### 媒体查看某个合约详细内容
#### 媒体签名，确认接受合约
#### 媒体请求第三方鉴别

### 第三方
#### 第三方查看合约列表
#### 第三方查看合约详细内容
#### 第三方签名，确认接受合约
#### 第三方上传文件地址

#### 各用户通用
#### 各用户查看自己账户信息（ID、名称、资产、信誉值）
#### 用户查看某个用户账户信息（ID、信誉值、交易记录）

GET getUserList?type=media/anticheat 获取用户列表
GET getUserInfo?id=* 获取其他用户信息
POST createSmartContract 创建智能合约
GET getContractList?type=advertiser/media/anticheat&id=* 获取合约列表
GET getContractInfo?contractId=* 获取合约详细信息
POST mediaConfirm 媒体确认
POST antiCheatConfirm 第三方确认
POST mediaSubmit 媒体提交
POST antiCheatSubmit 第三方提交
GET getAccount?id=* 获取自己账户信息
