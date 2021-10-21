# jira-orb

CircleCI Orb to handle notifying Jira with build results

It can be found in the CircleCI Orb Registry at https://circleci.com/developer/orbs/orb/opub/jira-orb.

This orb is based on the https://github.com/CircleCI-Public/jira-connect-orb implementation. It was customized to provide different default values for my typical use case and to work around CircleCI's limitation on setting enum values. See TODOs in main.yml for where assumptions were made that wouldn't fit most cases. See more on enum limitation at https://ideas.circleci.com/cloud-feature-requests/p/support-casting-strings-as-enum-values.

If new to CircleCI orb creation the [Manual Orb Authoring Process](https://circleci.com/docs/2.0/orb-author-validate-publish/) is much easier to follow for simple orbs like this. See the [Publishing Orbs](https://circleci.com/docs/2.0/creating-orbs/) page for versioning details. The full-blown [Orb Authoring Process](https://circleci.com/docs/2.0/orb-author/) is the CircleCI recommended method but I found it too complex for any simple orb work I was doing.
