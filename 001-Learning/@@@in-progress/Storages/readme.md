
## Local Storage vs Session Storage vs Cookie

|           #          |       Cookies      | Local storage | Session storage |
|:--------------------:|:------------------:|:-------------:|:---------------:|
|       Capacity       |         4KB        |      10MB     |       5MB       |
|       Browsers       |   HTML 4 / HTML 5  |     HTML 5    |      HTML 5     |
|    Accessible from   |     Any window     |   Any window  |     Same tab    |
|  Auto-expire option  |         Yes        |       No      |       Yes       |
|      Expiration      |    Manually set    |     Never     |   On tab close  |
|    Browser support   |      Very high     |   Very high   |    Very high    |
| Supported data types |     String only    |  String only  |   String only   |
|   Storage location   | Browser and server |  Browser only |   Browser only  |
|  Sent with requests  |         Yes        |       No      |        No       |
|  Blockable by users  |         Yes        |      Yes      |       Yes       |
|   Editable by users  |         Yes        |      Yes      |       Yes       |


<img src="./comparison.png" />