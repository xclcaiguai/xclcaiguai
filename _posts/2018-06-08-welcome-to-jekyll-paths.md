---
layout: post
title:  "Welcome to Massively: The Jekyll Theme!"
date:   2018-10-31
excerpt: "Huge thanks to HTML5 UP for making this awesome template! Let's see what it can do"
image: "/images/pic02.jpg"
---

<a name="paths"></a>
## Paths

<a name="queryactivitydepositorybymallidusingget"></a>
### 活动存款
```
GET /jupiter/api/bid/queryActivityDeposit
```


#### Description
活动存款


#### Responses

|HTTP Code|Description|Schema|
|---|---|---|
|**200**|OK|[BaseResponse](#baseresponse)|
|**201**|Created|No Content|
|**401**|Unauthorized|No Content|
|**403**|Forbidden|No Content|
|**404**|Not Found|No Content|
|**405**|Invalid input|integer (int32)|


#### Consumes

* `application/json`


#### Produces

* `*/*`


#### Tags

* bid-activity-query-controller


<a name="querybidactivitylistusingget"></a>
### 活动列表
```
GET /jupiter/api/bid/queryBidActivityList
```


#### Description
活动列表


#### Parameters

|Type|Name|Description|Schema|
|---|---|---|---|
|**Body**|**request**  <br>*required*|request|[QueryBidActivityListRequest](#querybidactivitylistrequest)|


#### Responses

|HTTP Code|Description|Schema|
|---|---|---|
|**200**|OK|[BaseResponse](#baseresponse)|
|**201**|Created|No Content|
|**401**|Unauthorized|No Content|
|**403**|Forbidden|No Content|
|**404**|Not Found|No Content|


#### Consumes

* `application/json`


#### Produces

* `*/*`


#### Tags

* bid-activity-query-controller


<a name="querybidforecastgoodslistusingget"></a>
### 竞价商品列表
```
GET /jupiter/api/bid/queryBidForecastGoodsList
```


#### Description
竞价商品列表


#### Parameters

|Type|Name|Description|Schema|
|---|---|---|---|
|**Body**|**BindingResult**  <br>*required*|绑定结果|string|
|**Body**|**QueryBidForecastGoodsListRequest**  <br>*required*|http请求|string|
|**Body**|**request**  <br>*required*|request|[QueryBidForecastGoodsListRequest](#querybidforecastgoodslistrequest)|


#### Responses

|HTTP Code|Description|Schema|
|---|---|---|
|**200**|OK|[BaseResponse](#baseresponse)|
|**201**|Created|No Content|
|**401**|Unauthorized|No Content|
|**403**|Forbidden|No Content|
|**404**|Not Found|No Content|


#### Consumes

* `application/json`


#### Produces

* `*/*`


#### Tags

* bid-activity-query-controller


<a name="queryuserbidflowusingget"></a>
### 查询流水
```
GET /jupiter/api/bid/queryUserBidFlow
```


#### Description
查询流水


#### Parameters

|Type|Name|Description|Schema|
|---|---|---|---|
|**Body**|**BindingResult**  <br>*required*|绑定结果|string|
|**Body**|**QueryBidFlowRequest**  <br>*required*|http请求|string|
|**Body**|**request**  <br>*required*|request|[QueryBidFlowRequest](#querybidflowrequest)|


#### Responses

|HTTP Code|Description|Schema|
|---|---|---|
|**200**|OK|[BaseResponse](#baseresponse)|
|**201**|Created|No Content|
|**401**|Unauthorized|No Content|
|**403**|Forbidden|No Content|
|**404**|Not Found|No Content|
|**405**|Invalid input|integer (int32)|


#### Consumes

* `application/json`


#### Produces

* `*/*`


#### Tags

* bid-activity-query-controller


<a name="querybidnoticedetailusingget"></a>
### 查询细节
```
GET /jupiter/api/bidNotice/detail
```


#### Description
查询细节接口


#### Parameters

|Type|Name|Description|Schema|
|---|---|---|---|
|**Body**|**BindingResult**  <br>*required*|绑定结果|string|
|**Body**|**QueryBidFlowRequest**  <br>*required*|http请求|string|
|**Body**|**request**  <br>*required*|request|[BidNoticeQueryDetailRequest](#bidnoticequerydetailrequest)|


#### Responses

|HTTP Code|Description|Schema|
|---|---|---|
|**200**|OK|[BaseResponse](#baseresponse)|
|**201**|Created|No Content|
|**401**|Unauthorized|No Content|
|**403**|Forbidden|No Content|
|**404**|Not Found|No Content|


#### Consumes

* `application/json`


#### Produces

* `*/*`


#### Tags

* bid-notice-query-controller


<a name="querybidnoticelistusingget"></a>
### 查询列表
```
GET /jupiter/api/bidNotice/list
```


#### Description
查询列表接口


#### Parameters

|Type|Name|Description|Schema|
|---|---|---|---|
|**Body**|**BindingResult**  <br>*required*|绑定结果|string|
|**Body**|**QueryBidFlowRequest**  <br>*required*|http请求|string|
|**Body**|**request**  <br>*required*|request|[BidNoticeQueryMmsListRequest](#bidnoticequerymmslistrequest)|


#### Responses

|HTTP Code|Description|Schema|
|---|---|---|
|**200**|OK|[BaseResponse](#baseresponse)|
|**201**|Created|No Content|
|**401**|Unauthorized|No Content|
|**403**|Forbidden|No Content|
|**404**|Not Found|No Content|


#### Consumes

* `application/json`


#### Produces

* `*/*`


#### Tags

* bid-notice-query-controller



