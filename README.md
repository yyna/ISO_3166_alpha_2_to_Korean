# iso-country-code-to-korean

> Convert ISO 3166 Alpha 2 Code to Country Name in Korean/English

## Install

```bash
npm i iso-country-code-to-korean
```

## Usage

```bash
import { convert } from 'iso-country-code-to-korean';

convert('KR'); // 대한민국
convert('KR', 'KR'); // 대한민국
convert('KR', 'EN'); // Korea (South)

convert('KR', 'DE'); // [ERR] Support Language : KR(Korean), EN(English)
```
## License

[MIT](http://vjpr.mit-license.org)
