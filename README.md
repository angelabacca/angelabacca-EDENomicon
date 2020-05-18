# EDENomicon

1. The name of the [game](./Nomicon/) is EDENomicon.
1. The goal of the game is TBD.
1. The players of the game are the members of the [players team](https://github.com/orgs/cryptotechguru/teams/players/members).
1. All rules should be logically self-consistent.
1. The source code for the game is maintained in the [website repository](https://github.com/cryptotechguru/EDENomicon).
1. The game is published on the [website](https://cryptotechguru.github.io/EDENomicon/).

## Jurisdiction

1. Only [Ulex 1.2](https://ulex.law/versions/1.2) governs any claim or question arising under or related to this agreement, including the proper forum for resolving disputes, all rules applied therein, and the form and effect of any judgement.

## Conventions

1. The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in these rules are to be interpreted as described in [RFC 2119](https://www.ietf.org/rfc/rfc2119.txt).

## Process

1. All players must unanimously agree to all rule changes.
1. All changes to the game MUST be submitted through a pull request (PR).
1. All changes to the game SHOULD be vetted by submitting an [issue](https://github.com/cryptotechguru/EDENomicon/issues).
    1. An issue is an inconsistency between a specification and an observation (analogous to a bug in software).
    1. If any player breaks the rules or witnesses another player breaking the rules, they SHOULD open an issue.
    1. Issues SHOULD be reviewed by the Operators to determine whether the rule should be changed or the player should be sanctioned.
1. Only players may fill [roles](Roles/).

### Multi-votes
1. If a proposal offers a choice between two or more options an Operator should call a multi-vote.
1. Each option is voted on with a +1 (acceptable), a -1 (not acceptable) or 0 (neutral).
1. Abstentions are counted as 0 (neutral).
1. Each option is assigned a score equal to the sum of votes.
1. If at least one option gets a positive score the multi-vote succeeds in choosing the one with the highest score, otherwise the proposal is defeated.
1. If there is a tie for high score among the options, the sponsor of the proposal may choose a winner among them, otherwise the proposal is defeated.
1. A multi-vote SHOULD have a single sponsor responsible for collecting and publishing options.
1. A multi-vote SHOULD have a specified deadline.
1. A multi-vote MAY be conducted on the game wiki.
1. An option MAY be added to the multi-vote by the sponsor during the vote but options MAY NOT be removed once the vote starts.
1. Voters MAY update their votes at any time before the vote ends but MUST NOT update anyone else's votes.
1. A multi-vote MAY be resolved early only if all eligible voters have voted on all options.
