# aurora-helpers

Helper scripts and configs to be used with Aurora Agent

## Sysmon Config

A complementary Sysmon configuration to add visibility that ETW lacks to provide.

Known blind spots:

- Registry Events
- NamedPipe Creation (workaround that uses polling in Aurora)
