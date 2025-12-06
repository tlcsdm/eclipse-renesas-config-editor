# Eclipse Renesas Config Editor

This plugin registers .mtpj, .scfg, .eww and .ewp files—commonly used in Renesas projects—to be opened by Eclipse’s built-in XML editor. It helps developers quickly view and edit project configuration files in a structured and readable way.

## Build

This project uses [Tycho](https://github.com/eclipse-tycho/tycho) with [Maven](https://maven.apache.org/) to build. It requires Maven 3.9.0 or higher version.

Dev build:

```
mvn clean verify
```

Release build:

```
mvn clean org.eclipse.tycho:tycho-versions-plugin:set-version -DnewVersion=2.0.0 verify
```

## Install

1. Add `https://raw.githubusercontent.com/tlcsdm/eclipse-renesas-config-editor/master/update_site/` as the upgrade location in Eclipse.
2. Download from [Jenkins](https://jenkins.tlcsdm.com/job/eclipse-plugin/job/eclipse-renesas-config-editor)

