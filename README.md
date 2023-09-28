# qc-abyss-integration


## Copy the whole repo from Zdzislaw (2023-0928-Thu)

drone-integration

## The original content of .drone.yml is

kind: pipeline
type: docker
name: default

steps:
- name: test
  image: alpine
  commands:
  - echo hello world
  - pwd
  - ls
