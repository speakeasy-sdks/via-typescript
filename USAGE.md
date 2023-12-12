<!-- Start SDK Example Usage [usage] -->
```typescript
import { Via } from "via";

async function run() {
    const sdk = new Via();

    const res = await sdk.getUsers();

    if (res.statusCode == 200) {
        // handle response
    }
}

run();

```
<!-- End SDK Example Usage [usage] -->