# TODO
-bootStrap the module using a script to update Build.ps1, Pester tests, Build tasks
  -Another option is to store the metadata of the module in a file at the root
-Find a way to be able to invoke the Pester tests without the build.ps1
    Kind of tough without the module being built :-/
-Add more badges
   -Code coverage:
        https://github.com/natescherer/ChangelogManagement
   -Download, Supported version
        https://github.com/felixfbecker/PSKubectl
-create CONTRIBUTIONS template
    https://github.com/natescherer/ChangelogManagement/blob/master/CONTRIBUTING.md
-Automate the CHANGELOG management
    https://github.com/natescherer/ChangelogManagement/
-Check if we can fetch the information in the "Edit" part with BuildHelpers (see below)
-publish release to github (see buildhelpers module)
-Make this file appraoch easily clonable
-Improve agnostic approach so it can work on any CI
-Minimalize files present in the root, possibly move build.ps1 ?
-Make the Build script flexible so we can call different tasks at different stages (build, deploy, tests..)
-Speed up dependencies installation
-Add more verbose/output messages
-Use invokebuild header ?
-Documentation automation
-add simple gitpitch
-add more verbose messages
-more pester tests
-tag pester tests
-separate build and deploy steps in CI
-test on ps core
-test on linux
-Tag commits with version
-Maintain a ChangLog automatically based on Git metadata ?
-Sign Module ?
-Automate Tweet when new version released
-Support Gerking specs check
   * https://github.com/KevinMarquette/PSGraph/blob/7f4faaebd24d5815f4e4f3f13953deb3edc60685/module.build.ps1#L45-L52
   * https://powershellexplained.com/2017-03-17-Powershell-Gherkin-specification-validation/
