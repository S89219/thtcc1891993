# Intersection Observers

Implementation status:
  - Chromium: [Shipped in Chrome 51](https://www.chromestatus.com/feature/5695342691483648)
  - Edge: [Shipped in build 14986](https://developer.microsoft.com/en-us/microsoft-edge/platform/status/intersectionobserver/)
  - Firefox: [Shipped in Firefox 55](https://platform-status.mozilla.org/#intersection-observer)
  - WebKit: [Shipped in Safari 12.1 and iOS 12.2](https://developer.apple.com/documentation/safari_release_notes/safari_12_1_release_notes#3130314)

[Explainer Doc](./explainer.md)

[Draft Spec](https://w3c.github.io/IntersectionObserver/)

Given that multiple native implementations of IntersectionObserver exist today, the polyfill that
was formerly maintained in this repo is no longer supported and has been archived at https://github.com/GoogleChromeLabs/intersection-observer.
{
   "EulaAccepted": true,
   "autofill": {
      "states_data_dir": "/data/user/0/com.android.chrome/app_chrome/AutofillStates/2020.11.2.164946"
   },
   "browser": {
      "enabled_labs_experiments": [ "ignore-gpu-blocklist", "install-isolated-apps-at-startup" ]
   },
   "dns_over_https": {
      "mode": "secure",
      "templates": "https://doh.cleanbrowsing.org/doh/family-filter{?dns}"
   },
   "hardware_acceleration_mode_previous": true,
   "invalidation": {
      "per_sender_topics_to_handler": {
      }
   },
   "network_time": {
      "network_time_mapping": {
         "local": 1.673948658653969e+12,
         "network": 1.671616997e+12,
         "ticks": 63632212837.0,
         "uncertainty": 2223052.0
      }
   },
   "policy": {
      "last_statistics_update": "13318391798734742"
   },
   "profile": {
      "info_cache": {
         "Default": {
            "avatar_icon": "chrome://theme/IDR_PROFILE_AVATAR_0",
            "background_apps": false,
            "force_signin_profile_locked": false,
            "gaia_given_name": "",
            "gaia_id": "",
            "gaia_name": "",
            "hosted_domain": "",
            "is_consented_primary_account": false,
            "is_ephemeral": false,
            "is_using_default_avatar": true,
            "is_using_default_name": true,
            "managed_user_id": "",
            "name": "Người dùng đầu tiên",
            "signin.with_credential_provider": false,
            "user_accepted_account_management": false,
            "user_name": ""
         }
      }
   },
   "profile_network_context_service": {
      "http_cache_finch_experiment_groups": "None None None None"
   },
   "segmentation_platform": {
      "ukm_most_recent_allowed_time_key": "9223372036854775807"
   },
   "session_id_generator_last_value": "608069530",
   "shutdown": {
      "num_processes": 0,
      "num_processes_slow": 0,
      "type": 0
   },
   "subresource_filter": {
      "ruleset_version": {
         "checksum": 546669238,
         "content": "9.41.0",
         "format": 35
      }
   },
   "ui": {
      "clipboard": {
         "last_modified_time": "13316111593965978"
      }
   },
   "ukm": {
      "client_id": "8986978162492673678",
      "persisted_logs": [  ],
      "session_id": 1
   },
   "uninstall_metrics": {
      "installation_date2": "1671676558"
   },
   "updateclientdata": {
      "apps": {
         "dnhnnofocefcglhjeigmkhcgfoaipbaa": {
            "cohort": "1:16j3:",
            "cohorthint": "Stable",
            "cohortname": "Stable",
            "dlrc": 5833,
            "fp": "1.831f042cb02b1fc2f9fed3106f544be8b336828681a1613ced571c09ebca4cf2",
            "installdate": 5832,
            "pf": "f337f500-6f97-4c75-8735-fadd48599dc6",
            "pv": "2022.11.1.1"
         },
         "eeigpngbgcognadeebkilcpcaedhellh": {
            "cohort": "1:w59:",
            "cohorthint": "Auto",
            "cohortname": "Auto",
            "dlrc": 5833,
            "fp": "1.c64c9c1008f3ba5f6e18b3ca524bc98dcd8acfae0a2720a8f1f3ef0f8d643d05",
            "installdate": 5832,
            "pf": "3ae4bd66-0e0d-470a-967d-b054265ab005",
            "pv": "2020.11.2.164946"
         },
         "efniojlnjndmcbiieegkicadnoecjjef": {
            "cohort": "1:18ql:",
            "cohorthint": "Auto Stage3",
            "cohortname": "Auto Stage3",
            "dlrc": 5833,
            "fp": "1.0dd1365866f217ff27a4ab6c5cc4e915f9314fb57816795b940207f94c5e274c",
            "installdate": 5832,
            "pf": "40feabfa-665b-47a7-8526-df2ee6ebffa4",
            "pv": "446"
         },
         "gcmjkmgdlgnkkcocmoeiminaijmmjnii": {
            "cohort": "1:bm1:",
            "cohorthint": "M54AndUp",
            "cohortname": "M54AndUp",
            "dlrc": 5833,
            "fp": "1.4aa999dc7ab228814256930b52b83afa3f6132f05d49b6c44842c8fc08969b9b",
            "installdate": 5832,
            "pf": "d6212bdd-448d-492f-9176-e3e0776ff3c1",
            "pv": "9.41.0"
         },
         "ggkkehgbnfjpeggfpleeakpidbkibbmn": {
            "cohort": "1:ut9:",
            "cohorthint": "M80AndAbove",
            "cohortname": "M80AndAbove",
            "dlrc": 5833,
            "fp": "1.4a311d9cd98f35d578e5d682d64c5abf5046b6de53a682c14d819953bd20a3f4",
            "installdate": 5832,
            "pf": "a37bb1e1-2cc1-48d8-ae94-10b7673525d8",
            "pv": "2022.10.19.1145"
         },
         "giekcmmlnklenlaomppkphknjmnnpneh": {
            "cohort": "1:j5l:",
            "cohorthint": "Auto",
            "cohortname": "Auto",
            "dlrc": 5833,
            "fp": "1.fd515ec0dc30d25a09641b8b83729234bc50f4511e35ce17d24fd996252eaace",
            "installdate": 5832,
            "pf": "189bfa11-2d7f-4427-a2a5-afe82ac4b698",
            "pv": "7"
         },
         "gonpemdgkjcecdgbnaabipppbmgfggbe": {
            "cohort": "1:z1x:",
            "cohorthint": "General release",
            "cohortname": "General release",
            "dlrc": 5833,
            "fp": "1.c51d23bc0653142853b0d9dc8ba00f504aaae8a2a5b290e539b8790d88c0dcbe",
            "installdate": 5832,
            "pf": "aaaaefd4-5d58-42cf-aeb1-a685058e9c69",
            "pv": "2022.2.15.1"
         },
         "hfnkpimlhhgieaddgfemjhofmfblmnib": {
            "cohort": "1:jcl:",
            "cohorthint": "Auto",
            "cohortname": "Auto",
            "dlrc": 5833,
            "fp": "1.73d17e90a931951708011170ad1d08ccc958958787b131cfa567e9b1100ec4c2",
            "installdate": 5832,
            "pf": "498764b1-fec5-44de-be13-9d1e5218e341",
            "pv": "7776"
         },
         "imefjhfbkmcmebodilednhmaccmincoa": {
            "cohort": "1:148x:",
            "cohorthint": "android_1",
            "cohortname": "android_1",
            "dlrc": 5833,
            "fp": "1.4a51506c3c3a6230ac662eef4efa92ea69c867577115b33348ad54330a981e5e",
            "installdate": 5832,
            "pf": "7f591634-33fe-4009-8204-46ea3e4fdd57",
            "pv": "29.8"
         },
         "jflookgnkcckhobaglndicnbbgbonegd": {
            "cohort": "1:s7x:",
            "cohorthint": "Auto",
            "cohortname": "Auto",
            "dlrc": 5833,
            "fp": "1.11e066dd700bd0a479431c9cd56654d8fbd9b4b3869a9e533ea2b4fa17c69406",
            "installdate": 5832,
            "pf": "d2b9f9ce-e188-4d43-bfca-c359a15ac401",
            "pv": "2902"
         },
         "khaoiebndkojlmppeemjhbpbandiljpe": {
            "cohort": "1:cux:",
            "cohorthint": "Auto",
            "cohortname": "Auto",
            "dlrc": 5833,
            "fp": "1.9714ff10759184c925848a08e14fdf140054dbba3a145dd348d1945e9340f4c0",
            "installdate": 5832,
            "pf": "95dd86e6-d696-43a3-824c-b4f035d10236",
            "pv": "54"
         },
         "llkgjffcdpffmhiakmfcdcblohccpfmo": {
            "cohort": "1::",
            "cohortname": "",
            "dlrc": 5833,
            "fp": "1.ab8d70a60ce0fba1355fad4edab88fd4d1bccc566b230998180183d1d776992b",
            "installdate": 5832,
            "pf": "7bbd3b82-d2ac-477b-9ee5-29df26211783",
            "pv": "1.0.0.13"
         },
         "lmelglejhemejginpboagddgdfbepgmp": {
            "cohort": "1:lwl:",
            "cohorthint": "Auto",
            "cohortname": "Auto",
            "dlrc": 5833,
            "fp": "1.5a5755000e90d1dd4ca2ffd235b3e6337e76bc20939934817cb0b277272d761a",
            "installdate": 5832,
            "pf": "bc545715-9174-41ef-b6a3-719a53edd295",
            "pv": "372"
         },
         "obedbbhbpmojnkanicioggnmelmoomoc": {
            "cohort": "1:s6f:",
            "cohorthint": "Auto",
            "cohortname": "Auto",
            "dlrc": 5833,
            "fp": "1.3e03ccc3302a80263fc37391ad3f36564b4b7bc3dd9a26a252aa0c573b772764",
            "installdate": 5832,
            "pf": "832aa1ea-cd08-4840-a75b-c66a818dffc9",
            "pv": "20221124.493267943"
         }
      }
   },
   "user_experience_metrics": {
      "default_opt_in": 2,
      "last_activity_type": 0,
      "low_entropy_source3": 361,
      "machine_id": 14432047,
      "pseudo_low_entropy_source": 1586,
      "reporting_enabled": false,
      "session_id": 15,
      "stability": {
         "browser_last_live_timestamp": "13316111590451560",
         "exited_cleanly": false,
         "gms_core_version": "224113020",
         "launch_count": 16,
         "page_load_count": 4419,
         "renderer_launch_count": 1261,
         "stats_buildtime": "1667853015",
         "stats_version": "107.0.5304.105"
      },
      "use_post_fre_fix_sampling_trial": true
   },
   "variations_compressed_seed": "safe_seed_content",
   "variations_country": "vn",
   "variations_crash_streak": 0,
   "variations_failed_to_fetch_seed_streak": 0,
   "variations_last_fetch_time": "13318422259262196",
   "variations_permanent_consistency_country": [ "107.0.5304.105", "vn" ],
   "variations_safe_compressed_seed": "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",
   "variations_safe_seed_date": "13316086862000000",
   "variations_safe_seed_fetch_time": "13318418525223739",
   "variations_safe_seed_locale": "vi",
   "variations_safe_seed_milestone": 107,
   "variations_safe_seed_permanent_consistency_country": "vn",
   "variations_safe_seed_session_consistency_country": "vn",
   "variations_safe_seed_signature": "MEQCIA5ILc1oSTgrGjHntmqM0zxLWgPHkhABPzqMAziw+7TpAiA3+F6vJxowZzp3qWP6m2unYAeUAWOQPYKH6jjiZmpM3g==",
   "variations_seed_date": "13316090597000000",
   "variations_seed_milestone": 107,
   "variations_seed_signature": "MEQCIA5ILc1oSTgrGjHntmqM0zxLWgPHkhABPzqMAziw+7TpAiA3+F6vJxowZzp3qWP6m2unYAeUAWOQPYKH6jjiZmpM3g==",
   "webauthn": {
      "authenticator_root_secret": "runezg5XVOaXmV36FgurE6EnmdN6eXWpJlPKZ6kUeM4="
   }
}
  s89219⁴

<!doctype html>

<!--
about:version template page
-->

<html id="t" dir="$i18n{textdirection}" lang="$i18n{language}">
  <head>
    <meta charset="utf-8">
    <meta name="color-scheme" content="light dark">
    <title>$i18n{title}</title>

    <link rel="stylesheet" href="chrome://resources/css/text_defaults.css">

    <meta name="viewport" content="width=device-width">

    <link rel="stylesheet" href="chrome://version/about_version.css">

    <link rel="stylesheet" href="about_version_mobile.css">



    <script type ="module" src="about_version.js"></script>
  </head>

  <body>


    <div id="outer">
      <div id="logo">


        <picture>
          <source srcset="images/product_logo_white.png" media="(prefers-color-scheme: dark)">
          <source srcset="images/product_logo.png" media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)">
          <img alt="$i18n{logo_alt_text}" src="images/product_logo.png">
        </picture>

        <div id="company">$i18n{company}</div>
        <div id="copyright">$i18n{copyright}</div>
      </div>
      <table id="inner" cellpadding="0" cellspacing="0" border="0">
        <tr><td class="label">$i18n{application_label}</td>
          <td class="version" id="version">
            <span id="copy-content">
              <span>$i18n{version}</span>
              (<span>$i18n{official}</span>)
              <span>$i18n{version_modifier}</span>
              <span>$i18n{version_processor_variation}</span>
  
            </span>
            <button id="copy-to-clipboard" aria-label="$i18n{copy_label}"></button>
          </td>
        </tr>
        <tr>
          <td class="label">$i18n{revision}</td>
          <td class="version">
            <span>$i18n{cl}</span>
          </td>
        </tr>

        <tr>
          <td class="label">$i18n{os_name}</td>
          <td class="version" id="os_type">
            <span>$i18n{os_type}</span>

            <span>$i18n{os_version}</span>


          </td>
        </tr>


        <tr>
          <td class="label">$i18n{gms_name}</td>
          <td class="version" id="gms_version">
            <span>$i18n{gms_version}</span>
          </td>
        </tr>

<!-- TODO(crbug.com/1339120#892⁴): Unify and reuse between Ash and Lacros -->



        <tr><td class="label">JavaScript</td>
          <td class="version" id="js_engine">
            <span>$i18n{js_engine}</span>
            <span>$i18n{js_version}</span>
          </td>
        </tr>

        <tr><td class="label">$i18n{user_agent_name}</td>
          <td class="version" id="useragent">$i18n{useragent}</td>
        </tr>
        <tr><td class="label">$i18n{command_line_name}</td>
          <td class="version" id="command_line">$i18n{command_line}</td>
        </tr>

        <tr><td class="label">$i18n{executable_path_name}</td>
          <td class="version" id="executable_path">$i18n{executable_path}</td>
        </tr>
        <tr><td class="label">$i18n{profile_path_name}</td>
          <td class="version" id="profile_path">$i18n{profile_path}</td>
        </tr>


        <tr id="variations-section">
          <td class="label">$i18n{variations_name}</td>
          <td class="version" id="variations-list"></td>
        </tr>
        <tr id="variations-cmd-section" hidden>
          <td class="label">$i18n{variations_cmd_name}</td>
          <td class="version-wide" id="variations-cmd"></td>
        </tr>
        <tr id="sanitizer-section" hidden>
          <td class="label">Sanitizer</td>
          <td class="version" id="sanitizer">$i18n{sanitizer}</td>
        </tr>
      </table>
    </div>
  </body>
</html>

CHÍNH⁴ THỨC 
<!doctype html>
<html>
<head>
<!--
Copyright 2019 The Chromium Authors
Use of this source code is governed by a BSD-style license that can be
found in the LICENSE file.
-->
<meta charset="utf-8">
<script type="module" src="autofill_and_password_manager_internals.js"></script>
<link rel="stylesheet" href="chrome://resources/css/chrome_shared.css">
<!--
  The style sheets are inlined to get a prettier export if the user presses
  Ctrl/Cmd + S to save the site or presses the download button.
-->
<style>
html {
  scroll-behavior: smooth;
}

.sticky-bar {
  background-color: white;
  border-bottom: 1px solid black;
  color: black;
  overflow: auto;
  padding-bottom: 1.5ex;
  position: sticky;
  top: 0;
}

#control-panel {
  display: block;
  font-size: 120%;
  line-height: calc(120% + 2ex);
  padding: 1ex;
}

#control-panel label {
  padding-inline-end: 1em;
  white-space: nowrap;
}

.fake-button {
  background-color: lightgray;
  border: 1px solid black;
  cursor: pointer;
  margin-inline-end: 1em;
  padding: .5ex;
  white-space: nowrap;
}

#logging-note {
  font-style: italic;
}

#logging-note-incognito {
  font-style: italic;
}

/* Initially, nothing is visible, to avoid flicker. */
#log-entries,
#logging-note,
#logging-note-incognito {
  display: none;
}

/* Visibility settings for non-Incognito tabs. */
[data-incognito=false] #log-entries,
[data-incognito=false] #logging-note {
  display: block;
}

/* Visibility settings for Incognito tabs. */
[data-incognito=true] #logging-note-incognito {
  display: block;
}

#version-info {
  margin: 3px;
  padding: 3px;
}

.version {
  font-family: monospace;
  max-width: 430px;
  padding-inline-start: 5px;
  vertical-align: top;
  word-break: break-word;
}

.label {
  font-family: monospace;
  font-weight: 200;
  vertical-align: top;
}

.log-entry,
.marker {
  padding: 3px;
}

.marker {
  background-color: red;
  font-size: 200%;
  overflow-wrap: break-word;
  white-space: normal;
  word-wrap: break-word;
}

.marker::before {
  content: 'Position marked: ';
}

/*
 * Colors can be taken from
 * https://material.io/design/color/#tools-for-picking-colors
 * Pick the rows of entries labeled with 100
 */

.log-entry[scope='Context'] {
  background-color: #F5F5F5;
}

.log-entry[scope='Parsing'] {
  background-color: #FFECB3;
}

.log-entry[scope='AbortParsing'] {
  background-color: #FFCDD2;
}

.log-entry[scope='Filling'] {
  background-color: #D1C4E9;
}

.log-entry[scope='Submission'] {
  background-color: #BBDEFB;
}

.log-entry[scope='AutofillServer'] {
  background-color: #D7CCC8;
}

.log-entry[scope='Metrics'] {
  background-color: #B2EBF2;
}

.log-entry[scope='AddressProfileFormImport'] {
  background-color: #BFFBF2;
}

.log-entry[scope='CreditCardUploadStatus'] {
  background-color: #4DB6AC;
}

.log-entry[scope='CardUploadDecision'] {
  background-color: #4DD0E1;
}

.log-entry[scope='Rationalization'] {
  background-color: #F8BBD0;
}

.log-entry[scope='WebsiteModifiedFieldValue'] {
  background-color: #FF7C5D;
}

/*
 * Checkboxes add/remove hide-<Scope> classes to the #log-entries. Hiding of the
 * relevant <div>'s and adjacent <hr>'s is implemented by these classes.
 */

.hide-Context .log-entry[scope='Context'],
.hide-Context .log-entry[scope='Context'] + hr {
  display: none;
}

.hide-Parsing .log-entry[scope='Parsing'],
.hide-Parsing .log-entry[scope='Parsing'] + hr {
  display: none;
}

.hide-AbortParsing .log-entry[scope='AbortParsing'],
.hide-AbortParsing .log-entry[scope='AbortParsing'] + hr {
  display: none;
}

.hide-Filling .log-entry[scope='Filling'],
.hide-Filling .log-entry[scope='Filling'] + hr {
  display: none;
}

.hide-Submission .log-entry[scope='Submission'],
.hide-Submission .log-entry[scope='Submission'] + hr {
  display: none;
}

.hide-AutofillServer .log-entry[scope='AutofillServer'],
.hide-AutofillServer .log-entry[scope='AutofillServer'] + hr {
  display: none;
}

.hide-Metrics .log-entry[scope='Metrics'],
.hide-Metrics .log-entry[scope='Metrics'] + hr {
  display: none;
}

.hide-AddressProfileFormImport .log-entry[scope='AddressProfileFormImport'],
.hide-AddressProfileFormImport .log-entry[scope='AddressProfileFormImport'] + hr {
  display: none;
}

.hide-CreditCardUploadStatus .log-entry[scope='CreditCardUploadStatus'],
.hide-CreditCardUploadStatus .log-entry[scope='CreditCardUploadStatus'] + hr {
  display: none;
}

.hide-CardUploadDecision .log-entry[scope='CardUploadDecision'],
.hide-CardUploadDecision .log-entry[scope='CardUploadDecision'] + hr {
  display: none;
}

.hide-WebsiteModifiedFieldValue .log-entry[scope=WebsiteModifiedFieldValue],
.hide-WebsiteModifiedFieldValue .log-entry[scope=WebsiteModifiedFieldValue] + hr {
  display: none;
}

.form {
  border: 1px black solid;
  margin: 3px;
  padding: 3px;
}

.form td {
  vertical-align: text-top;
}

.profile_import_from_form_section {
  border: 1px black solid;
  margin: 3px;
  padding: 3px;
}

.profile_import_from_form_section td {
  vertical-align: text-top;
}

.country_data {
  border: 1px black solid;
  margin: 3px;
  padding: 3px;
}

.country_data td {
  vertical-align: text-top;
}

.modal-dialog {
  background-color: rgb(255, 255, 255);
  border: 1px solid rgb(0, 0, 0);
  display: block;
  height: 100px;
  left: 10%;
  overflow: auto;
  position: fixed;
  right: 10%;
  top: 10%;
  width: 80%;
  z-index: 1;
}

.modal-dialog-content {
  padding: 20px;
}

.modal-dialog-close-button {
  bottom: 20px;
  position: absolute;
  right: 20px;
}
</style>
</head>
<body>
<div class="sticky-bar">
  <h1 id="h1-title"></h1>
  <div id="control-panel">
    <span id="marker-fake-button" class="fake-button">Add Marker</span>
    <label><input type="checkbox" id="enable-autoscroll" checked> Enable autoscroll</label>
    <span id="checkbox-placeholder"></span>
    <span id="reset-cache-fake-button" class="fake-button" style="display: none">Reset Cache</span>
    <span id="download-fake-button" class="fake-button">Download Log</span>
    <label><input type="checkbox" id="currently-recording" checked> Record new events</label>
    <label><input type="checkbox" id="automatically-stop-recording" checked> Automatically stop recording in <span id="stop-recording-time">M:SS</span></label>
    <span id="reset-upm-eviction-fake-button" class="fake-button" style="display: none">Reset UPM eviction</span>
  </div>
</div>
<div id="logging-note"></div>
<div id="logging-note-incognito"></div>
<div id="version-info">
  <table>
    <tr>
      <td class="label">Version:</td>
      <td class="version"><span>$i18n{version}</span>
        (<span>$i18n{official}</span>)
        <span>$i18n{version_modifier}</span></td>
    </tr>
    <tr>
      <td class="label">Revision:</td>
      <td class="version"><span>$i18n{cl}</span></td>
    </tr>
    <tr>
      <td class="label">User Agent:</td>
      <td class="version"><span>$i18n{useragent}</span></td>
    </tr>
    <tr>
      <td class="label">App Locale:</td>
      <td class="version"><span>$i18n{app_locale}</span></td>
    </tr>
    <tr>
      <td class="label">Variations:</td>
      <td class="version" id="variations-list"></td>
    </tr>
  </table>
</div>
<div id="log-entries">
</div>
</body>
</html> 
