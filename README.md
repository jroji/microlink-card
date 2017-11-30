# \<polymer-microlink\>

Polymer wrapper for https://microlink.io

## Usage

```HTML
<import href="/bower_components/microlink-card/microlink-card.html" rel="import">

...

<microlink-card url="https://microlink.io/"></microlink-card>
```
## Documentation

### Public properties

| Property         | Description                         | Notifies | Default |
| ---------------- | ----------------------------------- | -------- | ------- |
| `response`       | Response from the iron-ajax request | true     | (none)  |
| `key`            | API-KEY from microlinks             | false    | (none)  |
| `loading`        | Loading state from iron-ajax        | true     | false   |
| `url`            | Url to be analyzed by microlinks    | false    | (none)  |
| `scale-on-hover` | Set if the image scales on hover    | false    | (none)  |

### Styles

| Custom property                  | Description               | Default                                                                                            |
| -------------------------------- | ------------------------- | -------------------------------------------------------------------------------------------------- |
| `--microlink-border-radius`      | Border radius of the card | 5px                                                                                                |
| `--microlink-box-shadow`         | Shadow box of the card    | 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 1px 5px 0 rgba(0, 0, 0, 0.12),0 3px 1px -2px rgba(0, 0, 0, 0.2) |
| `--microlink-content-title-size` | Title font size           | 20px                                                                                               |
| `--microlink-content-text-size`  | Description font size     | 14px                                                                                               |
| `--microlink-content-color`      | Text color                | #333333                                                                                            |
| `--microlink-content-padding`    | Content section padding   | 20px                                                                                               |
| `--microlink-header-max-height`  | Max height of the header  | 150px                                                                                              |

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

And navigates to http://127.0.0.1:8081/components/microlink-card/demo/
## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
