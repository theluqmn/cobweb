# Cobweb

A GnuCOBOL compilation tool developed using bash script.

## Features

- User-friendly, and colorised.
- Locates all COBOL files in the specified directory.
- Separates the main COBOL file from its subprograms.
- Eases development of modularised COBOL programs.
- Uses user-installed GnuCOBOL.
- Cleans up after compilation.

## Usage

Cobweb has the following parameters: `./cobweb {arg_output} {arg_main} {arg_directory}`

> [!NOTE]
> All of the following parameters are optional.

1. `arg_output`: name of the resulting executable. Default: `main`
2. `arg_main`: location of the main COBOL file. Default: `main.cbl`
3. `arg_directory`: directory of the project. Defaults to the current directory of the terminal session.

## Notes

- Cobweb is originally developed to assist in the development of [Timecard](https://github.com/theluqmn/timecard), and both projects are developed for [Hack Club](https://hackclub.com)'s [Flavourtown](https://flavourtown.hackclub.com) event.
- This project is licensed under the MIT License.
