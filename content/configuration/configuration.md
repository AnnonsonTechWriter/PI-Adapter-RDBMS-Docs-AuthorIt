---
uid: Configuration
---

# Configuration

PI Adapter for RDBMS provides configuration of data source and data selection. The adapter also provides the ability to configure queries to run on the data source.

The examples in the configuration topics use `curl`, a commonly available tool on both Windows and Linux. You can configure the adapter with any programming language or tool that supports making REST calls, or with the EdgeCmd utility. For more information, see the [EdgeCmd utility documentation](https://osisoft.github.io/Edgecmd-Docs/content/edgecmd-utility.html). To validate successful configurations, you can perform data retrieval (GET commands) using a browser, if available on your device.

For more information on PI Adapter configuration tools, see [Configuration tools](xref:ConfigurationTools).

## Quick start

This Quick Start guides you through setup of each configuration file available for PI Adapter for RDBMS. As you complete each step, perform each required configuration to establish a data flow from a data source to one or more endpoints. Some configurations are optional.

**Important:** If you want to complete the optional configurations, complete those tasks before the required tasks.

1. Configure one or several RDBMS system components.<br>See [System components configuration](xref:SystemComponentsConfiguration#configure-system-components).

2. Configure an RDBMS data source for each RDBMS device.<br>See [PI Adapter for RDBMS data source configuration](xref:PIAdapterForRDBMSDataSourceConfiguration#configure-rdbms-data-files-data-source).

3. **Optional**: Configure schedules and RDBMS queries to run on the data source.<br>See the following topics:

    - [Schedules configuration](xref:SchedulesConfiguration)
    - [PI Adapter for RDBMS queries configuration](xref:PIAdapterForRDBMSQueriesConfiguration#configure-rdbms-queries).

4. Configure an RDBMS data selection for each RDBMS data source.<br>See [PI Adapter for RDBMS data selection configuration](xref:PIAdapterForRDBMSDataSelectionConfiguration#configure-rdbms-data-selection).

5. **Optional**: Configure data filters and if there is a proxy between the adapter and your egress endpoints, define it.<br>See the following topics:

    - [Data filters configuration](xref:DataFiltersConfiguration#configure-data-filters) 
    - [Configure a network proxy](xref:ConfigureANetworkProxy)

6. Configure one or more egress endpoints.<br>See [Egress endpoints configuration](xref:EgressEndpointsConfiguration#configure-egress-endpoints).

7. **Optional**: Configure health endpoints, general (diagnostics and metadata), buffering, and logging. See the following topics:

    - [Health endpoint configuration](xref:HealthEndpointConfiguration#configure-health-endpoint)
    - [General configuration](xref:GeneralConfiguration#configure-general)
    - [Buffering configuration](xref:BufferingConfiguration#configure-buffering)
    - [Logging configuration](xref:LoggingConfiguration#configure-logging)
 