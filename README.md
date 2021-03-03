# CS259-tests
Repo to share tests for the CS259 coursework.

If you want to add your own tests then submit a merge-request with your tests in a folder with a README.md describing the correct output etc.
By submiting a pull-request, you agree to licence the contents as below.

## Usage

The recommend way to use this repo is to add it as a [submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules) into the same folder as where you are working on `Assignment.jj`. (You can also manually download it as a zip file)

```bash
git submodule add https://github.com/Department-of-Administrative-Affairs/CS259-tests
git submodule update --init --recursive
```
Later on, when (if) there are ever any new tests added run:
```bash
git submodule update --init --recursive
``` 
to fetch the newest tests.

## License

Everything in this repository is licensed under CC BY-SA.

## `testprograms`
These are the mutualised tests from two years ago. 
Helpfully, a file was prepared to run them in series:
How to run:
- `chmod a+x testall`
- `./testall`
