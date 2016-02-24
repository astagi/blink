# Blink

## What?

With **blink** you can execute your commands and get the output from your **blink(1)** (https://blink1.thingm.com/)!

I developed this little script to receive an output from long running test suites.

## Install

You have to **enable API server** in the **Blink1Control** app and then put blink in your PATH env variable. It requires **curl** installed in your system.

## Usage

    $ blink command_you_want

## Customization

You can customize default colors or change the server endpoint using theses environment variables:

    BLINK_ENDPOINT (default = ""http://127.0.0.1:8934"")
    BLINK_SUCCESS_COLOR (default = "00ff00")
    BLINK_PROGRESS_COLOR (default = "ffcc00")
    BLINK_ERROR_COLOR (default "ff0000")

## License

MIT (c) Andrea Stagi 2016