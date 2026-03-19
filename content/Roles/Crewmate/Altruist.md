The Altruist is a crewmate that can sacrifice certain freedoms in order to revive players from the game. The Altruist gets two chances/stages. 

Each time the Altruist revives a player, it is announced that the player will be back in the game.
They can use the [[Revive]] command.

The Altruist may revive the first player by sacrificing their freedom to speak in Discord chat and meetings. After the first revival, they are server muted, but can still discuss in person and can still vote, as opposed to the effects of the [[Blackmailer]]. 

The second revival results in the cost of revealing for the Altruist. It may not sound that bad, but if [[Evil Guesser]] is enabled and they are not out yet, it could mean certain death.

**Config**
`free_revival: bool = false`: Determines whether the Altruist gets a free revival before the two take into effect, totaling to three total.
`task_barrier: Option<u8> = None`: Determines whether they need to have completed a certain number of tasks before they may initiate revivals.