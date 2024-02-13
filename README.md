This simple TypeScript project demonstrates how to export multiple subpaths from a TypeScript library

The important bits are:

* In `lib/tsconfig.json`:
  * `moduleResolution` must be set to `NodeNext`
  * `resolvePackageJsonExports` must be set to `true`

### Build the Library

* `cd typescript-library-subpaths/lib`
* `npm run build`

### Run the App

* `cd typescript-library-subpaths/app`
* `npm run build`
* `npm run start`
