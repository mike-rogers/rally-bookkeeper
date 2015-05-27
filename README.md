## Rally Bookkeeper
[![Build Status](https://travis-ci.org/mike-rogers/rally-bookkeeper.svg)](https://travis-ci.org/mike-rogers/rally-bookkeeper)
[![Coverage Status](https://coveralls.io/repos/mike-rogers/rally-bookkeeper/badge.svg)](https://coveralls.io/r/mike-rogers/rally-bookkeeper)

This is a Jenkins Plug-in which

1. pulls SCM ChangeSet information from Jenkins Builds and updates relevant Rally defect or story as a build action.
1. picks up Task details [status, actual hrs, todo hrs etc] from scm comments (if provided) and updates rally task details accordingly.
1. saves developers the effort of writing, installing, and maintaining check-in hooks for SCM tools (svn, cvs, perforce etc) in order to update Rally changsets, a task which is especially difficult if your organisation uses more than one configuration management tool.

For more information, please see the [project page](https://mike-rogers.github.io/rally-bookkeeper).

## License

This project is distributed under the MIT license.