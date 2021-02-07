# HelloWorldDockerAction

This action prints "Hello world"  or "Hello" + name of a specified person to the log.

## Inputs

### `who`

**required** The name of the person to greet.  Defaults to `"World"`.

## Outputs

### `time`

The time the greeting occured.

## Example usage

```
uses: moddyz/HelloWorldDockerAction@v1
with:
  who: 'Cobra Kai'
```
