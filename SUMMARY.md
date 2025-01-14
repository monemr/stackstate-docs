# Table of contents

* [Welcome to the StackState Docs!](README.md)

## 🚀 Setup

* [Requirements](setup/requirements.md)
* [Installation](setup/installation/README.md)
  * [Kubernetes install](setup/installation/kubernetes_install/README.md)
    * [Install StackState](setup/installation/kubernetes_install/install_stackstate.md)
    * [Required Permissions](setup/installation/kubernetes_install/required_permissions.md)
    * [Development setup](setup/installation/kubernetes_install/development_setup.md)
    * [Override default configuration](setup/installation/kubernetes_install/customize_config.md)
    * [Configure storage](setup/installation/kubernetes_install/storage.md)
    * [Configure Ingress](setup/installation/kubernetes_install/ingress.md)
    * [StackState images](setup/installation/kubernetes_install/image_configuration.md)
    * [Migrate from Linux install](setup/installation/kubernetes_install/migrate_from_linux.md)
    * [AAD Standalone Deployment](setup/installation/kubernetes_install/aad_standalone.md)
  * [Linux install](setup/installation/linux_install/README.md)
    * [Before you install](setup/installation/linux_install/before_you_install.md)
    * [Download](setup/installation/linux_install/download.md)
    * [Install StackState](setup/installation/linux_install/install_stackstate.md)
    * [Install with production configuration](setup/installation/linux_install/production-installation.md)
    * [Install with development configuration](setup/installation/linux_install/development-installation.md)
    * [Install with POC configuration](setup/installation/linux_install/poc-installation.md)
    * [Set up a reverse proxy](setup/installation/linux_install/reverse_proxy.md)
    * [Set up TLS without reverse proxy](setup/installation/linux_install/how_to_setup_tls_without_reverse_proxy.md)
  * [OpenShift install](setup/installation/openshift_install.md)
  * [Initial run guide](setup/installation/initial_run_guide.md)
  * [StackState CLI](setup/installation/cli-install.md)
  * [Troubleshooting](setup/installation/troubleshooting.md)
* [Data management](setup/data-management/README.md)
  * [Backup and Restore](setup/data-management/backup_restore/README.md)
    * [Kubernetes backup](setup/data-management/backup_restore/kubernetes_backup.md)
    * [Linux backup](setup/data-management/backup_restore/linux_backup.md)
    * [Configuration backup](setup/data-management/backup_restore/configuration_backup.md)
    * [Manually created topology backup](setup/data-management/backup_restore/manual_topology_backup.md)
  * [Data retention](setup/data-management/data_retention.md)
  * [Clear stored data](setup/data-management/clear_stored_data.md)
* [Upgrade StackState](setup/upgrade-stackstate/README.md)
  * [Steps to upgrade](setup/upgrade-stackstate/steps-to-upgrade.md)
  * [Version specific upgrade instructions](setup/upgrade-stackstate/version-specific-upgrade-instructions.md)
  * [StackPack versions](setup/upgrade-stackstate/stackpack-versions.md)
  * [StackState release notes](setup/upgrade-stackstate/sts-release-notes.md)

## 👤 Use

* [Introduction to StackState](use/introduction-to-stackstate/README.md)
  * [Getting Started](use/introduction-to-stackstate/getting_started.md)
  * [The 4T data model](use/introduction-to-stackstate/4t_data_model.md)
  * [Components and Relations](use/introduction-to-stackstate/components_and_relations.md)
  * [Perspectives](use/introduction-to-stackstate/perspectives.md)
  * [Anomaly detection](use/introduction-to-stackstate/anomaly-detection.md)
  * [Layers, Domains and Environments](use/introduction-to-stackstate/layers_domains_and_environments.md)
  * [Mapping functions](use/introduction-to-stackstate/mapping_functions.md)
  * [ID extraction](use/introduction-to-stackstate/id_extraction.md)
  * [StackState architecture](use/introduction-to-stackstate/stackstate_architecture.md)
* [Explore mode](use/explore_mode.md)
* [View filters](use/view_filters.md)
* [Views](use/views.md)
* [Perspectives](use/perspectives/README.md)
  * [Topology Perspective](use/perspectives/topology-perspective.md)
  * [Events Perspective](use/perspectives/events_perspective.md)
  * [Traces Perspective](use/perspectives/traces-perspective.md)
  * [Telemetry Perspective](use/perspectives/telemetry-perspective.md)
  * [Browse telemetry](use/perspectives/browse-telemetry.md)
* [Health state and event notifications](use/health-state-and-event-notifications/README.md)
  * [Add a health check](use/health-state-and-event-notifications/add-a-health-check.md)
  * [Add a telemetry stream](use/health-state-and-event-notifications/add-telemetry-to-element.md)
  * [Configure the view health](use/health-state-and-event-notifications/configure-view-health.md)
  * [Send event notifications](use/health-state-and-event-notifications/send-event-notifications.md)
  * [Anomaly health checks](use/health-state-and-event-notifications/anomaly-health-checks.md)
  * [Anomaly detection with baselines \(Deprecated\)](use/health-state-and-event-notifications/anomaly-detection-with-baselines.md)
* [Problems](use/problems/README.md)
  * [What is a problem?](use/problems/problems.md)
  * [Investigate a problem](use/problems/problem_investigation.md)
  * [Problem notifications](use/problems/problem_notifications.md)
* [Analytics](use/analytics.md)
* [Glossary](use/glossary.md)

## 🧩StackPacks

* [What is a StackPack?](stackpacks/about-stackpacks.md)
* [Add-ons](stackpacks/add-ons/README.md)
  * [Autonomous Anomaly Detector](stackpacks/add-ons/aad.md)
  * [Health Forecast](stackpacks/add-ons/health-forecast.md)
* [Integrations](stackpacks/integrations/README.md)
  * [StackState Agent](stackpacks/integrations/agent.md)
  * [AWS](stackpacks/integrations/aws.md)
  * [AWS X-ray](stackpacks/integrations/aws-x-ray.md)
  * [Azure](stackpacks/integrations/azure.md)
  * [API integration](stackpacks/integrations/api-integration.md)
  * [Cloudera](stackpacks/integrations/cloudera.md)
  * [Custom Synchronization](stackpacks/integrations/customsync.md)
  * [DotNet APM](stackpacks/integrations/dotnet-apm.md)
  * [Dynatrace](stackpacks/integrations/dynatrace.md)
  * [Google Analytics](stackpacks/integrations/google_analytics.md)
  * [Humio](stackpacks/integrations/humio.md)
  * [Java APM](stackpacks/integrations/java-apm.md)
  * [Kubernetes](stackpacks/integrations/kubernetes.md)
  * [Logz.io](stackpacks/integrations/logz.md)
  * [Manual Topology](stackpacks/integrations/manualtopo.md)
  * [Nagios](stackpacks/integrations/nagios.md)
  * [Openshift](stackpacks/integrations/openshift.md)
  * [SAP](stackpacks/integrations/sap.md)
  * [SCOM \(BETA\)](stackpacks/integrations/scom.md)
  * [ServiceNow](stackpacks/integrations/servicenow.md)
  * [Splunk](stackpacks/integrations/splunk/README.md)
    * [Splunk integration](stackpacks/integrations/splunk/splunk_stackpack.md)
    * [Splunk topology Agent check](stackpacks/integrations/splunk/splunk_topology.md)
    * [Splunk metrics Agent check](stackpacks/integrations/splunk/splunk_metrics.md)
    * [Splunk events Agent check](stackpacks/integrations/splunk/splunk_events.md)
  * [Static Topology](stackpacks/integrations/static_topology.md)
  * [Traefik \(BETA\)](stackpacks/integrations/traefik.md)
  * [VMWare vSphere](stackpacks/integrations/vsphere.md)
  * [Zabbix](stackpacks/integrations/zabbix.md)
* [Develop your own StackPacks](stackpacks/sdk.md)

## 🔧 Configure

* [Topology](configure/topology/README.md)
  * [Component actions](configure/topology/component_actions.md)
  * [How to: Configure component actions](configure/topology/how_to_configure_component_actions.md)
  * [Create a topology manually](configure/topology/how_to_create_manual_topology.md)
  * [Configure synchronizations](configure/topology/sync.md)
  * [Customize view health state reporting](configure/topology/view_state_configuration.md)
  * [Enable email event notifications](configure/topology/configure-email-event-notifications.md)
  * [Event handlers](configure/topology/event-handlers.md)
  * [Health state propagation](configure/topology/propagation.md)
  * [Naming guide](configure/topology/naming_guide.md)
  * [Tags](configure/topology/tagging.md)
  * [Topology sources](configure/topology/topology_sources.md)
  * [Topology synchronization](configure/topology/topology_synchronization.md)
  * [Debug topology synchronization](configure/topology/debugging_topology_synchronization.md)
* [Telemetry](configure/telemetry/README.md)
  * [Add telemetry during topology synchronization](configure/telemetry/telemetry_synchronized_topology.md)
  * [Checks and streams](configure/telemetry/checks_and_streams.md)
  * [Data sources](configure/telemetry/data-sources/README.md)
    * [Elasticsearch](configure/telemetry/data-sources/elasticsearch.md)
    * [Prometheus mirror](configure/telemetry/data-sources/prometheus-mirror.md)
  * [Push telemetry to StackState over HTTP](configure/telemetry/send_telemetry.md)
  * [Set telemetry stream priority](configure/telemetry/how_to_use_the_priority_field_for_components.md)
  * [Baseline functions \(Deprecated\)](configure/telemetry/baseline-functions.md)
* [Traces](configure/traces/README.md)
  * [Configure traces](configure/traces/configure_tracing.md)
  * [Set up traces](configure/traces/how_to_setup_traces.md)
* [Security](configure/security/README.md)
  * [Authentication](configure/security/authentication/README.md)
    * [Authentication options](configure/security/authentication/authentication_options.md)
    * [File based](configure/security/authentication/file.md)
    * [LDAP](configure/security/authentication/ldap.md)
    * [Open ID Connect \(OIDC\)](configure/security/authentication/oidc.md)
    * [KeyCloak](configure/security/authentication/keycloak.md)
  * [RBAC](configure/security/rbac/README.md)
    * [Role-based Access Control](configure/security/rbac/role_based_access_control.md)
    * [Permissions](configure/security/rbac/rbac_permissions.md)
    * [Roles](configure/security/rbac/rbac_roles.md)
    * [Scopes](configure/security/rbac/rbac_scopes.md)
    * [Subjects](configure/security/rbac/rbac_subjects.md)
  * [Self-signed certificates](configure/security/self-signed-cert.md)
  * [Secrets management](configure/security/secrets_management.md)
  * [Self-signed certificates](configure/security/self-signed-cert-1.md)
  * [Set up a security backend for Linux](configure/security/set_up_a_security_backend_for_linux.md)
  * [Set up a security backend for Windows](configure/security/set_up_a_security_backend_for_windows.md)
* [Identifiers](configure/identifiers.md)
* [Logging](configure/logging/README.md)
  * [Enable logging for functions](configure/logging/enable-logging.md)
  * [StackState log files](configure/logging/stackstate-log-files.md)

## 📖 Develop

* [Developer guides](develop/developer-guides/README.md)
  * [Develop StackPacks](develop/developer-guides/stackpack/README.md)
    * [How to create a StackPack](develop/developer-guides/stackpack/develop_stackpacks.md)
    * [Packaging](develop/developer-guides/stackpack/prepare_package.md)
    * [How to get a template file](develop/developer-guides/stackpack/how_to_get_a_template_file.md)
    * [How to make a multi-instance StackPack](develop/developer-guides/stackpack/how_to_make_a_multi-instance_stackpack.md)
    * [Prepare a multi-instance provisioning script](develop/developer-guides/stackpack/prepare_multi-instance_provisioning_script.md)
    * [Upload a StackPack file](develop/developer-guides/stackpack/how_to_pack_and_upload_stackpack.md)
    * [Prepare a shared template](develop/developer-guides/stackpack/prepare_shared_template.md)
    * [Customize a StackPack](develop/developer-guides/stackpack/how_to_customize_a_stackpack.md)
    * [Prepare instance template files](develop/developer-guides/stackpack/prepare_instance_template_file.md)
    * [Prepare a StackPack provisioning script](develop/developer-guides/stackpack/prepare_stackpack_provisioning_script.md)
    * [Resources in a StackPack](develop/developer-guides/stackpack/stackpack_resources.md)
    * [StackState Common Layer](develop/developer-guides/stackpack/stackstate-common-layer.md)
  * [Custom Synchronization StackPack](develop/developer-guides/custom_synchronization_stackpack/README.md)
    * [What is the Custom Synchronization StackPack?](develop/developer-guides/custom_synchronization_stackpack/custom_synchronization_stackpack.md)
    * [How to customize elements created by the Custom Synchronization StackPack](develop/developer-guides/custom_synchronization_stackpack/how_to_customize_elements_created_by_custom_synchronization_stackpack.md)
    * [How to connect an agent check with StackState](develop/developer-guides/custom_synchronization_stackpack/how_to_connect_agent_check_with_stackstate_instance.md)
    * [How to configure a custom synchronization](develop/developer-guides/custom_synchronization_stackpack/how_to_configure_custom_synchronization.md)
  * [Synchronizations and templated files](develop/developer-guides/synchronizations_and_templated_files.md)
  * [Agent checks](develop/developer-guides/agent_check/README.md)
    * [What are Agent checks?](develop/developer-guides/agent_check/agent_checks.md)
    * [Checks in Agent v2](develop/developer-guides/agent_check/checks_in_agent_v2.md)
    * [How to develop agent checks](develop/developer-guides/agent_check/how_to_develop_agent_checks.md)
  * [Extend StackState with functions](develop/developer-guides/functions.md)
  * [Anomaly check functions](develop/developer-guides/anomaly-check-functions.md)
  * [Mirroring Telemetry](develop/developer-guides/mirroring.md)
  * [Integrate external services](develop/developer-guides/integrating_external_services.md)
* [Reference](develop/reference/README.md)
  * [StackState CLI](develop/reference/cli_reference.md)
  * [StackState Template Json \(STJ\)](develop/reference/stj/README.md)
    * [Using STJ](develop/reference/stj/using_stj.md)
    * [Template functions](develop/reference/stj/stj_reference.md)
  * [StackState Markup Language \(STML\)](develop/reference/stml/README.md)
    * [Using STML](develop/reference/stml/using_stml.md)
    * [STML Tags](develop/reference/stml/tags.md)
  * [StackState Query Language \(STQL\)](develop/reference/stql_reference.md)
  * [StackState Scripting Language \(STSL\)](develop/reference/scripting/README.md)
    * [Scripting in StackState](develop/reference/scripting/scripting-in-stackstate.md)
    * [Async script result](develop/reference/scripting/async_script_result.md)
    * [Script APIs](develop/reference/scripting/script-apis/README.md)
      * [Async - script API](develop/reference/scripting/script-apis/async.md)
      * [Component - script API](develop/reference/scripting/script-apis/component.md)
      * [HTTP - script API](develop/reference/scripting/script-apis/http.md)
      * [Prediction - script API](develop/reference/scripting/script-apis/prediction.md)
      * [StackPack - script API](develop/reference/scripting/script-apis/stackpack.md)
      * [Telemetry - script API](develop/reference/scripting/script-apis/telemetry.md)
      * [Time - script API](develop/reference/scripting/script-apis/time.md)
      * [Topology - script API](develop/reference/scripting/script-apis/topology.md)
      * [UI - script API](develop/reference/scripting/script-apis/ui.md)
      * [View - script API](develop/reference/scripting/script-apis/view.md)
* [Tutorials](develop/tutorials/README.md)
  * [Create a simple StackPack](develop/tutorials/basic_stackpack_tutorial.md)
  * [Push data to StackState from an external system](develop/tutorials/push_integration_tutorial.md)
  * [Send events to StackState from an external system](develop/tutorials/events_tutorial.md)
  * [Set up a mirror to pull telemetry data from an external system](develop/tutorials/mirror_tutorial.md)

