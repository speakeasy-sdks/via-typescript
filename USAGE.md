<!-- Start SDK Example Usage -->


```typescript
import { Via } from "via";
import { GetUsersResponse } from "via/dist/sdk/models/operations";

const sdk = new Via();

sdk.getUsers().then((res: GetUsersResponse) => {
  if (res.statusCode == 200) {
    // handle response
  }
});
```
<!-- End SDK Example Usage -->