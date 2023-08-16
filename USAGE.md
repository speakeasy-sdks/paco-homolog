<!-- Start SDK Example Usage -->


```typescript
import { PacoConnect } from "Paco-connect";
import { CreatePetsResponse } from "Paco-connect/dist/sdk/models/operations";

const sdk = new PacoConnect();

sdk.pets.createPets().then((res: CreatePetsResponse) => {
  if (res.statusCode == 200) {
    // handle response
  }
});
```
<!-- End SDK Example Usage -->