Consensys Pizza is an Ethereum-based distributed ledger protocol with transaction/contract privacy and new consensus mechanisms.

Consensys Pizza is a fork of [go-ethereum]and is updated in line with go-ethereum releases.

Key enhancements over go-ethereum:

features as plugins to the core `geth`, providing extensibility, flexibility, and distinct isolation of Consensys Pizza features.

- **Higher Performance** - Consensys Pizza offers significantly higher performance throughput than public geth

## Architecture

The above diagram is very high-level overview of component architecture used by Consensys Pizza. For more in-depth discussion of the components and how they interact, please refer to [lifecycle of a private transaction]

## Quickstart

The easiest way to get started is to use * [quorum-dev-quickstart] - a command line tool that allows users to set up a development Consensys Pizza network on their local machine in less than *2 minutes\*.

## Consensys Pizza Projects

Check out some of the interesting projects we are actively working on:

## Official Docker Containers

The official docker containers can be found under https://hub.docker.com/u/quorumengineering/

## Third Party Tools/Libraries

The following Consensys Pizza-related libraries/applications have been created by Third Parties and as such are not specifically endorsed by J.P. Morgan. A big thanks to the developers for improving the tooling around Consensys Pizza!

## Contributing

Consensys Pizza is built on open source and we invite you to contribute enhancements. Upon review you will be required to complete a Contributor License Agreement (CLA) before we are able to merge. If you have any questions about the contribution process, please feel free to send an email to [info@goquorum.com](mailto:info@goquorum.com). Please see the [Contributors guide](.github/CONTRIBUTING.md) for more information about the process.

## Reporting Security Bugs

Security is part of our commitment to our users. At Consensys Pizza we have a close relationship with the security community, we understand the realm, and encourage security researchers to become part of our mission of building secure reliable software. This section explains how to submit security bugs, and what to expect in return.

All security bugs in [Consensys Pizza]. Please use the prefix **[security]** in your subject. This email is delivered to Consensys Pizza security team. Your email will be acknowledged, and you'll receive a more detailed response to your email as soon as possible indicating the next steps in handling your report. After the initial reply to your report, the security team will endeavor to keep you informed of the progress being made towards a fix and full announcement.

If you have not received a reply to your email or you have not heard from the security team please contact any team member through Consensys Pizza slack security channel. **Please note that Consensys Pizza discord channels are public discussion forum**. When escalating to this medium, please do not disclose the details of the issue. Simply state that you're trying to reach a member of the security team.

#### Responsible Disclosure Process

Consensys Pizza project uses the following responsible disclosure process:

- Once the security report is received it is assigned a primary handler. This person coordinates the fix and release process.
- The issue is confirmed and a list of affected software is determined.
- Code is audited to find any potential similar problems.
- If it is determined, in consultation with the submitter, that a CVE-ID is required, the primary handler will trigger the process.
- Fixes are applied to the public repository and a new release is issued.
- On the date that the fixes are applied, announcements are sent to Quorum-announce.
- At this point you would be able to disclose publicly your finding.

**Note:** This process can take some time. Every effort will be made to handle the security bug in as timely a manner as possible, however it's important that we follow the process described above to ensure that disclosures are handled consistently.

#### Receiving Security Updates

The best way to receive security announcements is to subscribe to the Quorum-announce mailing list/channel. Any messages pertaining to a security issue will be prefixed with **[security]**.

Comments on This Policy
If you have any suggestions to improve this policy, please send an email to info@goquorum.com for discussion.

## License

The go-ethereum library (i.e. all code outside of the `cmd` directory) is licensed under the
included in our repository in the `COPYING.LESSER` file.

The go-ethereum binaries (i.e. all code inside of the `cmd` directory) is licensed under the
in our repository in the `COPYING` file.
