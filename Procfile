web: /app/bin/plausible start
web-landing: /bin/busybox httpd -f -c /dev/null -p 8000 -h /app/landing
release: /app/bin/plausible eval Plausible.Release.interweave_migrate
