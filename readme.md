# repro

```sh
npm ci
npx asyncapi-generator --force-write --output dist asyncapi.yaml @asyncapi/html-template
```

```
Something went wrong:
Error: This template is not compatible with the current version of the generator (2.0.0). This template is compatible with the following version range: >=1.15.0 <2.0.0.
    at isTemplateCompatible (/Users/n637831/git/astest/node_modules/@asyncapi/generator/lib/templateConfigValidator.js:57:11)
    at module.exports.validateTemplateConfig (/Users/n637831/git/astest/node_modules/@asyncapi/generator/lib/templateConfigValidator.js:30:3)
    at Generator.configureTemplateWorkflow (/Users/n637831/git/astest/node_modules/@asyncapi/generator/lib/generator.js:314:5)
    at async Generator.generate (/Users/n637831/git/astest/node_modules/@asyncapi/generator/lib/generator.js:202:5)
    at async Generator.generateFromFile (/Users/n637831/git/astest/node_modules/@asyncapi/generator/lib/generator.js:503:12)
    at async /Users/n637831/git/astest/node_modules/@asyncapi/generator/cli.js:157:9
```
