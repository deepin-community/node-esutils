# Installation
> `npm install --save @types/esutils`

# Summary
This package contains type definitions for esutils (https://github.com/estools/esutils).

# Details
Files were exported from https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/esutils.
## [index.d.ts](https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/esutils/index.d.ts)
````ts
// Type definitions for esutils 2.0
// Project: https://github.com/estools/esutils
// Definitions by: Rhythm Bhiwani <https://github.com/rhythmbhiwani>
// Definitions: https://github.com/DefinitelyTyped/DefinitelyTyped

export = esutils;

declare const esutils: {
    ast: {
        isExpression: (node: any) => boolean;
        isIterationStatement: (node: any) => boolean;
        isProblematicIfStatement: (node: any) => boolean;
        isSourceElement: (node: any) => boolean;
        isStatement: (node: any) => boolean;
        trailingStatement: any;
    };
    code: {
        isDecimalDigit: (ch: any) => boolean;
        isHexDigit: (ch: any) => boolean;
        isIdentifierPartES5: (ch: any) => boolean;
        isIdentifierPartES6: (ch: any) => boolean;
        isIdentifierStartES5: (ch: any) => boolean;
        isIdentifierStartES6: (ch: any) => boolean;
        isLineTerminator: (ch: any) => boolean;
        isOctalDigit: (ch: any) => boolean;
        isWhiteSpace: (ch: any) => boolean;
    };
    keyword: {
        isStrictModeReservedWordES6: (id: any) => boolean;
        isIdentifierES5: (id: any, strict: any) => boolean;
        isIdentifierES6: (id: any, strict: any) => boolean;
        isIdentifierNameES5: (id: any) => boolean;
        isIdentifierNameES6: (id: any) => boolean;
        isKeywordES5: (id: any, strict: any) => boolean;
        isKeywordES6: (id: any, strict: any) => boolean;
        decodeUtf16: (lead: any, trail: any) => any;
        isReservedWordES5: (id: any, strict: any) => boolean;
        isReservedWordES6: (id: any, strict: any) => boolean;
        isRestrictedWord: (id: any) => boolean;
    };
};

````

### Additional Details
 * Last updated: Tue, 03 Aug 2021 07:01:18 GMT
 * Dependencies: none
 * Global values: none

# Credits
These definitions were written by [Rhythm Bhiwani](https://github.com/rhythmbhiwani).
