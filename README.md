# Radix Themes Datepicker

Styles that make [react-datepicker](https://www.npmjs.com/package/react-datepicker) beautiful and [@radix-ui/themes](https://www.radix-ui.com/) compatible.

## How to install

```npm install radix-themes-datepicker-styles```

## Usage

```JSX
import "@radix-ui/themes/styles.css";
import "react-datepicker/dist/react-datepicker.css";
import "radix-themes-datepicker-styles";

import { TextField } from "@radix-ui/themes"
import DatePicker from 'react-datepicker';

const App = () => (
    <DatePicker
      showPopperArrow={false}
      popperPlacement="bottom-start"
      customInput={<TextField.Root />}
      placeholderText="Select date"
    />
);

export default App;
```

## Default looks

<img width="229" alt="Screenshot 2025-05-03 at 1 01 25 AM" src="https://github.com/user-attachments/assets/7967066b-016b-46be-a8fc-3609bd0df395" />

## Improved looks

Light theme

<img width="395" alt="Screenshot 2025-05-03 at 1 01 48 AM" src="https://github.com/user-attachments/assets/c5e5cfc2-64e9-4206-bbfa-1f9ed1f886ea" />

Dark theme

<img width="404" alt="Screenshot 2025-05-03 at 1 02 10 AM" src="https://github.com/user-attachments/assets/73351e88-45af-47e0-8fb6-e22d616ec602" />

