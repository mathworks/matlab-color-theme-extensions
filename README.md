# MATLAB Theme Extensions

[![View MATLAB Theme Extensions on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/matlab-theme-extensions) [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=github.com/mathworks/matlab-theme-extensions) 

**MATLAB Theme Extensions** enhances MATLAB’s built-in themes by enabling users to create, import, and share custom color themes. This extension allows you to personalize your MATLAB environment and easily switch between different color schemes.

### Features
1. Import custom color scheme from JSON files, (e.g., the Cobalt scheme):
```matlab
import_scheme('schemes/cobalt.json');
```
2. Export your current color settings along with MATLAB Theme to a JSON file.
```matlab
export_scheme('exampleCustomColors.json');
```

The project works by customizing colors on top of the existing MATLAB Themes (either Light or Dark).

### Scheme File Structure

Scheme files are JSON documents that must include a `DesktopTheme` field and follow the structure of the provided [template.json](./template.json) in this project. Customizable fields include:
- Background Color
- Text Color
- MATLAB Syntax Highlighting Colors
- Output Colors
- Programming Tools
- Syntax Highlighting for other languages such as C, Java, HTML, etc.
- Current Line Highlight
- Right-hand Text limit line
- Boolean fields to enable or disable specific customizations

The fields in the JSON file are inspired from MATLAB's Settings panel.

## MathWorks Products (https://www.mathworks.com)
MATLAB R2025a or newer

## License
See [LICENSE](./LICENSE.txt)

## Contributing
If you have suggestions for color schemes or improvements, please [create an issue or pull request](https://github.com/mathworks/matlab-theme-extensions). See [CONTRIBUTING](./CONTRIBUTING.md)

## Community Support
[MATLAB Central](https://www.mathworks.com/matlabcentral)

Copyright 2025 The MathWorks, Inc.