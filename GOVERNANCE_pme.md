# PyPSA-meets-Earth Governance

This document defines the governance structure for the PyPSA-meets-Earth initiative, inspired by the Flyte project.

## Overview

PyPSA-meets-Earth is a collaborative open source initiative dedicated to building a transparent, inclusive, and reproducible energy system modeling ecosystem, leveraging the PyPSA framework and contributing to the broader scientific and policy discourse around sustainable transitions. This document outlines how the community collaborates and governs to achieve these goals.

## Groups and Streams
The PyPSA-meets-Earth initiative is organized in multiple streams each having, each focusing on different aspects of the project. All streams are equally important and interdependent; they can be created. The main streams are:
- **Code Stream**: stream dedicated to the development and maintenance of the core PyPSA-meets-Earth packages, including features, bug fixes, and releases.
- **Impact Stream**: streams focused on activities that aims to have impact without necessarily code activities. Examples include but are not limited to outreach, documentation, among others.
- **Steering Committee**: it is a special stream responsible for strategic direction, cross-repo/stream concerns, and governance decisions.

## Decision Making: Lazy Consensus

Most decisions in PyPSA-meets-Earth are made using **lazy consensus**: if no one objects within a reasonable period (typically 5-7 days), the proposal is accepted. Only in rare cases where consensus cannot be reached, a more formal vote may be called (see "Supermajority" below).

## Community Roles and Path to Maintainer

Roles apply equally to code and non-code activities (e.g., documentation, community, tools, streams). The following table lists the roles within the PyPSA-meets-Earth community, describing:

- General responsibilities expected by individuals in each role
- Requirements necessary to join or remain in a role
- Associated access rights

<table>
  <thead>
    <tr>
      <th>Role</th>
      <th>Responsibilities</th>
      <th>Requirements</th>
      <th>Access Rights</th>
      <th>Scope</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Participant</td>
      <td>
        <ul>
          <li>Follow the <a href="https://lfprojects.org/policies/code-of-conduct/">Code of Conduct</a></li>
          <li>Engage in discussions, submit issues and PRs, contribute to code or non-code streams</li>
        </ul>
      </td>
      <td>None</td>
      <td>
        <ul>
          <li>Can submit PRs and issues from forks</li>
          <li>Can join the PyPSA-meets-Earth Discord channel (<a href="https://discord.gg/AnuJBk23FU">join here</a>)</li>
          <li>Can take part in community discussions</li>
        </ul>
      </td>
      <td>GitHub organization</td>
    </tr>
    <tr><td colspan="5"><em>Inherits from Participant</em></td></tr>
    <tr>
      <td>Contributor</td>
      <td>
        <ul>
          <li>Report and help resolve issues</li>
          <li>Answer community questions</li>
          <li>Review and provide feedback on issues/PRs</li>
          <li>Contribute to code, documentation, tools, or community streams</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Active participation (e.g., merged contribution, regular discussion, or content creation)</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Can review PRs</li>
          <li>May close/open/reassign issues</li>
          <li>May request PR reviews</li>
          <li>Can mark duplicates</li>
          <li>Can propose new streams and propose revision to existing ones</li>
        </ul>
      </td>
      <td>Specific repo(s) or streams under pypsa-meets-earth</td>
    </tr>
    <tr><td colspan="5"><em>Inherits from Contributor</em></td></tr>
    <tr>
      <td>Maintainer</td>
      <td>
        <ul>
          <li>Guide project direction and quality</li>
          <li>Help cut releases</li>
          <li>Actively engages and mentors contributors</li>
          <li>Review and merge PRs</li>
          <li>Coordinate with other streams (code, docs, tools, community)</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Consistent, high-quality contributions</li>
          <li>Broad project knowledge</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Approve and merge PRs</li>
          <li>Manage releases</li>
          <li>Moderate discussions</li>
          <li>Vote on major decisions (if needed)</li>
        </ul>
      </td>
      <td>Specific repo(s) or streams under pypsa-meets-earth</td>
    </tr>
    <tr><td colspan="5"><em>Inherits from Maintainer</em></td></tr>
    <tr>
      <td>Steering Committee</td>
      <td>
        <ul>
          <li>Set roadmap/priorities</li>
          <li>Mentor contributors/Maintainers</li>
          <li>Reviews, approves and closes streams</li>
          <li>Vote on governance and roles</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Must be a Maintainer</li>
          <li>Highly active in multiple areas</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Org-wide access rights</li>
        </ul>
      </td>
      <td>GitHub organization</td>
    </tr>
  </tbody>
</table>

## Role Description and Processes

### Participant

Anyone can contribute by using PyPSA-meets-Earth tools, providing feedback, joining discussions, submitting issues and PRs, or helping others.

### Contributor

Contributors actively engage with the community and support others across all streams (code, docs, tools, community).

#### Becoming a Contributor

- Participate actively (e.g., merged PR, regular discussion, or content creation).
- Recognition is informal and based on ongoing participation.

### Maintainer

Maintainers manage daily project contributions, review PRs, and ensure quality across all streams.

#### Nomination Process

1. Open an issue in the community repo using the `maintainer-nomination` label.
2. Assign current Maintainers as reviewers.
3. Approval is by lazy consensus (if no objections in 7 days, nomination is accepted).
4. If consensus cannot be reached, a supermajority vote of Maintainers may be called.

#### Removal or Resignation

Maintainers may step down voluntarily or be removed by lazy consensus (or supermajority vote if needed) due to inactivity or other circumstances.

### Steering Committee

Responsible for strategic direction, cross-repo/stream concerns, and governance decisions. Duties include:

- Reviewing, proposing and approving proposals for new sub-projects or streams
- Establishing Working Groups
- Approving governance and role changes

## Stepping Down / Emeritus Process

Contributors can step down to a lower role or request emeritus status by contacting the Maintainers.

---

**NOTE:** The current list of Maintainers and Steering Committee members is maintained in [MAINTAINERS](MAINTAINERS.md).

## Definitions

### Lazy Consensus

A decision-making process where a proposal is accepted if no one objects within a set period (usually 5-7 days). Objections should be accompanied by reasoning and, ideally, alternatives.

### Supermajority

A supermajority is defined as two-thirds of members in the group (66%). Used only if lazy consensus fails. Voting can happen on the mailing list, GitHub, Discord, email, or via a voting service, when appropriate. Members can either vote "agree, yes, +1", "disagree, no, -1", or "abstain". A vote passes when supermajority is met. An abstain vote equals not voting at all.


