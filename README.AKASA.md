

# Playwright Akasa Fork

Akasa maintains a small fork of the [Playwright](https://github.com/microsoft/playwright) project to enable various features specific to Aksasa use cases.


## Changes

* **1.35.2-akasa1**: Expose the hideHighlight option in `BrowserContext.enableRecorder` so that we can toggle the highlight view showing during user actions. (mjeti, September 2023)

* **1.35.1-akasa1**: Expose `BrowserContext.enableRecorder` so that we can initiate recordings programmatically. (masoncj, June 2023)

## Release process

We don't independently release the full Playwright package, just the Python version.

See the Akasa forked playwright-python repository for build instructions.



