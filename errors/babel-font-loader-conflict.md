# Babel and Font loader conflict

#### Why This Error Occurred

You have tried to use `experimental.fontLoaders` with a custom babel config. When your application has a custom babel config you opt-out of the Next.js Compiler which is required to use `experimental.fontLoaders`.

#### Possible Ways to Fix It

- Remove your custom babel config and use the Next.js Compiler

### Useful Links

- [Next.js Compiler](https://nextjs.org/docs/advanced-features/compiler)
- [Customizing Babel Config](https://nextjs.org/docs/advanced-features/customizing-babel-config)
