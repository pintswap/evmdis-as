# evmdis-as

EVM bytecode disassembly within a subgraph (or any other context that requires AssemblyScript).

## Usage

```js
import { disassemble } from "evmdis-as";

const disassembly: string[][] = disassemble(bytecode);
```
