# Is String Single Line (ES)

[**⚖️** MIT](./LICENSE.md)

🔗
[DistBoard @hugoalh](https://hugoalh.github.io/distboard/is_string_singleline_ecmascript)
● [GitHub](https://github.com/hugoalh/is-string-singleline-es)
● [JSR](https://jsr.io/@hugoalh/is-string-singleline)
● [NPM](https://www.npmjs.com/package/@hugoalh/is-string-singleline)

An ECMAScript module to determine whether the string is single line.

## 🎯 Runtime Targets

Any runtime which support ECMAScript should able to use this; These runtimes are officially supported:

- **[Bun](https://bun.sh/)** >= v1.1.0
- **[Deno](https://deno.land/)** >= v2.1.0
- **[NodeJS](https://nodejs.org/)** >= v20.9.0

## 🛡️ Runtime Permissions

This does not request any runtime permission.

## #️⃣ Sources & Entrypoints

- GitHub Raw
  ```
  https://raw.githubusercontent.com/hugoalh/is-string-singleline-es/{Tag}/mod.ts
  ```
- JSR
  ```
  jsr:@hugoalh/is-string-singleline[@{Tag}]
  ```
- NPM
  ```
  npm:@hugoalh/is-string-singleline[@{Tag}]
  ```

| **Name** | **Path** | **Description** |
|:--|:--|:--|
| `.` | `./mod.ts` | Default. |

> [!NOTE]
> - Different runtimes have vary support for the sources and entrypoints, visit the runtime documentation for more information.
> - It is recommended to include tag for immutability.
> - These are not part of the public APIs hence should not be used:
>   - Benchmark/Test file (e.g.: `example.bench.ts`, `example.test.ts`).
>   - Entrypoint name or path include any underscore prefix (e.g.: `_example.ts`, `foo/_example.ts`).
>   - Identifier/Namespace/Symbol include any underscore prefix (e.g.: `_example`, `Foo._example`).

## 🧩 APIs

- ```ts
  function isStringSingleLine(item: string): boolean;
  ```

> [!NOTE]
> - For the full or prettier documentation, can visit via:
>   - [Deno CLI `deno doc`](https://docs.deno.com/runtime/reference/cli/doc/)
>   - [JSR](https://jsr.io/@hugoalh/is-string-singleline)

## ✍️ Examples

- ```ts
  isStringSingleLine(`Wisi sed et at vero eos nostrud volutpat sed stet dignissim sit sanctus in eros.
  Et laoreet odio sanctus ea.
  Sea in dolores diam tincidunt labore sea stet vero dolor ut est.
  At aliquyam diam facilisis lorem et takimata et volutpat eros erat ipsum velit labore sed ea illum.
  Dolor lorem sed et volutpat exerci gubergren gubergren tempor quis ea eirmod eos ut dolor autem ipsum accumsan.`);
  //=> false
  ```
- ```ts
  isStringSingleLine("Hello, world!");
  //=> true
  ```
