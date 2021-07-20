For Chrome, to disable CORS, 
https://alfilatov.com/posts/run-chrome-without-cors/
cmd > open -n -a /Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --args --user-data-dir="/tmp/chrome_dev_test" --disable-web-security


For Firefox, to disable CORS, 
https://stackoverflow.com/questions/17088609/disable-firefox-same-origin-policy
about:config > security.fileuri.strict_origin_policy > false