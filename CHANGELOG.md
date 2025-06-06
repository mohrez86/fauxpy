# FauxPy Changelog

## FauxPy 0.7.0

- Update minimum supported Python version to 3.7.

## FauxPy 0.6.0

- Revise the documentation.
- Fix a bug in the handler that prevented CSV files from being saved.
- Revise help messages for command-line options.
- Update the `setup.py` description.
- Update the README file.
- Improve the order and structure of terminal reporting for FauxPy’s analysis.
- Add tests for the output reporting module.
- Revise printed messages.
- Fix a bug in the output reporting module that could cause PS to crash.
- Perform general refactoring.
- Added a new command-line option `--fauxpy-verbose`: when not 
  set, FauxPy displays minimal output.

## FauxPy 0.5.0

- Update the **Quick Start** guide to reflect the new reporting format.
- Enhance the `FauxpyPath` class and add corresponding tests.
- Perform minor refactoring.
- Improve the fault localization report output in the terminal.

## FauxPy 0.4.0

- Update the theme color in the documentation.
- Revise Example 2 in the Quick Start page of the documentation.
- Add test status badge to the README and documentation.
- Add GitHub Actions workflow to test FauxPy on Linux 
  and macOS with multiple Python versions.
- Implement two new strategies for the `GPT4o` model 
  and update the documentation accordingly.


## FauxPy 0.3.0

- Add documentation to the Makefile, explaining the purpose of each target for better contributor understanding.
- Add explanations about the new `--mutation` command line option 
  in the "Command Line Options" page of the FauxPy documentation.
- Add new example in the "Getting Started" page of the 
  FauxPy documentation demonstrating how to use
  LLM-driven MBFL techniques with the new `--mutation` 
  command line option.
- Add instructions to the installation guide for setting up an LLM API key.
- Extend the schema of the MBFL database to store PyLLMut results.
- Include mutation strategy in the report directory name.
- Change the format of the config and time files from plain text to JSON.
- Add support for LLM-driven mutation-based fault localization
  by integrating PyLLMut into FauxPy. This includes 
  the added `--mutation` command-line option to specify the mutation 
  strategy for MBFL techniques.
- Refactor some modules and add docstrings.
- Improve help messages for command-line options.
- Add shorthand options `--granularity s` and 
  `--granularity f` for `--granularity statement` 
  and `--granularity function`.
- Revise and improve documentation content.
- Migrate documentation from Sphinx to MkDocs.


## FauxPy 0.2.0

- Add entry for Analysis Mode.
- Refactor code structure.
- Add input validation for command-line arguments.
- Improve the Read the Docs
documentation.
- Update the README files in the
root and triangle example 
directory.
- Add `version.py` file to manage FauxPy's versioning.


## FauxPy 0.1.1

- Remove tests depending on FauxPy.
- Add Read the Docs documentation.
- Fix a bug in ST.
- Adopt the black code style.
- Add Triangle area example.
- Update readme.


## FauxPy 0.1

- The first release.
