
# react-native-sunmi-printer

## SUNMI V2 Printer for React-Native

### Caution: this is not the official project and forked form https://github.com/januslo/react-native-sunmi-inner-printer

Offical Demos refer: https://github.com/shangmisunmi/SunmiPrinterDemo

## Installation

**Step 1.**

Install via NPM

```bash
npm install react-native-sunmi-v2-printer --save
```

Install via Yarn

```bash
yarn add react-native-sunmi-v2-printer
```

Install from source

```bash
npm install https://github.com/suraneti/react-native-sunmi-v2-printer.git --save
yarn add https://github.com/suraneti/react-native-sunmi-v2-printer.git --save
```
Note: This project is not tested on React Native < 0.64.1 since this was done to support latest versions.


**Step 2:**

Import in React-Native:

```javascript
import SunmiV2Printer from 'react-native-sunmi-printer';
```

## API

### Constants

| Name | Type| Description |
|:-----:|:-----:|:-----------:|
| Constants | string | Printer's status |
| hasPrinter | boolean | Is printer available |
| printerVersion | string | Printer's version |
| printerSerialNo | string | Printer's serial number |
| printerModal | string | Printer's model |

### Printer Status

|  Name | Description |
|:-----:|:-----------:|
| OUT_OF_PAPER_ACTION | Printer of paper |
| ERROR_ACTION | Printing error |
| NORMAL_ACTION | Printing normal |
| COVER_OPEN_ACTION | Printer's cover has open |
| COVER_ERROR_ACTION | Printer's cover is unusal |
| KNIFE_ERROR_1_ACTION | 切刀异常1－卡切刀 |
| KNIFE_ERROR_2_ACTION | 切刀异常2－切刀修复 |
| OVER_HEATING_ACITON | Printer is overheat |
| FIRMWARE_UPDATING_ACITON | Upgrade printer's firmware |

### Example

Please check on `example/` floder
