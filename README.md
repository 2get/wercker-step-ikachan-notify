# ikachan-notify

Send a message to an Ikachan

# Options

* `url` (required) Ikachan post url.
* `channel` (required) sent target irc channel name.

# Example

```yaml
build:
  after-steps:
    - ikachan-notify:
      url: ikachan post url
      channel: channel name
```

# License

The MIT License (MIT)

# Changelog

## 0.0.1

- First version release
