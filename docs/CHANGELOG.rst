
Changelog
=========

`1.2.2 <https://github.com/saltstack-formulas/vault-formula/compare/v1.2.1...v1.2.2>`_ (2019-10-09)
-------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **cert-gen.sh.j2:** fix ``salt-lint`` errors (\ ` <https://github.com/saltstack-formulas/vault-formula/commit/12fd2f9>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** install required packages to bootstrapped ``opensuse`` (\ ` <https://github.com/saltstack-formulas/vault-formula/commit/5f1c3cd>`_\ )
* **kitchen:** use bootstrapped ``opensuse`` images until ``2019.2.2`` (\ ` <https://github.com/saltstack-formulas/vault-formula/commit/c090077>`_\ )
* merge travis matrix, add ``salt-lint`` & ``rubocop`` to ``lint`` job (\ ` <https://github.com/saltstack-formulas/vault-formula/commit/ba82312>`_\ )

`1.2.1 <https://github.com/saltstack-formulas/vault-formula/compare/v1.2.0...v1.2.1>`_ (2019-10-01)
-------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **gemfile:** restrict ``inspec`` version to ``~> 4.16.0`` (\ `c82034a <https://github.com/saltstack-formulas/vault-formula/commit/c82034a>`_\ ), closes `/travis-ci.com/saltstack-formulas/vault-formula/jobs/239671364#L2219-L2220 <https://github.com//travis-ci.com/saltstack-formulas/vault-formula/jobs/239671364/issues/L2219-L2220>`_ `/travis-ci.com/saltstack-formulas/vault-formula/jobs/239671365#L1925-L1926 <https://github.com//travis-ci.com/saltstack-formulas/vault-formula/jobs/239671365/issues/L1925-L1926>`_ `/travis-ci.com/saltstack-formulas/vault-formula/jobs/239671366#L1515-L1520 <https://github.com//travis-ci.com/saltstack-formulas/vault-formula/jobs/239671366/issues/L1515-L1520>`_
* **inspec:** fix Ruby lint warnings (\ `9d823ed <https://github.com/saltstack-formulas/vault-formula/commit/9d823ed>`_\ )
* **osfamilymap:** add support for ``Arch`` (\ `b64a589 <https://github.com/saltstack-formulas/vault-formula/commit/b64a589>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* use ``dist: bionic`` & apply ``opensuse-leap-15`` SCP error workaround (\ `d2c97f4 <https://github.com/saltstack-formulas/vault-formula/commit/d2c97f4>`_\ )
* **kitchen:** change ``log_level`` to ``debug`` instead of ``info`` (\ `79b902e <https://github.com/saltstack-formulas/vault-formula/commit/79b902e>`_\ )
* **kitchen+travis:** replace EOL pre-salted images (\ `346cd1e <https://github.com/saltstack-formulas/vault-formula/commit/346cd1e>`_\ )
* **platform:** add ``arch-base-latest`` (\ `6dd656f <https://github.com/saltstack-formulas/vault-formula/commit/6dd656f>`_\ )
* **travis:** apply suggestions from code review (\ `800d842 <https://github.com/saltstack-formulas/vault-formula/commit/800d842>`_\ )
* **travis:** split suites across instances (\ `bfdba0c <https://github.com/saltstack-formulas/vault-formula/commit/bfdba0c>`_\ )
* **travis:** use ``kitchen verify`` instead of ``kitchen test`` (\ `6939af9 <https://github.com/saltstack-formulas/vault-formula/commit/6939af9>`_\ )
* **yamllint:** add rule ``empty-values`` & use new ``yaml-files`` setting (\ `ece89fa <https://github.com/saltstack-formulas/vault-formula/commit/ece89fa>`_\ )

Tests
^^^^^


* **inspec:** move tests to standard ``controls`` sub-directory (\ `bd8649c <https://github.com/saltstack-formulas/vault-formula/commit/bd8649c>`_\ )

`1.2.0 <https://github.com/saltstack-formulas/vault-formula/compare/v1.1.1...v1.2.0>`_ (2019-08-17)
-------------------------------------------------------------------------------------------------------

Features
^^^^^^^^


* **yamllint:** include for this repo and apply rules throughout (\ `073f66e <https://github.com/saltstack-formulas/vault-formula/commit/073f66e>`_\ )

`1.1.1 <https://github.com/saltstack-formulas/vault-formula/compare/v1.1.0...v1.1.1>`_ (2019-07-13)
-------------------------------------------------------------------------------------------------------

Code Refactoring
^^^^^^^^^^^^^^^^


* **kitchen+inspec:** move inline pillars to files (\ `4dc3025 <https://github.com/saltstack-formulas/vault-formula/commit/4dc3025>`_\ )

`1.1.0 <https://github.com/saltstack-formulas/vault-formula/compare/v1.0.6...v1.1.0>`_ (2019-07-10)
-------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **package:** explicitly require package providing setcap (\ `d476700 <https://github.com/saltstack-formulas/vault-formula/commit/d476700>`_\ )
* **user:** handle removal of ``gid_from_name`` in Salt develop branch (\ `dee3748 <https://github.com/saltstack-formulas/vault-formula/commit/dee3748>`_\ ), closes `saltstack/salt#48640 <https://github.com/saltstack/salt/issues/48640>`_

Code Refactoring
^^^^^^^^^^^^^^^^


* **defaults:** place common values in defaults.yaml (\ `3656e31 <https://github.com/saltstack-formulas/vault-formula/commit/3656e31>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen+travis:** bring into line with ``template-formula`` (\ `34f05bd <https://github.com/saltstack-formulas/vault-formula/commit/34f05bd>`_\ )

Features
^^^^^^^^


* add support for openSUSE (\ `76b8ac3 <https://github.com/saltstack-formulas/vault-formula/commit/76b8ac3>`_\ )

Tests
^^^^^


* **user+group:** test for vault user/group existence (\ `ff5cdf9 <https://github.com/saltstack-formulas/vault-formula/commit/ff5cdf9>`_\ )

`1.0.6 <https://github.com/saltstack-formulas/vault-formula/compare/v1.0.5...v1.0.6>`_ (2019-06-24)
-------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* use gpg2 (\ `d755cb4 <https://github.com/saltstack-formulas/vault-formula/commit/d755cb4>`_\ )

`1.0.5 <https://github.com/saltstack-formulas/vault-formula/compare/v1.0.4...v1.0.5>`_ (2019-05-15)
-------------------------------------------------------------------------------------------------------

Documentation
^^^^^^^^^^^^^


* **readme:** move requirements section under testing header (\ `dfca3a6 <https://github.com/saltstack-formulas/vault-formula/commit/dfca3a6>`_\ )

`1.0.4 <https://github.com/saltstack-formulas/vault-formula/compare/v1.0.3...v1.0.4>`_ (2019-05-14)
-------------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** don't put Gemfile.lock in git (\ `cfd5daf <https://github.com/saltstack-formulas/vault-formula/commit/cfd5daf>`_\ )
* **kitchen:** update Gemfile from template-formula (\ `541ec63 <https://github.com/saltstack-formulas/vault-formula/commit/541ec63>`_\ )
* **travis:** use default bundler on Travis (\ `b9f40b3 <https://github.com/saltstack-formulas/vault-formula/commit/b9f40b3>`_\ )

Documentation
^^^^^^^^^^^^^


* **readme:** restore requirements section (\ `5f2256c <https://github.com/saltstack-formulas/vault-formula/commit/5f2256c>`_\ )

`1.0.3 <https://github.com/saltstack-formulas/vault-formula/compare/v1.0.2...v1.0.3>`_ (2019-05-13)
-------------------------------------------------------------------------------------------------------

Documentation
^^^^^^^^^^^^^


* **readme:** improve readme sections (\ `10e2bde <https://github.com/saltstack-formulas/vault-formula/commit/10e2bde>`_\ )

`1.0.2 <https://github.com/saltstack-formulas/vault-formula/compare/v1.0.1...v1.0.2>`_ (2019-05-13)
-------------------------------------------------------------------------------------------------------

Documentation
^^^^^^^^^^^^^


* **readme:** update readme, add badges (\ `1fc3142 <https://github.com/saltstack-formulas/vault-formula/commit/1fc3142>`_\ )

`1.0.1 <https://github.com/saltstack-formulas/vault-formula/compare/v1.0.0...v1.0.1>`_ (2019-04-20)
-------------------------------------------------------------------------------------------------------

Code Refactoring
^^^^^^^^^^^^^^^^


* **kitchen:** prefer ``kitchen.yml`` to ``.kitchen.yml`` (\ `5baaf24 <https://github.com/saltstack-formulas/vault-formula/commit/5baaf24>`_\ )

`1.0.0 <https://github.com/saltstack-formulas/vault-formula/compare/v0.5.1...v1.0.0>`_ (2019-04-01)
-------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **everything:** review comments & tests (\ `297d784 <https://github.com/saltstack-formulas/vault-formula/commit/297d784>`_\ )
* **package:** add missed cleanup & add storage backend to prod test (\ `d0ed5e5 <https://github.com/saltstack-formulas/vault-formula/commit/d0ed5e5>`_\ )
* **package:** fix more review comments (\ `65482c2 <https://github.com/saltstack-formulas/vault-formula/commit/65482c2>`_\ )
* **service:** re-add support for Ubuntu 14.04 and older (\ `1b1611f <https://github.com/saltstack-formulas/vault-formula/commit/1b1611f>`_\ )
* **upgrade:** upgrade procedure & add MacOS platform (\ `b7b0d1d <https://github.com/saltstack-formulas/vault-formula/commit/b7b0d1d>`_\ )

Code Refactoring
^^^^^^^^^^^^^^^^


* **everything:** overhaul to align with the template-formula (\ `15d4e34 <https://github.com/saltstack-formulas/vault-formula/commit/15d4e34>`_\ )
* **map.jinja:** cleanup map.jinja merge & add lookup (\ `a640f01 <https://github.com/saltstack-formulas/vault-formula/commit/a640f01>`_\ )
* **service:** move config watch statement as it breaks in dev_mode (\ `c6ce242 <https://github.com/saltstack-formulas/vault-formula/commit/c6ce242>`_\ )

Features
^^^^^^^^


* **version:** bump version to 1.1.0 (\ `7671f87 <https://github.com/saltstack-formulas/vault-formula/commit/7671f87>`_\ )

Reverts
^^^^^^^


* **defaults:** some defaults were incorrectly changed (\ `140db23 <https://github.com/saltstack-formulas/vault-formula/commit/140db23>`_\ )

Tests
^^^^^


* **config:** correct more test cases (\ `507ee9f <https://github.com/saltstack-formulas/vault-formula/commit/507ee9f>`_\ )
* **install_binary:** fix version & hash returned by vault v1.1.0 (\ `8d74960 <https://github.com/saltstack-formulas/vault-formula/commit/8d74960>`_\ )
* **kitchen:** change version pillar (\ `7fed7e6 <https://github.com/saltstack-formulas/vault-formula/commit/7fed7e6>`_\ )
* **manual:** update test, clean link (\ `1f533d3 <https://github.com/saltstack-formulas/vault-formula/commit/1f533d3>`_\ )

BREAKING CHANGES
^^^^^^^^^^^^^^^^


* **everything:** This renames all states and the config file being
  generated.

`0.5.1 <https://github.com/saltstack-formulas/vault-formula/compare/v0.5.0...v0.5.1>`_ (2019-03-27)
-------------------------------------------------------------------------------------------------------

Documentation
^^^^^^^^^^^^^


* **semantic-release:** implement an automated changelog (\ `728ebd8 <https://github.com/saltstack-formulas/vault-formula/commit/728ebd8>`_\ ), closes `#24 <https://github.com/saltstack-formulas/vault-formula/issues/24>`_
