# What is this?
Handlers for frida that will allow you to log requests outgoing request from an app on your iphone.

# How to use?
- `git clone https://github.com/ivanhrabcak/frida-request-logging.git`
- `cd frida-request-logging`
- Connect your jailbroken iphone
- `frida-trace -m  "-[NSURLSession dataTaskWithRequest*]" -U -f <app_bundle_id>`