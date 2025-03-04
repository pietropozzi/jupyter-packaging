# Changelog

## 0.8.1

* Fix Usage of install_npm [#71](https://github.com/jupyter/jupyter-packaging/pull/71) ([@afshin](https://github.com/afshin))

## 0.8.0

* Proposal: Improved integration with setuptools [#69](https://github.com/jupyter/jupyter-packaging/pull/69) ([@afshin](https://github.com/afshin))
* Update changelog [#68](https://github.com/jupyter/jupyter-packaging/pull/68) ([@blink1073](https://github.com/blink1073))


## 0.7.12

* Use sdist from setuptools not distutils [#66](https://github.com/jupyter/jupyter-packaging/pull/66) ([@astrofrog](https://github.com/astrofrog))

## 0.7.11

* Fix packagedata docstring examples [#62](https://github.com/jupyter/jupyter-packaging/pull/62) ([@vidartf](https://github.com/vidartf))

## 0.7.10

* Only run build command if one is given [#61](https://github.com/jupyter/jupyter-packaging/pull/61) ([@vidartf](https://github.com/vidartf))
* Add basic test for skip_if_exists [#60](https://github.com/jupyter/jupyter-packaging/pull/60) ([@jtpio](https://github.com/jtpio))

## 0.7.9

* Fix typo in skip_if_exists [#59](https://github.com/jupyter/jupyter-packaging/pull/59) ([@jtpio](https://github.com/jtpio))

## 0.7.8

* Fix skip_if_exists logic [#58](https://github.com/jupyter/jupyter-packaging/pull/58) ([@jtpio](https://github.com/jtpio))
* test for nested source folder [#57](https://github.com/jupyter/jupyter-packaging/pull/57) ([@vidartf](https://github.com/vidartf))

## 0.7.7

* allow trailing slashes in spec [#56](https://github.com/jupyter/jupyter-packaging/pull/56) ([@vidartf](https://github.com/vidartf))

## 0.7.6

* Add local testing instructions [#55](https://github.com/jupyter/jupyter-packaging/pull/55) ([@blink1073](https://github.com/blink1073))
* feat: add skip_if_exists command to skip when paths exists [#54](https://github.com/jupyter/jupyter-packaging/pull/54) ([@maartenbreddels](https://github.com/maartenbreddels))
* Allow --prefix to work [#52](https://github.com/jupyter/jupyter-packaging/pull/52) ([@dsblank](https://github.com/dsblank))

## 0.7.4

* Import sdist from distutils instead of setuptools [#51](https://github.com/jupyter/jupyter-packaging/pull/51) ([@jasongrout](https://github.com/jasongrout))

## 0.7.2

* Require the packaging package [#49](https://github.com/jupyter/jupyter-packaging/pull/49) ([@blink1073](https://github.com/blink1073))
* Switch to gh actions [#48](https://github.com/jupyter/jupyter-packaging/pull/48) ([@blink1073](https://github.com/blink1073))

## 0.7.1

* Allow files to be excluded [#47](https://github.com/jupyter/jupyter-packaging/pull/47) ([@blink1073](https://github.com/blink1073))

## 0.7.0

* Test using pyproject.toml and modernize [#46](https://github.com/jupyter/jupyter-packaging/pull/46) ([@blink1073](https://github.com/blink1073))

## 0.6.1

* Remove brittle check for whether to run npm/yarn install [#44](https://github.com/jupyter/jupyter-packaging/pull/44) ([@blink1073](https://github.com/blink1073))

## 0.6.0

* move data files to the correct place on develop install [#41](https://github.com/jupyter/jupyter-packaging/pull/41) ([@Zsailer](https://github.com/Zsailer))

## 0.5.0

* Add changelog and update example [#37](https://github.com/jupyter/jupyter-packaging/pull/37) ([@blink1073](https://github.com/blink1073))
* Update readme to mention pep 518 [#36](https://github.com/jupyter/jupyter-packaging/pull/36) ([@blink1073](https://github.com/blink1073))
* Add handling of data_files in develop mode and add test [#35](https://github.com/jupyter/jupyter-packaging/pull/35) ([@blink1073](https://github.com/blink1073))
* do not pass absolute path to which [#33](https://github.com/jupyter/jupyter-packaging/pull/33) ([@MeggyCal](https://github.com/MeggyCal))
* which finds python executable [#32](https://github.com/jupyter/jupyter-packaging/pull/32) ([@MeggyCal](https://github.com/MeggyCal))

## 0.4.0

* Remove HERE [#30](https://github.com/jupyter/jupyter-packaging/pull/30) ([@vidartf](https://github.com/vidartf))

## 0.3.0

* Cleanup pt 2 [#29](https://github.com/jupyter/jupyter-packaging/pull/29) ([@vidartf](https://github.com/vidartf))
* Clean up [#28](https://github.com/jupyter/jupyter-packaging/pull/28) ([@vidartf](https://github.com/vidartf))
* Additional error checking in run() [#27](https://github.com/jupyter/jupyter-packaging/pull/27) ([@jmsdnns](https://github.com/jmsdnns))
* Add appveyor test dependencies [#26](https://github.com/jupyter/jupyter-packaging/pull/26) ([@vidartf](https://github.com/vidartf))
* Data spec path issues [#25](https://github.com/jupyter/jupyter-packaging/pull/25) ([@vidartf](https://github.com/vidartf))
* Fixed a broken test in test_find_packages [#22](https://github.com/jupyter/jupyter-packaging/pull/22) ([@jmsdnns](https://github.com/jmsdnns))
* Fix handling of pip install [#21](https://github.com/jupyter/jupyter-packaging/pull/21) ([@blink1073](https://github.com/blink1073))
* restore setuptools import [#20](https://github.com/jupyter/jupyter-packaging/pull/20) ([@minrk](https://github.com/minrk))
* Updates from using this as the JupyterLab basis [#19](https://github.com/jupyter/jupyter-packaging/pull/19) ([@blink1073](https://github.com/blink1073))
* Fix handling of data files [#18](https://github.com/jupyter/jupyter-packaging/pull/18) ([@blink1073](https://github.com/blink1073))
* Append data files instead of overwrite them [#17](https://github.com/jupyter/jupyter-packaging/pull/17) ([@jasongrout](https://github.com/jasongrout))
* Ensure targets [#16](https://github.com/jupyter/jupyter-packaging/pull/16) ([@vidartf](https://github.com/vidartf))
* Add option to force npm install/build [#15](https://github.com/jupyter/jupyter-packaging/pull/15) ([@vidartf](https://github.com/vidartf))
* Add basic tests + fixes for find_packages [#14](https://github.com/jupyter/jupyter-packaging/pull/14) ([@vidartf](https://github.com/vidartf))
* Fix `is_stale` for file paths [#13](https://github.com/jupyter/jupyter-packaging/pull/13) ([@vidartf](https://github.com/vidartf))
* Update package data after wrapped commands [#12](https://github.com/jupyter/jupyter-packaging/pull/12) ([@vidartf](https://github.com/vidartf))
* Adjust is_stale to use recursive mtimes [#10](https://github.com/jupyter/jupyter-packaging/pull/10) ([@vidartf](https://github.com/vidartf))
* Add `main` module [#8](https://github.com/jupyter/jupyter-packaging/pull/8) ([@vidartf](https://github.com/vidartf))
