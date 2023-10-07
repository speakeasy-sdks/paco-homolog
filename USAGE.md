<!-- Start SDK Example Usage -->


```typescript
import { PacoConnect } from "Paco-connect";

(async() => {
  const sdk = new PacoConnect();

  const res = await sdk.pets.createPets();

  if (res.statusCode == 200) {
    // handle response
  }
})();
```
<!-- End SDK Example Usage -->