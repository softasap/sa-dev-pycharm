sa-dev-pycharm
==============

[![Build Status](https://travis-ci.org/softasap/sa-dev-pycharm.svg?branch=master)](https://travis-ci.org/softasap/sa-dev-pycharm)

Installs Jetbrains pycharm

Example of use:
```YAML

     - {
         role: "sa-dev-pycharm"
       }

```

Advanced:
```YAML
     - {
         role: "sa-dev-pycharm",
         option_install_java: true,
         java_version: 7,
         pycharm_version: "2016.3.2", #"2016.2.1" #"2016.2" #"2016.1.4" #"2016.1" #5.0.1 # 4.5.4
         pycharm_edition: community # professional | community
         apps_dir: "/home/{{ansible_user_id}}/apps",
         desktop_dir: "Desktop"
       }
```



Usage with ansible galaxy workflow
----------------------------------

2. If you installed the sa-dev-pycharm role using the command


`
   ansible galaxy install softasap.sa-dev-pycharm
`

the role will be available in the folder library\softasap.sa-dev-pycharm.
Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-dev-pycharm"
       }

```


Copyright and license
---------------------

Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

