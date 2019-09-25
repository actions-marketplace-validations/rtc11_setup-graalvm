# setup-graalvm
Github Action for setting up GraalVm

## Usage

### GitHub Actions
```
on: push
jobs:
  setup-graalvm:
    runs-on: ubuntu-latest
    steps:
    - name: setup-graalvm
      uses: rtc11/setup-graalvm@master
      with:
        args: https://github.com/oracle/graal/releases/download/vm-19.2.0.1/graalvm-ce-linux-amd64-19.2.0.1.tar.gz
```

