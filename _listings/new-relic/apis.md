---
name: New Relic
x-slug: new-relic
description: New Relic???s digital intelligence platform lets developers, ops, and
  tech teams measure and monitor the performance of their applications and infrastructure.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
x-kinRank: "8"
x-alexaRank: "10322"
tags: Policies
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/new-relic/apis.md
specificationVersion: "0.14"
apis:
- name: New Relic Add Alerts Plugins Conditions Policies Policy  . Format
  x-api-slug: new-relic
  description: "This API endpoint allows you to create Plugins conditions for your
    alert policies.\n\nNote: Admin User\u2019s API Key is required.\n\nSee our documentation
    for a discussion on creating conditions for plugins.\n\nAll fields are required
    except for \u201Crunbook_url\u201D, \u201Cenabled\u201D (defaults to false).\n\nname:
    A title for your condition.\n\nenabled: The status of your condition (optional).\n\nentities:
    An array of instance IDs associated with your condition.\n\nmetric_description:
    A title for the metric to display in notifications.\n\nmetric: The metric to evaluate
    on.\n\nvalue_function: min, max, average, sample_size, total, percent\n\nrunbook_url:
    Runbook URL to display in notifications (optional).\n\nterms[duration] (in minutes):
    5, 10, 15, 30, 60, 120.\n\nterms[operator]: above, below, equal.\n\nterms[priority]:
    critical, warning.\n\nterms[threshold]: Must be 0 or greater.\n\nterms[time_function]:
    all, any.\n\nplugin[id]: The ID of the plugin.\n\nplugin[guid]: The GUID of the
    plugin."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
  humanURL: https://newrelic.com/
  baseURL: https:///v2///alerts_plugins_conditions/policies/{policy_id}.{format}
  tags: Alerts, Plugins, Conditions, Policies, Policy, , ., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/new-relic/alerts-plugins-conditionspoliciespolicy-id-format-post-openapi.md
- name: New Relic Add Alerts Conditions Policies Policy  . Format
  x-api-slug: new-relic
  description: "This API endpoint allows you to create conditions for your alert policies.\n\nNote:
    Admin User\u2019s API Key is required.\n\nSee our documentation for a discussion
    on creating conditions for policies.\n\n\nAll fields are required except for \u201Crunbook_url\u201D,
    \u201Cenabled\u201D (defaults to false), \u201Cuser_defined\u201D.\n\ntype: apm_app_metric,
    apm_kt_metric, servers_metric, browser_metric, mobile_metric.\n\nname: A title
    for your condition.\n\nenabled: The status of your condition (optional).\n\nentities:
    An array of instance IDs associated with your condition.\n\nmetric: The metric
    field accepts parameters based on the condition type selected as follows:\n\n\_\_When
    apm_app_metric: apdex, error_percentage, response_time_web, response_time_background,
    throughput_web, throughput_background, user_defined.\n\n\_\_When apm_kt_metric:
    apdex, error_percentage, error_count, response_time, throughput.\n\n\_\_When servers_metric:
    cpu_percentage, disk_io_percentage, memory_percentage, fullest_disk_percentage,
    load_average_one_minute, user_defined.\n\n\_\_When browser_metric: end_user_apdex,
    total_page_load, page_rendering, web_application, network, dom_processing, request_queuing,
    ajax_response_time, page_views_with_js_errors, page_view_throughput, ajax_throughput,
    user_defined.\n\n\_\_When mobile_metric: database, images, json, network, view_loading,
    network_error_percentage, status_error_percentage, mobile_crash_rate, user_defined.\n\nrunbook_url:
    Runbook URL to display in notifications (optional).\n\nterms[duration] (in minutes):
    5, 10, 15, 30, 60, 120.\n\nterms[operator]: above, below, equal.\n\nterms[priority]:
    critical, warning.\n\nterms[threshold]: Must be 0 or greater.\n\nterms[time_function]:
    all, any.\n\nuser_defined[metric]: A custom metric to be evaluated.\n\nuser_defined[value_function]:
    average, min, max, total, sample_size."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
  humanURL: https://newrelic.com/
  baseURL: https:///v2///alerts_conditions/policies/{policy_id}.{format}
  tags: Alerts, Conditions, Policies, Policy, , ., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/new-relic/alerts-conditionspoliciespolicy-id-format-post-openapi.md
- name: New Relic Add Alerts External Service Conditions Policies Policy  . Format
  x-api-slug: new-relic
  description: "This API endpoint allows you to create external service conditions
    for your alert policies.\n\nNote: Admin User\u2019s API Key is required.\n\nSee
    our documentation for a discussion on creating conditions for external services.\n\nAll
    fields are required except for \u201Crunbook_url\u201D, \u201Cenabled\u201D (defaults
    to false).\n\ntype: apm_external_service, mobile_external_service.\n\nname: A
    title for your condition.\n\nenabled: The status of your condition (optional).\n\nentities:
    An array of instance IDs associated with your condition.\n\nexternal_service_url:
    The URL of the external service. Must not include protocol (\u201Cexample.com\u201D,
    not \u201Chttps://example.com\u201D)\n\nmetric: The metric field accepts parameters
    based on the condition type selected as follows:\n\n\_\_When apm_external_service:
    response_time_average, response_time_minimum, response_time_maximum, throughput.\n\n\_\_When
    mobile_external_service: response_time_average, response_time_minimum, response_time_maximum,
    throughput, network_failure_percentage, http_status_error_percentage.\n\nrunbook_url:
    Runbook URL to display in notifications (optional).\n\nterms[duration] (in minutes):
    5, 10, 15, 30, 60, 120.\n\nterms[operator]: above, below, equal.\n\nterms[priority]:
    critical, warning.\n\nterms[threshold]: Must be 0 or greater.\n\nterms[time_function]:
    all, any."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
  humanURL: https://newrelic.com/
  baseURL: https:///v2///alerts_external_service_conditions/policies/{policy_id}.{format}
  tags: Alerts, External, Service, Conditions, Policies, Policy, , ., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/new-relic/alerts-external-service-conditionspoliciespolicy-id-format-post-openapi.md
- name: New Relic Add Alerts Synthetics Conditions Policies Policy  . Format
  x-api-slug: new-relic
  description: "This API endpoint allows you to create Synthetics conditions for your
    alert policies.\n\nNote: Admin User\u2019s API Key is required.\n\nSee our documentation
    for a discussion on creating Synthetic conditions.\n\nAll fields are required
    except for \u201Crunbook_url\u201D, \u201Cenabled\u201D (defaults to false).\n\nname:
    A title for your condition.\n\nmonitor_id: The GUID of the Synthetics monitor
    to alert on.\n\nrunbook_url: Runbook URL to display in notifications (optional).\n\nenabled:
    The status of your condition (optional)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
  humanURL: https://newrelic.com/
  baseURL: https:///v2///alerts_synthetics_conditions/policies/{policy_id}.{format}
  tags: Alerts, Synthetics, Conditions, Policies, Policy, , ., Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/new-relic/alerts-synthetics-conditionspoliciespolicy-id-format-post-openapi.md
- name: New Relic
  x-api-slug: new-relic
  description: New Relic???s digital intelligence platform lets developers, ops, and
    tech teams measure and monitor the performance of their applications and infrastructure.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22963-new-relic.jpg
  humanURL: https://newrelic.com/
  baseURL: https:///v2/
  tags: Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/policies/master/_listings/new-relic/openapi.md
x-common:
- type: x-blog
  url: https://blog.newrelic.com/
- type: x-blog-rss
  url: https://blog.newrelic.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/new-relic
- type: x-developer
  url: https://rpm.newrelic.com/api/explore/
- type: x-email
  url: billing@newrelic.com
- type: x-email
  url: resume@newrelic.com
- type: x-email
  url: PR@newrelic.com
- type: x-email
  url: copyright@newrelic.com
- type: x-email
  url: dataprivacy@newrelic.com
- type: x-email
  url: PersonalDataRequest@newrelic.com
- type: x-email
  url: support@newrelic.com
- type: x-email
  url: compliance@newrelic.com
- type: x-github
  url: https://github.com/newrelic
- type: x-twitter
  url: https://twitter.com/NewRelic
- type: x-website
  url: https://newrelic.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---