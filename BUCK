include_defs('//bucklets/gerrit_plugin.bucklet')

MODULE = 'com.googlesource.gerrit.plugins.github.pullrequest'

gerrit_plugin(
  name = 'github-pullrequest',
  srcs = glob(['src/main/java/**/*.java']),
  resources = glob(['src/main/**/*']),
  manifest_entries = [
    'Gerrit-PluginName: github-pullrequest',
    'Gerrit-Module: com.googlesource.gerrit.plugins.github.pullrequest.Module',
    'Implementation-Title: GitHub PullRequests Importer',
    'Implementation-URL: https://gerrit-review.googlesource.com/#/admin/projects/plugins/github-pullrequest',
  ],
)
