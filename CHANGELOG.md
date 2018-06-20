# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)


## Unreleased as of Sprint 88 ending 2018-06-18

### Added
- Reset API headers after each call [(#99)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/99)
- Inventory FloatingIps [(#97)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/97)
- Inventory L2 Domain entity (Nuage) as CloudSubnet model (MIQ) [(#94)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/94)
- Cleanup config/settings.yaml after changes in UI [(#89)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/89)

## Unreleased as of Sprint 87 ending 2018-06-04

### Added
- Inventory L3 Domain (Nuage) into NetworkRouter (MIQ) [(#93)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/93)

## Gaprindashvili-3 - Released 2018-05-15

### Added
- Add `stop_event_monitor_queue_on_change` method [(#65)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/65)
- Redirect logs into log/nuage.log file [(#66)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/66)
- Don't run EventCatcher when user opts-in for "None" [(#69)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/69)
- Also connect to CNAAlarms AMQP topic [(#73)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/73)
- Don't raise exceptions from within AMQP callbacks [(#78)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/78)

### Fixed
- Add name method [(#62)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/62)
- Handle subnets with missing gateway/netmask [(#68)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/68)

## Unreleased as of Sprint 85 ending 2018-05-07

### Added
- Prefix Nuage events with "nuage" [(#84)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/84)
- Harden refresh parser [(#71)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/71)

## Gaprindashvili-1 - Released 2018-01-31

### Added
- Implement graph inventory refresh for network manager [(#13)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/13)
- Provide extensive unit tests for legacy refresher [(#12)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/12)
- Install qpid_proton for Travis [(#11)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/11)
- Assign :ems_ref to the event [(#59)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/59)
- Upgrade qpid_proton related stuff to support v0.19.0 [(#58)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/58)

### Fixed
- Fix exception handing for credential validation on raw_connect [(#40)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/40)
- Fix a problem when no policy groups exist [(#4)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/4)
- Fix protocol selection when adding a new nuage provider [(#45)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/45)
- Human readable error when selecting wrong security protocol [(#43)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/43)
- Return empy list instead of nil for responses with empty bodies [(#53)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/53)

## Unreleased as of Sprint 72 ending 2017-10-30

### Added
- Enable Nuage network manager [(#33)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/33)
- Update raw_connect to simplify validation from UI [(#32)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/32)
- Use AMQP fallback endpoints when available [(#30)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/30)
- Connect events to targeted refresh [(#28)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/28)
- Implement targeted refresh for NetworkManager [(#20)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/20)
