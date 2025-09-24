# MATLAB Color Theme Extensions

[![View MATLAB Color Theme Extensions on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/181402-matlab-color-theme-extensions) [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=mathworks/matlab-color-theme-extensions) 

**MATLAB Color Theme Extensions** enhance MATLAB’s built-in themes by enabling users to create, import, and share custom color schemes. This extension allows you to personalize your MATLAB environment and easily switch between different color schemes.

The project works by customizing colors on top of the existing MATLAB Themes (either Light or Dark).

## Get Started

Use MATLAB Add-Ons Explorer and download the project, or follow these steps:
1. Download the project from MATLAB File Exchange or GitHub.
2. Extract the zip file to any directory on your system.
3. Open MATLAB and navigate to the extracted project folder.

Run project scripts (such as `import_scheme` or `export_scheme`) from within project directory.

## Features
- **Import a standard color scheme**
  - To import a color scheme JSON file, run `import_scheme.p`
  - A file chooser will appear; try any standard scheme from the [schemes folder](./schemes/) folder.
  - Or, use the command:
    ```matlab
    import_scheme('schemes/cobalt.json');
    ```

- **Create custom schemes**
  - To create a custom color scheme, use [template.json](./template.json) as a reference. The `"DesktopTheme"` field is required in the JSON file; it determines the base theme (Light/Dark) before applying further color customizations.
  - To validate the structure of this custom color scheme JSON file, run `validateJsonFile.p`:
    ```matlab
    validationJsonFile('updatedColorScheme.json')
    ```

- **Export Current Color Settings**
  - To export current color personalizations to a JSON file, run `export_scheme.p`.
  - A file chooser will prompt to select a save location and name.
  - Or, use the command:
    ```matlab
    export_scheme('myCustomScheme.json');
    ```
  - It should export customization for the current MATLAB Theme.

- **Reset customizations**
  - To reset color settings to their default values, run:
    ```matlab
    import_scheme('schemes/matlab-dark.json');
    import_scheme('schemes/matlab-light.json');
    ```

## Scheme File Structure

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

The fields in the JSON file are inspired by MATLAB's Settings panel (previously _Preference Panel_), see **MATLAB Toolstrip → Home → Settings**

## MathWorks Products (https://www.mathworks.com)

MATLAB R2025a or newer

## License

See [LICENSE](./LICENSE.txt).

## Contributing

If you have suggestions for color schemes or improvements, please [create an issue or pull request](https://github.com/mathworks/matlab-color-theme-extensions/issues). See [CONTRIBUTING](./CONTRIBUTING.md).

## Community Support

[MATLAB Central](https://www.mathworks.com/matlabcentral)

Copyright 2025 The MathWorks, Inc.