## Usage Example

**This is an untested port of luxon for deno.**

```ts
import { DateTime } from "https://raw.githubusercontent.com/ipmanlk/deno-luxon/master/mod.ts";

const dateTimeStr =DateTime.local().setZone("Asia/Colombo").toFormat("YYYY-MM-DD hh:mm A");

console.log(dateTimeStr);
```

## Details 
see [original docs](https://moment.github.io/luxon/)