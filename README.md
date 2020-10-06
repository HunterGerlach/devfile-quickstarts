# devfile-quickstarts

See a devfile in action by clicking the button below...

[![Contribute](https://www.eclipse.org/che/factory-contribute.svg)](https://che.openshift.io/f?url=https://github.com/redhat-developer/devfile)

## Devfile Diff v1.0/v2.0 Quick Reference

| Attribute          | v1.0          |  v2.0           | Description                                                                                                 |
|--------------------|---------------|-----------------|-------------------------------------------------------------------------------------------------------------|
| Version definition | `apiVersion`  | `schemaVersion` | Definition changed to avoid confusion with K8s definitions                                                  |
| Projects           | null          | null            | No notable changes                                                                                          |
| Components         | MAJOR CHANGES | MAJOR CHANGES   | See: https://devfile.github.io/devfile/migration_guide.html#_how_to_migrate_components                      |
| Plugins            | MAJOR CHANGES | MAJOR CHANGES   | See: https://devfile.github.io/devfile/migration_guide.html#_how_to_migrate_plugins                         |
| Commands           | MAJOR CHANGES | MAJOR CHANGES   | See: https://devfile.github.io/devfile/migration_guide.html#_how_to_migrate_commands                        |
| Parent             | null          | NEW             | See: https://devfile.github.io/devfile/migration_guide.html#_using_parent_devfiles_to_build_reusable_stacks |
| Events             | null          | NEW             | See: https://devfile.github.io/devfile/migration_guide.html#_adding_event_bindings                          |
| Metadata           | minor changes | minor changes   | See: https://devfile.github.io/devfile/migration_guide.html#_new_metadata                                   |

Additional devfile details can be found here: https://devfile.github.io/devfile/index.html

