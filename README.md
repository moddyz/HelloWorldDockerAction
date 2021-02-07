<a href="https://github.com/moddyz/HelloWorldDockerAction/actions?query=workflow%3A%22Main%22"><img src="https://github.com/moddyz/HelloWorldDockerAction/workflows/Main/badge.svg"/></a><a href="https://github.com/moddyz/HelloWorldDockerAction/actions?query=workflow%3A%22Private%020Main%22"><img src="https://github.com/moddyz/HelloWorldDockerAction/workflows/Private%20Main/badge.svg"/></a>

# HelloWorldDockerAction

This action prints "Hello world"  or "Hello" + name of a specified person to the log.

## Inputs

### `who`

**Required** The name of the person to greet.  Defaults to `"World"`.

## Outputs

### `time`

The time the greeting occured.

## Example usage

```
uses: moddyz/HelloWorldDockerAction@v1
with:
  who: 'Cobra Kai'
```
