<!-- Start SDK Example Usage [usage] -->
```typescript
import { PacoConnect } from "Paco-connect";

async function run() {
    const sdk = new PacoConnect();

    const res = await sdk.pets.createPets({
        id: 596804,
        name: "string",
    });

    if (res.statusCode == 200) {
        // handle response
    }
}

run();

```
<!-- End SDK Example Usage [usage] -->