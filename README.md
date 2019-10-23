# noop-template
Example template for noop jobs

### Usage

Example `screwdriver.yaml`

```
jobs:
    main:
        template: sd/noop
        requires: [~pr, ~commit]

```

