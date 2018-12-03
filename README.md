# Ember QUnit Testem launcher

Opens testem server with QUnit module from open file.

## Features

Open your ember qunit test file and run `Testem: Run file module` command via CMD-SHIFT-P.

It opens new browser tab with the Testem server with the first module ID declared in the test file.

You can configure keyboard shortcut for the command using VS Code Keyboard Shortcuts settings.

## Requirements

None

## Extension Settings

None

## Install

Install from Extensions market place: 

https://marketplace.visualstudio.com/items?itemName=DocX.ember-qunit-testem-launcher

Or build locally:

```
npm install -g vsce
vsce package
```

Then install the generated `vsxi` file from Extensions menu in VS Code 

## Next ideas

* It always open new tab in browswer. Can we open/reload the existing tab?
* Start the Testem server if it does not run.
* Run specific test or submodule from current line.
* Find test file for current component/controller file and run the module from that.
