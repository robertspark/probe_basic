![](probe_basic/images/probe_basic_icon.png)


## Documentation

### installation

https://kcjengr.github.io/probe_basic/quick_start.html

### Development installation

https://kcjengr.github.io/probe_basic/dev_install.html

### QtPyVCP use documentation

https://qtpyvcp.com



## Development

* [Documentation](https://www.qtpyvcp.com)
* [Documentation](https://kcjengr.github.io/probe_basic/)
* [GitHub Repo](https://github.com/kcjengr/probe_basic/)
* [Issue Tracker](https://github.com/kcjengr/probe_basic/issues)

## Documentation and Help

* [Documentation](https://www.qtpyvcp.com)
* [LinuxCNC Forum](https://forum.linuxcnc.org/qtpyvcp)
* [libera.chat IRC](http://web.libera.chat/) (#qtpyvcp)
* [The Matrix](https://app.element.io/#/room/#qtpyvcp:matrix.org) (#qtpyvcp:matrix.org)
* [Discord](https://discord.gg/463hMhd)



## Dependencies

* [LinuxCNC](https://linuxcnc.org)
* Python 2.7
* PyQt5 or PySide2
* [QtPyVCP](https://qtpyvcp.com/)

Probe Basic is developed and tested using the LinuxCNC Debian 9 x64 (stretch)
[Live ISO](http://www.linuxcnc.org/testing-stretch-rtpreempt/) and Ubuntu 18.10 x64 SIM. It should run
on any system that can have PyQt5 installed, but Debian 9 x64 is the only OS
that is officially supported.


## DISCLAIMER

THE AUTHORS OF THIS SOFTWARE ACCEPT ABSOLUTELY NO LIABILITY FOR
ANY HARM OR LOSS RESULTING FROM ITS USE.  IT IS _EXTREMELY_ UNWISE
TO RELY ON SOFTWARE ALONE FOR SAFETY.  Any machinery capable of
harming persons must have provisions for completely removing power
from all motors, etc, before persons enter any danger area.  All
machinery must be designed to comply with local and national safety
codes, and the authors of this software can not, and do not, take
any responsibility for such compliance.

This software is released under the GPLv2.

## Repository status and workstream maintenance

Documentation review: 3 November 2026. This is repository-local status, not an upstream release or deployment acceptance.

### Purpose and function

User interface for the LinuxCNC machine control.

### Current objective

Maintain a clearly documented local copy for authorised evaluation/development, preserving upstream attribution and distinguishing local changes from upstream capabilities.

### Progress and evidence

This is a fork of kcjengr/probe_basic. Existing upstream documentation and attribution are retained. Local customisation, upstream parity, build success and runtime/hardware acceptance have not been verified in this documentation review.

### Next steps and roadmap

1. Confirm the next owner-approved outcome and reconcile this default branch with the workstream's actual source, test evidence and deployed version.
2. Compare with the upstream project before updating and use an appropriate disposable/non-live test setup.
3. Keep completed/in-progress/blocked work and next actions current here. Broader feature priorities remain for the owning workstream to agree; this update does not invent a feature commitment.

### Documentation chain

Read this README first, then the existing records and source/example entry points below. Listed paths were observed on the inspected default branch; source folders are not test results.

- [LICENSE.md](LICENSE.md)

- [Upstream repository](https://github.com/kcjengr/probe_basic)

### Standing instruction for every workstream

Every agent, developer or project workstream maintaining this repository must automatically keep this README current with its purpose/function, agreed objective, dated progress, blockers, roadmap/next actions and links to authoritative records. Update it when these facts materially change, at meaningful milestones and before handback, interruption or completion; do not wait for a separate owner reminder.

Read applicable project instructions, preserve concurrent work and existing attribution/licences, and distinguish source commits from deployed versions and verified results. Link requirements, design, handover, validation and recovery records when they exist rather than creating conflicting copies. If a fact is unknown, say so and identify the next verification action. Check affected links, publish authorised changes and verify the remote commit before claiming completion.

Keep credentials, private infrastructure/access routes, private datasets and confidential material out of public documentation. This instruction does not grant new access, replace project-specific authority or approve untested hardware/live operations. Retain detailed historical evidence in project records/version history rather than an ever-growing README log.
