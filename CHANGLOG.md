# Change log

## Version 0.1.10 (Nov 29, 2016)

Bug fixes:
  * Cleaned up install path before installation

## Version 0.1.9 (Nov 27, 2016)

Minor enhancements:
  * Specified control_file_dir to properly handle linked files
  * Bump up gem dependency of Luban to version 0.10.8

Bug fixes:
  * Fixed superclass mismatch exception when loading gem from filesystem directly

## Version 0.1.8 (Nov 24, 2016)

Minor enhancements:
  * Made use of linked_files convention
    * Relocated kibana.yml.erb to templates/config
    * As a result, bump up gem dependency of Luban to version 0.10.4

## Version 0.1.7 (Oct 23, 2016)

Minor enhancements:
  * Added a new parameter, #network_host, in Kibana configuration
  * Cleaned up the design and implementation of app parameters in a deployment project
    * As a result, bump up gem dependency on Luban to version 0.9.10

## Version 0.1.6 (Oct 19, 2016)

Minor enhancements:
  * Utilized new parameters, #logrotate_max_age, #logrotate_count, from Luban to unify logrotate setup
  * Bump up gem dependency of Luban to version 0.9.8

## Version 0.1.5 (Oct 17, 2016)

Bug fixes:
  * Corrected the logrotate template file name

## Version 0.1.4 (Oct 12, 2016)

Minor enhancements:
  * Added logrotate configuration for Kibana
  * Bump up gem dependency of Luban to version 0.9.0

## Version 0.1.3 (Sept 28, 2016)

Minor enhancements:
  * Applied subcommand grouping for better clarity
    * As a result, bump up gem dependency of Luban to version 0.8.8

## Version 0.1.2 (Sept 20, 2016)

Minor enhancements:
  * Refactored the way of composing shell commands
    * As a result, bumped up the gem dependency on Luban to version 0.8.0

## Version 0.1.1 (Sept 02, 2016)

Minor enhancements:
  * Refactored to make use of #shell_command_output to change the default compose command result
    * As a result, bump up the gem dependency of Luban to version 0.7.12

## Version 0.1.0 (Aug 31, 2016)

New features:
  * Initialized Luban deployemnt package of Kibana
