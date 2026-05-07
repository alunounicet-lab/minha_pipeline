# minha_pipeline
nome: pipeline

on:

    release: event type

    issues: event type
      type[opene, edited, milestoned]

    push:
      branches:
        - 'main'
        - 'releases/**'

    pull_request: Event type
      types:
        - opened
      branches:
        - 'releases/**'
