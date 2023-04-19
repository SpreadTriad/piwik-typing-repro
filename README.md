## Setup

Run npm install

## Issue

Please open in IDE with TypeScript validation on. Then see src/index:

- the type of `PiwikProSdk.initialize` is `any`: type inference is not working
- `PiwikProSdkType` cannot be imported: package does not export it's typing