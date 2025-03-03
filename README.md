# yambar-scripts

This is a collection of module scripts for [Yambar](https://codeberg.org/dnkl/yambar).

## loadavg

This fetches the system's load average.

The only argument is the interval to run (in seconds).

```yaml
- script:
    path: /usr/local/bin/yambar-loadavg
    args: [1]
    content:
      string: {text: "{one} {five} {fifteen}"}
```
