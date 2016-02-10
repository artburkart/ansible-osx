# Ansible playbooks for OSX

### Installation

```command
brew install ansible
git clone https://github.com/artburkart/ansible-osx.git
ansible-playbook ./ansible-osx/env/common.yml
```

#### You now have a bunch of:

Taps installed and upgraded:
- homebrew/dupes
- homebrew/versions

Packages installed and upgraded:
- ansible
- git
- gnu-sed
- jq
- macvim
- the_silver_searcher
- vim
- watchman
- wget

Casks installed and upgraded:
- caffeine
- charles
- iterm2


### To use with local capybara development

```command
ansible-playbook ./ansible-osx/env/capybara.yml
```

#### You now have a bunch of:

Packages installed and upgraded:
- libxml2
- libxslt
- libiconv
- qt5
- chromedriver
- ruby

Gems installed and upgraded:
- cucumber
- selenium-webdriver
- chromedriver-helper
- headless
- mime-types
- xpath
- capybara-webkit
- capybara

