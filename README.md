# withings-relay

Withings only sends you back to a public HTTPS address after you approve access. This one-page site
receives that redirect and forwards the one-time code to the Withings Sync app on my home network
(`homeassistant.local:8099`), which exchanges it straight away. Nothing is stored here.
