# Cecilia ZeroOmega Rules

This repository hosts public domain rules for the Cecilia US HTTPS proxy.
Proxy credentials are intentionally not stored here.

## ZeroOmega setup

1. Create or select the local HTTPS proxy profile named `proxy`.
2. In the `auto switch` profile, enable `Rule list rules` and select `proxy`.
3. Keep the default profile set to `[Direct]`.
4. Under `Rule List Config`, select the `Switchy` format.
5. Set the Rule List URL to:

   ```text
   https://raw.githubusercontent.com/stephen198400/SwitchyOmega/main/rules/cecilia-us-sites.sorl
   ```

6. Click `Download Profile Now`, then apply the changes.

The list routes `.gov` and `.org` domains, common GIS services, Home Depot,
Yelp, Houzz, Claude, Claude Code on the web, Gemini, and Reddit through the
selected proxy profile. Other sites remain direct.
