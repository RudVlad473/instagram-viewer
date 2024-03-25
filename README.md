
# Usage guidelines

## How to add new package
1. Create directory in either `/apps` or `/packages`
2. `cd` into it
2. `pnpm init`
3. `npx tsc --init` (add tsconfig)
4. add desired eslint config 
    - you have to extend it from eslint config in the root of the project
5. add scripts for `lint` and `prettier` to `package.json`