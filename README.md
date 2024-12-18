# firefox-stig-policy
This contains the Firefox policies.json for implementing the Mozilla Firefox STIG version 6.

This policy file will implement all finding IDs except for the following:
- V-251545: requires software version manager
- V-251550: needs further investigation

This file can be installed into /etc/firefox/policies on Linux or into $FIREFOX_BIN_DIR/distribution cross-platform.

Please see https://support.mozilla.org/en-US/kb/customizing-firefox-using-policiesjson for more information on this file.