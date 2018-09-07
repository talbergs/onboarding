# onboarding
New language onboarding checklist.
----
Clone this repo for personal use.

## How:
By abusing githubs templating feature.

## Why:
- There is list of basic building blocks you should cover while learning a new language.
- It will scaffold checkbox list namespaced by issue name (language).
- This repos serves as a tool for managing onboarding process.

## Usage:
- Create new issue named by language.
- Work along and check check.
- Meanwhile referencing that HEAD SHA link in the list (for lookup).
- List must not be completed in any particulal sequence.

on new lang:
`git checkout --orphan <lang> fresh`
before every next checkbox:
`git push --force origin fresh:<lang> && git checkout fresh`
before writing down sha-ref into issue for later lookup:
`git push origin <lang>`

