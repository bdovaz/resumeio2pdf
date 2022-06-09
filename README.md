# resumeio2pdf

This program downloads resumes from [resume.io](https://resume.io/) and saves them in PDF format (including links).

## Usage

```bash
resumeio2pdf [options] [ID or URL]
```

Options:
*  `-pdf` (string)  name of pdf file (default: `SecureID` + `.pdf`)
*  `-sid` (string) SecureID of resume
*  `-url` (string) link to resume of the format: https://resume.io/r/SecureID
*  `-verbose` show detail information
*  `-version` show version
*  `-y`	overwrite PDF file

## How to build an executable file

In brief:
```bash
go build
```

If you don't understand, visit:
* [Download and install Go](https://go.dev/doc/install)
* [Compile and install the application](https://go.dev/doc/tutorial/compile-install)

## Docker

There is a complete example in [examples/docker](examples/docker).