# Useless Developers Eslint Config
MMmhhmmmm
```typescript
const config = {
  plugins: [
    "@ianvs/prettier-plugin-sort-imports",
    "prettier-plugin-tailwindcss",
  ],
  tailwindConfig: "tailwind.config.ts",
  importOrder: [
    "^(react/(.*)$)|^(react$)|^(react-native(.*)$)",
    "^(next/(.*)$)|^(next$)",
    "^(expo(.*)$)|^(expo$)",
    "<THIRD_PARTY_MODULES>",
    "",
    "^@acme/(.*)$",
    "",
    "^~/utils/(.*)$",
    "^~/components/(.*)$",
    "^~/styles/(.*)$",
    "^~/(.*)$",
    "^[./]",
  ],
  importOrderParserPlugins: ["typescript", "jsx", "decorators-legacy"],
  importOrderTypeScriptVersion: "5.1.6",
};
````
