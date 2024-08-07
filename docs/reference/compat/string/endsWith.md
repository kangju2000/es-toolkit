# endsWith

::: info
This function is fully compatible with lodash. You can find it in our [compatibility library](../../../compatibility.md), `es-toolkit/compat`.
:::

Checks if a string contains another string at the end of the string.

Checks if one string ends with another string. Optional position parameter to search up the this position.

## Signature

```typescript
function endsWith(str: string, target: string, position: number = 0): string;
```

### Parameters

- `str` (`string`): The string that will be searched.
- `target` (`string`): The string that it should contain at the end.
- `position` (`number`, optional): Optional: position to search up to this character position.

### Returns

(`boolean`): Whether or not the str string ends with the target string

## Examples

```typescript
import { endsWith } from 'es-toolkit/string';

endsWith('fooBar', 'foo') // returns false
endsWith('fooBar', 'Bar') // returns true
endsWith('fooBar', 'abcdef') // returns false
endsWith('fooBar', 'foo', 3) // returns true
```
