# ikachan-notify

Send a message to an Ikachan

# Options

* `url` (required) Ikachan post url.
* `channel` (required) sent target irc channel name.
* `passed-message` (optional) The message which will be shown on a passed build or deploy.
* `failed-message` (optional) The message which will be shown on a failed build or deploy.

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

## 0.0.2

- Supported passed and failed messages.
- Supported deploy.

## 0.0.1

- First version release
