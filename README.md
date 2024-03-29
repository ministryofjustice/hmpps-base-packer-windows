# Packer images

## How to use

The base images for Amazon Linux and Amazon Linux 2 are publically available.

To use them you can search for the names listed in the build and use the account alias 'hmpps-engineering'

An example for using the base images is in the jenkins_agent.json builder

## Images

* Windows Base
* Windows Jenkins Agent
* Windows MIS NART Base
* Windows MIS NART BCS
* Windows MIS NART BFS

## GitHub Actions

An action to delete the branch after merge has been added.
Also an action that will tag when branch is merged to master
See https://github.com/anothrNick/github-tag-action

```
Bumping

Manual Bumping: Any commit message that includes #major, #minor, or #patch will trigger the respective version bump. If two or more are present, the highest-ranking one will take precedence.

Automatic Bumping: If no #major, #minor or #patch tag is contained in the commit messages, it will bump whichever DEFAULT_BUMP is set to (which is minor by default).

Note: This action will not bump the tag if the HEAD commit has already been tagged.
```

## AMI Users

| aws_account_ids             |              |
|-----------------------------|--------------|
| alfresco-dev                | 563502482979 |
| eng-dev                     | 895523100917 |
| eng-prod                    | 077643444046 |
| hmpps-delius-mis-dev        | 479759138745 |
| hmpps-delius-pre-prod       | 010587221707 |
| hmpps-delius-prod           | 050243167760 |
| hmpps-delius-stage          | 205048117103 |
| hmpps-delius-test           | 728765553488 |
| hmpps-delius-training       | 330914586320 |
| pcs-tools                   | 766455809178 |
