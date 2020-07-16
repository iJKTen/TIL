# Console
Different ways to use console.log

## Instead of logging think about warn and error
Instead of always using console.log think about console.warn and console.error when logging relevant messages.

## Logging objects
Instead of logging a variable you can wrap the variable in an object and the console will display that object.
```
console.log({variable1, variabl2});
```

## Color coded logs
You can log messages in different colors with
```
console.log('%c Here is your message', 'color: orange');
```