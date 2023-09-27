# Via SDK


## Overview

Sample API: Optional multiline or single-line description in [CommonMark](http://commonmark.org/help/) or HTML.

### Available Operations

* [getUsers](#getusers) - Returns a list of users.

## getUsers

Optional extended description in CommonMark or HTML.

### Example Usage

```typescript
import { Via } from "via";
import { GetUsersResponse } from "via/dist/sdk/models/operations";

const sdk = new Via();

sdk.via.getUsers().then((res: GetUsersResponse) => {
  if (res.statusCode == 200) {
    // handle response
  }
});
```

### Parameters

| Parameter                                                    | Type                                                         | Required                                                     | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| `config`                                                     | [AxiosRequestConfig](https://axios-http.com/docs/req_config) | :heavy_minus_sign:                                           | Available config options for making requests.                |


### Response

**Promise<[operations.GetUsersResponse](../../models/operations/getusersresponse.md)>**

