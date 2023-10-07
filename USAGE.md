<!-- Start SDK Example Usage -->


```typescript
import { Via } from "via";

(async() => {
  const sdk = new Via();

  const res = await sdk.getUsers();

  if (res.statusCode == 200) {
    // handle response
  }
})();
```
<!-- End SDK Example Usage -->