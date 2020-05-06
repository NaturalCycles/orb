
## orbs

> Set of reusable CircleCI Orbs.

# [naturalcycles/tools](https://circleci.com/orbs/registry/orb/naturalcycles/tools)
# [naturalcycles/internal-tools](https://circleci.com/orbs/registry/orb/naturalcycles/internal-tools)
# [naturalcycles/doc-tools](https://circleci.com/orbs/registry/orb/naturalcycles/doc-tools)

Executors:

- `node`: Default executor, using `naturalcycles/ci-node` Docker image.


## Create new orb

    circleci orb create naturalcycles/tools
    circleci orb validate naturalcycles/tools.yml
    circleci orb publish naturalcycles/tools.yml naturalcycles/tools@dev:1
    circleci orb publish naturalcycles/tools.yml naturalcycles/tools@0.0.1
    circleci orb publish increment naturalcycles/tools.yml naturalcycles/tools patch
