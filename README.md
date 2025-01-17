# react-native-country-flag-quality forked by DuduLourenco

This is a React-Native package to display every 254 Country flags with the [ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) Standard and image uality select!

[![NPM](https://img.shields.io/npm/v/react-native-country-flag.svg)](https://www.npmjs.com/package/react-native-country-flag)

## Install

```bash
npm install --save react-native-country-flag-quality
or
yarn add react-native-country-flag-quality
```

## Usage

This is a simple example how you can use the `CountryFlag` component.

```jsx
import CountryFlag from "react-native-country-flag-quality";

<CountryFlag isoCode="de" size={25} quality={"low"} />
```

You can only use the [ISO 3166-1 alpha-2 Standard](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) for the isoCode property.

## Props

| Prop    |    Type    |                                                    Desciption                                                    |
|---------|:----------:| :--------------------------------------------------------------------------------------------------------------: |
| isoCode |   String   | Define the country flag with the [ISO 3166-1 alpha-2 Standard](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2). |
| size    |  Integer   |Define the size from the country flag.                                            |
| style   | Stylesheet |Customize the style from the `CountryFlag` component.                             |                              
| quality |   string   |Define the image quality from the country flag.

## License

MIT © [Yannis Hofmann](https://github.com/YannisHofmann)

MIT © [Eduardo Lourenco da Silva](https://github.com/DuduLourenco)
