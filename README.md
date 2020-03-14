# emotion-global-type-injection-repro

## Setup

First install all the dependencies with `yarn`.

Then run `yarn test`.

## Current Behavior

No error in the console.

## Expected behavior

There should be an error such as this:
```
test/test.tsx:4:6 - error TS2322: Type '{ css: string; }' is not assignable to type 'DetailedHTMLProps<HTMLAttributes<HTMLDivElement>, HTMLDivElement>'.
  Property 'css' does not exist on type 'DetailedHTMLProps<HTMLAttributes<HTMLDivElement>, HTMLDivElement>'.

4 <div css="" />
       ~~~


Found 1 error.
```
