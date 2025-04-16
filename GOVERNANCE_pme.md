
# PyPSA-meets-Earth Governance

This document defines the governance structure for the PyPSA-meets-Earth initiative, inspired by the Flyte project.

## Overview

PyPSA-meets-Earth is a collaborative open source initiative dedicated to building a transparent, inclusive, and reproducible energy system modeling ecosystem, leveraging the PyPSA framework and contributing to the broader scientific and policy discourse around sustainable transitions. This document outlines how the community collaborates and governs to achieve these goals.

## Community Roles and Path to Maintainership

The following table lists the roles within the PyPSA-meets-Earth community, describing:

- General responsibilities expected by individuals in each role
- Requirements necessary to join or remain in a role
- Associated permissions and privileges

<table>
  <thead>
    <tr>
      <th>Role</th>
      <th>Responsibilities</th>
      <th>Requirements</th>
      <th>Privileges</th>
      <th>Scope</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Community Member</td>
      <td>
        <ul>
          <li>Follow the <a href="https://lfprojects.org/policies/code-of-conduct/">Code of Conduct</a></li>
        </ul>
      </td>
      <td>None</td>
      <td>
        <ul>
          <li>Can submit PRs and issues from forks</li>
          <li>Can join the PyPSA-meets-Earth Discord channel</li>
          <li>Can take part in community discussions</li>
        </ul>
      </td>
      <td>GitHub organization</td>
    </tr>
    <tr><td colspan="5"><em>Inherits from Community Member</em></td></tr>
    <tr>
      <td>Collaborator</td>
      <td>
        <ul>
          <li>Report and resolve issues</li>
          <li>Answer community questions</li>
          <li>Submit feedback on issues/PRs</li>
        </ul>
      </td>
      <td>
      <p><b>One or several of the below:</p></b>
          <p>Attend community meetings regularly</p>
          <p>At least a merged contribution</p> 
          <p>Active on Slack posting/answering questions</p>
          <p>Promote the project creating content/delivering talks/demos</p>     
      </td>
      <td>
        <ul>
          <li>Can submit PR reviews</li>
          <li>May close/open/reassign issues</li>
          <li>May request PR reviews</li>
          <li>Can mark duplicates</li>
        </ul>
      </td>
      <td>Specific repo(s) under pypsa-meets-earth</td>
    </tr>
    <tr><td colspan="5"><em>Inherits from Collaborator</em></td></tr>
    <tr>
      <td>Committer</td>
      <td>
        <ul>
          <li>Follow contributing guide</li>
          <li>Occasionally submit PRs</li>
          <li>Test releases, review PRs</li>
          <li>Triage issues</li>
          <li>Join working groups</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Multiple PRs merged</li>
          <li>Run/organize events</li>
          <li>Public promotion</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Request changes</li>
          <li>Review/approve (non-binding) PRs</li>
          <li>Merge approved PRs</li>
          <li>Create/edit releases</li>
          <li>Push branches</li>
        </ul>
      </td>
      <td>Specific repo(s) under pypsa-meets-earth</td>
    </tr>
    <tr><td colspan="5"><em>Inherits from Committer</em></td></tr>
    <tr>
      <td>Maintainer</td>
      <td>
        <ul>
          <li>Ensure quality & alignment</li>
          <li>Help cut releases</li>
          <li>Mentor contributors</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Must be a contributor</li>
          <li>Active, experienced reviewer</li>
          <li>Broad project knowledge</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Approve PRs (binding)</li>
          <li>Merge PRs</li>
          <li>Vote on RFCs (non-binding)</li>
          <li>Publicly represent project</li>
        </ul>
      </td>
      <td>Specific repo(s) under pypsa-meets-earth</td>
    </tr>
    <tr><td colspan="5"><em>Inherits from Collaborator</em></td></tr>
    <tr>
      <td>Steering Committee</td>
      <td>
        <ul>
          <li>Set roadmap/priorities</li>
          <li>Mentor contributors/maintainers</li>
          <li>Vote on governance, roles, RFCs</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Must be a maintainer</li>
          <li>Highly active in multiple areas</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Org-wide permissions</li>
          <li>Binding vote on RFCs</li>
          <li>Represent project externally</li>
        </ul>
      </td>
      <td>GitHub organization</td>
    </tr>
  </tbody>
</table>

## Role Description and Processes

### Community Participant

Anyone can contribute by using PyPSA-meets-Earth tools, providing feedback, joining discussions, submitting issues and PRs, or helping others.

### Collaborator

Collaborators actively engage with the community and support others.

#### Nomination Process

1. Open an issue in the community repo using the `collaborator-nomination` label.
2. Assign current maintainers as reviewers.
3. Approval requires a supermajority of repo maintainers within 14 days.
4. Accepted collaborators will be added to the GitHub organization with appropriate permissions.

### Committer

Committers are regular contributors with write access.

#### Nomination Process

1. Open an issue in the community repo using the `committer-nomination` label.
2. Assign current maintainers as reviewers.
3. Approval requires a supermajority of repo maintainers within 14 days.
4. Accepted committers will be granted write access to the scoped repositories.

### Maintainers

Maintainers manage daily project contributions, review PRs, and ensure quality.

> Note: Maintainer responsibilities may require significant time and commitment. To avoid burnout, current maintainers are working on processes to reduce barriers and distribute responsibilities.

#### Removal or Resignation

Maintainers may step down voluntarily or be removed by supermajority vote due to inactivity or other circumstances.

### Steering Committee

Responsible for strategic direction, cross-repo concerns, and governance decisions. Duties include:

- Reviewing proposals for new sub-projects
- Establishing Working Groups
- Approving governance and role changes
- Voting on significant RFCs

## Stepping Down / Emeritus Process

Contributors can step down to a lower role or request emeritus status by contacting the maintainers.

---

**NOTE:** The current list of maintainers and Steering Committee members is maintained in [MAINTAINERS](MAINTAINERS.md).
