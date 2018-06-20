---
swagger: "2.0"
x-collection-name: New Relic
x-complete: 0
info:
  title: New Relic Add Alerts External Service Conditions Policies Policy  . Format
  version: 1.0.0
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
basePath: v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /alerts_plugins_conditions/policies/{policy_id}.{format}:
    post:
      summary: Add Alerts Plugins Conditions Policies Policy  . Format
      description: "This API endpoint allows you to create Plugins conditions for
        your alert policies.\n\nNote: Admin User\u2019s API Key is required.\n\nSee
        our documentation for a discussion on creating conditions for plugins.\n\nAll
        fields are required except for \u201Crunbook_url\u201D, \u201Cenabled\u201D
        (defaults to false).\n\nname: A title for your condition.\n\nenabled: The
        status of your condition (optional).\n\nentities: An array of instance IDs
        associated with your condition.\n\nmetric_description: A title for the metric
        to display in notifications.\n\nmetric: The metric to evaluate on.\n\nvalue_function:
        min, max, average, sample_size, total, percent\n\nrunbook_url: Runbook URL
        to display in notifications (optional).\n\nterms[duration] (in minutes): 5,
        10, 15, 30, 60, 120.\n\nterms[operator]: above, below, equal.\n\nterms[priority]:
        critical, warning.\n\nterms[threshold]: Must be 0 or greater.\n\nterms[time_function]:
        all, any.\n\nplugin[id]: The ID of the plugin.\n\nplugin[guid]: The GUID of
        the plugin."
      operationId: postAlertsPluginsConditionsPoliciesPolicy.Format
      x-api-path-slug: alerts-plugins-conditionspoliciespolicy-id-format-post
      parameters:
      - in: body
        name: plugins_condition
        description: Condition schema
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: policy_id
        description: Alerts policy ID
        type: integer
      responses:
        200:
          description: OK
      tags:
      - Alerts
      - Plugins
      - Conditions
      - Policies
      - Policy
      - ""
      - .
      - Format
  /alerts_conditions/policies/{policy_id}.{format}:
    post:
      summary: Add Alerts Conditions Policies Policy  . Format
      description: "This API endpoint allows you to create conditions for your alert
        policies.\n\nNote: Admin User\u2019s API Key is required.\n\nSee our documentation
        for a discussion on creating conditions for policies.\n\n\nAll fields are
        required except for \u201Crunbook_url\u201D, \u201Cenabled\u201D (defaults
        to false), \u201Cuser_defined\u201D.\n\ntype: apm_app_metric, apm_kt_metric,
        servers_metric, browser_metric, mobile_metric.\n\nname: A title for your condition.\n\nenabled:
        The status of your condition (optional).\n\nentities: An array of instance
        IDs associated with your condition.\n\nmetric: The metric field accepts parameters
        based on the condition type selected as follows:\n\n\_\_When apm_app_metric:
        apdex, error_percentage, response_time_web, response_time_background, throughput_web,
        throughput_background, user_defined.\n\n\_\_When apm_kt_metric: apdex, error_percentage,
        error_count, response_time, throughput.\n\n\_\_When servers_metric: cpu_percentage,
        disk_io_percentage, memory_percentage, fullest_disk_percentage, load_average_one_minute,
        user_defined.\n\n\_\_When browser_metric: end_user_apdex, total_page_load,
        page_rendering, web_application, network, dom_processing, request_queuing,
        ajax_response_time, page_views_with_js_errors, page_view_throughput, ajax_throughput,
        user_defined.\n\n\_\_When mobile_metric: database, images, json, network,
        view_loading, network_error_percentage, status_error_percentage, mobile_crash_rate,
        user_defined.\n\nrunbook_url: Runbook URL to display in notifications (optional).\n\nterms[duration]
        (in minutes): 5, 10, 15, 30, 60, 120.\n\nterms[operator]: above, below, equal.\n\nterms[priority]:
        critical, warning.\n\nterms[threshold]: Must be 0 or greater.\n\nterms[time_function]:
        all, any.\n\nuser_defined[metric]: A custom metric to be evaluated.\n\nuser_defined[value_function]:
        average, min, max, total, sample_size."
      operationId: postAlertsConditionsPoliciesPolicy.Format
      x-api-path-slug: alerts-conditionspoliciespolicy-id-format-post
      parameters:
      - in: body
        name: condition
        description: Condition schema
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: policy_id
        description: Alerts policy ID
        type: integer
      responses:
        200:
          description: OK
      tags:
      - Alerts
      - Conditions
      - Policies
      - Policy
      - ""
      - .
      - Format
  /alerts_external_service_conditions/policies/{policy_id}.{format}:
    post:
      summary: Add Alerts External Service Conditions Policies Policy  . Format
      description: "This API endpoint allows you to create external service conditions
        for your alert policies.\n\nNote: Admin User\u2019s API Key is required.\n\nSee
        our documentation for a discussion on creating conditions for external services.\n\nAll
        fields are required except for \u201Crunbook_url\u201D, \u201Cenabled\u201D
        (defaults to false).\n\ntype: apm_external_service, mobile_external_service.\n\nname:
        A title for your condition.\n\nenabled: The status of your condition (optional).\n\nentities:
        An array of instance IDs associated with your condition.\n\nexternal_service_url:
        The URL of the external service. Must not include protocol (\u201Cexample.com\u201D,
        not \u201Chttps://example.com\u201D)\n\nmetric: The metric field accepts parameters
        based on the condition type selected as follows:\n\n\_\_When apm_external_service:
        response_time_average, response_time_minimum, response_time_maximum, throughput.\n\n\_\_When
        mobile_external_service: response_time_average, response_time_minimum, response_time_maximum,
        throughput, network_failure_percentage, http_status_error_percentage.\n\nrunbook_url:
        Runbook URL to display in notifications (optional).\n\nterms[duration] (in
        minutes): 5, 10, 15, 30, 60, 120.\n\nterms[operator]: above, below, equal.\n\nterms[priority]:
        critical, warning.\n\nterms[threshold]: Must be 0 or greater.\n\nterms[time_function]:
        all, any."
      operationId: postAlertsExternalServiceConditionsPoliciesPolicy.Format
      x-api-path-slug: alerts-external-service-conditionspoliciespolicy-id-format-post
      parameters:
      - in: body
        name: external_service_condition
        description: Condition schema
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: policy_id
        description: Alerts policy ID
        type: integer
      responses:
        200:
          description: OK
      tags:
      - Alerts
      - External
      - Service
      - Conditions
      - Policies
      - Policy
      - ""
      - .
      - Format
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---