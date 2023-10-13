# action-install-step-cli

This GitHub Action installs `step` CLI on Linux and MacOS. It also supports x86_64 and aarch64 CPU architectures.

## Usage

You can use this action by adding the following to your workflow:

Install the latest version:

```yaml
- uses: smallstep/action-install-step-cli@v1

- name: Get Version
  run: step version
```

Install with a specific version:

```yaml
- uses: smallstep/action-install-step-cli@v1
  with:
    step-cli-version: 0.25.0

- name: Get Version
  run: step version
```

## License

MIT License

Copyright (c) 2023 Smallstep Labs, Inc

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
