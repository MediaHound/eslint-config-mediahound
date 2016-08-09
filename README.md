# MediaHound ESLint config

Our in-house config for ESLint.

## Requirements

We use Babel and React in our projects and we use a few ESLint plugins. They are marked as `peerDependencies` to this project. You will need to install them along with this config:

```
npm install --save-dev eslint-config-mediahound babel-eslint eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react eslint-plugin-filenames
```

Then, in your `.eslintrc` file, add:

```
{
  "extends": "mediahound"
}
```
