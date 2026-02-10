---
name: Bug report
about: Create a report to help us improve.
title: My issue name [Repository-name]
labels: ''
assignees: ''

---

**Which repository/component?**
Please specify:

- [ ] citrineos-core
- [ ] operator-ui
- [ ] citrineos-ocpi
- [ ] citrineos.github.io
- [ ] citrineos-payment

**Version/Branch Information**
- Component version/tag: [e.g. v1.2.3, main, next]
- Commit hash (if applicable): [e.g. abc123def]

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Configure component with '...'
2. Send OCPP message '...' or perform action '...'
3. Observe behavior in '...'
4. See error

**Expected behavior**
A clear and concise description of what you expected to happen.

**Application Logs**
Please include relevant logs from Docker containers:
```
[Paste container logs here - use `docker logs <container_name>` or `docker compose logs`]
```

**OCPP Messages** (if applicable)
Include relevant OCPP messages sent/received by the charging station:
```json
Paste OCPP message JSON here
```

**Environment Information:**
- OS: [e.g. Ubuntu 20.04, macOS 13.1, Windows 11]

**Charging Station Information** (if applicable):
- Station manufacturer/model: [e.g. ABB Terra 54]
- OCPP version: [e.g. 1.6J, 2.0.1]
- Firmware version: [e.g. 1.2.3]

**Screenshots/Configuration Files**
If applicable, add screenshots of error messages or relevant configuration files.

**Additional context**
Add any other context about the problem here, including:
- Network configuration details
- Load/scale information
- Timing of when the issue occurs
