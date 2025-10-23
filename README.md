# Renovate Configurations

This repository is a collection of configurations for Renovate.

## Structure

- Files in the first order are fully configured and ready-to-use configs.
- Files in folders are partial (but still valid) configurations that can be included in other configurations.

## Example

To include a configuration, you can reference it in your `renovate.json` file like this:

```json
{
    "extends": [
        "github>DenuxPlays/renovate-config"
    ]
}
````

## Configurations

### [all.json5](all.json5)

The config combines all configurations into one.

### [default.json5](default.json5)

The default and base configuration for Renovate.

### [rust.json5](rust.json5)

Configuration specifically for Rust projects.

### [jvm.json5](jvm.json5)

Configuration specifically for JVM projects.  
Tested with Java, Kotlin and Gradle.

## Contributions

We are open to contributions! If you have any improvements or new configurations to add, feel free to open a pull
request.
