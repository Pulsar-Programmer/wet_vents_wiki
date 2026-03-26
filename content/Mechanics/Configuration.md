
# Standard

## Voting
`voting_colors: bool = false`: Determines whether or not to show colors of players after voting.
`voting_confirmation: bool = false`: Determines whether or not to show a confirmation message that the player was/was not an imposter.
`vote_overriding: bool = false`: Allows you to override votes during the day.

## Tasks
`task_amt: u8 = 7`: Amount of tasks Crewmates are given to complete.

## Game Control Flow
`dm_info: bool = true`: Whether to DM info or private thread info.
`imposters_num: Option<u8> = None`: How many imposters are present. If `None` is given, it autoadjusts.
`ghosts_know: bool = true`: Whether ghosts can use the [[Role]] command to find your role.

# Role Specific Config
`guardian_angel_pct: f32 = 0.2`: Percent chance of a Crewmate becoming a Guardian Angel when they die.
# Roles Percentages
Simply a percentage on role assignment.
Roles are assigned by having a `x%` chance of being present in the pool. If not enough roles were assigned to players, more pools are generated until it fills them. Imposters are generated first.

