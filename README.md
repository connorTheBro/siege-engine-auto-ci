# Siege engine CI

Take them down.

## How to
If you want join the community you can use free github continuous integration servers for that.
[Here is the step-by-step guide with some screenshots](https://github.com/kqf/go-brrrrr/wiki/How-to-github), long story short:

1. Create github account
2. Fork this repo
3. Go to Actions section and accept 
4. Do a dummy commit (e.g. change the README)

This will spawn a github server that will keep attacking 21 URL for 1 hour.
You can run 2 workflows at once. After an hour you can just create another dummy commit to continue the attack

Maximum you can [six hours](https://docs.github.com/en/actions/learn-github-actions/usage-limits-billing-and-administration#usage-limits) of concurrent jobs.
Your free plan should sufice for some time.


## GitLab
You can use your `GitHub` account to create a `GitLab` account (sign using github), they have free runners on their own. [Here is the mirrored version of this repo](https://gitlab.com/an0nymus/go-brrrrr)


## Notabene
Please conside changing the list of targets, it may happen they are already down

## Thanks
Inspired by [kqf/go-brrrrr](https://github.com/kqf/go-brrrrr), obviously things are mostly smart copy-paste with new addresses added.
