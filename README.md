# Helper Options Modifier

An internal method for Pulsar’s form helpers which checks for the presence of
errors or help text and creates GUIDs to be targeted by aria attributes.

## Usage

Presumes the presence of an `options` variable, which is passed to the 
`modify_options()` method and overwrites itself with the modified array, or an 
empty one to prevent errors being thrown.

```twig
{% set options = modify_options(options|default({})) %}
```
