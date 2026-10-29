> [!WARNING]
> **This repository is scheduled to be archived on 13th November 2026.**
>
> After that date it will be read-only: no new commits, issues, or pull requests, and no further maintenance or security updates will be issued.

# Sensu::Extensions::RubyHash

This mutator extension provides the Sensu Core built-in mutator
`ruby_hash`. This mutator provides an unmodified event Ruby hash
object, which can only be used by handler extensions (can not be used
by regular Sensu event handlers).

This mutator will return an unmodified event Ruby hash object.
