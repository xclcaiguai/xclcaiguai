
<a name="definitions"></a>
## Definitions

<a name="baseresponse"></a>
### BaseResponse

|Name|Schema|
|---|---|
|**errorCode**  <br>*optional*|integer (int32)|
|**errorMsg**  <br>*optional*|string|
|**result**  <br>*optional*|object|
|**success**  <br>*optional*|boolean|


<a name="bidnoticequerydetailrequest"></a>
### BidNoticeQueryDetailRequest

|Name|Schema|
|---|---|
|**id**  <br>*optional*|integer (int64)|
|**pageNumber**  <br>*optional*|integer (int32)|
|**pageSize**  <br>*optional*|integer (int32)|


<a name="bidnoticequerymmslistrequest"></a>
### BidNoticeQueryMmsListRequest

|Name|Schema|
|---|---|
|**activityId**  <br>*optional*|integer (int64)|
|**keyword**  <br>*optional*|string|


<a name="querybidactivitylistrequest"></a>
### QueryBidActivityListRequest

|Name|Schema|
|---|---|
|**pageNumber**  <br>*optional*|integer (int32)|
|**pageSize**  <br>*optional*|integer (int32)|
|**status**  <br>*optional*|integer (int32)|


<a name="querybidflowrequest"></a>
### QueryBidFlowRequest

|Name|Schema|
|---|---|
|**bidActivityId**  <br>*optional*|integer (int64)|
|**bidGoodsId**  <br>*optional*|integer (int64)|


<a name="querybidforecastgoodslistrequest"></a>
### QueryBidForecastGoodsListRequest

|Name|Schema|
|---|---|
|**pageNumber**  <br>*optional*|integer (int32)|
|**pageSize**  <br>*optional*|integer (int32)|
|**type**  <br>*optional*|integer (int32)|



