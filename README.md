# Made By Web Component

Web component that shows contact information for the project creator

## Demo

[Check it live!](http://webcomponents.github.io/made-by)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install made-by --save
```

Or [download as ZIP](https://github.com/webcomponents/made-by/archive/master.zip).

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/made-by/made-by.html">
    ```

3. Start using it!

    ```html
    <made-by></made-by>
    ```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`by`       | *string*                  | `Made by...`        | Primary text
`author`   | *string*                  | `Short name`        | Author name
`phone`    | *string*                  | `Phone number`      | Phone number
`more`     | *string*                  | `Read more`         | Read more text for href link
`href`     | *string*                  | `#`                 | URL for more text



<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="made-by.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<link rel="import" href="made-by.html">
<made-by by="Made by" author="Gui Seek" phone="44 99999 9999" more="Show more" href="https://guiseek.js.org"></made-by>
```
