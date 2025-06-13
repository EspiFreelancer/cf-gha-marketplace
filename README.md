# cf-gha-marketplace
Código Facilito exercise: creating an GitHub Actions and placing it in the Marketplace.

# Hello world javascript action exercise

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: actions/hello-world-javascript-action-by-espifreelancer@v1.0
with:
  who-to-greet: 'Mona the Octocat'
```
