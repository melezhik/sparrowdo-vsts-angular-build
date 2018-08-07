# Sparrowdo::VSTS::YAML:Solution

Sparrowdo module to generate VSTS yaml steps to build angular project.

    $ cat sparrowfile

    module_run "VSTS::YAML::Angular::Build", %(
      build-dir => "cicd/build"
    );

    $ sparrowdo --local_mode --no_sudo

# Author

Alexey Melezhik

