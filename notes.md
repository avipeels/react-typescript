# Journey of Typescript file
1. The typescript file starts in *src* folder.
2. Runs through the *TS compiler*.
3. Runs through the *webpack* and ends up in *main.js* file in *dist*.

# @Types
These are the declaration files that Typescript checks.

# ts-loader & source-map-loader
Both of these dependencies let Typescript and webpack play well together.
1. ts-loader: helps webpack to compile TS code using tsconfig.json. This is not the only loaader for typescript.
2. source-map-loader: will inform webpack to generate source maps for TS files. Finally helps in debugging ts files at the end.
