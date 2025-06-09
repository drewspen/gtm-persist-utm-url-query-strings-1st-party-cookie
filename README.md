# gtm-persist-utm-url-query-strings-1st-party-cookie
GTM persist UTM URL query string parameters as 1st party cookies

JSON file that can be imported into GTM Google Tag Manager that persists the UTM URL query string parameters as first party cookies. The first for the _ga anonymous browser client id and current / last for the GA Google Analytics session are persisted. The purpose is to make the values available at any time during the session to be sent to Salesforce or Marketo or HubSpot as part of the lead form submission. Import into a GTM workspace. Uses the Cookie Creator GTM tag template to address CSP Content Security Policy SHA-256 issues. 
