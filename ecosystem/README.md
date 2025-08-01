# Stellar Ecosystem Proposals (SEPs)

SEPs are ideas, standards, and specifications in the form of proposals that the
author is intending to be adopted by participants in the Stellar ecosystem.

## Roles

All SEPs have individuals fulfilling the following roles:

- **Author** - The author is the individual(s) who created the proposal. The
  author is responsible for writing the SEP, encouraging adoption of the SEP,
  and the general success of the SEP.
- **Maintainer** - The maintainer is optional. If not present, the maintainer
  is the author. The maintainer is responsible for reviewing changes to the
  SEP. For SEPs that have ecosystem adoption, SDF may identify or become a
  maintainer of last resort. A maintainer of last resort steps in and acts as
  the maintainer if the maintainer ceases to respond or engage.

## SEP Status Terms

- **Draft** - A SEP that is currently open for consideration, iteration and
  actively being discussed. It may change.
- **FCP** - A SEP that has entered a Final Comment Period (FCP). An author
  places their SEP in FCP when they wish to signal that they plan to cease
  making changes. After at least one week has passed the SEP's status should
  move to `Active` or `Final`, or back to `Draft`. If changes are required, it
  should be moved back to `Draft`.
- **Active** - A SEP ready to be adopted, and the proposal is a living document
  and may still receive changes. The author intends the SEP in its current form
  to be actively adopted. Changes can be made without changing the SEP number,
  although in the interest of growing an ecosystem of interopable participants
  the author should endeavor to make changes backwards compatible so that
  participants who have already adopted the SEP can continue to participate.
  Where changes cannot be backwards compatible, the major version should be
  updated to clearly distinguish new incompatible versions.
- **Final** - A SEP ready to be adopted, and the proposal is an immutable
  document and will no longer receive changes, other than minor errata. The
  author intends to make no further changes. Adopters can expect significant
  changes to be proposed in a new SEP.

### Additional Statuses

- **Abandoned** - A SEP has been abandoned by the author. SDF may move a SEP
  into this state if the SEP has no activity, no visible adoption, and the
  author is not responsive.

## Proposals

| Number                  | Title                                                                  | Author                                                        | Status |
| ----------------------- | ---------------------------------------------------------------------- | ------------------------------------------------------------- | ------ |
| [SEP-0001](sep-0001.md) | Stellar Info File                                                      | SDF                                                           | Active |
| [SEP-0002](sep-0002.md) | Federation Protocol                                                    | SDF                                                           | Final  |
| [SEP-0004](sep-0004.md) | Tx Status Endpoint                                                     | SDF                                                           | Final  |
| [SEP-0005](sep-0005.md) | Key Derivation Methods for Stellar Accounts                            | SDF                                                           | Final  |
| [SEP-0006](sep-0006.md) | Deposit and Withdrawal API                                             | SDF                                                           | Active |
| [SEP-0007](sep-0007.md) | URI Scheme to facilitate delegated signing                             | Interstellar                                                  | Final  |
| [SEP-0008](sep-0008.md) | Regulated Assets                                                       | Interstellar                                                  | Final  |
| [SEP-0009](sep-0009.md) | Standard KYC Fields                                                    | SDF                                                           | Active |
| [SEP-0010](sep-0010.md) | Stellar Authentication                                                 | Sergey Nebolsin, Tom Quisel                                   | Active |
| [SEP-0011](sep-0011.md) | Txrep: Human-Readable Low-Level Representation of Stellar Transactions | David Mazières                                                | Active |
| [SEP-0012](sep-0012.md) | KYC API                                                                | Interstellar                                                  | Active |
| [SEP-0014](sep-0014.md) | Dynamic Asset Metadata                                                 | OrbitLens, Paul Tiplady                                       | Draft  |
| [SEP-0018](sep-0018.md) | Data Entry Namespaces                                                  | Mister.Ticot                                                  | Active |
| [SEP-0020](sep-0020.md) | Self-verification of validator nodes                                   | Johan Stén                                                    | Active |
| [SEP-0023](sep-0023.md) | Muxed Account Strkeys                                                  | David Mazières, Tomer Weller, Leigh McCulloch, Alfonso Acosta | Active |
| [SEP-0024](sep-0024.md) | Hosted Deposit and Withdrawal                                          | SDF                                                           | Active |
| [SEP-0028](sep-0028.md) | XDR Base64 Encoding                                                    | SDF                                                           | Final  |
| [SEP-0029](sep-0029.md) | Account Memo Requirements                                              | OrbitLens, Tomer Weller, Leigh McCulloch, David Mazières      | Active |
| [SEP-0031](sep-0031.md) | Cross-Border Payments API                                              | SDF                                                           | Active |
| [SEP-0033](sep-0033.md) | Identicons for Stellar Accounts                                        | Lobstr.co, Gleb Pitsevich                                     | Active |
| [SEP-0046](sep-0046.md) | Contract Meta                                                          | Leigh McCulloch                                               | Active |
| [SEP-0048](sep-0048.md) | Contract Interface Specification                                       | Leigh McCulloch                                               | Active |

### Draft Proposals

| Number                  | Title                                                          | Author                                        | Status               |
| ----------------------- | -------------------------------------------------------------- | --------------------------------------------- | -------------------- |
| [SEP-0015](sep-0015.md) | Attachment Convention                                          | Interstellar                                  | Draft                |
| [SEP-0016](sep-0016.md) | Account Transfer Permissionless Payment Protocol (@p2p)        | Jeremy Rubin                                  | Draft                |
| [SEP-0017](sep-0017.md) | Issuer account funding protocol (CAP-13 Based)                 | Tom Quisel                                    | Draft                |
| [SEP-0019](sep-0019.md) | Bootstrapping Multisig Transaction Submission                  | Paul Selden, Nikhil Saraf                     | Draft                |
| [SEP-0021](sep-0021.md) | On-chain signature & transaction sharing                       | Mister.Ticot                                  | Draft                |
| [SEP-0022](sep-0022.md) | IPFS Support                                                   | Samuel B. Sendelbach                          | Draft                |
| [SEP-0030](sep-0030.md) | Recoverysigner: multi-party key management of Stellar accounts | Leigh McCulloch, Lindsay Lin                  | Draft                |
| [SEP-0032](sep-0032.md) | Asset Address                                                  | Leigh McCulloch                               | Draft                |
| [SEP-0034](sep-0034.md) | Wallet Attribution for Anchors                                 | Jake Urban and Leigh McCulloch                | Final Comment Period |
| [SEP-0035](sep-0035.md) | Operation IDs                                                  | Isaiah Turner, Debnil Sur, Scott Fleckenstein | Draft                |
| [SEP-0037](sep-0037.md) | Address Directory API                                          | OrbitLens                                     | Draft                |
| [SEP-0038](sep-0038.md) | Anchor RFQ API                                                 | Jake Urban and Leigh McCulloch                | Draft                |
| [SEP-0039](sep-0039.md) | Interoperability Recommendations for NFTs                      | SDF, Litemint.io                              | Active               |
| [SEP-0040](sep-0040.md) | Oracle Consumer Interface                                      | Alex Mootz, OrbitLens, Markus Paulson-Luna    | Draft                |
| [SEP-0041](sep-0041.md) | Soroban Token Interface                                        | Jonathan Jove, Siddharth Suresh               | Draft                |
| [SEP-0045](sep-0045.md) | Stellar Web Authentication for Contract Accounts               | Philip Liu, Marcelo Salloum, Leigh McCulloch  | Draft                |
| [SEP-0047](sep-0047.md) | Contract Interface Discovery                                   | Leigh McCulloch                               | Draft                |
| [SEP-0049](sep-0049.md) | Upgradeable Contracts                                          | OpenZeppelin, Boyan Barakov, Özgün Özerk      | Draft                |
| [SEP-0050](sep-0050.md) | Non-Fungible Tokens                                            | OpenZeppelin, Boyan Barakov, Özgün Özerk      | Draft                |
| [SEP-0051](sep-0051.md) | XDR-JSON                                                       | Leigh McCulloch                               | Draft                |
| [SEP-0052](sep-0052.md) | Key Sharing Method for Stellar Keys                            | Pamphile Roy, Jun Luo                         | Draft                |
| [SEP-0053](sep-0053.md) | Sign and Verify Messages                                       | Jun Luo, Pamphile Roy, OrbitLens, Piyal Basu  | Draft                |
| [SEP-0054](sep-0054.md) | Ledger Metadata Storage                                        | Tamir Sen                                     | Draft                |

### Abandoned Proposals

| Number                  | Title                                        | Author                                                   | Status    |
| ----------------------- | -------------------------------------------- | -------------------------------------------------------- | --------- |
| [SEP-0003](sep-0003.md) | Compliance Protocol                          | SDF                                                      | Abandoned |
| [SEP-0013](sep-0013.md) | DEPOSIT_SERVER proposal                      | @no, @ant, @manran, @pacngfar                            | Abandoned |
| [SEP-0026](sep-0026.md) | Non-interactive Anchor/Wallet Asset Transfer | SDF, Fritz Ekwoge (@efritze), Ernest Mbenkum (@cameroon) | Abandoned |

# Contribution Process

The Stellar Ecosystem, like most software ecosystems in the world, continues to
evolve over time to meet the needs of our network's participants and to drive
technology forward into new territory.

Unlike Stellar's Core development (CAPs), Stellar's Ecosystem Proposals are
intended to be a more dynamic way of introducing standards and protocols
utilized in the ecosystem that are built on top of the Stellar Network. It uses
a lightweight process.

A SEPs author is responsible for a proposals adoption. Other ecosystem
participants, including SDF, may encourage adoption of a proposal, but authors
should expect each proposal to stand on its own merits and authors and
maintainers should plan to drive adoption themselves.

Before contributing, consider the following:

- Gather feedback from discussion on the [GitHub discussion forum], [Stellar
  Dev Discord], or [stellar-dev mailing list], and utilize it to begin a draft
  proposal.
- Follow the proposal process listed below. If you're having difficulty moving
  the proposal forward, talk to folks in the ecosystem, or folks at SDF;
  they'll often have guidance on how to move things forward, as well as
  feedback regarding feasibility and how the proposal does or does not align
  with the Stellar Network's goals.

## SEP Process

### Pre-SEP (Initial Discussion)

Introduce your idea on the [GitHub discussion forum], [Stellar Dev Discord], or
[stellar-dev mailing list] and other community forums dedicated to Stellar.

- Make sure to gather feedback and alternative ideas — it's useful before
  putting together a formal draft!
- Consider contacting experts in a particular area for feedback while you're
  hashing out the details.
- Prototype, demo, and build confidence in the idea.
- Iterate as much as possible in this stage — making changes is easier before
  participants start adopting.

### Creating a SEP Draft

Draft a formal proposal using the [SEP Template](../sep-template.md), and
submit a PR to this repository. You should make sure to adhere to the
following:

- Use the following format for the filename of your draft:
  `sep_{shorttitle}.md`, for example `sep_newaccountdeposit.md`
- Make sure to place your SEP in the `ecosystem/` folder.
- Include GitHub handles or emails for all authors listed. GitHub handles are
  preferred.
- Set the version to `v0.0.1`.
- Submit a PR of your draft via your fork of this repository.
- Enable the GitHub feature `Maintainers are allowed to edit this pull request`
  on the PR so that a maintainer can assign a SEP number and merge the PR.
- A maintainer of the stellar-protocol repository will:
  - Review the PR to ensure the SEP follows the template and does not introduce
    any abuse to the repository.
  - If the template is followed and the change does not introduce any abuse to
    the repository:
    - Assign a SEP number.
    - Merge the PR.

#### Additional Tips

- If your SEP requires images or other supporting files, they should be
  included in a subdirectory of the `contents` folder for that SEP, such as
  `contents/sep_happycoder_b274f73c/`. Links should be relative, for example a
  link to an image from SEP-X would be
  `../contents/sep_happycoder_b274f73c/image.png`.

### Draft: Further Iteration

From there, the following process will happen:

- You should continue the discussion of the draft SEP on the [GitHub discussion
  forum], [Stellar Dev Discord], or [stellar-dev mailing list] to gather
  additional feedback. We welcome any additional PRs that iterate on the draft.
- Keep the version of the SEP as a `v0.y.z` version while in draft.
- Increment the minor or patch versions on each change while in draft. See [SEP
  Versioning].

### Draft -> Final Comment Period (FCP)

When you're ready for others to adopt the proposal:

- Decide if the proposal should be a living document and move to `Active`, or
  an immutable document and move to `Final`.
- Submit a PR changing the status in the draft to
  `Final Comment Period (Active)` or `Final Comment Period (Final)`.
- Keep the proposal in FCP for at least one week, then submit a PR changing the
  status to `Active`, `Final`, or back to `Draft`.

#### Deciding Active vs Final

You choose whether your proposal targets an Active or Final status.

Active proposals are living documents that the author intends to iterate on and
maintain over time, such as a specification that expects evolution in a
responsible manner with regards to backwards compatibility, and semver usage.

Final documents are immutable documents that the author intends to write once,
but do not intend to maintain over time.

### FCP (Active) -> Active

After at least one week in FCP:

- Submit a PR changing the status to `Active` and setting the version to
  `v1.0.0`.
- A maintainer of the stellar-protocol repository will review the PR to ensure
  the changes are limited to changing the status and updating the version.

### Active: Further Iteration

- Increment the major, minor, or patch versions on each change. See [SEP
  Versioning].
- Patch changes may be made to address bugs, errors, clarifications, or to fix
  errata.
- Minor changes may be made as more implementations are brought online
  highlighting any edge cases.
- Major changes, and breaking changes, should be considered with care as they
  may reduce interoperability.

### FCP (Final) -> Final

- Submit a PR changing the status to `Final` and update the version to
  `v1.0.0`.

### Final: No Further Iteration

- No changes will be made to a finalized SEP aside from fixing errata.
- Fixing errata should be so minor it is not accompanied by a version change.
- Much consideration should be given before moving to Final status, it is OK
  for SEPs to live in Draft or Active status for a long time.
- Any significant changes should be proposed as a new SEP.

## SEP Versioning

SEPs may stay in `Draft` status for an extended period of time. They are are
assigned versions so that the ecosystem can communicate about which version
they are implementing or discussing. SEPs use [semantic versioning] in the form
`vMAJOR.MINOR.PATCH` to determine an appropriate version for each change.

During draft a SEP should have a major version of `0` to indicate that anything
in the SEP may change at anytime. Once a SEP moves to Active it should be
changed to `v1.0.0` and the rules of semantic versioning apply.

All changes to a SEP should be accompanied by an update to its version, no
matter how small even typographical corrections. The exceptions that do not
require version updates:

- Correcting metadata in the `Pragma` section.
- Updating broken links.
- Updating links to implementations.
- Final SEPs where very minor errata is being corrected.

Proposals in the `Final` status should not be changed and should not see their
version number change once moved into the status.

[GitHub discussion forum]:
  https://github.com/orgs/stellar/discussions/categories/stellar-ecosystem-proposals
[Stellar Dev Discord]: https://discord.gg/stellardev
[stellar-dev mailing list]: https://groups.google.com/g/stellar-dev
[ietf]: https://ietf.org/
[semantic versioning]: https://semver.org/
[SEP Versioning]: #sep-versioning
